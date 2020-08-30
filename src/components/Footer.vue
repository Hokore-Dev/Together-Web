<template>
  <div class="footer-wrapper" ref="appFooter">
    <div class="linker">
      <router-link to="/jobs">서비스 소개</router-link>
      <router-link to="/jobs">이용약관</router-link>
      <router-link to="/jobs">디렉토리</router-link>
      <router-link to="/jobs">개인정보 처리방침</router-link>
      <router-link to="/jobs">기업 서비스</router-link>
    </div>
    <p>© 2020 TeamTogether. Inc</p>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.footer-wrapper {
  display: flex;
  flex-direction: column;
  margin: 30px 40px 40px 40px;
}
.footer-wrapper p {
  color: #bbc0c5;
  letter-spacing: -0.5px;
}
.footer-wrapper .linker {
  margin-bottom: 10px;
}
.footer-wrapper .linker a {
  padding: 8px;
}
.footer-wrapper .linker a:visited {
  color: #94969b;
}
.footer-wrapper .linker a:active {
  color: #35495e;
}
.footer-wrapper .linker a.router-link-active {
  text-decoration: none;
  color: #94969b;
}
</style>