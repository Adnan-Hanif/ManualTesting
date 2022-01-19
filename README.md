# How to use Git and Github;
 first we will install git on local computer then we will make acount account on github. then we will go to local computer. open git bash or cmd write the following command
 git config --list
 
 ## step 2
 we will set the name and email. we will write the following command for this purpose
 git config --global user.name "Name" then Enter
 git config --global user.email "Email" then Enter
 
 ## step 3 (Clonning project)
 open the desired project on github then click on the code button on the right side.
 then you will get the link of that project. Just copy that link and go to your desired place where you want to clone project.
 in my case i want to clone project on desktop.
 write the following command for the exact Desktop
 cd Desktop/
 ### step 4 
 for intilization of git in the desired folder 
 open the location of that folder in git bash 
 then write  git init. there will  create a file with the name of git.
 #### step 5
 for checking status 
 just write git status
 
 ##### step 6
 for adding file 
 git add file name with extention(index.html)
 if you want to add multiple files we will use the following command
 git add . and then enter
  
 ###### step 7
 for commit
 after adding files, we will save our changes with commit. we will write the following command
 git commit -m "added new files( it will be part of first input field of commit " -m "it is descript(option) it will be the part of 2nd input field of commit"
 for checking status just write
 git status
 ####### set 8
 for pushing files from local to remote 
 we will write the follwoing command
 git remote add origin http link of the repositry
 after remoting we will push our files 
 git push origin master and then enter

 
 
 

