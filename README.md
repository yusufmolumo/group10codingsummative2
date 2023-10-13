# BSE GROUP CODING SUMMATIVE

## Negpod 10

## Table of Contents
- [Summary](#Summary)
- [Description](#Description)
  -[Question 1](#Question 1)
  -[Question 2](#Question 2)
- [Contributors](#Contributors)
  
## Summary
The ALU Student Registration System is an application that takes user input and loads and builds the Bachelor of Software Engineering cohort list of students. The inputs the application takes are the following information (student email, age, and student ID).

## Description

### Question 1
## ALU Student Registration System

We created four files which are:
1. `main.sh`: the script file containing the code to Create the student record, Save each student record in a file under the name “students-list_0923.txt”, View all students saved in the file and list them on the terminal, Delete the student in the file (By using the student ID), Update the student record in the list (By using the student ID) and Exit the application. To run the main.sh script file. Use this command ./main.sh and follow the steps showed on how to use the application.
   
2. `Students-list_0923.txt`: This is where all the information gotten from the main.sh and all the information a user provided when using the application is stored. The information to be stored is the (student email, age, and student ID)

3. `select-emails.sh`: that get's all the student emails from the students-list_0923.txt file. To run the script file, use this command in  your command line:
 `./select-emails.sh`

4. `student-emails.txt`: A text file that saves all the emails gotten after you run the `select-emails.sh` script file. So all the emails that's gotten after you run the `select-emails.sh` script file would be saved in student-emails.txt

So you should have all the four files required for question 1 and how to run the scripts

### Testing the ALU Student Registration System
1. **To create a student record:**
- Run  the `./main.sh`
- Select option 1
- Enter student email
![BSE_1](https://github.com/yusufmolumo/group10codingsummative2/assets/112552126/ba8e7c61-dcaf-46af-b330-4a2736a12f31)

2. **To view all students:**
- Run the `./main.sh`
- Select option 2
![BSE_2](https://github.com/yusufmolumo/group10codingsummative2/assets/112552126/2dbcf24e-ef04-4113-b6a4-89dcea06dea4)

3. **To delete a student record:**
- Run the `./main.sh`
- Select option 3
- Enter Student ID to delete
![BSE_3](https://github.com/yusufmolumo/group10codingsummative2/assets/112552126/5566857a-8a77-4e9c-af00-ea1d54b77494)

4. **To update a student record:**
- Run the `./main.sh` script
- Select option 4
- Enter Student ID to update
- Enter new student email
- Enter new age
![BSE_4](https://github.com/yusufmolumo/group10codingsummative2/assets/112552126/f35a0a18-43d1-47ec-b776-67ad88ee46bc)

5. **To select emails:**
- Run the `./main.sh` script
- Select option 5
![BSE_5](https://github.com/yusufmolumo/group10codingsummative2/assets/112552126/904506ee-25aa-4548-813e-c89f0affbbd4)

### Question 2
## Automation with Linux

1. We Created a shell script to automatically move all 4 files created in question 1 in a directory with the name `negpod_id-q1`. We named our directory `negpod_10-q1`
The name of the script is `move-to-directory.sh` and when you run the script file it is meant to move all the files from question 1 and move them into our folder called `negpod_10-q1`. And to run `move-to-directory.sh` script file. Use this command:
`./move-to-directory.sh`

2. We created a shell script to back up the directory created in [Question 2](#Question 2) part 1 to a remote server computer. Each group will create a backup-Negpod_ID.sh. We named our's `backup-Negpod_10.sh`. And in the script file was the code to create a backup of the directory we made here in question 2 which was negpod_10-q1 to a remote server computer. To run the backup-Negpod_10.sh script file, use this command:
 `./backup-Negpod_10.sh`

To complete the backup to a remote sever computer we installed rsync and we used an sshpass. So to run the `backup-Negpod_10.sh` script file you need to install rsync on your terminal.
To do that type "sudo apt-get install rsync"

### Contributors:
1. [Yusuf Molumo](https://github.com/yusufmolumo)
2. [Clinton Pikita](https://github.com/Clint07-datascientist)
3. [Armand Kayiranga](https://github.com/Armandkay)
4. [Déolinda Bogore](https://github.com/Deolinda1506)
5. [Gift Don-Emmanuel](https://github.com/Giftiee001)
6. [Angel Kevine Gitego Rugema](https://github.com/AngeGitego)
