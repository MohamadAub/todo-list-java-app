# todo-list: A command line application in JAVA
A simple command-line To-Do List application built in Java.   Users can create, edit, mark as done, and delete tasks.   Tasks are saved to a data file and automatically reloaded when the program restarts.   Includes a text-based menu system for easy navigation.

A brief overview:
This program is menu-driven. User will be presented with available options corresponding to selected menu. User will select an option from given choices and press ENTER key to move to next step. This program will save all tasks in the data file, therefore, next time when you open the program, it will resume its state.

Basic features
Models a task with:
task title
due date
completion status
project (if any)
Display a collection of tasks that can be sorted
by date
by project
Support the ability to
add task
edit task
mark a task as done
remove (delete) tasks
Support a text-based user interface
Load and save task list to data file

Class Diagram
![ToDoList-class-diagram](https://github.com/user-attachments/assets/eb41396f-de2c-48b0-ae6f-c75912b8f551)

User Manual
Starting the application
When user will run the program, main menu of the program (as shown below) will be shown to the user:
<img width="753" height="285" alt="00-mainmenu" src="https://github.com/user-attachments/assets/f4e129d0-5a57-42e4-b0ad-a5b7a653004d" />

Display list of tasks
If user types number [1] and press ENTER key, the application will display the options for user to get list of all previously added tasks sorted by date or by project.
<img width="753" height="491" alt="01-displayalltasks" src="https://github.com/user-attachments/assets/8818b1fc-96f9-4539-8a02-555db05c4cd3" />

Add a new task
If user types number [2] and press ENTER key, the application will prompt the user to enter the required fields of a task to add in the task list.
<img width="753" height="165" alt="02A-addnewtask" src="https://github.com/user-attachments/assets/4d51d124-1cb5-4482-bca1-e1033ac941a3" />
<img width="753" height="246" alt="02B-addnewtask" src="https://github.com/user-attachments/assets/122a1a0f-0d77-450a-a020-57724043672e" />
Edit an existing task (update, mark as done, remove)
If user types number [3] and press ENTER key, the application will display the list of all previously saved tasks with index number and user has to select a task to perform any update, to mark as done or to remove.
<img width="753" height="593" alt="03-edittask" src="https://github.com/user-attachments/assets/3a966554-71f3-4edf-b8c1-9070abf56e01" />
Closing the application
If user types number [4] and press ENTER key, the application will save data of all tasks from memory and write to the data file on disk (defaut filename is tasks.obj).
<img width="753" height="124" alt="04-closingapp" src="https://github.com/user-attachments/assets/c192caa0-221b-4b91-a821-62ac381bbc48" />



