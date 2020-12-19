# html5+css3练习仓库


## 本仓库适用于html和css3初学者

我本人业余没事写写，就当作消遣和学习了，下面是目录可以用于检索。

##  html5 一些特性

[html5一些特性](./0/fitstPage.html)

##  第一章
### 第一个html5页面
[检测浏览器是否支持canvas标记](./1/CanvasBroswerTest.html)
### Hello World
- 不区分大小写
- 属性无需双引号
- 不区分标记结束符
- 可以直接忽略主题内容直接编写页面，浏览器会自动添加

[HelloWorld页面](./1/HelloWorld.html)
![浏览器调试信息](./1/html会自动添加html%20head%20body标记.png)

### 使用html5特有的标记替代id指代内容的写法
示例
[老式的写法](./1/老式的divID写法.html)
[HTML5写法](./1/使用html5元素书写的更加明确的页面写法.html)
两端代码效果相同，h5元素简化了页面构建过程，利用id来标记页面内容是没有意义的浏览器不嫩通过id推断元素类型，因为id会随时变化

html5中可以使用使用一些新的元素明确告诉浏览器内容，
header 页头   nav 构建页面的导航 article 页面内容的一部分 footer表示页面已经到达了尾部


Html5中一个article标签可以创建一个节点，每个节点都会有自己的独立元素。

article标签不能依赖于其他元素，作为页面有意义的一部分可以是文章也可以是一个评论等。
示例[html创建节点](./1/使用html5元素书写的更加明确的页面写法.html)

#### 使用css美化HTML 文档

需要注意CSS默认元素的属性是inline（经过实验发现现在的chrome默认将元素的display的属性设置为block，所以书上写得不对） 为了正确显示设置的页面效果，需要将元素的display为block。
[CSS的Display](./1/display需要使用设置为block.html)

