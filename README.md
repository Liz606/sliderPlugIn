# sliderPlugIn
##功能描述##
一个基于jQuery的无限轮播图插件
- 可以在手机端横屏触摸滑动。
- 可以点击小圆点滑动到指定图片。
- 当没有点击也没有触摸滑动时将自动左滑。
##使用##
在你需要此插件的位置添加如下html
```
<div id="slider">
  <ul id="sliderBox">
  		<li></li>
  		<li></li>
  		<li></li>
	</ul>
</div>
```
在页面引入插件
```
<script src="slider.js"></script>
```
调用插件
```
<script>
window.onload = function() {
	var constIndex=4;//轮播图个数
    var sliderBox = '#sliderBox';//轮播图盒子的ID（当页面多次使用此插件时可自定义ID）
    init (sliderBox,constIndex,true);//此处的true控制是否显示小圆点
}
</script>
```

