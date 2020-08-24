<template>
  <div class="header-wrapper" ref="appHeader">
    <div class="header-content">
      <div class="header-top">
      <p class="time">UTC+09:00, 2020년 08월 24일 월요일</p>
      <div class="user">
        <button>로그인</button>
        <button>회원가입</button>
      </div>
      </div>
      <div class="header-tab">
        <img src="../assets/logo.svg" alt="logo" class="logo">
        <p class="title">Short News.com</p>
        <router-link to="/news">뉴스</router-link> |
        <router-link to="/ask">질문</router-link> |
        <router-link to="/jobs">일</router-link>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.header-wrapper {
  background-color: #42b883;
  border-bottom: 1px solid #42b223;
  color: white;
  top: 0;
  z-index: 999;
  display: flex;
  justify-content: center;
  position: sticky;
}
.header-content {
  display: flex;
  flex-direction: column;
  width: 1200px;
  margin : 15px 30px 0px 30px;
}
.header-tab .title {
  margin : 0px;
  padding : 0px;
  font-weight: bold;
  font-size: 2em;
  margin-left: 5px;
  margin-right: 70px;

}
.header-top {
  display: flex;
  justify-content: space-between;
}
.header-top button {
  background-color: rgba(0,0,0,0);
  color: white;
  border: none;
  text-decoration: none;
  cursor: pointer;
}
.header-top .user button {
  margin: 0px 5px 0px 5px;  
}
.header-top .time {
  font-size: 0.9em;
}
.header-tab {
  display: flex;
  justify-content: flex-start;
  align-items:baseline;
  margin-top: 10px;
}
.header-tab a:visited {
  color: white;
}
.header-tab a:active {
  color: #35495e;
}
.header-tab a.router-link-active {
  text-decoration: none;
  color: blanchedalmond;
}
.fixed {
  position: fixed;
  width: 100%;
  z-index: 999;
}
.logo {
  width: 30px;
  margin-right: 5px;
}
a {
  margin: 0 5px;
}
</style>
