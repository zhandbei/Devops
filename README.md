# Devops
**学习收获：**

ssh基于应用层的非对称加密协议。

### 基于ssh的git访问，本地创建公钥和私钥，公钥上传git用于验证(git keygen -t rsa -C "xxx" -f "id_rsa_github")

当前文件下有多个公钥和私钥时，添加config文件解决ssh冲突。

测试本机与github是否相连通：git -T git@github.com

拷贝项目：git clone 

全局设置：git config --global user.name  user.eamil

推送分支：git push -u origin main    git push github main

关联远程分支： git remote add github https://github.com/zhandbei/Devops.git    避免向不同的仓库提交多次

文件改动需要提交： git add .  git commit -m "first commit"    提交之后记得推送git push




