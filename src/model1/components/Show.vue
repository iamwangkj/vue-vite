<template>
  <div class="section detail">
    <div class="container">
      <!-- l1 -->
      <div class="row">
        <div class="bg-circle">
          <div class="bg-white">
            <div class="img d1"></div>
          </div>
        </div>
        <div class="text-wrapper">
          <div class="lightspot">精湛抛光技术</div>
          <div class="desc">多层抗氧化电镀工艺反复打磨雕琢，不但可以保护银质，而且可以增添光亮</div>
        </div>
      </div>
      <!-- l2 -->
      <div class="row">
        <div class="text-wrapper">
          <div class="lightspot">S925银材质</div>
          <div class="desc">采用S925银材质，亲肤舒适，不易过敏，不易氧化</div>
        </div>
        <div class="bg-circle">
          <div class="bg-white">
            <div class="img d2"></div>
          </div>
        </div>
      </div>
      <!-- m -->
      <div class="img1-wrapper">
        <div class="img"></div>
      </div>
      <div class="wrapper2">
        <div class="img2-wrapper">
          <div class="img"></div>
        </div>
        <div class="img2-wrapper">
          <div class="img2"></div>
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { ref, defineComponent } from 'vue'

export default defineComponent({
  props: {},
  setup (props) {},
  data () {
    return {}
  }
})
</script>

<style scoped lang="scss">
.detail {
  width: 100%;
  height: 2088px;
  background: url("../assets/bg-detail.jpg") center/cover no-repeat;
  padding-top: 200px;
  position: relative;
}

.container {
  width: 700px;
  margin: 0 auto;
}

.row {
  margin-bottom: 40px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.bg-circle {
  width: 400px;
  height: 400px;
  background: #fff5eb;
  border-radius: 50%;
  position: relative;
  .bg-white {
    width: 100%;
    height: 100%;
    background: #fff;
    border-radius: 50%;
    position: absolute;
    left: -20px;
    top: -20px;
    .img {
      width: 100%;
      height: 100%;
      border-radius: 50%;
      position: absolute;
      left: -20px;
      top: -20px;
    }
    .d1 {
      background: url("../imgs/d1.jpg") center/cover no-repeat;
    }
    .d2 {
      background: url("../imgs/d2.jpg") center/cover no-repeat;
    }
  }
}
.text-wrapper {
  width: 250px;
  margin-top: -150px;
  .lightspot {
    color: #844d38;
    font-size: 34px;
    // font-style: italic;
    line-height: 2;
  }
  .desc {
    color: #be7c5f;
    line-height: 1.5;
  }
}

.img1-wrapper {
  box-sizing: border-box;
  width: 700px;
  height: 500px;
  background-color: #fff;
  padding: 10px;
  box-shadow: 5px 5px 10px #999;
  margin-bottom: 30px;
  .img {
    width: 100%;
    height: 100%;
    background: url("../imgs/d3.jpg") center/cover no-repeat;
  }
}

.wrapper2 {
  display: flex;
  justify-content: space-between;
}

.img2-wrapper {
  box-sizing: border-box;
  width: 340px;
  height: 440px;
  background-color: #fff;
  padding: 10px;
  box-shadow: 5px 5px 10px #999;
  .img {
    width: 100%;
    height: 100%;
    background: url("../imgs/d4.jpg") center/cover no-repeat;
  }
  .img2 {
    width: 100%;
    height: 100%;
    background: url("../imgs/d5.jpg") center/cover no-repeat;
  }
}

</style>
