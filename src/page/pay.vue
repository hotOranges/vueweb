<template>
   <div class="main index">
        <div class="h_10"></div>
        <div class="h_10"></div>
        <div class="s_main1080 s_warp">
            <img src="../../static/images/setp3.png" alt="">
        </div>
        <div class="h_10"></div>
        <div class="s_main1080 main">
            <div class="row-s selectingoffer pay">
                <div class="row text-center">
                    <!-- <img src="../../static/images/icon-no-pass.png" alt="">
                    <span>核保未通过！</span> -->
                    <img src="../../static/images/icon-pass.png" alt="">
                    <span>核保通过！</span>
                </div>
                <div class="row">
                    <p @click="detial" class="s-cursor">
                        <i>温馨提示：</i>请再次核对您本次的支付信息，如果确定无误请点击“立即支付”。查看投保信息</p>
                </div>
                <div class="row s-pay-title">
                    <div class="col-sm-4">
                        投保单号
                    </div>
                    <div class="col-sm-2 text-center">
                        投保人姓名
                    </div>
                    <div class="col-sm-5 text-center">
                        起保期间
                    </div>
                    <div class="col-sm-2 text-center">
                        金额
                    </div>
                </div>
                <div class="row s-pay-content">
                    <div class="col-sm-4">
                        TDDC201731012400031239
                    </div>
                    <div class="col-sm-2 text-center">
                        张三
                    </div>
                    <div class="col-sm-5 text-center">
                        2017-12-27
                    </div>
                    <div class="col-sm-2 text-center">
                        7085.14
                    </div>
                </div>

            </div>
        </div>
        <div class="h_10"></div>
        <div class="s_main1080 s_next">
            <div class="next_btn">
                <button type="submit" class="s-default">立即支付</button>
            </div>

        </div>
        <footer class="foot">
            <p>车险出单平台 版权所有</p>
            <p>Copyright@2017 Chexianchudanpingtai</p>
        </footer>
    </div>
</template>

<script>
export default {
  data () {
    return {
    };
  },
  methods: {
      detial:function(){
          this.$router.push("insuranceDetial");
      }
  }
}

</script>
<style>
</style>