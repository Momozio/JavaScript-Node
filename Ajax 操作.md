# Ajax操作

### 步骤
1.**创建一个XMLHttPRequest对象**
```javascript
//主流的浏览器
var request = new XMLEHttPRequest();
//(IE5和IE6)
var request = new ActiveXObject("Microsoft.XMLHTTP");
```
2.**调用XMLHttPRequest对象的open方法**
```javascript
request.open(method,url,async)
//method为请求方式，GET或POST
//url文件在服务器上的位置
//async为同步或异步(ture为异步操作)
```
3.**调用XMLHttpRequest对象的send方法**
```javascript
request.sent(null);
```
4.**为XMLHttPRequest对象添加onreadystatechange响应函数在响应函数中判断相应是否可用(status为200，readyState属性为4，表示响应可用并接受请求)**

```javascript
request.onreadystatechange = function{
    if(request.readyState == 4 && request.status == 200)
    //操作代码
}
```
6.**操作responseText或responseXMl**
```javascript
request.onreadystatechange = function{
    if(request.readyState == 4 && request.status == 200)
    //在此处添加代码
}
```