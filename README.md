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

### ***The Growth Mindset***

The topic of preparing oneself to study a new programming and development course is crucial because it lays the foundation for successful learning and skill acquisition. Just as when I would carefully prepare my home before embarking on a renovation project, preparing oneself for a new course involves understanding the necessary tools, gathering resources, and cultivating the right mindset.

In the article "Upgrade your technical skills with deliberate practice," the concept of deliberate practice is highlighted. Deliberate practice involves intentionally focusing on specific areas of improvement, breaking down complex skills into smaller components, and engaging in targeted practice to enhance proficiency. This approach mirrors the careful planning and preparation required before starting a home renovation. It involves researching and understanding the specific skills and knowledge needed for the course, gathering relevant study materials and resources, and creating a structured plan for learning and practice.

In Carol Dweck's TEDxNorrkoping talk on "The power of believing that you can improve," she discusses the importance of having a growth mindset. Just as a homeowner needs to believe in their ability to learn and overcome challenges during a renovation project, adopting a growth mindset is essential for success in learning programming and development. Embracing the belief that skills can be developed through dedication, effort, and learning from mistakes empowers individuals to persist in the face of difficulties and setbacks.

Angela Lee Duckworth's TED Talks Education video on "Grit: The power of passion and perseverance" emphasizes the role of determination and perseverance in achieving long-term goals. Just as a homeowner must exhibit grit and determination to see a renovation project through to completion, developing grit is crucial for navigating the challenges and complexities of studying a new programming and development course. It involves maintaining focus, staying motivated, and persisting in the face of obstacles.

In Alain de Botton's TEDGlobal 2009 talk on "A kinder, gentler philosophy of success," he encourages a reevaluation of society's definition of success. Similarly, when preparing to study a new programming and development course, it is important to redefine personal success. Rather than solely focusing on immediate outcomes or comparing oneself to others, it is more beneficial to embrace a broader perspective. Success can be measured by the growth and progress made, the skills acquired, and the joy and fulfillment derived from the learning process itself.

In summary, just as a homeowner carefully prepares for a renovation project by understanding the necessary tools, gathering resources, and adopting the right mindset, preparing oneself for a new programming and development course requires deliberate practice, a growth mindset, grit, and a redefined notion of success. By incorporating these elements, individuals can effectively navigate the learning journey and maximize their chances of success in acquiring new technical skills.


### EMOTIONAL INTELLIGENCE SELF-ASSESSMENT TOOL:

1. always I am aware of the physical reactions (twinges, aches,
sudden changes) that signal a “gut reaction.”
 2. usually I readily admit mistakes and apologize.
3. sometimes When I feel angry I can still stay composed.
4. usually I generally have an accurate idea of how another person
perceives me during a particular interaction.
5. rarely In assessing a situation, I look at my biases and adjust my
assessment accordingly.
6. usually I can keep going on a project, despite obstacles.
7. usually I can engage in an interaction with another and pretty well
size-up that person’s mood based on non-verbal signals.
8. somtimes Others feel encouraged after talking to me.
 9. rarely I consider my “emotional temperature” before I make
important decisions.
10. When I feel a strong impulse to do something, I usually
pause to reflect and decide whether I really want to act on
it.
11. usually I can deal calmly, sensitively, and proactively with the
emotional displays of others.
 12. sometimes I can identify the emotion I am feeling at any given
moment.
 13. usually I am able to honestly say how I feel without getting others
upset.
14. usually I can show empathy and match my feelings with those of
another person in an interaction.
15. usually I think about the emotions behind my actions.
16. usually I am respected and liked by others, even when they don’t
agree with me.
17. usually I watch how others react to me to understand which of my own behaviors are effective and which are not.
18. rarley to sometimes I am good at managing my moods, and I refrain from bringing negative emotions to work.
19. usually It’s easy to understand why other people feel the way they
do.
20. usually I can effectively persuade others to adopt my point of view without coercing them.


 I have a good overall level of emotional intelligence. I demonstrate self-awareness by being aware of physical reactions signaling gut reactions and identifying my emotions in the moment. I also show self-regulation by admitting mistakes, apologizing, and staying composed when angry. In terms of social awareness, I have a good ability to perceive others' perceptions, read non-verbal signals, and show empathy. While there are a few areas where I indicated lower frequency, such as adjusting assessments based on biases and managing negative emotions at work, overall, my results indicate a solid foundation of emotional intelligence.


### Bias Self-Assessment:

My score is between 75 and 99, that's mean I’ve made some progress in this area but still have room to grow. I should continue improve the
areas of unconscious bias where I scored the lowest. I should prioritize my self care to improves my overall performance as well as my ability to mitigate bias. I should more like to challenge myself with
new points of view or opinions from podcasts, new authors or documentaries, or new hobbies in order to constantly learn and
expand my perspective. 

---

# Classes Readings:

## Readings Class 01: Exception Handling

- The major benefit of debugging, in simple words, is that it helps in finding and fixing problems or errors in software. When we encounter unexpected behavior or issues in a program, debugging allows us to investigate and understand what is going wrong. By identifying and resolving these problems, debugging improves the overall functionality and reliability of the software. Also, Debugging offers several advantages that contribute to the overall improvement of software development. Firstly, it helps in identifying the root cause of problems, enabling developers to locate errors in the code. Secondly, it allows for efficient error fixing, reducing the time required to resolve issues and improving the functionality of the software. Additionally, debugging provides developers with a better understanding of program execution, aiding in comprehension of the codebase. Moreover, it saves time by narrowing down the search for errors, leading to faster bug resolution. Lastly, debugging contributes to software improvement by enhancing performance, stability, and usability.

- One major benefit of being able to trace the call stack is that it helps in understanding the sequence of function calls and how the program flow reaches a particular point in the code. By examining the call stack, developers can gain insights into the execution path of their program, identify which functions or methods were called leading up to an error or unexpected behavior, and determine the order in which these functions were executed.Tracing the call stack can be particularly useful during debugging, as it allows developers to pinpoint the exact location in the code where an issue occurred. This information helps in isolating the cause of the problem and enables developers to focus their debugging efforts on the relevant parts of the code, leading to faster and more efficient bug fixing.

- Describe how you explain the .Net approach to exception handling to a non technical friend: 

Imagine you're baking a cake using a recipe. While following the steps, you accidentally add too much salt instead of sugar. Now, you have a problem because your cake won't taste good. In software development, similar unexpected problems can occur, called exceptions.

In the .NET framework, developers use a special mechanism called exception handling to deal with these unexpected issues in their code. It's like having a backup plan in case something goes wrong while the program is running.

When an exception occurs, the program doesn't crash immediately. Instead, it jumps to a specific part of the code called an exception handler. This handler acts like a safety net that catches the exception and decides what to do next.

Just like a chef would taste the cake batter and decide whether to fix it or start over, the exception handler in .NET can take different actions depending on the type of exception. It can try to fix the problem, provide an alternative solution, or simply display an error message to the user.

Developers can also write their own exception handlers to handle specific types of exceptions that may occur in their code. This way, they can customize how the program responds to different problems.

The goal of exception handling in .NET is to make sure that even if something unexpected happens, the program doesn't crash completely and the user is informed about the issue in a graceful manner. It helps developers create more robust and reliable software by effectively managing errors and keeping the program running smoothly.

So, in a nutshell, exception handling in .NET is like having a safety net that catches and deals with unexpected problems in software, ensuring that the program doesn't break and providing a better user experience.

- Case StudiesTherac-25 and Ariane 5 : Name glaring mistakes that were made during the production of these systems:


  1. Therac-25: The Therac-25 was a medical radiation therapy machine that caused several accidents in the 1980s. The following glaring mistakes were made during its production:

         a. Software Design Flaw: The software controlling the Therac-25 had a design flaw that led to a race condition. This flaw allowed the machine to deliver a higher radiation dose than intended, resulting in severe overdoses for patients.

         b. Lack of Adequate Safety Interlocks: The Therac-25 lacked proper safety interlocks, which are mechanisms designed to prevent incorrect operation or unsafe conditions. These interlocks would have detected and prevented the high radiation doses, but they were not implemented effectively.

         c. Insufficient Testing: The Therac-25 underwent inadequate testing before being released to the market. The testing did not adequately simulate real-world scenarios, leading to the failure of identifying and fixing the software design flaw.

2. Ariane 5: The Ariane 5 is a European space launch vehicle that encountered a catastrophic failure during its inaugural flight in 1996. The following glaring mistakes were made during its production:

       a. Incompatible Software: The Ariane 5 reused software code from its predecessor, the Ariane 4. However, the guidance system's software for the Ariane 5 was not suitable for the new, more powerful engines and flight characteristics. This incompatibility caused the system to crash shortly after liftoff.

       b. Lack of Error Handling: The reused software code from Ariane 4 included a piece of code that calculated the rocket's horizontal velocity. This value exceeded the maximum representable value in the system, triggering an integer overflow. The lack of appropriate error handling for this exceptional condition resulted in the system malfunctioning.

       c. Insufficient Testing and Verification: The Ariane 5's software was not thoroughly tested and verified under real-flight conditions. The test data used for validation did not adequately cover the range of possible input values, failing to detect the incompatibility and software limitations.



## Things I want to know more about:

----