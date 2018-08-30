<template>
  <Col span="4" class="side-nav" >
    <Menu :theme="'light'" :open-names="['5']" accordion width="auto">
      <Submenu name="1">
        <template slot="title">
          <Icon type="ios-paper" />
          收入管理
        </template>
        <MenuItem name="1-1">文章管理</MenuItem>
        <MenuItem name="1-2">评论管理</MenuItem>
        <MenuItem name="1-3">举报管理</MenuItem>
      </Submenu>
      <Submenu name="2">
        <template slot="title">
          <Icon type="ios-people" />
          收款管理
        </template>
        <MenuItem name="2-1">新增用户</MenuItem>
        <MenuItem name="2-2">活跃用户</MenuItem>
      </Submenu>
      <Submenu name="3">
        <template slot="title">
          <Icon type="ios-card-outline" />
          付款管理
        </template>
        <MenuGroup title="使用">
          <MenuItem name="3-1">新增和启动</MenuItem>
          <MenuItem name="3-2">活跃分析</MenuItem>
          <MenuItem name="3-3">时段分析</MenuItem>
        </MenuGroup>
        <MenuGroup title="留存">
          <MenuItem name="3-4">用户留存</MenuItem>
          <MenuItem name="3-5">流失用户</MenuItem>
        </MenuGroup>
      </Submenu>
      <Submenu name="4">
        <template slot="title">
          <Icon type="ios-document-outline" />
          发票管理
        </template>
        <MenuItem name="2-1">新增用户</MenuItem>
        <MenuItem name="2-2">活跃用户</MenuItem>
      </Submenu>
      <Submenu name="5">
        <template slot="title">
          <Icon type="ios-people" />
          基础数据
        </template>
        <MenuItem name="5-1">法人主体</MenuItem>
        <MenuItem name="5-2">营收业务期间</MenuItem>
        <MenuItem name="5-3">业务线会计期控制</MenuItem>
        <MenuItem name="5-4">税种税率（销项）</MenuItem>
        <MenuItem name="5-5">收入类型税选项</MenuItem>
        <MenuItem name="5-6">汇率</MenuItem>
        <MenuItem name="5-7">银行账号</MenuItem>
        <MenuItem name="5-8">交易方</MenuItem>
        <MenuItem name="5-9">映射集</MenuItem>
        <MenuItem name="5-10">程序</MenuItem>
      </Submenu>
      <Submenu name="6">
        <template slot="title">
          <Icon type="ios-people" />
          系统管理
        </template>
        <MenuItem name="2-1">新增用户</MenuItem>
        <MenuItem name="2-2">活跃用户</MenuItem>
      </Submenu>
      <Submenu name="7">
        <template slot="title">
          <Icon type="ios-document-outline" />
          日志管理
        </template>
        <MenuItem name="2-1">新增用户</MenuItem>
        <MenuItem name="2-2">活跃用户</MenuItem>
      </Submenu>
      <Submenu name="8">
        <template slot="title">
          <Icon type="ios-copy-outline" />
          核销管理
        </template>
        <MenuItem name="2-1">新增用户</MenuItem>
        <MenuItem name="2-2">活跃用户</MenuItem>
      </Submenu>
    </Menu>
  </Col>
</template>

<script>
    export default {
        name: "side-nav",

    }
</script>

<style scoped lang='scss'>
  .side-nav{
    border-right: 0.02rem solid #f8f8f8;
    /*Menu{*/
      /*width:2.28rem*/
    /*}*/
  }
  .ivu-menu-vertical .ivu-menu-item, .ivu-menu-vertical .ivu-menu-submenu-title{
    font-size:0.14rem;
    padding: 0.14rem 0.24rem;
  }
  .ivu-menu{
    font-size:0.14rem;
  }
  .ivu-menu-item{

  }
</style>
