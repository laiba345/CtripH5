# CtripH5
使用flex布局对移动端携程网站进行布局

flex 布局父项常见属性
① flex-direction：设置主轴方向  
② justify-content：设置主轴上的子元素排列方式
③ flex-wrap：设置子元素是否换行
④ align-content：设置侧轴上的子元素排列方式(多行)
⑤ align-items：设置侧轴上的子元素排列方式(单行)
⑥ flex-flow：复合属性，相当于同时设置了flex-direction和flex-wrap

flex-direction
- 默认主轴为x方向，水平向右 （row）
- 默认侧轴方向y轴方向，水平向下 （column）

justify-content
- flex-start 默认值从头部开始，如果主轴是x轴，则从左到右
- flex-end 从尾部开始排列
- center 在主轴居中对齐（如果主轴是x轴，则水平居中）
- space-around（平分剩余空间）
- space-between 先两边贴边 再平分剩余空间（重要）
- space-evenly 可以使项目与项目之间以及项目与边框之间的间隔相等

flex-wrap
- nowrap 默认值 不换行
- wrap 换行

align-content（多行）
- 

align-items（单行）
- flex-start 从上到下
- flex-end 从下到上
- center 挤在一起居中
- stretch 拉伸（默认值）

注：想要让盒子垂直居中，需在两个轴上面都居中


flex布局子项常见属性
① flex子项目占的份数
② align-self 控制子项自己在侧轴的排列方式
③ order 定义子项的排列顺序（前后顺序）

flex 
- 定义子项目分配剩余空间，flex来表示占多少份数
之前京东移动端的制作用到过，左右给定一个固定大小，中间flex权重分配就是一种自适应效果

align-self
- 允许单个项目与其他项目不一样的对齐方式，可以覆盖align-items 属性
- 默认值auto，表示继承父元素的align-items属性，如果没有父元素，等同于stretch

order
- 数值越小，排列越靠前，默认值为 0



