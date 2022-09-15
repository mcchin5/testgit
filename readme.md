hello testgit
revided here under

mkdir testgit
cd testgit
echo hello testgit >> readme.md
git init
git config --global --add safe.directory /media/sf_Share/testgit
git commit -m "first commit"
git remote add testgit https://github.com/mcchin5/testgit.git
git push --set-upstream testgit master

