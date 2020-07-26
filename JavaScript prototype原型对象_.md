#  JavaScript prototype原型对象
  
###  介绍
  
每一个对象都有一个原型对象，如Data对象，number对象
  
对象构造器无法直接添加属性或方法，这是我们就可以采用prototype原型对象来为构造函数添加方法
###  **为原型对象添加属性或方法**
  
构造函数名.prototype.新属性或者新方法
```javascript
function Person(first, last, age, eyecolor){
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eyecolor;
}
  
Person.prototype.name = function() {
  return this.firstName + " " + this.lastName;
};
  