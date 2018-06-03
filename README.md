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
