# reading-notes
This is website to keep track of my observations and questions from the reading assignments throughout the **.NET Code 401 course**.

![photo](https://clockify.me/blog/wp-content/uploads/2021/10/Best-brainstorming-techniques-for-productive-work-cover-min.png)

## Code 401 - Advanced Software Development



### *Overview*
Reading Notes is a website that can help you to write down and keep track of your observations and questions from the reading assignments throughout the Code 401 - Advanced Software Development. 


---


> It's a way to document and highlight your new knowledge. 


---


### *utilities* 

-  Observations
-  Questions 
-  Organizing ideas and new knowledge 

---

### ***Introduction to SQL*** 

Relational databases are a fundamental concept in data management, where data is organized into tables with rows and columns. SQL (Structured Query Language) is the standard language used to interact with relational databases. It allows users to retrieve, manipulate, and store data by using commands such as SELECT, INSERT, UPDATE, and DELETE. SQL Bolt website that offers interactive lessons to learn SQL through practical examples. It covers various topics including querying data, filtering and sorting results, modifying data, and working with multiple tables using joins. So I practiced with these stuff and by completing these lessons, I gained a solid understanding of relational databases and SQL, and this will enable me to effectively work with databases in my projects and applications.


- SQL Lesson 1: SELECT queries 101 <br>
![photo](./assets/images/SQL%20Lesson1.png)

- SQL Lesson 2: Queries with constraints (Pt. 1) <br>
![photo](./assets/images/SQL%20Lesson2.png)

- SQL Lesson 3: Queries with constraints (Pt. 2) <br>
![photo](./assets/images/SQL%20Lesson3.png)

- SQL Lesson 4: Filtering and sorting Query results <br>
![photo](./assets/images/SQL%20Lesson4.png)

- SQL Review: Simple SELECT Queries <br>
![photo](./assets/images/SQL%20Lesson5.png)

- SQL Lesson 6: Multi-table queries with JOINs <br>
![photo](./assets/images/SQL%20Lesson6.png)

- SQL Lesson 13: Inserting rows <br>
![photo](./assets/images/SQL%20Lesson13.png) <br>

- SQL Lesson 14: Updating rows <br>
![photo](./assets/images/SQL%20Lesson14.png) <br>

- SQL Lesson 15: Deleting rows <br>
![photo](./assets/images/SQL%20Lesson15.png)

- SQL Lesson 16: Creating tables <br>
![photo](./assets/images/SQL%20Lesson16.png)

- SQL Lesson 17: Altering tables <br>
![photo](./assets/images/SQL%20Lesson17.png)

- SQL Lesson 18: Dropping tables <br>
![photo](./assets/images/SQL%20Lesson18.png)

---

### ***Practice in the Terminal***

1. **The Command Line** - What is it, how does it work, and how do I get to one:
- The command line, also known as the shell or terminal, is a text-based interface in which you can interact with your computer's operating system.

- It allows you to execute commands by typing them in, and the computer responds by executing those commands.

- The command line provides more control and flexibility than graphical user interfaces (GUIs) in certain scenarios, such as scripting and automating tasks.

- To access the command line, you can open a terminal application on your computer. In Linux, you can use the terminal emulator provided by your distribution, such as GNOME Terminal or Konsole. On macOS, you can use Terminal.app, and on Windows, you can use PowerShell or Command Prompt.

2. **Basic Navigation** - An introduction to the Linux directory system and how to get around it:

- The Linux directory system follows a hierarchical structure, with the root directory ("/") at the top. All other directories and files are organized within this structure.

- The command line provides several commands to navigate the directory system:
  - **`pwd`** (print working directory) displays the current directory you are in.
  - **`ls`** (list) lists the contents of the current directory.
  - **`cd`** (change directory) allows you to navigate to different directories. For example, 
  - **`cd directory_name`** moves to a directory named "directory_name" within the current directory.
  - **`cd ..`** moves up one level to the parent directory.
  - **`cd ~`** moves to the home directory.
- Directory paths in Linux are represented using forward slashes ("/"). For example, "/home/user/Documents" represents the "Documents" directory within the "user" directory, which is inside the "home" directory at the root ("/").
- You can use the Tab key for auto-completion of commands and directory/file names, which can save time and prevent typos.

3. **More About Files** - Find out some interesting characteristics of files and directories in a Linux environment:

- Linux treats everything as a file, including regular files, directories, devices, and even processes.
- Filenames in Linux are case-sensitive, so "file.txt" and "File.txt" are considered as different files.
- Hidden files and directories are prefixed with a dot (".") in their names, and they are not displayed by default in **`ls`** command output. You can use the **`-a`** option with ls (e.g., **`ls -a`**) to show hidden files.
- Directories have two special entries: "." (dot), which refers to the current directory, and ".." (dot dot), which refers to the parent directory.
- The **`file`** command allows you to determine the type of a file. For example, **`file myfile.txt`** provides information about the type of "myfile.txt".
- File and directory names can contain spaces, but it is generally recommended to avoid them to simplify command line operations.

4. **Manual Pages** - Learn how to make the most of the Linux commands you are learning:

- Linux provides comprehensive documentation for commands through manual pages, which can be accessed using the **`man`** command. For example, **`man ls`** displays the manual page for the **`ls`** command.
- Manual pages provide detailed information about a command's usage, options, and examples.
 - The **`man`** command opens the manual page in a pager program that allows you to navigate using keyboard keys, such as the up and down arrow keys.
- To search for a specific term within the manual page, you can use the forward slash ("/") followed by the term and press Enter. For example, **`/search_term`** searches for "search_term" within the manual page.
- Pressing "q" exits the manual page and returns to the command line.

5. **File Manipulation** - How to make, remove, rename, copy, and move files and directories:

- The **`touch`** command creates an empty file. For example, **`touch myfile.txt`** creates a file named "myfile.txt" if it doesn't exist or updates its modification time if it does.
- The **`rm`** command removes files and directories. For example, **`rm myfile.txt`** deletes the file "myfile.txt". To remove directories, you can use the **`-r`** (recursive) option, e.g., **`rm -r mydir`**.
- The **`mv`** command renames and moves files and directories. To rename a file, use **`mv oldname newname`**. To move a file or directory, use **`mv source destination`**.
- The **`cp`** command copies files and directories. For example, **`cp myfile.txt mydir/`** copies "myfile.txt" to the "mydir" directory. Use the **`-r`** option to copy directories recursively.
- Be cautious when using commands like **`rm`** and **`mv`**, as they can permanently delete or overwrite files. Always double-check your commands before executing them.

---

