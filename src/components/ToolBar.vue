<template>
  <!-- fixed 코드 -->
  <!-- :class="{ 'fixed': isFixed }" -->
  <div class="header-wrapper" ref="appHeader">
    <div class="header-content">
      <img src="../assets/logo.svg" alt="logo" class="logo">
      <router-link to="/news">News</router-link> |
      <router-link to="/ask">Ask</router-link> |
      <router-link to="/jobs">Jobs</router-link>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      navHeight: 0,
      isFixed: false,
    }
  },
  mounted() {
    this.navHeight = this.$refs.appHeader.offsetHeight;
    window.addEventListener('scroll', this.checkHeight);
  },
  methods: {
    checkHeight() {
      this.isFixed = window.scrollY > this.navHeight ? true : false;
    }
  },
  beforeDestroy() {
    window.removeEventListener('scroll', this.checkHeight);
  }
}
</script>

<style scoped>
.header-wrapper {
  background-color: #42b883;
  border-bottom: 1px solid #42b223;
  color: white;
  height: 96px;
  z-index: 999;
  text-align: center;
}
.header-content {
  display: inline-block;
  width: 1200px;
  text-align: left;
}
.header-content a:visited {
  color: white;
}
.header-content a:active {
  color: #35495e;
}
.fixed {
  position: fixed;
  width: 100%;
  z-index: 999;
}
.logo {
  width: 30px;
  margin-right: 18px;
}
a {
  margin: 0 5px;
}
</style>
