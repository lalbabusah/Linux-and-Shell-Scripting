sudo apt-get install git

mkdir myproject
cd myproject
vim helloworld.py

git init
git config --global user.name 'user_name'
git config --global user.email 'user_email'
git remote add origin https://github.com/user_name/myproject.git

git add helloworld.py
git add.
git commit -m 'commit message'
git push origin master
