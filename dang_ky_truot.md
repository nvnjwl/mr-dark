```
<!-- BEGIN switch_user_logged_out -->
<!-- Start Login Board --> <div id="loginboard" style="position:absolute; visibility:show; z-index:1000; filter: alpha(opacity=70); opacity:70; top:51px; left: 700px; width: 180px;"onmouseover="this.style.opacity=1;this.filters.alpha.opacity=100"onmouseout="this.style.opacity=0.4;this.filters.alpha.opacity=40">
<table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse; padding-top: 0px;" width="180"

align="left">
<tr>

<td width="100%" valign="middle" align="left">

<table border="0" cellpadding="0" cellspacing="0" style="border-collapse: collapse" width="180" align="left">
<tr>

<td width="100%" valign="middle" align="right" colspan="2"><a href="/profile.forum?mode=register" target="_parent"><img src="http://i46.servimg.com/u/f46/17/56/78/10/dk1010.png" width="100%" height="100%" border="0" />

Unknown end tag for &lt;/a&gt;



Unknown end tag for &lt;/td&gt;




Unknown end tag for &lt;/tr&gt;



Unknown end tag for &lt;/table&gt;




Unknown end tag for &lt;/td&gt;





Unknown end tag for &lt;/tr&gt;




Unknown end tag for &lt;/table&gt;





Unknown end tag for &lt;/div&gt;







<script>
var curx=250;
var cury=0;


Unknown end tag for &lt;/script&gt;



<script>
var ie45,ns6,ns4,dom;
if (navigator.appName=="Windows Internet Explorer") ie45=parseInt(navigator.appVersion)>=4;
else if (navigator.appName=="Netscape"){  ns6=parseInt(navigator.appVersion)>=5;  ns4=parseInt(navigator.appVersion)<5;}
dom=ie45 || ns6;

var timershow=false;
var win_w=window.innerWidth ? window.innerWidth : document.body.offsetWidth;
var mid_w=win_w/2;
var timershow1=window.setInterval("stayMiddle()",1);
function getobj(id) {
el = document.all ? document.all[id] :  dom ? document.getElementById(id) :  document.layers[id];
return el;
}

function moveobj(obj,x,y) {
obj.style.left=x + "px";
obj.style.top=y+ "px";
curx=x;
cury=y;
}

function stayMiddle() {
if (document.documentElement && document.documentElement.scrollTop)
var pY =  document.documentElement.scrollTop;
else if (document.body)
var pY =  document.body.scrollTop;

obj = getobj('loginboard');
newy = cury+((pY-cury)/16)+5;
moveobj(obj,curx,newy);
}



Unknown end tag for &lt;/script&gt;


<!-- END switch_user_logged_out -->
```