# java

git github 安装及使用方法

git安装配置步骤
1 在想要创建respository的地方 右键 git bashhere
2 初始化仓库 git init 会创建一个隐藏的.git文件夹 在仓库中新建一个文件
3 git status 查看变化 
4 使用命令 git add -A 将文件加入
5 使用 git commit -m "提交信息" 将文件添加到仓库中
6 git log 命令可以查看提交记录
git diff 命令查看文件改动内容
git log 中查询到的版本号 使用 git reset --hard加版本号前7位可以返回到上一个版本

设置ssh

1生成sshkey值  ssh-keygen -t rsa -C "你的邮箱"
2 在github设置里面添加该sshkey值

git和github远程仓库之间进行关联 

复制该远程仓库的ssh地址  git remote add oringin "复制的地址"
然后 git pull --rebase origin master命令将reademe文件 放到本地仓库
git push -u origin master 远程仓库和本地仓库就成功关联

复制该仓库的ssh地址 通过git clone 到本地进行关联

实现push本地改动到远程仓库 

git add -A 添加文件
git commit -m "改动信息"
git push

clone 方法
git ssh地址 可以下载仓库到本地

