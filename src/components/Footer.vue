<template>
  <div class="footer-wrapper" ref="appFooter">
    <div class="footer-content">
      <div class="logo">
      <img src="../assets/logo.svg" alt="logo" class="logo">
      <p class="title">TestCommunity.com</p>
    </div>
    <div class="info">
      <p class="short-msg">치킨무 족발 보쌈 피자 먹어본지가 언젠지</p>
      <p class="description">아 피곤하다. 자고 싶다. 코딩하자.
        <br>
        똑똑한 AI 번역기 파파고, 언어 장벽 없이 대화하는 세상을 꿈꿉니다.<br>
        미국/영국식 발음, 한영,영한,영영사전, 분야별/중요도별 단어찾기<br>
        중고교 교과서 단어찾기, 명언·속담 검색서비스 등 제공.</p>
      <p class="company">제휴제안: <a>biz@chicken.co.kr</a>   고객센터: <a>cs@pizza.co.kr</a><br>
      법인명(단체명):주식회사 피나치공<br>
      사업장 소재지: 광주시 오포읍 신현로 65-22 현대모닝사이드1차 상가<br>
      2020 PNCG</p>
    </div>
    <div class="button-layer">
      <div class="follow">
      <p>Follow Us</p>
      <img class="twitter">
      <img class="facebook">
      <img class="telegram">
    </div>
    <div class="subsdcribeUs">
      <p>Subscribe Us</p>
      <img class="twitter">
      <img class="facebook">
    </div>
    </div>
    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.footer-wrapper {
  background-color: #19212d;
  border-top: 1px solid #232a4a;
  color: white;
  z-index: 999;
  display: flex;
  justify-content: center;
}

.footer-content {
  display: flex;
  flex-direction:row;
  width: 1200px;
  margin : 50px 30px 50px 30px;
}

.logo {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  align-items: center;
  /* margin: 30px; */
  margin-top : 15px;
  margin-right: 50px;
}

.logo img {
  width: 60px;
  margin: 0px;
  padding: 0px;
  margin-bottom: 20px;
}

.logo .title {
  font-weight: bold;
  font-size: 1.5em;
}

.info {
  margin-right: 100px;
}

.info .short-msg {
  color: #61688a;
  margin-bottom: 15px;
  font-size: 0.9em;
}

.info .description {
  color: #C7CCE6;
  font-size: 0.88em;
  line-height: 145%;
}

.info .company {
  color: #61688a;
  font-size: 0.78em;
  line-height: 160%;
}

.info .company a {
  color: #6F90F7;
}

.follow {
  margin-bottom: 20px;
}

.follow p {
  color: #61688a;
  margin-bottom: 10px;
}

.subsdcribeUs p {
  color: #61688a;
  margin-bottom: 10px;
}

.twitter {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAAAh1BMVEUAAABzeJpiaIthaIthaYthaYuLkbNhaYtiaYthaIpiaYtiaYtnbYxqcZViaYtiaItiaYtiaotjaoxjaoxhaIphaYtiaYpka41haIphaItiaYtiaYtiaYtjaotkaoxhaYpiaYtiaYtlbo9ob5BhaYtiaIthaYpiaYtjaotiaoxiaYthaYthaIqpd23kAAAALHRSTlMAB/rz7ugDzWjfdHkVDdPHflZBLOOblyPZs2NeiEc2wbqNHRGqpINtUD6RobB/+bgAAAJsSURBVFjDndbpeqowEAbggYAssgiyCm7VWm2/+7++0z6elmwQ8P0ZHUImMyE0Jr6vy1PDHLcI0vIjj2iRw+ZoQ5SGbzST1XnQSn2LzOKNi1GBvyKDzMWkoKMpby2M2mhieoYZ3D2NWGOmG+msSsz2qYtvsUCp7kaJRd4N6zdbS/nHUnYu7D/DYi7fGy1ecDIswOz+1z8uXtL8NucGRm4SQBX+73/XFB3WRHTpGvxwEvxynq+wA+dLUzPxb7HeAM+PuPmevZ1gcKRPSCoaHC5EN+HvP4Pg+ERnCBKLBDs4XDpqOYX7YWAY4R36e+0Mv/ZElILzoG+Pgkug0nYXDwOPKLbByZ6F0f8NtiSJ+HjYFt3BO9NTXTH90VFL9fAY+lh649g/2QBKEnVKV5dycQ2sPKzWJG+C6EonCNiWJn0oLdmIm3Zrp59whsgjBt6WDK4QFeRArESDAiJGYiumhvgtJLb8yIwmhZA4FCzahRSSQBli9yUrgKf5Il1zi0ZU6mmjVIa9zw9jD4gYZBvKDd8sw/czowiYm8YtVBGRpyR25AlWAkWi21ow/XXua+SmUUNVnDNLrSGNA33zoGoes+KbocXFcWUNq37ilmEVQh0k51w5id+O0GEX6ZRxwzpaadIfOtDqieRXSLpYCd8F0HMi3Ulpt92Fi35UDGP8sSuO7b1v/F3nb6rUxjiPW23kYjGnJs7+xWveoMdCvuGsMKkMvWJy0pTL6rpg/hXpbObmz6cRe2fW/vH5V5vGKK1pShYYpt+RgbVmE+G3C5nFuxRaTRjTTNvek9soOR9okThfX49JwWwn+G7OLKIR/wAmuZ5tcgC81QAAAABJRU5ErkJggg==) no-repeat 50%;
  background-size: cover;
  border: none !important;
  outline: none;
  margin-left: 0;
  width: 30px;
  height: 30px;
  background-color: transparent;
  text-decoration: none;
  margin-right: 20px;
}

.facebook {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAAAXVBMVEUAAABkao1iaItiaYtla5JhaYthaIpiaIpiaYtiaYxiaYuTmKNkaY5kdptiaYpiaYpiaIpjaopja41iaYphaIpiaYthaYthaYtiaYpiaYtiaY9iaYxjaoxiaYthaIosB3ifAAAAHnRSTlMANOyKE/b6j39iUgM9DO/WzHQe6t/TxaWyXCJsSJ72S+ZXAAABpUlEQVRYw6TS227DIBBF0WNEAOP7PWnT8/+f2SiWXNUeDFbWs9nyDCBEe7e0ozJGje3ivMYlmZ24M9kMiaquoajpKsRpVzOodhoRueIpleNMPzNq7hFUDkwwlAjIDZMYeYzCMpkthPN3XnA/FiwvsYf5eVG+27+hqHFlvz4/v99k+e/+B0puD2w8d4Yef2b5fIaTAOfoAr4hBKQ1aEWJqiIBpbFyFP0gEqDDW1XHJii01tKY9fqPHWXP7Y0aBnTAS0NZidWTQQ1eMgZkWD24Eb+xnwQsgOmTwARoRgO3N4o0PCVfLwU24VV5OEpw4ClyWBIDHUUL2sSApajFmBi4UzRCJQZaihRMYkBRZH5Lr5MVAGEohqJxwurCefj/P1V44C5SeruWsyjSJAbo3lMpThO/gQN8mH7Ab9jqYMChhQGLbgbcSgxIGhkwqmVAK50EOCX1BOglVQCIb+ZyYI6nohxYTbQZwEWbUimQTLwbwMe7hkzA96yrBLhMycoF9s3UPAe4muevYarjdOYCYNXFZZvXfT44+OTho4vPPj48+fTl4xvP/wdpeD3ZzKQlMwAAAABJRU5ErkJggg==) no-repeat 50%;
  background-size: cover;
  border: none !important;
  outline: none;
  margin-left: 0;
  width: 30px;
  height: 30px;
  background-color: transparent;
  text-decoration: none;
  margin-right: 20px;
}

.telegram {
  background: url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAEAAAABACAMAAACdt4HsAAAAe1BMVEUAAABhaIphaYphaIuTk6diaIxkao1ndZhkbZJka4xhaIpiaItiaIpiaItiaYpiaYthaIphaYtiaYtjaoxhaYtiaothaYxoa5ZiaYtiaIphaYtiaYtiaYtnbI5iaYpiaYthaItiaYtjaYxkaYxiaIxhaYpibI1iaYthaIriQAhwAAAAKHRSTlMA+u3qBGIzDBQg39bMxXRS0qaMO7KAfhCP5PKFbxm+l2dbSkOgnCq4ZqYwBAAAAjBJREFUWMOll+mWgjAMhVNApiL7poC4jMvk/Z9wDogc2sYC9vvjUWhtb5PcFD7BozLxPYsxy/OTMuKwCjeNUSJO3aWjf8IdkuzCH5hnX1j4EavYz43f2KjF3miHbwOcJdh+Hp/ZuAA7+7h8hotg9DacAy7m4BDjc1xBrs5wwFUclP3jSiQdMoYrYZlw/jauxp7GQ4BfEBgIIMmwt/Er7HdmFfglxZD/Fn6J9aoPIS4lDq9irQmhY7fw785dTYvEGtXXP1zC6fpa7g0FujlTnKVqxqC5oEAKAPFczCa/k9S7S6oA8Bndjnyo9BEpGB9UoanP7rvUn6tn/4kSEZRa3QaiarelNEQsIZnVDbY5BhzomEnAp3TLJ7o5xxrz91qUuueDRzgYn9qkj3gfp6tQwgNL0u2RCT6ZMsRm/Nqq8QlMSNCLaJ+/3fqOMBKpuxUnEB28Tbo3rpNfGnUCcQuPdvL2pXtU32DCSd2CLGIQDsf3DPo9CWtyapTxiGOMGxechvWPRSd+ooJPB1LlvZ7yWfdJNKGMf3JHc0aFUpNMgWygVNRGmnR+KAZO+B/XFJRUaWCIcqEraSFIHIk/0RXVS5cL90kgEAfm6sp6BLAPkI2pQCWu1lhuwHvZ8yEaOLFLrbW57aBvlb1Sk7A2rbmm45JZ6ZCvFcvt/dSCs1PtfUWDUSdqGG5MWxzjJsu0zTNtNE1bXeNm27zdN79wmF95zC9d5tc+84un+dXX/PJtfP3/B8Zlo/QCJ2bxAAAAAElFTkSuQmCC) no-repeat 50%;  background-size: cover;
  border: none !important;
  outline: none;
  margin-left: 0;
  width: 30px;
  height: 30px;
  background-color: transparent;
  text-decoration: none;
}
</style>