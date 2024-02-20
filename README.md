# -
上传超出限制大文件教学
下载好git后 就全部默认安装就好 然后找到要上传的文件在同一个文件夹里输入
git init （获得初始文件）
git add * （我也不懂）
git commit -m "firt commit" (这里要去配置文件config弄一下[user]
                                                        email=2325271820@qq.com
                                                        name=qq256141）输入这些表明身份
git commit -m "fitst commit"(再输一遍 用向上的箭头就行不用重新打，然后就开始下载了）
git remote add origin https://github.com/qq256141/ceshi.git (后面就是项目的网址）
git push -u origin master （这是上传到master的分支）
（如果报错error: unable to rewind rpc post data - try increasing http.postBuffer）
（就到配置文件config里加入
[https]
	postBuffer = 524288000）就OK了

