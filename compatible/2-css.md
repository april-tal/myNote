## CSS属性前缀法

```
body{
	background:red;
	background:blue\0/;	ie8专属HACK
	background:blue\9;		IE6/IE7/IE8/IE9/IE10都生效
	background:blue\0;		ie8及以上
	background:blue\9\0;	ie9  ie10
	_background:blue;		ie6
	*background:blue;		ie6&7
｝
```
注意：!important		提升优先级（只在IE6里面管用）
