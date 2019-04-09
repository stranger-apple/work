# flex布局
 display：flex（容器）display：inline-flex（行内元素）
### 属性
- flex-direction： row（水平方向，起点在左端） row-reverse（水平方向起点在右端）   
column（竖直方向，起点在上）  
    column-reverse（竖直方向，起点在下）  
- flex-wrap（一条轴线排不下，如何换行）：
nowrap（不换行）   
nowrap（换行，第一行在上方）  
wrap-reverse（换行，第一行在下方）  
- flex-flow（是flex-direction 和flex-wrap的简写）
- justify-content（项目在主轴上对齐）  
flex-start:左对齐  
flex-end：右对齐  
center： 居中  
space-between：两端对齐，项目之间的间隔都相等。  
space-around：每个项目两侧的间隔相等。
- align-items交叉轴上如何对齐:  
stretch（默认值）：如果项目未设置高度或设为auto，将占满整个容器的高度。    
flex-start：交叉轴的起点对齐。  
flex-end：交叉轴的终点对齐。  
center：交叉轴的中点对齐。  
baseline: 项目的第一行文字的基线对齐。  
- align-content:多根轴线的对齐方式。如果项目只有一根轴线，该属性不起作用。  
 stretch（默认值）：轴线占满整个交叉轴。   
flex-start：与交叉轴的起点对齐。  
flex-end：与交叉轴的终点对齐。  
center：与交叉轴的中点对齐。  
space-between：与交叉轴两端对齐，轴线之间的间隔平均分布。  
space-around：每根轴线两侧的间隔都相等。所以，轴线之间的间隔比轴线与边框的间隔大一倍。  
- order:项目的排列顺序。  
数值越小，排列越靠前，默认为0
- flex-grow:项目的放大比例，默认为0，即如果存在剩余空间，也不放大。
- flex-shrink属性定义了项目的缩小比例，默认为1，即如果空间不足，该项目将缩小。
- align-self:允许单个项目有与其他项目不一样的对齐方式，可覆盖align-items属性。默认值为auto，表示继承父元素的align-items属性，如果没有父元素，则等同于stretch.
# css3动画
### 属性
- @keyframes:规定动画。
- animation	所有动画属性的简写属性  
- animation-play-state 属性
- animation-name:@keyframes 动画的名称。	3
- animation-duration:规定动画完成一个周期所花费的秒或毫秒。默认是 0.  
- animation-timing-function	规定动画的速度曲线。默认是 "ease"。
- animation-delay:规定动画何时开始。默认是 0。
- animation-iteration-count	规定动画被播放的次数。默认是 1。	
- animation-direction:规定动画是否在下一周期逆向地播放。默认是 "normal"。	
- animation-play-state	规定动画是否正在运行或暂停。默认是 "running"。  
# js  
### 用法
- 放置在head中
- 放置在body中
- 放置在外部：`<script src=""></script>`
### 输出
- window.alert() 弹出警告框。
- document.write() 方法将内容写到HTML文档中。
- innerHTML 写入到 HTML 元素。
- console.log() 写入到浏览器的控制台。
### 注释
- 单行注释以 // 开头。
- 多行注释以 /* 开始，以 */ 结尾。
### 变量
- 变量必须以字母开头  
- 变量也能以 $ 和 _ 符号开头  
- 变量名称对大小写敏感  