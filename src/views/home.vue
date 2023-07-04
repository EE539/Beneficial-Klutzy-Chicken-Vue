<template>
  <div class="home-container">
    <span class="home-text">Text</span>
    <button type="button" class="home-button button">Button</button>
  </div>
</template>

<script>
export default {
  name: 'Home',
  metaInfo: {
    title: 'Beneficial Klutzy Chicken',
    meta: [
      {
        property: 'og:title',
        content: 'Beneficial Klutzy Chicken',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  flex-direction: column;
}
.home-text {
  font-size: 15px;
  font-style: normal;
  font-family: Inter;
  font-weight: 400;
}
.home-button {
  padding-left: var(--dl-space-space-unit);
}
</style>
