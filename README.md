#  #创建项目：
1. 登录github后，在主页右上角点击“+” -> new repository新建一个项目。
2. 进入新建项目页面后，填写Repository name和Description。
3. 点击“Create repository”后生成项目地址https://github.com/zhaoqingyue/xxx.git。
4. 在要上传的工程master下（工程里面目录），右键—>GitBash。
5. echo "# xxx(项目名)" >> README.md
6. git init
7. git add . -A
8. git commit -m "更新说明"
9. git remote add origin https://github.com/zhaoqingyue/xxx.git
10. git push -u origin master

#  #更新代码：
1. git remote add origin https://github.com/zhaoqingyue/xxx.git
2. git push -u origin master