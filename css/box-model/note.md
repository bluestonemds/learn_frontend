盒模型(CSS1, CSS2)
===============
- size计算方法
```
width = margin-width + border-width + padding-width + content-width
```
- margin-collapsing (边界折叠)
  - 只发生在垂直方向,也就是margin-top, margin-bottom.
  - 两个元素相比,数值最小的元素的数值为变为0. 也就是说两个元素最终的距离采用最大的数值.
  - 发生在相邻的两个元素之间.
  - 发生在父级元素及其每一个和最后一个子元素之间.
  - 可以采用负数的方式调整元素之前的距离, 公式为实际距离 = 最大数值 + (负数数值). 
  
  

