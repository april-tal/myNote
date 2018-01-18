## 方法

* .push()    向数组最后面添加一个或多个元素，并返回新数组的长度
* .pop()		删除数组中的最后一项，并返回被删除的元素
* .unshift()	 向数组最前面添加一个或多个元素，并返回新数组的长度
* .shift()	 删除数组中的第一项，并返回被删除的元素
* .concat()	  合并两个或多个数组
* .reverse()	 颠倒数组的顺序
* .join()		将数组使用连接符a拼接成字符串并返回，原数组并不会改变
* .slice(a,b)   数组的截取，从a开始（包括a）截取到b（不包括b），返回截取的数组
* .splice(a,b,c)	 a添加或删除的位置，b删除的个数，c添加的元素
* .indexOf()	 检测数组中是否存在某一个元素，如果存在则返回第一个存在的索引，不存在则返回 -1
* .sort		数组排序。直接使用.sort() 会将数字和字符串的首位字符顺序排序
* .filter()		过滤/筛选
* .filter(function(item,index,array){})
	 item    数组中的每一项	index数组每一项的索引值		array原数组
* .find() 	返回符合条件的第一个元素，不符合返回undefined
* .map()	 映射，返回新的长度一样的数组
* random()		返回0-1之间的随机数
* floor() 		下舍,舍去小数点之后的所有
* ceil()		上近
* round		四舍五入
* Date		日期对象
```
var date = new Date()
```
* .getFullYear()		获取年份
* .getMonth()		获取月份
* .getDate()		号
* .getDay()			星期
* .getHours()		小时
* .getMinutes()		分钟
* .getSeconds()		秒数
* .getMilliseconds()	毫秒数
* setInterval（函数名，毫秒数）    每过这个毫秒数之后就会执行一次前面的函数
* setTimeout（函数名，毫秒数）     延迟这个毫秒数之后，执行一次前面的函数
* clearInterval()      停止倒计时
