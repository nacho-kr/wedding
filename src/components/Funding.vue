<template>
  <div class="funding">
    <img src="~@/assets/images/flower.png" class="flower" />
    <h2 class="h2">
      축하해주셔서 감사합니다.
    </h2>
    <p>
    <Button @click="funding"> 참석 여부 알리기</Button>
  </div>
</template>

<script>
export default {
  name: "Divider",
  methods: {
    funding() {
      window.open("https://joey.team/block/?id=adv7EanqvKXC7bMCsefkgAsxlby2&block_id=W2RNLZJ1Ydm0i2IfvImU");
    },
  },
};
</script>

<style lang="scss" scoped>
.funding {
  padding-top: 48px;
  padding-bottom: 72px;
  padding-left: $padding-vertical;
  padding-right: $padding-vertical;
  text-align: center;

  .flower {
    width: 70px;
    margin-bottom: 26px;
  }
  .h2 {
    font-size: 16px;
    font-weight: normal;
    margin-bottom: 24px;
    color: #295138;
  }
  p {
    margin-bottom: 32px;
    line-height: 24px;
    color: #202121;
  }
  .link {
    display: inline-block;
    margin-top: 24px;
    color: #295238;
  }
}
</style>
