<template>
  <div class="top-right-cmp">
    <div class="chart-name">
      近一周人员体温情况
      <dv-decoration-3 style="width:200px;height:20px;" />
    </div>
    <dv-charts :option="option" />
  </div>
</template>

<script>
export default {
  name: 'TopRightCmp2',
  data () {
    return {
      option: {
        legend: {
          data: [
            {
              name: '体温达标率',
              color: '#ff5ca9'
            }
          ],
          textStyle: {
            fill: '#fff'
          }
        },
        xAxis: {
          data: [
            '5/15', '5/16', '5/17', '5/18', '5/19', '5/20', '5/21'
          ],
          axisLine: {
            style: {
              stroke: '#999'
            }
          },
          axisLabel: {
            style: {
              fill: '#999'
            }
          },
          axisTick: {
            show: false
          }
        },
        yAxis: {
          data: 'value',
          splitLine: {
            show: false
          },
          axisLine: {
            style: {
              stroke: '#999'
            }
          },
          axisLabel: {
            style: {
              fill: '#999'
            }
          },
          axisTick: {
            show: false
          },
          min: 0,
          max: 100
        },
        series: [
          {
            name: '体温达标率',
            data: [
              15, 35, 65, 65, 75, 65, 75
            ],
            type: 'line',
            lable: {
              show: true,
              formatter: '{value}'
            },
            lineStyle: {
              stroke: '#ff5ca9'
            },
            linePoint: {
              radius: 4,
              style: {
                fill: '#ff5ca9',
                stroke: 'transparent'
              }
            }
          }
        ]
      }
    }
  }
}
</script>

<style lang="less">
.top-right-cmp {
  position: relative;
  padding: 0 50px;
  box-sizing: border-box;

  .chart-name {
    position: absolute;
    right: 213px;
    text-align: right;
    font-size: 20px;
    top: -4px;
  }
}
</style>
