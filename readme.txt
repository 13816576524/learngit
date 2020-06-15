master
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


git restore .
git restore --staged .

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

