##This is my personal Data Science Course note
###Organized by course and by week

##Course 1
###Week 1

/*Git hub in GitBash*/

git config --global user.name "name"
git config --global user.email "xx@xx" /*match with github account*/
git config --list;

/*New repo, starting  from local*/

mkdir ~/somename
cd somename

git init

touch readme.md 

git add -A

git commit -m "comment"
/*********************************************/
/*Create a new repository on the command line*/
touch README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/owenjy/dcnote.git
git push -u origin master

/*Push an existing repository from the command line*/
git remote add origin https://github.com/owenjy/dcnote.git
git push -u origin master