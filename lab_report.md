# Lab Report 4
##Step 4:
![IMAGE](step4.png)
Used ```ssh lnovilla@ieng6.ucsd.edu``` to log into ieng6.

##Step 5:
![IMAGE](step5.png)
Used ```git clone git@github.com:lnovilla8/lab7.git``` to clone fork of lab7 repository from Github account into ieng6.

##Step 6:
![IMAGE](step6.png)
Used ```cd lab7``` to change directory into lab7 to access test repository files. Ran ```bash test.sh``` to run ```ListExamplesTests.java```.

##Step 7:

![IMAGE](step7vim.png)
![IMAGE](step7.png)
Error is that in merge method's 3rd while loop, ```index1``` is being incremented instead of ```index2``` for ```list2```. Used ```vim ListExamples.java``` to edit file. Typed ```43j``` to get onto 44th line. Pressed ```e``` to get cursor onto ```"2"```, pressed ```<shift> R ``` to go into replace mode, typed 1, pressed ```<esc>``` to go into normal mode. Finished by typing ```:wq!``` to save and close file.

##Step 8:
![IMAGE](step8.png)
Re-ran tests by running ```bash test.sh```. Both tests successfully passed.

##Step 9:
![IMAGE](step9.png)
Ran ```git add .``` to save all changes to files in lab7. Used ```git commit -m "Changed index1 to index2"``` to commit changes to local repository. Finally ran ```git push origin main``` to push committed changes from local main branch to repository branch on Github.
