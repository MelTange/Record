git init 初始化<br/>
git add main.c 将main.c添加到暂存区<br/>
git commit -m ‘版本信息说明’ 将暂存区的文件提交到版本库里面<br/>
git log 查看日志信息<br/>
git config --global user.name “你的名字”<br/>
git config --global user.email “你的邮箱”<br/>
git reset --hard HEAD^ 其中“HEAD^” 与 HEAD~1 和用序列号是等价的<br/>
git reflog 查看之前操作的信息<br/>
git status 查看工作区状态<br/>
git checkout – filename 丢弃修改<br/>
git reset HEAD filename 从暂存区撤离<br/>
git rm filename 删除一个文件并提交到暂存区<br/>
git branch 查看分支<br/>
git branch 创建分支<br/>
git checkout 切换分支<br/>
git checkout -b 创建 切换分支<br/>
git branch -d 删除分支<br/>
git merge 合并某分支到当前分支<br/>
git log –pretty=oneline 历史记录显示一行<br/>
git log --graph --pretty=oneline<br/>
git stash<br/>
git stash list 列出保存的工作现场<br/>
git stash pop 恢复工作现场<br/>
git merge --no-ff -m ‘描述符 禁用快速合并’ <要合并的分支名字><br/>
生成通信密钥 方法：ssh-keygen -t rsa -C “youxiang@126.com”<br/>
-t 指定密钥类型，默认是 rsa ，可以省略。<br/>
-C 设置注释文字，比如邮箱。<br/>
测试 ssh -T git@github.com<br/>
git clone xiangmudizhi 克隆项目<br/>
git push origin 分支名 提交分支到 github<br/>
git push -u origin 分支名 提交分支到 github ，并跟踪改分支<br/>
git branch --set-upstream-to=origin/远程分支名 本地分支名<br/>
功能为：设置本地分支跟踪服务器分支（待验证）<br/>
git pull origin fenzhiming 拉取远程服务器上的分支 更新到本地
