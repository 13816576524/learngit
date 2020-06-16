seventh
###远程操作
###git clone 在本地复制远程仓库
git clone https://github.com/13816576524/learngit.git

###git remote 查看本地添加的远程仓库名称
###git remote -v	查看本地添加的远程仓库名称和url
###git remote show origin	在本地查看某个远程仓库的具体信息
###git remote add hello https://github.com/13816576524/hello.git	在本地添加一个远程仓库名称和url
###git rm hello		在本地删除一个远程仓库名称和url

###git fetch learngit master  将远程仓库中某个分支复制到本地仓库的分支中
###git merge  将本地仓库中文件来刷新本地工作区中文件

###git branch	查看分支
###git branch -a	查看所有分支的详情

###git pull leanrgit master   将远程仓库分支拉到本地仓库分支，并把本地仓库分支的内容拉到本地工作区。

###git push learngit master	将本地仓库分支推送到远程仓库分支

###git log		查看提交日志
###git reflog	查看操作日志

###git reset --hard head~1	退回上一个版本
###git reset --hard 4e56	退回到指定版本

###git push -f		强制推送


#git rm readme.txt		删除文件

#git merge seventh		与当前分支合并某个分支

git clone https://github.com/13816576524/learngit.git
git checkout second
git pull
git add .
git commit -u 'm'
git push

git checkout -b sixth
git push --set-upstream origin fifth

git branch
git status

git config --global user.name "13816576524"

git config --global alias.checkin '!f(){ git add -A && git commit -m "$@" && git push; }; f'

git reset --hard head~1


git restore .		撤销工作区的修改
git restore --staged .		撤销暂存区的修改

git checkout second
git pull
git checkout master
git pull
git merge second


git push -u origin master
git push

git push origin -d test

git branch -d test

git remote -v

###fetch 'second' branch from the remote server to the local repository
git fetch origin second		
###merge file of the workspace with file of the repository
git merge second

