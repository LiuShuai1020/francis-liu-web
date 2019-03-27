<template>
  <section>
    <section class="hero is-primary">
      <div class="hero-body">
        <div class="container">
          <h1 class="title">
            Francis Liu
          </h1>
          <h2 class="subtitle">
            技术知识栈
          </h2>
        </div>
      </div>
    </section>
    <b-tabs v-model="activeTab">
      <b-tab-item class="content_left" label="Android">
        <h2>暂无内容</h2>
      </b-tab-item>
      <b-tab-item class="content_left" label="Java">
        <h2>暂无内容</h2>
      </b-tab-item>
      <b-tab-item class="content_left" label="Vue">
        <a href="https://cn.vuejs.org/v2/guide/index.html#">-->官方文档<--</a>
      </b-tab-item>
      <b-tab-item class="content_left" label="Element-ui">
        <a href="http://element-cn.eleme.io/#/zh-CN/component/installation">-->官方文档<--</a>
      </b-tab-item>
      <b-tab-item class="content_left" label="Buefy">
        <a href="https://buefy.org/documentation/layout">-->官方文档<--</a>
      </b-tab-item>
      <b-tab-item class="content_left" label="阿里云">
        <h1>常用命令:</h1>
        <h1>启动服务：  systemctl start nginx</h1>
        <h1>关闭服务：  systemctl stop nginx</h1>
        <h1>重启服务：  systemctl reload nginx</h1>
        <h1>查看端口：  netstat -tnlp</h1>
      </b-tab-item>
    </b-tabs>
  </section>
</template>

<script>
  import BTable from "buefy/src/components/table/Table";

  export default {
    components: {BTable},
    data() {
      return {
        activeTab: 0
      }
    }
  }
</script>
<style>
  .content_left {
    text-align: left;
  }
</style>
