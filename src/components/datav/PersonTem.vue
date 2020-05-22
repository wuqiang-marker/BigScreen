<template>
    <div class="per-tem-detail">
       <dv-border-box-8>
          <div class="per-tem-border">
            <div class="per-header">今日员工监测情况</div>
            <div class="per-tem-info-1">
              出勤：<span class="per-span1">26人</span>
            </div>
            <div class="per-tem-info-2">
            缺勤：<span class="per-span2">26人</span>
            </div>
             <div class="per-tem-info-3">
            出勤率：<span class="per-span3">100%</span>
            </div>
             <div class="per-tem-info-4">
            体温正常：<span class="per-span4">36人</span>
            </div>
             <div class="per-tem-info-5">
            体温异常：<span class="per-span4">36人</span>
            </div>
             <div class="per-tem-info-6">
            合格率：<span class="per-span4">100%</span>
            </div>
            <!-- <div class="circle-box">
              <div class="circle">
                <span>一楼中央厨房</span>
              </div>
            </div> -->
          </div>
       </dv-border-box-8>
    </div>
</template>
<script>
export default {

}
</script>
<style scoped>
 .per-tem-detail{
   width: 620px;
   height: auto;
 }
  .per-tem-border{
    width: 620px;
    height: 350px;
  }
   .per-header{
   font-size: 20px;
   columns: #ffffff;
   margin-left: 219px;
 }
 .per-tem-info-1{
   float: left;
   font-size: 20px;
   margin-left:60px;
   margin-top:10px;
  }
  .per-span1{
    margin-left: 20px;
    color: darkorange;
    font-weight: bold;
  }
  .per-tem-info-2{
   float: left;
   font-size: 20px;
   margin-top:10px;
   margin-left: 57px;
  }
   .per-span2{
    margin-left: 20px;
    color: darkorange;
    font-weight: bold;
  }
  .per-tem-info-3{
   float: left;
   font-size: 20px;
   margin-top:10px;
   margin-left: 66px;
  }
   .per-span3{
    margin-left: 20px;
    color: darkorange;
    font-weight: bold;
  }
  .per-tem-info-4{
   float: left;
   font-size: 20px;
   margin-top:10px;
   margin-left: 21px;
  }
   .per-span4{
    margin-left: 20px;
    color: darkorange;
    font-weight: bold;
  }
  .per-tem-info-5{
   float: left;
   font-size: 20px;
   margin-top:10px;
   margin-left: 16px;
  }
   .per-span5{
    margin-left: 20px;
    color: darkorange;
    font-weight: bold;
  }
  .per-tem-info-6{
   float: left;
   font-size: 20px;
   margin-top:10px;
   margin-left: 66px;
  }
   .per-span6{
    margin-left: 20px;
    color: darkorange;
    font-weight: bold;
  }
  .circle{
    width:30px;
    height:30px;
    -moz-border-radius:15px;
    -webkit-border-radius:15px;
    border-radius:25px;
    background-color:#0F0;
    /* position:absolute; */
  }
   span{
     font-size: 15px;
   }
  .circle-box{
    width: 100%;
    height: 90%;
  }
</style>
