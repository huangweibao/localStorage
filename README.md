# localStorage
保存数据到localStorage 及从localStorage取出数据

保存数据：

localStorage.setItem(key,value);
取出数据:
var len = localStorage.length;
for(var i=len-1; i>=0;i--){
  var key = localStorage.key(i);//取出key值
  var value = localStorage.getItem(key);//通过key取出value值
}
