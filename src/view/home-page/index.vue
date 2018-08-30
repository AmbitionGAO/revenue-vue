<template>
    <div class="index-main">
        <Header></Header>
        <side-nav></side-nav>
        <test></test>
    </div>
</template>

<script>
    import Header from "../../components/header";
    import SideNav from "../../components/side-nav";
    import Test from "../../components/test";
    export default {
      name: "Index",
      components: {Test, SideNav, Header},
      data() {
            return {

            };
        },
    };
</script>
<style scoped lang='scss'>
  .index-main{
    background: #f8f8f8;
    font-family: "Helvetica Neue",Helvetica,"PingFang SC","Hiragino Sans GB","Microsoft YaHei","微软雅黑",Arial,sans-serif;

  }

</style>
