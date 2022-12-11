First time our code push into github
======================================
1. create github repo in github account
2. create folder in your local machine(pc,vm(virtual machine)) by using mkdir [or] via console.
3. login with gitbash in same folder(your pc)
4. copy some files(tasks) into your folder 
5. use git commands to push your files to github

some commands
==============
mkdir <-foldername->

ls

cd <-foldername->

ls

touch <-filename->

vi filename (it opens vi editor to insert the data)

click "i" button insert some data

add some data like hello world or anything

commands: to save the data into a file
--------

esc 

shift + colon 

wq!

[OR]
  
cp -r <-source-path/file/folder-> <-destination-path/file/folder->  # -r means recursive (copy inside folders files/folders)

git init
  
ls
  
ls -la
  
git add <-filename/folder-> [OR] git add -A [OR] git add .
  
git commit -m "<-message->"
  
git branch -M main
  
git remote add origin <-https github repo url->
  
git push -u origin main

6. Refresh the page in github repo website


Second time our code push into same github repo
================================================
1. git add <-filename/folder-> [OR] git add -A [OR] git add .
  
2. git commit -m "<-message->"
  
3. git push -u origin main
