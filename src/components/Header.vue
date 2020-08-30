<template>
  <div class="header-wrapper" ref="appHeader">
    <div class="header-content">
      <div class="header-tab">
        <div class="title">
          <h1 class="text">TOGETHER</h1>
          <p class="slogan">몸은 멀어도 마음은 가까이</p>
        </div>

        <router-link to="/news">홈</router-link>
        <router-link to="/ask">모임</router-link>
        <router-link to="/jobs">커뮤니티</router-link>
      </div>
    </div>

    <div class="topic">
      <router-link to="/news">와인 모임</router-link>
      <router-link to="/news">양주 모임</router-link>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.topic {
  margin: 15px 15px 0px 15px;
  padding-bottom: 10px;
  border-bottom: 1px solid #d4d4d4;
}
.topic a {
  padding: 15px;
}
.topic a:visited {
  color: #94969b;
}
.topic a:active {
  color: #35495e;
}
.topic a.router-link-active {
  text-decoration: none;
  color: #94969b;
}
.header-wrapper {
  color: black;
  top: 0;
  z-index: 999;
  display: flex;
  flex-direction: column;
  justify-content: center;
  position: relative;
}
.header-content {
  display: flex;
  flex-direction: column;
  border-bottom: 1px solid #d4d4d4;
}
.header-tab .title {
  margin: 0px;
  padding: 0px;
  margin-left: 5px;
  margin-right: 70px;
  display: flex;
  flex-direction: column;
  align-items: center;
  line-height: 25px;
}
.header-tab .title h1 {
  color: #c62917;
  font-size: 2.5em;
  font-weight: 800;
  letter-spacing: -2px;
}
.header-tab a {
  margin: 0 15px 3px;
  font-size: 1.3em;
}
.header-tab {
  display: flex;
  justify-content: flex-start;
  align-items: flex-end;
  margin-top: 10px;
  margin-bottom: 10px;
  margin: 30px 30px 15px 30px;
  width: 1200px;
}
.header-tab a:visited {
  color: black;
}
.header-tab a:active {
  color: #35495e;
}
.header-tab a.router-link-active {
  text-decoration: none;
  color: black;
}
.fixed {
  position: fixed;
  width: 100%;
  z-index: 999;
}
</style>
