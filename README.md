# canvas-scratch-card
canvas实现刮刮卡 移动端应用


``` bash
# 功能很简单 不过效果还是不错的

＃获取事件是通过 touchmove等事件来执行的，所以请用手机模式来浏览。。

#＃＃
1.通过canvas api先在图片上面画一层灰色背景
2.获取手指或鼠标移动的位置，从canvas来画粗点的线
3.通过canvas api  context.globalCompositeOperation = 'destination-out'; 来实现刮开效果

##
