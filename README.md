# How to use Git and Github;
 first we will install git on local computer then we will make acount account on github. then we will go to local computer. open git bash or cmd write the following command
 git config --list
 
 # step 2
 we will set the name and email. we will write the following command for this purpose
 git config --global user.name "Name" then Enter
 git config --global user.email "Email" then Enter
 
 # step 3 (Clonning project)
 open the desired project on github then click on the code button on the right side.
 then you will get the link of that project. Just copy that link and go to your desired place where you want to clone project.
 in my case i want to clone project on desktop.
 write the following command for the exact Desktop
 cd Desktop/
 # step 4 
 for intilization of git in the desired folder 
 open the location of that folder in git bash 
 then write  git init. there will  create a file with the name of git.
 # step 5
 for checking status 
 just write git status
 
 # step 6
 for adding file 
 git add file name with extention(index.html)
 if you want to add multiple files we will use the following command
 git add . and then enter
  
 # step 7
 for commit
 after adding files, we will save our changes with commit. we will write the following command
 git commit -m "added new files( it will be part of first input field of commit " -m "it is descript(option) it will be the part of 2nd input field of commit"
 for checking status just write
 git status
 
 # Pushing files or anything to repositry with an easy way(clonning)
 first make your repositry on github then copy the link of that repositry. go to your local computer then clone repositry on desired location. 
 then open that folder in visual studio or any editer. add files then open bit bash write the same command like
 ### git init
 ### git add .
 ### git commit -m "etc. file added"
 ### git push origin master 
 your code will push 
 
 # set 8
 for pushing files from local to remote 
 we will write the follwoing command
 git remote add origin http link of the repositry
 after remoting we will push our files 
 git push origin master and then enter
 # set 9
 if you get error realted to un related histories then write the follwoing command
 git pull origin master  --allow-unrelated-histories then enter

 # for log
 Command: git log

 # for checking branch
 command: git branch
 # for making new branch
 Command: git checkout -b (feature/branch.name) ( feature in that case k its a feature of website. for example i am designing login page of website then the command will be
 git checktou -b feature/login
 # for changing brach 
 command: git checkout (desired Branch name)
 # comparing with branch
 command:
 git diff branch_name
 # mergin branch
 command: git merge branch_name
 
 # deleting branch
 when should we delete branch?
 when we merge the branches with master branch. after that we delete the branch for that purpose we will write the folloing command
 git branch -d Branch_name

 # pull command
 if you make a file on the remote and you are not getting that file in visual studio or any editor. In that case you have to take latest for that we will write a command
 git pull origin branch_name

 # Conflict
 if a file is in 1 branch and that same file in the other branch when you will so some changes in both files and save then when you merge them there will be an error (confilicting Error)
 for resolving it open branch with the help of following command
 ### git checkout branch_name
 then go to visual studio in my case. VC will display option like you want to save changes or not or you want to save both. after selecting save that file 
 then again go to bit bash 
 again write the following commands
 #### git add .
  #### git commit -m "Message" -m "description"
 #### git push origin branchName
 
 
 # Ignoring File
 if you want to push some of the files from local to remote not all. then you should make a file with the name of .gitignore in visual studio. THen you can write the name of file in it or folder with comment # is use for comment * + extion of log(.log) is use for block file. For example:
 img folder and there is a file pic.png. for ignoring this file 
 ### go to .gitignore file then write. /img and save 
 ### if you have log files and you want to block just write *.log or you want to block just one file of log then just write the name of that file e.g. development.log. A
 After that same procedure for pushing 
 
 
 

