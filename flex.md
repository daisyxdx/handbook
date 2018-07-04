块级元素 display:lefx

行内元素 display:inline-flex

tips：设为flex之后，子元素的float、clear、vertical-align属性失效



### 容器属性

#### 1.flex-direction

主轴方向。

row 

row-reverse

column

column-reverse

#### 2.flex-wrap

如何换行。

nowrap(不换行)

wrap

wrap-reverse(第一行在下方)

#### 3.justify-content

主轴对齐方式。

flex-start(头（左）对齐)

flex-end(尾（右）对齐)

center（中间对齐）

space-between（两头对齐，两头顶到）

space-around（两头对齐，但两头不顶到，两头的padding=item之间间隔的一半）

#### 4.align-items

在副轴上的对齐方式。

flex-start

flex-end

center

baseline

stretch(拉伸满轴)（默认值）

#### 5.align-content

多行时，副轴对齐方式。

flex-start

flex-end

center

stretch

space-between

space-around



### item属性

#### 1.order

int 排列顺序。数值越小，越靠前。默认为0。

#### 2.flex-grow

number 放大比例。默认为0（即不放大）。相当于对剩余空间进行weight。

#### 3.flex-shrink

number 缩小比例。默认为1（即缩小）。

#### 4.flex-basis

px 设置之后，item将占据固定空间，不随容器大小变化而调整。

#### 5.align-self

设置单个item的副轴对齐方式

auto

flex-start

flex-end

center

baseline

stretch