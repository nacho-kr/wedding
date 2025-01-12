<template>
  <div class="live">
    <p class = "desc">
      위 애니메이션은 꼭 소리를 켜고 봐주세요!
    </p>
    <img src="~@/assets/images/hands.png" class="hands" />
    <div>
      <p class = "header">
        "이제는 함께 합니다."<br />
      </p>
      <p>
        1997년 10월 15일<br />
        같은 날 태어나 다른 삶을 살아온 저희가,<br />
        이제는 하나가 되어 함께 걸어가려 합니다.<br />
        사랑이라는 말이 어울리는 사람과 함께.<br />
        기쁨이 가득한 결혼 소식을<br />
        알려드립니다.
      </p>
      <p class = "header">
        25년 5월 17일 토요일<br />
        17시 30분<br />
        라움 아트센터<br />
      </p>

    </div>
    <Button @click="attendance">앨범 구경하기<template>
  <div class="live">
    <p class = "desc">
      위 애니메이션은 꼭 소리를 켜고 봐주세요!
    </p>
    <img src="~@/assets/images/hands.png" class="hands" />
    <div>
      <p class = "header">
        "이제는 함께 합니다.<br />
      </p>
      <p>
        1997년 10월 15일<br />
        같은 날 태어나 다른 삶을 살아온 저희가,<br />
        이제는 하나가 되어 함께 걸어가려 합니다.<br />
        사랑이라는 말이 어울리는 사람과 함께.<br />
        기쁨이 가득한 결혼 소식을<br />
        알려드립니다.
      </p>
      <p class = "header">
        25년 5월 17일 토요일<br />
        17시 30분<br />
        라움 아트센터<br />
      </p>

    </div>
    <Button @click="attendance">앨범 구경하기</Button>
  </div>
</template>

<script>
export default {
  name: "Divider",
  methods: {
    attendance() {
      window.open("https://drive.google.com/drive/folders/1dmUd-frxoltnCk4RQLNeRxlk_p_uVWFW?usp=sharing");
    },
  },
};
</script>

<style lang="scss" scoped>
.live {
  padding-top: 4px;
  padding-bottom: 68px;
  padding-left: $padding-vertical;
  padding-right: $padding-vertical;
  text-align: center;
  .hands {
    width: 75px;
    margin-bottom: 16px;
  }
  p {
    margin-bottom: 16px;
    line-height: 24px;
    &.desc {
      color: #295238;
      font-size: 10px;
      opacity: 0.6;
      margin-bottom: 36px;
    }
    &.header {
      color: #295238;
    }
    &:last-child {
      margin-bottom: 40px;
    }
  }
}
</style>
