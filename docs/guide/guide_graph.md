# 确定可视化图表
根据数据的内容和分析的维度，可以以此来确定可视化图表的内容
![大屏可视化的主要内容](https://github.com/cjywoo/DataVNote/blob/master/docs/img/001.jpeg?raw=true)
![可视化图表分析](https://github.com/cjywoo/DataVNote/blob/master/docs/img/2190569.png?raw=true)

而上图，可以引导我们从“联系、分布、比较、构成”四个维度更有逻辑的思考这个问题。
* 联系：数据之间的相关性
* 分布：指标里的数据主要集中在什么范围、表现出怎样的规律
* 比较：数据之间存在何种差异、差异主要体现在哪些方面
* 构成：指标里的数据都由哪几部分组成、每部分占比如何

图表的设计方式具体可以参考[数据可视化图表和表格的设计经验分享](https://www.zcool.com.cn/article/ZOTY2NDE2.html),下面我简单做一个归纳

## 图
* 图的数值建议占整体画布的2/3，可以基于数据的min,max自动调整区间取值
* 刻度线的颜色、透明度建议降低，弱化
* x轴标签文字过多时，可以横向排列，即x轴旋转90度
* 饼图中的数值建议在外围，且按照占比从小到大顺时针排列

## 表
* 文字左对齐，数据右对齐
* 标题随内容同样的对齐格式
* 表格的竖线建议去除
* 对于一些重要数据，建议通过背景色进行强化处理