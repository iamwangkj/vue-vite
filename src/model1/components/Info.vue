<template>
  <div class="section info">
    <!-- <div class="section-title">产品参数</div> -->
    <div class="row">
      <div class="label">品牌:</div>
      <div class="val">FASUM (花芯)</div>
    </div>
    <div class="row">
      <div class="label">品名:</div>
      <div class="val">小金鱼项链</div>
    </div>
    <div class="row">
      <div class="label">材质:</div>
      <div class="val">S925银+猫眼石</div>
    </div>
    <div class="row">
      <div class="label">链长:</div>
      <div class="val">40cm+5cm(可调节)</div>
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
.row {
  width: 600px;
  margin: 0 auto;
  font-size: 30px;
  display: flex;
  // justify-content: space-between;
  border-bottom: 1px solid #a4958f;
  margin-bottom: 10px;
  padding-top: 20px;

  .label {
    width: fit-content;
    // font-size: 1.1em;
    text-align: center;
    border-bottom: 6px solid #9c6550;
    margin-right: 40px;
  }
  .val {
    text-align: right;
    font-style: italic;
  }
}
</style>
