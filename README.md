# BSE GROUP CODING SUMMATIVE
---
## Negpod 10
---
## Table of Contents
---
## Summary
---
## Description
### Question 1

We created four files which are:
1. **main.sh** : the script file containing the code to Create the student record, Save each student record in a file under the name “students-list_0923.txt”, View all students saved in the file and list them on the terminal, Delete the student in the file (By using the student ID), Update the student record in the list (By using the student ID) and Exit the application. To run the main.sh script file. Use this command ./main.sh and follow the steps showed on how to use the application.
   
2. **Students-list_0923.txt** : This is where all the information gotten from the main.sh and all the information a user provided when using the application is stored. The information to be stored is the (student email, age, and student ID)

3. **select-emails.sh** : that get's all the student emails from the students-list_0923.txt file. To run the script file, use this command in  your command line ./select-emails.sh

4. **student-emails.txt** : A text file that saves all the emails gotten after you run the select-emails.sh script file. So all the emails that's gotten after you run the select-emails.sh script file would be saved in student-emails.txt

So you should have all the four files required for question 1 and how to run the scripts


This is how to run the second question

So for question 2, we were told to Create a shell script to automatically move all 4 files created in question 1 in a directory with the name negpod_id-q1. We named our directory negpod_10-q1
The name of the script is move-to-directory.sh and when you run the script file it is meant to move all the files from question 1 and move them into our folder called negpod_10-q1. And to run the move-to-directory.sh script file. Use this command: ./move-to-directory.sh

And for the second part of question 2, we were told to create a shell script to back up the directory created in Question 2, a. to a remote server computer. Each group will create a backup-Negpod_ID.sh. We named our's backup-Negpod_10.sh. And in the script file was the code to create a backup of the directory we made here in question 2 which was negpod_10-q1 to a remote server computer. To run the backup-Negpod_10.sh script file, use this command: ./backup-Negpod_10.sh

To complete the backup to a remote sever computer we installed rsync and we used an sshpass. So to run the backup-Negpod_10.sh script file you need to install rsync on your terminal.
To do that type "sudo apt-get install rsync"

We had the entire negpod 10 group contribute to this entire repo and their names are as follows:
1. Yusuf Molumo
2. Clinton Pikita
3. Armand Kayiranga
4. Gnon Deolinda Bogore
5. Gift Don-Emmanuel
6. Angel Kevine Gitego Rugema
