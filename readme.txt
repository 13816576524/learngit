second
<<<<<<< HEAD
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
=======
git reset hard head~1
git reset soft head~1
>>>>>>> 2abed8794069b0005a9993b21ec1518a87abc368
