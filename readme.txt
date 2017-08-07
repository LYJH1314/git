第一:初始化一个git仓库  git init
第二步:添加文件到仓库   第一:git  add a.txt  第二步 git commit -m '提交了a.txt文件'

随时掌握工作区的状态,使用  git status
如果执行git status 告诉你文件被修改过，那么可以使用git diff查看被修改的内容
HEAD指向的版本就是当前版本,因此git允许我们在版本的历史之间穿梭使用命令git reset --haed commit_id
穿梭前，用git log可以查看提交历史,以确定要退回到哪个版本
要重返未来,用git reflog 查看命令历史,以便确定要回退到哪个版本