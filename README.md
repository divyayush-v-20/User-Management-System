# User Management System
This project is a simple **Task Management System** written in **C**, designed to help users
add, view, and manage tasks efficiently. The program provides user registration and
authentication, ensuring that each user's tasks are securely managed.

## Key Features
- **User Registration & Authentication:** Users can register with a username and a password. Credentials are securely encoded and stored, and users can login in multiple sessions. <br>
- **Task Management:** Users can:
    - Add new tasks
    - View existing tasks
    - Remove tasks<br>
- **File-based Storage:** Tasks and user credentials are stored in plain text files, making it easy to maintain data across sessions. Each user has their own task file, in the format `username.txt`.<br>
- **Optimized Searching:** A Binary-Search-Tree is used to store sessional data, providing a logarithmic searching time during a session. The nodes of the tree are of the type
`char*, char*`, which stores `username, password`.<br>
- **Dynamic Memory Allocation:** The project includes *dynamic memory allocation* at majority of the portions, which ensures smooth interaction between the file system and in-memory data structure (BST) for efficient task handling.<br>

## Installation
Clone this repository in your device using the following commands :<br>
```
git clone https://github.com/divyayush-v-20/User-Management-System
cd User-Management-System
```
<br>
Run the following commands in the terminal: <br> 

```
gcc main.c -o ex -L. library.a
./ex
```
And you are ready to go!
