<template>
    <div id="app">
      <Index></Index>
    </div>
</template>

<script>
import Index from "./view/home-page/index";
export default {
  name: "App",
  components: {Index},
  data() {
    return {

    };
  }
};
(function () {
  let winW = document.documentElement.clientWidth, desW = 1440, htmlFont = winW / desW * 100;
  window.htmlFont = htmlFont;
  document.documentElement.style.fontSize = htmlFont + "px";
})();
</script>

<style scoped lang='scss'>
  body{
    background: #f8f8f8;
  }
</style>

