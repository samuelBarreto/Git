

# Git Command line instructions

Git global setup
git config --global user.name "samukacfc"
git config --global user.email "samukacfc@hotmail.com"

#Create a new repository
git clone https://git.ng.bluemix.net/samukacfc/TecChat.git
cd TecChat
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master

#Existing folder
cd existing_folder
git init
git remote add origin https://git.ng.bluemix.net/samukacfc/TecChat.git
git add .
git commit -m "Initial commit"
git push -u origin master

#Existing Git repository
cd existing_repo
git remote rename origin old-origin
git remote add origin https://git.ng.bluemix.net/samukacfc/TecChat.git
git push -u origin --all
git push -u origin --tags
