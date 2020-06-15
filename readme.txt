master
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
