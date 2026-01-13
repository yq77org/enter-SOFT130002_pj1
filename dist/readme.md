# web PJ1 文档

#### 作者 ：

​	17307130286吴妍琪

##### Github地址：

​	https://github.com/wutang22/SOFT130002_pj1

##### Github Pages地址：

​	 https://wutang22.github.io/SOFT130002_pj1/



#### 项目完成情况：

​	完成所有文档中提及的基本需求与bonus。



#### Bonus完成情况和解决方法：

##### 	1、 更复杂的图片处理

​	解决方法：将图片设为背景图片，然后height设为0，调整width和padding-bottom的数值来实现固定比例裁剪。然后利用background-size：cover 的特性，把背景图像扩展至足够大，以使背景图像完全覆盖背景区域。

```css
width: 100%;
height: 0;
padding-bottom: 100%;
overflow: hidden;
background-position: center center;
background-repeat: no-repeat;
-webkit-background-size:cover;
-moz-background-size:cover;
 background-size:cover;
```

##### 	2、响应式布局：

​	解决方法：在设置图片时利用background-size：cover 的特性，布置各个组件的位置时采用百分数比较多。

##### 	3、界面美观：

​	解决方法：提高自己的审美。	



