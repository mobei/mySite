<template>
  <div id="app">
    <hello></hello>
    <p>个人网站开发中......</p>
    <p>简历地址：<a href="http://www.mobei.website/resume/">http://www.mobei.website/resume/</a></p>
  </div>
</template>

<script>
import Hello from './components/Hello';

export default {
  components: {
    Hello,
  },
};
</script>

<style>
html {
  height: 100%;
}

body {
  display: flex;
  align-items: center;
  justify-content: center;
  height: 100%;
}

#app {
  color: #2c3e50;
  margin-top: -100px;
  max-width: 600px;
  font-family: Source Sans Pro, Helvetica, sans-serif;
  text-align: center;
}

#app a {
  color: #42b983;
  text-decoration: none;
}

.logo {
  width: 100px;
  height: 100px
}
</style>
