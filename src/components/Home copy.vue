<template>
  <!--  header  -->
  <div id="header">
    <img id="headerImg" alt="갤러리" src="@/assets/img/header.png"/>
  </div>
  <!--  header  -->

  <!--  container  -->
  <div id="wrap">
    <div id="content">
      <div class="youtubeMV">

      </div>
      <div class="award">
        <span class="awardImg01"></span>
        <span class="awardImg02"></span>
      </div>
      <div class="reform01">
        <ul class="reformImg01_1">
          <li class="reformImg01_1_1"><p class="reformImgTop">[소파 리폼]</p></li>
          <li class="reformImgInfo">
            <img alt="이미지소개" src="@/assets/icon/dsBuffer.png"/>
            <span>카시나 르고르뷔지예 LC 소파 복원</span>
          </li>
        </ul>
        <ul class="reformImg01_2">
          <li class="reformImg01_1_2"><p class="reformImgTop">[식탁/의자 리폼]</p></li>
          <li class="reformImgInfo">
            <img alt="이미지소개" src="@/assets/icon/dsBuffer.png"/>
            <span>10인용 이태리 식탁Set 복원</span>
          </li>
          <li class="reformImg01_1_3"><p class="reformImgTop">[가구 리폼]</p></li>
          <li class="reformImgInfo">
            <img alt="이미지소개" src="@/assets/icon/dsBuffer.png"/>
            <span>1930년대 영국 클래식 장식장 복원</span>
          </li>
        </ul>
      </div>
      <div class="reform02">
        <ul class="reformImg02_1">
          <li class="reformImg02_1_1"><p class="reformImgTop">[소파 리폼]</p></li>
          <li class="reformImgInfo">
            <img alt="이미지소개" src="@/assets/icon/dsBuffer.png"/>
            <span>연예인 베르사체 소파 복원</span>
          </li>
          <li class="reformImg02_1_2"><p class="reformImgTop">[고가구 리폼]</p></li>
          <li class="reformImgInfo">
            <img alt="이미지소개" src="@/assets/icon/dsBuffer.png"/>
            <span>덕감나무 앞닫이 3층장롱 복원</span>
          </li>
        </ul>
        <ul class="reformImg02_2">
          <li class="reformImg02_1_3"><p class="reformImgTop">[나전칠기 작품]</p></li>
          <li class="reformImgInfo">
            <img alt="이미지소개" src="@/assets/icon/dsBuffer.png"/>
            <span>(고)일사 김봉룡 선생(국가무형문화제 제10호) 애기2층장 복원</span>
          </li>
        </ul>
      </div>
      <div class="youtube">
        <img alt="유튜브 들어가기" src="@/assets/img/YouTube.jpg"/>
        <div class="youtubeLink">
          <img alt="유튜브 들어가기" src="@/assets/img/YouTubeImg.jpg"/>
        </div>
      </div>
      <div class="gallery">
        <div>
          <img alt="갤러리" src="@/assets/img/galleryLogo.png" class="galleryTitle"/>
          <span class="search_span">
            <img alt="검색" src="@/assets/icon/search_FILL0_wght400_GRAD0_opsz48.png" class="searchIcon"/>
            <input type="search" class="gallerySearch" placeholder="검색">
          </span>
        </div>
        <div class="galleryBlog">
          <ul>
            <li class="blogImg01"></li>
            <li class="blogInfo_Title01">디사모빌리에서 수입하는 독일ERPO의 ER100 리클라이너 쇼파 가죽갈이편!</li>
            <li class="blogInfo_content01">독일남부 에르팅겐에서 1952년 시작된 에르뽀</li>
            <li class="blogInfo_like01"><img alt="좋아요" src="@/assets/icon/favorite_FILL0_wght400_GRAD0_opsz48.png" class="blogInfo_LikeIcon"/><span>0</span></li>
          </ul>
          <ul>
            <li class="blogImg02"></li>
            <li class="blogInfo_Title02">7월 오픈 예정인 부단 기장 빌라쥬 드 아난티 현장 가구 실측 다녀왔습니다~</li>
            <li class="blogInfo_content02">엄마 환갑이라 이모들이랑 모이기로 한 4월 22일 토요일 이날 저는 부산 기장에 있었습니다. 저희 리나FRS에서 아난티에 가구리폼이나 수리 등 제작을 일부분 받아서 하고 있거든요</li>
            <li class="blogInfo_like02"><img alt="좋아요" src="@/assets/icon/favorite_FILL0_wght400_GRAD0_opsz48.png" class="blogInfo_LikeIcon"/><span>0</span></li>
          </ul>
          <ul>
            <li class="blogImg03"></li>
            <li class="blogInfo_Title03">레이지보이 1인 리모컨형 전통 매버릭 리클라이너 쇼파 리폼 금액 공개!</li>
            <li class="blogInfo_content03">간혹 상담바드시는 고객님들 중에 리클라이너를 추천해달라는 분들이 많습니다. 가장 중요한 건 가격이죠 어느 정도 금액을 생각하고 계시는지..</li>
            <li class="blogInfo_like03"><img alt="좋아요" src="@/assets/icon/favorite_FILL0_wght400_GRAD0_opsz48.png" class="blogInfo_LikeIcon"/><span>0</span></li>
          </ul>
        </div>
      </div><!--gallery-->
      <div class="story">
        <img alt="스토리" src="@/assets/img/hongsong_story.png" class="storyTitle"/>
        <div>
          <ul>
            <li class="storyList01"></li>
            <li class="storyList02"></li>
            <li class="storyList03"></li>
            <li class="storyList04"></li>
          </ul>
        </div>
      </div>
    </div><!--content-->
  </div><!--wrap-->

  <!--  container  -->

  <!--  footer  -->
  <!--  footer  -->
</template>

<script>

export default {
  name: 'Home',
  components: {
  },
}
</script>

<style scoped>
@import "@/assets/css/style.css";
html, body {
  margin: 0;
  padding: 0;
}

/* header */

/* container */
#wrap {
  width: 100%;
  margin: 0;
}
.award {
  margin: 100px auto 0 auto;
  text-align: center;
}

.awardImg01 {
  background-image: url("@/assets/img/award01.png");
  width: 330px;
  height: 80px;
  display: inline-block;
  margin-right: 30px;
  background-size: 330px 80px;
}

.awardImg02 {
  background-image: url("@/assets/img/award02.png");
  width: 330px;
  height: 80px;
  display: inline-block;
  background-size: 330px 80px;
}

.reform01 {
  margin: 50px auto 30px auto;
  text-align: center;
}

.reformImgTop {
  text-align: left;
  color: white;
  padding: 3px 0 0 5px;
  font-size: 13px;
}

.reformImgInfo {
  text-align: left;
}

.reformImgInfo img {
  margin: 5px 2px 0 3px;
  width: 13px;
  height: 10px;
}

.reformImgInfo span {
  font-size: 11px;
  margin-bottom: 3px;
}

.reformImg01_1 {
  display: inline-block;
}

.reformImg01_1_1 {
  background-image: url("@/assets/img/reform01_1.png");
  width: 520px;
  height: 525px;
  display: inline-block;
  background-repeat: no-repeat;
  background-size: 520px 525px;
}

.reformImg01_2 {
  display: inline-block;
  margin-left: 8px;
}

.reformImg01_1_2 {
  background-image: url("@/assets/img/reform01_2.png");
  width: 520px;
  height: 250px;
  display: block;
  background-repeat: no-repeat;
  background-size: 520px 250px;
}

.reformImg01_1_3 {
  background-image: url("@/assets/img/reform01_3.png");
  width: 520px;
  height: 250px;
  display: block;
  background-repeat: no-repeat;
  background-size: 520px 250px;
  margin-top: 6px;
}

.reformImg02_1 {
  display: inline-block;
}

.reformImg02_1_1 {
  background-image: url("@/assets/img/reform02_1.png");
  width: 520px;
  height: 250px;
  display: block;
  background-repeat: no-repeat;
  background-size: 520px 250px;
  margin: 1px 0 0 0;
}

.reformImg02_1_2 {
  background-image: url("@/assets/img/reform02_2.png");
  width: 520px;
  height: 250px;
  display: block;
  background-repeat: no-repeat;
  background-size: 520px 250px;
  margin-top: 6px;
}

.reformImg02_2 {
  display: inline-block;
  margin-left: 8px;
}

.reformImg02_1_3 {
  background-image: url("@/assets/img/reform02_3.png");
  width: 520px;
  height: 525px;
  display: inline-block;
  background-size: 520px 525px;
}

.youtube {
  margin-top: 40px;
}

.youtubeLink {
  margin-top: 30px;
}

.youtubeLink img {
  width: 900px;
  height: 550px;
}

.gallery {
  margin: 100px auto;
  width: 100%;
}

.galleryTitle {
  width: 100px;
  height: 25px;
  position: absolute;
  margin-left: -50px;
}
.gal1-Title {
  width: 100px;
  height: 25px;
}
.search_span {
  width: 175px;
  height: 30px;
  border: 1px solid black;
  position: absolute;
  margin-left: 270px;
}

.gallerySearch {
  width: 150px;
  height: 25px;
  border: 0;
  outline: none;
  background-color: hsl(160, 0%, 237%);
  padding: 0 0 0 3px;
}

.searchIcon {
  width: 20px;
  height: 20px;
  float: right;
  margin: 3px 3px 0 0;
}
.galleryBlog {
  width: 890px;
  margin: 0 auto;
}

.galleryBlog ul{
  position: absolute;
  margin-top: 40px;
}
.blogImg01 {
  background-image: url("@/assets/img/sofa01.png");
  display: inline-block;
  width: 280px;
  height: 260px;
  background-size: 310px 260px;
}
.galleryBlog .blogInfo_Title01 {
  text-align: center;
  margin-top: 10px;
  width: 280px;
  font-weight: bold;
  font-size: 14px;
}
.galleryBlog .blogInfo_content01 {
  margin-top: 5px;
  width: 280px;
  font-size: 10px;
}
.galleryBlog .blogInfo_LikeIcon {
  width: 15px;
  height: 15px;
}
.galleryBlog .blogInfo_like01 {
  margin-top: 5px;
  text-align: left;
  font-size: 10px;
}
.galleryBlog .blogInfo_like01 span {
  font-size: 13px;
  margin-left: 3px;
}
.blogImg02 {
  background-image: url("@/assets/img/sofa02.png");
  display: inline-block;
  width: 280px;
  height: 260px;
  margin-left: 305px;
  background-size: 310px 260px;
}
.galleryBlog .blogInfo_Title02 {
  text-align: center;
  margin-top: 10px;
  margin-left: 300px;
  width: 280px;
  font-weight: bold;
  font-size: 14px;
}
.galleryBlog .blogInfo_content02 {
  margin-top: 5px;
  margin-left: 300px;
  width: 280px;
  font-size: 10px;
}
.galleryBlog .blogInfo_like02 {
  margin-top: 5px;
  text-align: left;
  font-size: 10px;
  margin-left: 300px;
}
.galleryBlog .blogInfo_like02 span {
  font-size: 13px;
  margin-left: 3px;
}
.blogImg03 {
  background-image: url("@/assets/img/sofa03.png");
  display: inline-block;
  width: 280px;
  height: 260px;
  margin-left: 610px;
  background-size: 280px 260px;
}
.galleryBlog .blogInfo_Title03 {
  text-align: center;
  margin-top: 10px;
  margin-left: 610px;
  width: 280px;
  font-weight: bold;
  font-size: 14px;
}
.galleryBlog .blogInfo_content03 {
  margin-top: 5px;
  margin-left: 610px;
  width: 280px;
  font-size: 10px;
}
.galleryBlog .blogInfo_like03 {
  margin-top: 5px;
  text-align: left;
  font-size: 10px;
  margin-left: 610px;
}
.galleryBlog .blogInfo_like03 span {
  font-size: 13px;
  margin-left: 3px;
}
.story {
  width: 900px;
  margin: 0 auto;
}
.storyTitle {
  width: 150px;
  height: 25px;
  position: absolute;
  margin-left: -70px;
  margin-top: 430px;
}
.story ul {
  position: absolute;
  margin-top: 480px;
}
.story .storyList01 {
  background-image: url("@/assets/img/banner01.png");
  display: inline-block;
  width: 220px;
  height: 150px;
  margin-left: 5px;
  background-size: 220px 150px;
}
.story .storyList02 {
  background-image: url("@/assets/img/banner02.png");
  display: inline-block;
  width: 220px;
  height: 150px;
  margin-left: 5px;
  background-size: 220px 150px;
}
.story .storyList03 {
  background-image: url("@/assets/img/banner03.png");
  display: inline-block;
  width: 220px;
  height: 150px;
  margin-left: 5px;
  background-size: 220px 150px;
}
.story .storyList04 {
  background-image: url("@/assets/img/banner04.png");
  display: inline-block;
  width: 220px;
  height: 150px;
  margin-left: 5px;
  background-size: 220px 150px;
}
/* footer */
#footer {
  bottom: 0px;
}

#headerImg {
  width: 100vw;
}
</style>