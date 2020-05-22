<template>
  <div class="man-box">
        <dv-border-box-10>
          <div class="man-org-name">
          <div class="man-org"><span>今日疫情防控消毒情况</span></div>
          <div class="man-in-name"><h4>车 间</h4>
          <div class="man-in-name-detail">
            消毒点：
            <div class="man-value">9个</div>
          </div>
           <div class="man-in-name-detail-1">
            累计消毒次数：
            <div class="man-value-1">28次</div>
          </div>
           <div class="man-in-name-detail-2">
            平均消毒频率：
            <div class="man-value-2">3.1次/个</div>
          </div>
          </div>
           <div class="man-in-office"><h4>办公区</h4>
            <div class="man-in-name-detail">
            消毒点：
            <div class="man-value">8个</div>
          </div>
           <div class="man-in-name-detail-1">
            累计消毒次数：
            <div class="man-value-1">17次</div>
          </div>
           <div class="man-in-name-detail-2">
            平均消毒频率：
            <div class="man-value-2">2.1次/个</div>
          </div>
           </div>
          </div>
        </dv-border-box-10>
  </div>
</template>
<script>
export default {

}
</script>
<style scoped>
.man-box{
   width: 620px;
   height: auto;
   margin-top: -22px;
 }
 .man-org-name{
   width: 100%;
   height: 100%;
 }
  .man-org{
   width: 100%;
 }
  span{
    font-size: 20px;
    margin-left: 216px;
  }
  .man-in-name{
    width: 50%;
    height: 80%;
    float: left;
    text-align: center;
  }
  h4{
    font-size: 20px;
  }
  .man-in-office{
    width: 50%;
    height: 80%;
    float: left;
    text-align: center;
  }
  .man-in-name-detail{
    font-size: 18px;
    float: left;
    font-weight: bold;
    margin: 20px 68px;
  }
  .man-value{
    font-size: 18px;
    clear: both;
    font-weight: bold;
    color: darkorange;
    float: right;
    margin-left: 66px;
  }
  .man-in-name-detail-1{
    font-size: 18px;
    float: left;
    font-weight: bold;
    margin: 20px 15px;
  }
  .man-value-1{
    font-size: 18px;
    clear: both;
    font-weight: bold;
    color: darkorange;
    float: right;
    margin-left: 66px;
  }
   .man-in-name-detail-2{
    font-size: 18px;
    float: left;
    font-weight: bold;
    margin: 20px 15px;
  }
  .man-value-2{
    font-size: 18px;
    clear: both;
    font-weight: bold;
    color: darkorange;
    float: right;
    margin-left: 66px;
  }
</style>
