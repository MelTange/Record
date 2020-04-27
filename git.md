git init 初始化
git add main.c 将main.c添加到暂存区
git commit -m ‘版本信息说明’ 将暂存区的文件提交到版本库里面
git log 查看日志信息
git config --global user.name “你的名字”
git config --global user.email “你的邮箱”
git reset --hard HEAD^ 其中“HEAD^” 与 HEAD~1 和用序列号是等价的
git reflog 查看之前操作的信息
git status 查看工作区状态
git checkout – filename 丢弃修改
git reset HEAD filename 从暂存区撤离
git rm filename 删除一个文件并提交到暂存区
git branch 查看分支
git branch 创建分支
git checkout 切换分支
git checkout -b 创建 切换分支
git branch -d 删除分支
git merge 合并某分支到当前分支
git log –pretty=oneline 历史记录显示一行
git log --graph --pretty=oneline
git stash
git stash list 列出保存的工作现场
git stash pop 恢复工作现场
git merge --no-ff -m ‘描述符 禁用快速合并’ <要合并的分支名字>
生成通信密钥 方法：ssh-keygen -t rsa -C “youxiang@126.com”
-t 指定密钥类型，默认是 rsa ，可以省略。
-C 设置注释文字，比如邮箱。
测试 ssh -T git@github.com
git clone xiangmudizhi 克隆项目
git push origin 分支名 提交分支到 github
git push -u origin 分支名 提交分支到 github ，并跟踪改分支
git branch --set-upstream-to=origin/远程分支名 本地分支名
功能为：设置本地分支跟踪服务器分支（待验证）
git pull origin fenzhiming 拉取远程服务器上的分支 更新到本地
