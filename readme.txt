sudo apt-get install git

mkdir myproject
cd myproject

git init
git config --global user.name 'user_name'
git config --global user.email 'user_email'
git remote add origin https://github.com/user_name/project_name.git

vim file.py
git add file.py
git add.
git commit -m 'file added'
git push origin master
