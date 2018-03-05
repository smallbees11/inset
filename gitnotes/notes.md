# Linux的发行版
- `Linux操作基础`
- `ls`列出当前目录的所有不隐藏的文件
- `cd`进入
- `mkdir`创建
- `ls -ah`列出目录下隐藏文件
- `cd:`回到首页
# 编辑器基本操作
- `vi或vim`编辑
- `i`进入编辑模式
- `w`保存
- `q`退出
- `wq`保存后退出
- `shift+;`输出:
- `esc`推出编辑状态
# git 基础操作
- `git`
- `sudo apt install git`安装git
- `sudo`使用管理员运行
- `ssh-keygen -t rsa -C"git注册的邮箱"`
- `vim.ssh/id_rsa.pub或者vi .ssh/id_rsa,pub`
- `git config --global user.name"your name"`
- `git config --global user.email"your email"`
# 推送到git仓库
- `git clone git你的仓库url`
- `git status`查看修改
- `git add *或者是你编辑过后的文件的名字`
- `git commit -m"这次更新的主要是什么提示"`
- `git push`命令用于把本地的更新推送到远程主机
- `git diff`查看提交了什么
- `git log`查看提交历史
- `git log --pretty=oneline`git log参数简洁显示最近提交的信息
- # git 时光机总总结
- `HEAD`指向当前版本
- `HEAD^`指向前一个版本^^前一个的前一个版本
- `id`git log 前面的psh
- `git log`查看当前提交的历史
- `git log --pretty=oneline`常看当前提交的历史简洁版
- `git reset --hard commit_id`commit_id代表指向的HEAD^
- `git reflog`查看命令历史进行回到未来
