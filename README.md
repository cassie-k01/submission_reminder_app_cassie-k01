# Submission Reminder App

## What It Is
This is a simple Bash script that helps you keep track of student assignment submissions. It creates folders and files you need.

#1.Folder Structure
When you run the script, it will create this structure:
submission_reminder_<yourName>/
├── config/
│   └── config.env
├── modules/
│   └── functions.sh
├── app/
│   └── reminder.sh
├── assets/
│   └── submissions.txt
└── startup.sh

#2. What Each File Does
- config/config.env: Has details about the assignment.
- assets/submissions.txt: Contains example student submissions.
- modules/functions.sh: Has functions to check submissions.
- app/reminder.sh: The main script that checks for submissions.
- startup.sh: Starts the application by executing 

#3. How to Set It Up
1. Download or Clone the project.
2. Go to the Project Folder:
3. Run the script:bash create_environment.sh
4. cd submission_reminder_<yourName>
5. Run the script:./ startup.sh to launch the app
#NB:You can change the assignment info in config/config.env.
#Update assets/submissions.txt with real student names.
