# Lab Report 4 - Vim  
## Aidan Rikic  
Step 4.  
![Image](lab4_ss1.png)  
Commands: `ssh arikic@ieng6.ucsd.edu` <enter>  
Explanation: To log in to ieng6 I had to use the ssh command and put my login and hit enter.   

Step 5.  
![Image](lab4_ss2.png)  
Commands: `git clone` <command v> `git@github.com:aidanRik/lab7_aidan.git` <enter>  
Explanation: To clone the repository I had to copy the link from github, and then type into the terminal `git clone` and then I pasted the copied path with command v and then I hit enter.    

Step 6.  
![Image](lab4_ss3.png)  
Commands: `bash test.sh` <enter>  
Explanation: To show the test failing I ran the bash script `test.sh`. In order to do that, I typed `bash test.sh` and hit enter.  

Step 7.  
![Image](lab4_ss4.png)  
Commands: `vim ListExamples.java` <enter>, <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down> <down>, <right> <right> <right> <right> <right> <right> <right> <right> <right> <right> <right>, `x`, `a 2`, `:wq`  
Explanation: In order to change the code of the failing tests, I need to go to line 44 in `ListExamples.java` and change index1 to index2. 
I can do this by typing `vim ListExamples.java` then hitting `down` 43 times and `right` 11 times to place the cursor over 1 in `index1`. 
I hit `x` to delete the 1 and then hit `a` and `2` which will append 2 to `index` producing `index2`.  

Step 8.  
![Image](lab4_ss5.png)  
Commands: <caps lock> `ZZ` <caps lock> `bash test.sh` <enter>
Explanation: In order to run the tests again, I have to exit vim. So to save what I changed and exit I type `ZZ`. 
Then I typed `bash test.sh` to run the tests again.  

Step 9.  
![Image](lab4_ss6.png)  
Commands: `git add .` <enter> `git commit -m "It's been commited"` <enter> `git push` <enter>  
Explanation: In order to commit and push the changes I made to Github I typed in `git add .` that will add all files in the current directory and then I typed in `git commit -m "It's been committed"` to commit the changes made and then I typed in `git push` to push them to Github. 
