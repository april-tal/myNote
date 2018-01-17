## 创建 gh-pages 分支

命令行输入命令
```
npm i gh-pages
```
用喜欢的编辑器打开想上传的文件，然后命令行输入
```
npm init
```
一律都按回车
在 package.json 文件中 加入
```
script:{"deploy": "gh-pages -d _book"
},
"homepage": "https://april-tal.github.io/gitbook"
```
然后，执行上传文件命令
```
git add .
git commit -m 'updata'
git push
gitbook build
```
