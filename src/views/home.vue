<template>
  <div class="home-container">
    <span class="home-text">Text</span>
    <button type="button" class="home-button button">Button</button>
    <lottie-vue-player
      :src="`https://presentation-website-assets.teleporthq.io/features/lottie.json`"
      :autoplay="true"
      :speed="1"
      :backgroundColor="transparent"
      class="home-lottie-node"
    ></lottie-vue-player>
    <form class="home-form">
      <button type="button" class="home-button1 button">Button</button>
    </form>
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
.home-lottie-node {
  width: 300px;
  height: 300px;
}
.home-form {
  width: 799px;
  height: 305px;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-button1 {
  width: 284px;
  padding-right: 0px;
}
</style>
