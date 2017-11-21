# interview

1.用过哪些标签
2.请描述一下 cookies，sessionStorage 和 localStorage 的区别？
cookie是网站为了标示用户身份而储存在用户本地终端（Client Side）上的数据（通常经过加密）。
cookie数据始终在同源的http请求中携带（即使不需要），记会在浏览器和服务器间来回传递。
sessionStorage和localStorage不会自动把数据发给服务器，仅在本地保存。

存储大小：
    cookie数据大小不能超过4k。
    sessionStorage和localStorage 虽然也有存储大小的限制，但比cookie大得多，可以达到5M或更大。

有期时间：
    localStorage    存储持久数据，浏览器关闭后数据不丢失除非主动删除数据；
    sessionStorage  数据在当前浏览器窗口关闭后自动删除。
    cookie          设置的cookie过期时间之前一直有效，即使窗口或浏览器关闭

3.pushState

3.Label的作用是什么？是怎么用的？

label标签来定义表单控制间的关系,当用户选择该标签时，浏览器会自动将焦点转到和标签相关的表单控件上。

<label for="Name">Number:</label>
<input type=“text“ name="Name" id="Name"/>

<label>Date:<input type="text" name="B"/></label>

4. 网页验证码是干嘛的，是为了解决什么安全问题。

区分用户是计算机还是人的公共全自动程序。可以防止：恶意破解密码、刷票、论坛灌水；
有效防止黑客对某一个特定注册用户用特定程序暴力破解方式进行不断的登陆尝试；

5. 提交ajax请求的时候，后台如何知道你的身份。
6. 事件捕获和冒泡
7. 设备与平台监测。

css：
1. CSS选择符有哪些？哪些属性可以继承？如何写选择器的性能好。
2. position
3. CSS优先级算法如何计算？
4. display有哪些值？说明他们的作用。
5. 请解释一下CSS3的Flexbox（弹性盒布局模型）,以及适用场景？
6. 为什么要初始化CSS样式。
7. css定义的权重
8. 全屏滚动的原理是什么？用到了CSS的那些属性？
9. png、jpg、gif 这些图片格式解释一下，分别什么时候用。有没有了解过webp？
10. 垂直居中
11. 实现一个网页布局框架。
12、margin的重叠


Javascript：
1. ajax promise
2. 从list里删除元素，将2个list连接, 头部插入/删除，尾部插入和删除
3. settimeout(function，0)
4. JS里的this指的是什么？

　　var name = "The Window";
　　var object = {
　　　　name : "My Object",
　　　　getNameFunc : function(){
　　　　　　return function(){
　　　　　　　　return this.name;
　　　　　　};
　　　　}
　　};
　　alert(object.getNameFunc()());  

5. 什么是闭包（closure），为什么要用它？
6. if (new Boolean(false)) {
    console.log("true"); 
   } // true
7. for(var i in obeject) 和 for(var i of list)
8. js实现继承
9. 怎么写选择器高效
10. js是单线程的，又是异步的。event loop。
11. jQuery选中element性能

function User(login) {
  this.login = login;
  this.sayHi = function() {
    console.log(this.login);
  }
}

var user = new User('John');

setTimeout(user.sayHi, 1000);

12. 用过哪些es6,7的语法，箭头函数，解构, 模板字符串, 变量字符串，函数默认参数， async/await

13. webpack的使用，如何配置解决跨域请求问题。大概如何工作
14. JS变量提升、匿名函数、原型继承、作用域、闭包机制等


微信公众号
app

