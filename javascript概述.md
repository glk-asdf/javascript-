#javascript概述
##程序语言
*基础逻辑处理部分
	*变量 数据类型(数据存储)
	*分支和循环（逻辑操作）
	*函数（对语言的扩展）
```javascript
var vr=1;             //number
var vr=1.2;           
var vr="asd";         //string
var vr=undefind;      //undefind
var vr=function(){};   //function
var vr=null;           //null
var vr=true;          //boolean
var vr={a:1,b:2};     //object
var vr=[1,2,3];       //array

+ - * / %
=== !== > < >= <=
&&  ||  !


if(){};
if(){}else{};
if(){}else if(){}else if(){};
for(var i=0;i < n;i++){
	
};
swich(x){
	case 1:
	break;
	default;
	
};
while(i < n){
i++
};
do{
i++
}while(i<0);
function vr(){
	
}
var vr=function(a,b){
	//arguments
}
vr(d,f);
//数组的常用方法
//字符串的常用方法

function vr(){
	 this.a="a";
	 this.b=function(){

	}
}
vr.prototype.console=function(){
	console.log(this.a);
}
var vr=new vr();
vr.console();
```
*针对特定用途的部分
>当js来浏览器运行的那一刻
>浏览器会创建一个window对象
>window对象中很多属性和方法
>这些属性和方法不用加 window.就可以使用
setInterval();

dom对象 dom
###选取元素
*var el=document.getElementById();
*var el=document.getElementsByClassName();
*var el=document.getElementsByTagName();
*var el=document.getElementsByName();
*var el=document.querySelector();          //通过选择器 得到第一个 不兼容IE6
*var el=document.querySelectorAll();       //通过选择器 得到全部
*var el=document.createElement();
经过这一步 我们

js 会用一个很大的对象来描述dom对象


###筛选元素

父元素
*el.parentNode;
*el.parentElement;

子元素
*el.firstChild;
*el.firstElementChild;

*el.children
*el.nodeChilds;

*el.lastChild;
*el.lastElementChild;

兄弟元素
*el.nextSibling;
*el.previousSibling;

###操作样式
*el.style.color="red";
*el.currentStyle.width;          
*getComputedStyle(el,null).width //"100px"


###获取元素信息
*document.documentElement.clinkX;
*document.documentElement.clinkY;
*document.documentElement.screenX;
*document.documentElement.screenY;
*el.offsetWidth;
*el.offsetHeight;
*el.offsetLeft;
*el.offsetTop;
*el.offsetParent;           //具有定位属性的父元素
*el.getBoundingClietRect();  //计算元素距离窗口的位置
*el.innerHTML;
*el.currentStyle.width;          
*getComputedStyle(el,null).width //"100px"


###操作属性(Element)
*el.setAttribute();
*el.getAttribute();            //获得元素属性的值
*el.removeAtttribute();
*el.hasAttribute();
*el.className;
*el.Id;


###节点操作
*el.appendChild();
*el.removeChild();
*el.insertBefore();
*el.cloneNode();
*el.replaceChild

###其他






