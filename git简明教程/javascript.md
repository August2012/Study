Javascript
=======================================

1. 计算机无法计算无限小数的精确数值，所以无法比较浮点型数字的大小，只能通过数值绝对值的误差来比较浮点数是否相等
	`Math.abs(a - b) < 0.00000001`
2. 在JS里面Null和undefined没有本质的区别，大多数情况下应该使用null，只有在判断函数参数是否传递的情况下使用
3. strict模式下，变量必须通过var声明，否则出错（前提是浏览器支持的情况下，在文件前添加 `'use strict';`；如果浏览器不支持，则他会作为字符串处理）。
4. 在新ES6标准支持的浏览器中 小引号 ` ` 中可以换行字符串
	alert(`多行
	字符串
	测试`);
5. 用`in`判断对象是否存在某个属性，当然也会判断继承的属性
	`hasOwnProperty`判断自身是否存在某属性，不会判断继承
6. JavaScript把`null`、`undefined`、`0`、`NaN`和空字符串`''`视为false
7. Map Set 是ES6的新特性
	Map：get，has，delete
	Set：add，delete
8. iterable类型， array，map，set都属于iterable类型，具有iterable类型的集合可以使用`for...of...`来遍历
	Array :  `a.forEach(function(element, index, array){...})`
	Map   :  `a.forEach(function(value, key, map){...})`
	Set   :  `a.forEach(function(element, set){...})`
9. arguments 关键字，是JS自带，在函数内部可用，类似Array
10. 
