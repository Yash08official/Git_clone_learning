# Git_clone_learning

<h1> Author : Yash Wasankar </h1>

git init

git clone "copy URl from Githib"

file will be in local machine (here)

then add some changes
check status "git status"

then

git add . OR "git add name_of_file"
check status "git status"

then
git commit -m "new change in new file"

then
git push origin main

there is also one command called ""git log"

which says how many times commit oocur.


<h2>If you change the file or delete something (code) then you think that i dont want to change the file  then we will used following</h2>

you change something

then you said `git add . 
changes will done
then you realize i dont want to do it 
then you used "git reset index.html" file_name
then when you do again git status
then it will say your changes not "satged for commit"


<h2>After commiting you want to reset your changes then </h2>

if you do

git add file_name
git commit -m "msg"
and now you want to reset
then 
you can do
"I you want to reset "recent" commit then you can simply write"
"git reset HEAD~1 "


HEAD : Pointing to the latest commit
that 1 means "that only one commit you want to  undo or removed"
