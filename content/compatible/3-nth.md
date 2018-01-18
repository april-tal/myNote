## 选择器前缀法

```
*html                                         *前缀只对IE6生效
*+html 													              *+前缀只对IE7生效
@media screen\9{...}										          只对IE6/7生效
@media \0screen {body { background: red; }}				只对IE8有效
@media \0screen\,screen\9{body { background: blue; }}		只对IE6/7/8有效
@media screen\0 {body { background: green; }} 				只对IE8/9/10有效
@media screen and (min-width:0\0) {body { background: gray; }} 只对IE9/10有效
@media screen and (-ms-high-contrast: active), (-ms-high-contrast: none) {body      { background: orange; }} 			只对IE10 IE11有效等等
```
