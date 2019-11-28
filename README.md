# nodejs_server_for_android
Experss 从入门到放弃系列
# 视频笔记系列
## 全局对象
console就是一个全局对象，console.log()  
setTimeout(() => {   //显然setTimeout  setInterval也是一个全局对象
    console.log()
},3000)
console.log(__dirname);
console.log(__filename);
## 回调函数
function callFunction(fun){
    fun();
}

function sayHi(){
    console.log('Hi');
}
sayHi();

var sayBye = function(){
    console.log('Bye');
}
## 模块
js中模块的导入
## 事件
element,in()