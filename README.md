# 说明
## github 上传代码步骤

1. 创建账号
2. 添加ssh密匙  
```angular2html
ssh-keygen -t rsa -C "1691937600@qq.com"
```
3. 查看密匙
```angular2html
cd ~/.ssh
ls  #会显示三个文件 id_rsa  id_rsa.pub  known_hosts
gedit id_rsa.pub  # 打开文件查看密匙并添加到github中
```
4. 设置全局email和用户名
```angular2html
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```
5. git clone 仓库代码  
6. 添加代码  
```angular2html
git add .
```
7. 添加说明
```angular2html
git commit -m "add SE_resnet"
```
8. 上传代码
```angular2html
git push -u origin main
```
