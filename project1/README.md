# pj1开发文档 

> 19302010063卢雅棋

## github地址与github Pages地址
github地址：

### 项目完成情况
#### - 基本要求
基础功能已全部实现，对配色构图略有调整，用到边框圆角、渐变背景色、阴影等

#### - 额外
  1.渐变的modify、delete等按钮在鼠标移上去会有动画效果
  2.导航栏鼠标移上去的高亮有动画效果
 
#### -bonus完成情况
```
####图片自动裁减
>>使用css中的object-fit属性

.travelimage {
    margin: 20px 20px 20px 30px;
    height: 280px;
    width: 280px;
    border-radius: 10px;
    object-fit: cover;
}

```
关于object-fit：cover
>>按比例放缩图片并对溢出部分进行裁剪
####响应式布局
部分用 %作为长度单位，可以随着浏览器大小改变

 
####美化
>>主要仿照样例图片效果，构图配色方面略有改动

###对pj和课程建议
课程速度适中，难度适中，挺好的
