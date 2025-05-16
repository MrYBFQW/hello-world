# 如何上传本地文件到github
小白第一次使用GitHub
本地库上传方法：
1.git init //把这个目录变成Git可以管理的仓库
2.git add README.md //文件添加到仓库
3.git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 
4.git commit -m "说明信息" //把文件提交到仓库，附上说明信息
5.git remote add origin (git@github.com:wangjiax9/practice.git) //关联远程仓库,括号里面的内容由仓库自己生成
6.git push -u origin main -f //把本地库的所有内容推送到远程库上
