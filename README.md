![ScreenShot](https://raw.github.com/karacas/imgLiquid/master/dev/logoimgliquid.png)
  
imgLiquid.js v0.67 - 18-10-2012  
#####A jQuery Plugin to resize images to fit in a container.  
Alejandro Emparan (karacas), twitter: @krc_ale  
Dual licensed under the MIT and GPL licenses.  
## 
#Usage  

####Include:
```html
<script src="js/imgLiquid-min.js"></script>
```  

####js:
```js
$(document).ready(function() {
	$(".imgLiquid").imgLiquid();
});
```

####Html:
```html
<div class="imgLiquid" style="width:300px; height:200px;">
	<img alt="Woody" src="Woody.jpg" />
</div>
```
  
####css:
```css
/*
Important: 	
	set "visibility:hidden" for better results
	or use src/css/imgLiquid.js.css
*/
.imgLiquid img{
    visibility:hidden;
}
```
 
####View in action:  		
http://goo.gl/Wk8bU  
####or play with it:  	
http://jsfiddle.net/karacas/3CRx7/#base  
http://codepen.io/karacas/pen/nlugd
## 
###Features:
```
	- Align
	- Fill/Crop
	- FadeIn Anim
	- Svg support
	- Responsive (Optional, default is off)
	- All browsers (Incl. ie6)
```
   
###Options:
```
	>js
	fill: true,
	verticalAlign: 'center', //'top' // 'bottom'
	horizontalAlign: 'center', // 'left' // 'right'
	fadeInTime: 0,
	responsive: false
	
	>css (set useCssAligns: true) (overwrite js)
	text-align: center;
	vertical-align : middle;

	>hml5 data attr (overwrite all)
	data-imgLiquid-fill='true'
	data-imgLiquid-horizontalAlign ='center'
	data-imgLiquid-verticalAlign' ='center'
	data-imgLiquid-fadeInTime = '1000'
```  
