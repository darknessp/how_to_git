# how_to_git
## 从远程仓库clone  
	git clone git@github.com:username/repo.git  
	git remote -v//查看远程库  
  会自动关联远程库，名字是origin  
## 本地管理  
	cd repo  
	git add *  
	git commit -m "info"  
## 分支管理  
	git branch _name//创建新分支  
	git checkout _name//切换分支  
	git branch//查看所有分支  
	git merge _name//将_name分支与当前分支合并  
## push & pull  
	git push origin master//将本地master分支push到远程origin仓库
	git pull origin master//将远程origin仓库同步到本地master分支


常用的一些Git命令  

显示command的helpgit help <command>  
将工作文件修改提交到本地暂存区git add <file>  
提交修改内容git commit "message"  
将本地主分支推到远程git push -u <remoteName> <localBrachName>  
克隆远程仓库git clone <url>  
初始化仓库git init  
创建仓库git remote add <remoteName> <url>  
删除远程仓库git remote rm <name>  
修改远程主机名git remote rename <remoteName> <newRemoteName>  
拉取远程仓库git pull <remoteName> <localBrachName>  
修改远程仓库git remote set-url --push <remoteName> <newUrl>  
获取远程仓库的更新git fetch <remoteName>  
获取远程仓库特定分支的更新git fetch <remoteName> <brachName>  