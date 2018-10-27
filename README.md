

# Git Command line instructions
**************************************

![git](https://static1.squarespace.com/static/5783a7e19de4bb11478ae2d8/5821d2b909e1c46748736b4a/583d6f01e58c627c3a6b7e47/1502273213995/Github_Blog.gif)


****************************************

=====================================
Git global setup

=====================================

git config --global user.name "name"

git config --global user.email "email"

---------------------------------------------

Create a new repository 

---------------------------------------------

git clone https://

cd folder

touch README.md

git add README.md

git commit -m "add README"

git push -u origin master


-------------------------------------------------

Existing folder

-------------------------------------------------

cd existing_folder

git init

git remote add origin https://

git add .

git commit -m "Initial commit"

git push -u origin 

---------------------------------------------

#Existing Git repository

--------------------------------------------

cd existing_repo

git remote rename origin old-origin

git remote add origin https://

git push -u origin --all

git push -u origin --tags
