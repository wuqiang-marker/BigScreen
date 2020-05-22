<template>
  <div class="bottom-right-table-1">
    <dv-border-box-6>
      <div class="table-name">
        <img src="./img/icon1.png" />员工体温情况录入
      </div>

      <dv-scroll-board :config="config" />
    </dv-border-box-6>
  </div>
</template>

<script>
export default {
  name: 'BottomRightTable1',
  data () {
    return {
      config: {
        // hearder: ['部门', '姓名', '时段', '体温'],
        // data: [
        //   // ['张三', '月累计排除故障：4起'],
        //   // ['李四', '月累计排除故障：3起'],
        //   // ['王五', '月累计排除故障：3起'],
        //   // ['赵六', '月累计排除故障：3起'],
        //   // ['钱七', '月累计排除故障：2起'],
        //   // ['孙八', '月累计排除故障：2起'],
        //   // ['杨九', '月累计排除故障：2起'],
        //   // ['吴十', '月累计排除故障：2起'],
        //   // ['李雷', '月累计排除故障：2起'],
        //   // ['韩梅梅', '月累计排除故障：2起']
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
        //   ['中央厨房服务班', '杨进翠', '上午', '36.3℃']
        // ],
        // index: true,
        // columnWidth: [30, 70],
        // align: ['center'],
        // oddRowBGC: 'rgba(9, 37, 50, 0.4)',
        // evenRowBGC: 'rgba(10, 32, 50, 0.3)'
        header: ['部门', '姓名', '时段', '体温'],
        data: [
          ['中央厨房服务班', '杨进翠', '上午', '36.3℃'],
          ['中央厨房服务班', '杨锦芳', '上午', '36.3℃'],
          ['中央厨房服务班', '林登香', '上午', '36.3℃'],
          ['中央厨房服务班', '汪自红', '上午', '36.3℃'],
          ['中央厨房服务班', '王怀亮', '上午', '36.3℃'],
          ['中央厨房服务班', '荣会', '上午', '36.3℃']
        ],
        columnWidth:[150],
        headerBGC: '#9FB6CD'
      }
    }
  }
}
</script>

<style lang="less">
.bottom-right-table-1 {
  width: calc(~"25% + 10px");
  height: 100%;
  margin: -8px 72px;

  .border-box-content {
    padding: 20px;
    box-sizing: border-box;
  }

  .table-name {
    height: 45px;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-bottom: 15px;

    img {
      width: 40px;
      height: 40px;
      margin-right: 5px;
    }
  }

  .dv-scroll-board {
    height: calc(~"100% - 60px");
  }
}
</style>
