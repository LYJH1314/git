第一:初始化一个git仓库  git init
第二步:添加文件到仓库   第一:git  add a.txt  第二步 git commit -m '提交了a.txt文件'

随时掌握工作区的状态,使用  git status
如果执行git status 告诉你文件被修改过，那么可以使用git diff查看被修改的内容
HEAD指向的版本就是当前版本,因此git允许我们在版本的历史之间穿梭使用命令git reset --haed commit_id
穿梭前，用git log可以查看提交历史,以确定要退回到哪个版本
要重返未来,用git reflog 查看命令历史,以便确定要回退到哪个版本
第一步是用git add把文件添加进去,实际上就是把文件修改添加到缓存区
第二步是用git commit提交更改,实际上就是把缓存区的所有内容提交到当前分支
因为我们创建git版本库的时候,git自动为我们创建了唯一一个master分支，现在，git commit 
就是往master分支上提交更改
需要提交的文件修改通通放到缓存区,一次性提交缓存区的所有修改
缓存区是git非常重要的概念,弄明白了缓存区就弄明白了git的很多操作到底是噶干什么的
