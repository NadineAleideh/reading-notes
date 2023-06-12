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

1. Name one major benefit of being able to trace the call stack?

    - One major benefit of being able to trace the call stack during debugging, is that it helps in understanding the sequence of function calls in their program and how the program flow reaches a particular point in the code and identify which functions or methods were called leading up to an error or unexpected behavior.

2. If you could use try/catch in your day to day life, name an exception you’d like to ‘catch’ and handle?

   - If I could use try/catch in my day-to-day life, I'd like to use it when I book a flight for vacation , there's a possibility that the airline might cancel or reschedule the flight at the last minute or I be late. To handle this situation, I can use try/catch exception handling and do some altrnative solutions.

3. From an efficiency standpoint, are there downsides to try/catch blocks?
   - From an efficiency standpoint, downsides of try/catch blocks include potential performance impact due to overhead and disruption of control flow. Debugging can also be more complex, and excessive use can harm code readability.

4. Describe how you explain the .Net approach to exception handling to a non technical friend.

   - I'd like to say imagine you're cooking a recipe. While following the steps, you accidentally add too much sugar instead of salt. Now, you have a problem because your cake won't taste good. In software development, similar unexpected problems can occur, called exceptions. And just like a chef would taste the recipe better and decide whether to fix it or start over, in the .NET framework developers use a special mechanism called exception handling to deal with these unexpected issues in their code. It's like having a backup plan in case something goes wrong while the program is running.
 
5. Case Studies Therac-25 and Ariane 5: Name glaring mistakes that were made during the production of these systems.


   - Therac-25: The Therac-25 was a medical radiation therapy machine that caused several accidents in the 1980s. The following glaring mistakes were made during its production: Software Design Flaw, Lack of Adequate Safety Interlocks, Insufficient Testing.


   - Ariane 5: The Ariane 5 is a European space launch vehicle that encountered a catastrophic failure during its inaugural flight in 1996. The following glaring mistakes were made during its production: Incompatible Software, Lack of Error Handling, Insufficient Testing and Verification.


## Things I want to know more about:

----

## Data Structures and Algorithms

- Why Does This Topic Matter?

  Data structures and algorithms are crucial topics in computer science and software development. They impact the efficiency, scalability, problem-solving abilities, and code maintainability of software systems. Understanding and applying appropriate data structures and algorithms are fundamental skills for developing efficient and high-performing software.

- What is 1 of the more important things you should consider when deciding which data structure is best suited to solve a particular problem?


  When deciding which data structure is best suited to solve a particular problem, one of the more important things to consider is the efficiency of the operations required by the problem. By considering the specific operations required by the problem and their associated time complexities, we can choose a data structure that optimizes performance. It's essential to balance the trade-offs between different operations and choose the one that suits our problem's requirements the best. And different data structures excel at different operations. For example:

  1. Arrays: They provide constant-time access to elements by index, but inserting or deleting elements in the middle of the array can be inefficient, as it requires shifting the subsequent elements.

  2. Linked Lists: They allow for efficient insertion and deletion of elements anywhere in the list, but accessing elements by index requires traversing the list, resulting in a linear-time operation.

  3. Hash Tables: They provide fast average-case access, insertion, and deletion operations using a hash function. However, they may have collisions, which can degrade performance.

  4. Trees: They provide efficient search, insertion, and deletion operations for sorted data, especially when balanced. Binary search trees, AVL trees, and red-black trees are examples of tree-based structures.

  5. Heaps: They excel at maintaining a collection of elements where the highest or lowest value needs to be retrieved efficiently. Heap operations, such as insertion and extraction of the extremum, have logarithmic time complexity.

  6. Graphs: They are useful for representing relationships between entities. Graph traversal algorithms, such as depth-first search (DFS) and breadth-first search (BFS), are commonly used to solve graph-related problems.

  By considering the specific operations required by the problem and their associated time complexities, you can choose a data structure that optimizes performance. It's essential to balance the trade-offs between different operations and choose the one that suits your problem's requirements the best.


***Big O notation*** is a tool used to evaluate the efficiency of a data structure when performing specific operations like adding elements, sorting data, or searching for elements. It allows us to measure and compare how well different data structures handle these tasks in terms of their time complexity or performance. By analyzing the Big O notation of a data structure, we can determine how its performance scales with increasing input sizes and make informed decisions about which data structure is best suited for a particular operation.


- How can we ensure that we’ll avoid an infinite recursive call stack?

  To avoid an infinite recursive call stack, we should consider these measures:

  1. Base Case: Every recursive function should have a base case that acts as the termination condition for the recursion. The base case should be defined such that it can be reached eventually, breaking the recursion. Without a proper base case, the recursion will continue indefinitely, causing a stack overflow.

  2. Recursive Step: Within the recursive function, there should be a step that moves towards the base case. Each recursive call should be closer to reaching the base case, ensuring that the recursion progresses towards termination. If the recursive step does not bring the problem closer to the base case, it may result in infinite recursion.

  3. Correct Parameterization: Ensure that the parameters passed to the recursive function are appropriate and move the problem closer to the base case. Incorrect parameterization can lead to infinite recursion.

  4. Test with Small Inputs: Before running the recursive function on large inputs, it's advisable to test it with small inputs to verify that it terminates correctly. By testing on small inputs, you can catch any potential issues with infinite recursion earlier and debug them.

  5. Analyze Recursion Depth: Consider the depth of recursion that your program might encounter. Recursive functions rely on the call stack to keep track of function calls. If the recursion depth is too large, it can exhaust the available stack space and lead to a stack overflow. In such cases, you might need to optimize your algorithm or consider using an iterative approach instead.

  6. Tail Recursion Optimization (if applicable): Some programming languages and compilers offer tail call optimization, where recursive calls in tail position (i.e., the last operation of a function) do not consume additional stack space. This optimization effectively eliminates the risk of a stack overflow caused by infinite recursion in tail-recursive functions.

     By carefully designing your recursive function with a proper base case, recursive step, and correct parameterization, and by testing and analyzing recursion depth, we can reduce the chances of encountering an infinite recursive call stack.

## Things I want to know more about:

----

## Engineering Readings


- why this topic matters as it relates to what you are studying in this module?

  These stuff will help get us in the right frame of mind for our works ,our study and getting ready to start on our career.

- What’s the one thing I bring to this career (and a potential employer) that nobody else can?

  Attention to Detail: I have a keen eye for detail and a commitment to producing high-quality work. And Collaboration and Communication: I bring exceptional collaboration and communication skills to the table. My strong interpersonal skills contribute to a positive and productive work environment.

- What are 3 things I’ll start doing to “un-stick” myself whenever I get stuck on tough piece of code, logic, or feature?

   When facing a tough piece of code, logic, or feature, here are  things that I will start to do to "un-stick" myself:
  
  1. Debug: Step through my solution to find errors and understand what the code is actually doing.

  2. Reassess: Take a different perspective, look for general approaches, or start fresh to gain new insights.

  3. Research: Use resources like Google to find solutions to sub-problems and learn from others' approaches.

  4. Stay persistent, maintain a problem-solving mindset, and embrace the opportunity to learn and grow from these experiences.

  These steps help overcome obstacles and promote learning and growth in problem-solving.

  ## Things I want to know more about:

----

## Readings: Unit Testing and Documentation

1. Name 3 ways in which Unit Testing improves your codebase and productivity:


  - Early Bug Detection: Unit testing catches bugs early, preventing them from spreading to other parts of the codebase, which reduces debugging time and effort.

  - Code Refactoring and Maintenance: Unit tests act as a safety net, ensuring that changes to the codebase don't introduce unintended issues or break existing functionality, enabling more agile development and easier code maintenance.

  - Documentation and Code Understanding: Unit tests prompt developers to think about code usage and expected behavior, serving as executable documentation and providing examples of how to use specific parts of the codebase, thus enhancing code understanding and collaboration among team members.
 
 2. How would you write a unit test for a household task such as putting away laundry?

    I would define a function that represents a specific step or behavior of the task and write assertions to verify its expected outcome. `test_put_away_laundry()` function is a unit test that verifies the behavior of the `put_away_laundry()` function. It could include assertions to ensure that the function returns the expected output or behaves correctly based on certain inputs.

 3. Name 3 reasons a quality README is just as important as quality code.

    A quality README complements quality code by providing documentation, easing project understanding and collaboration, and fostering community engagement and adoption. It is an essential component of any software project, helping to ensure its success and maintainability.


4. When writing a README for your co-developers, name 4 crucial elements to include.

- Project Overview: Provide a brief description of the project's purpose and goals.

- Installation and Setup: Clearly explain how to install and set up the project, including any dependencies or prerequisites.

-  Usage and Examples: Describe how to use the project and provide illustrative examples.

-  Contribution Guidelines: Encourage and guide co-developers to contribute, specifying guidelines for bug reports, feature requests, coding style, and testing.

   These elements ensure that co-developers quickly understand the project, can set it up easily, know how to use it effectively, and are empowered to contribute to its development.


  ## Things I want to know more about:

----