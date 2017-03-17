# JQueryMoblie 学习

## data-transition属性值：
slide  默认值   从左到右
slideup  向上
slidedown 向下
pop 一弹出的效果来打开页面
fade 渐变褪色的动画效果
flip 旧页面飞出，新页面飞入
##  页面事件

页面初始化事件

pagebeforecreat  pagecreat  pageinit
页面加载事件
pagebeforeload/pageload
页面过渡事件page Transition

页面过渡之前和过渡之后
pagebeforeshow   pageshow    pagebeforehide  pagehide


## JQueryMoblie按钮

	    <input type="submit" value="哈哈"/>
        <a  class="ui-btn">haha </a>


ui-cornor-all   圆角
ui-shadow		阴影
ui-btn-inline   并排显示
ui-btn-a		不同的样式
ui-btn-b	    不同的样式

## JQueryMoblie导航栏

水平排列的连接组成，通常位于页眉或页脚内部,
导航栏的链个自动转化为按钮，可以使用
data-role="navbar"属性来定义导航栏就ＯＫ了

导航栏和标题位置不变
data-position="fixed"

## JQueryMoblie列表

有序列表 无序列表
在ul或是ol中 添加 data-role="listview"
 data-inset="true"

## JQueryMoblie事件

Touch 触摸屏幕的
tap   点击
taploud		在某一个事物上保持一秒
swipe		在某一个元素上水平滑动超过30px
scrollstart 事件在用户开始滚动页面时
scrollstop	事件在用户停止滚动页面时


注意：在页面加载时候 使用
$(document).on("pageinit","#page",function(){


})


## JQueryMoblie Ajax  跨域问题
和JQuery中使用的是一样的

jQuery 使用的是jsonp


通过CORS（跨域资源共享）Procy对请求进行转发，就可以实现共享。服务端对于CORS的支持，主要是通过设置Access-Control-Allow-Origin来进行的。
http://cors.itxti.net/?+URL
在地址后面加上，URL 就可以了

主要学习了 JQueryMoblie 的一些基础知识以及解决了AJax跨域的问题

