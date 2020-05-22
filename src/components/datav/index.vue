<template>
  <div id="data-view">
    <dv-full-screen-container>
      <div class="main-header">
        <div class="mh-middle">疫情防控管理驾驶舱</div>
      </div>

      <dv-border-box-1 class="main-container">
        <div class="mc-top">
          <Top-right-Cmp />
          <Person-tem />
          <Manager-org />
        </div>
        <div class="mc-top">
          <Top-right-Cmp2 />
           <Bottom-Right-Table-1 />
           <Instruction/>
        </div>
         <div class="mc-top">
         <Qrcode/>
         <Qrcode1/>
         <Qrcode2/>
        </div>
      </dv-border-box-1>

    </dv-full-screen-container>
  </div>
</template>

<script>
import TopLeftCmp from './TopLeftCmp'
import TopMiddleCmp from './TopMiddleCmp'
import TopRightCmp from './TopRightCmp'
import TopRightCmp2 from './TopRightCmp2'
import BottomLeftChart1 from './BottomLeftChart1'
import BottomLeftChart2 from './BottomLeftChart2'
import PersonTem from './PersonTem'
import ManagerOrg from './ManagerOrg'
import Instruction from './Instruction'
import Qrcode from './Qrcode'
import Qrcode1 from './Qrcode1'
import Qrcode2 from './Qrcode2'
import BottomRightTable1 from './BottomRightTable1'
import BottomRightTable2 from './BottomRightTable2'
import BottomRightTable3 from './BottomRightTable3'
import BottomRightTable4 from './BottomRightTable4'

export default {
  name: 'DataView',
  components: {
    TopRightCmp2,
    TopLeftCmp,
    TopMiddleCmp,
    Qrcode2,
    Qrcode1,
    Qrcode,
    Instruction,
    TopRightCmp,
    PersonTem,
    ManagerOrg,
    BottomLeftChart1,
    BottomLeftChart2,
    BottomRightTable1,
    BottomRightTable2,
    BottomRightTable3,
    BottomRightTable4
  },
  data () {
    return {}
  }
}
</script>

<style lang="less">
#data-view {
  width: 100%;
  height: 100%;
  background-color: #030409;
  color: #fff;

  #dv-full-screen-container {
    background-image: url('./img/bg.png');
    background-size: 100% 100%;
    box-shadow: 0 0 3px blue;
    display: flex;
    flex-direction: column;
  }

  .main-header {
    height: 45px;
    display: flex;
    justify-content: space-between;
    align-items: flex-end;

    .mh-left {
      font-size: 20px;
      color: rgb(1,134,187);

      a:visited {
        color: rgb(1,134,187);
      }
    }

    .mh-middle {
       margin-right: auto;
      margin-left: auto;
      font-size: 30px;
    }

    .mh-left, .mh-right {
      width: 450px;
    }
  }

  .main-container {
    height: calc(~"100% - 80px");

    .mc-top, .mc-bottom {
      box-sizing: border-box;
      padding: 30px;
      display: flex;
    }

    .mc-top {
      height: 40%;
    }
    mc-top-1{
      height: 60%;
    }

    .mc-bottom {
      height: 60%;
    }
    mc-bottom-1{
      height: 40%;
    }

    .top-left-cmp, .bottom-left-container {
      width: 32%;
    }

    .top-middle-cmp, .top-right-cmp {
      width: 34%;
    }

    .bottom-left-container {
      position: relative;

      .border-box-content {
        display: flex;
      }

      .mcb-decoration-1, .mcb-decoration-2 {
        position: absolute;
        left: 50%;
        margin-left: -2px;
      }

      .mcb-decoration-1 {
        top: 5%;
        transform: rotate(180deg);
      }

      .mcb-decoration-2 {
        top: 50%;
      }

      .bottom-left-chart-1, .bottom-left-chart-2 {
        width: 50%;
        height: 100%;
      }
    }

    .bottom-right-container {
      width: 68%;
      padding-left: 30px;
      box-sizing: border-box;
      display: flex;
    }
  }
}
</style>
