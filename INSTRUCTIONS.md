DETAILED INSTRUCTIONS ON HOW TO GO ABOUT YOUR SIMPLE_SHELL PROJECT
Pages 1------- 4 instructions for WHO CREATED the repository
Pages 5 ------ 7 instructions for the COLLABORATOR 
PLEASE NOTE: 
These instructions are written for anyone who has NOT STARTED their simple_shell project.
BUT if you have STARTED, and you are NOT SURE of your answers,
PLEASE RENAME your existing simple_shell repo and call it practice_shell
Type the following command to rename it 
mv simple_shell practice_shell
Press enter
And also go to your GitHub and rename the repository to practice _shell
To prevent errors such as: repository already exists
INSTRUCTIONS FOR PARTNER A. (creator of the GitHub repository) 
Carefully follow these instructions:
1. Use this link to a repo that contains solutions https://github.com/besthor/simple_shell
2. By the right hand side of your screen, click on a box icon called code
3. A drop-down menu will appear, click on https
4. Copy the link, open a sandbox or go to whatever terminal you often use for your ALX projects
5. Write git clone give a space and Paste the https on your terminal
6. Please DO NOT ADD YOUR TOKEN
7. Everything should look like this
8. root@c8d57ccd7f28:/# git clone https://github.com/besthor/simple_shell.git
9. Press enter
10. Rename the cloned repo to a new name called soft_copy, type in the command to rename
11. Everything should look like this
12. root@c8d57ccd7f28:/# mv simple_shell soft_copy
13. Press enter
INSTRUCTIONS FOR PARTNER A ONLY (creator of the GitHub repo)
How to create a GitHub repository and add a Collaborator:
1. open your GitHub account
2. by the top right side of your screen
3. click on the + icon
4. a drop-down menu will appear
5. click on new repository
6. write in the name for your new repository as simple_shell
7. Write in a description that suits your taste. for example: My second ALX collaborative project on 
C-programming
8. Please ensure you make it a public repository by clicking Public
9. Click on the box icon Create repository
10. Press enter
11. By the right side of your screen
12. Click on settings
13. By the top left of your screen
14. Click on collaborator 
15. Scroll down 
16. Click on Add people
17. (It MAY prompt you to enter your password for authentication, Enter your GitHub password)
18. Type in your Partner’s GitHub username
19. Click on add, an email notification will be sent to him/her to confirm your request
20. You have successfully completed this process
21. Continue the next set of instructions while you wait for his/her acceptance.
Instructions for bringing the new remote repository into your local 
computer/system
1. Go to your GitHub
2. Click on the new simple_shell repository you just created
3. By the right hand side of your screen
4. Click on https
5. Copy the link
6. Go to your sandbox or whatever terminal you often use for your Alx projects
7. Write, git clone give a space and paste the link you copied
8. PLEASE PUT IN YOUR OWN TOKEN and put the @ symbol to avoid username and 
password prompts when trying to git push
9. Everything should look like this:
git clone https://ghp_dHpg0EoGa5IfEX2@github.com/partner/simple_shell.git
10. Press enter
Instructions for copying files into your new simple_shell repository
1. Change your directory into the directory with the solutions 
2. cd soft_copy
3. Press enter
4. List the files in it to see the file names (you should have 25 files)
5. ls
6. Press enter
7. PLEASE CHANGE YOUR DIRECTORY OUT OF soft_copy
8. cd ..
9. Press enter
10. Type in the command bellow to copy 13 files from the repository with the solutions to the 
simple_shell repository you just created 
11. Please leave the rest 12 files for your partner to do.
12. cp –r soft_copy/AUTHORS soft_copy/README.md soft_copy/_atoi.c soft_copy/builtin.c 
soft_copy/builtin1.c soft_copy/environ.c soft_copy/errors.c soft_copy/errors1.c 
soft_copy/exists.c soft_copy/getLine.c soft-copy/getenv.c soft_copy/getinfo.c 
soft_copy/history.c simple_shell
13. Press enter
14. Change your directory into simple_shell
15. cd simple_shell
16. Press enter
17. List the files to see if you actually did the right thing
18. ls
19. IF you have followed these instructions correctly, you should have 13 files in your simple_shell
directory or else, please retrace your steps.
20. IF you can see 13 files, you are Awesome!!!
21. PLEASE EDIT the file called AUTHORS
22. vi AUTHORS
23. Press enter
24. Press i
25. EDIT lines 4 and 5 ONLY from what it is, to your own name and email. You can add your 
partner’s own name and email as well.
26. Press esc key
27. Save AND exit
28. :wq
29. Press enter
30. Now, you are ready to add and push your files
31. PLEASE DO NOT USE git add .
32. ADD THE FILES ONE AFTER THE OTHER so that you can have 13 commits in total
33. For example
git add AUTHORS 
git commit –m “put in your commit message here”
git push
git add _atoi.c
git commit –m “put in your commit message here”
git push
git add builtin.c
git commit –m “put in your commit message here”
git push
REPEAT THIS SYNTAX UNTIL YOU HAVE SUCCESSFULLY ADDED ALL THE 13 
FILES
CHECK YOUR GITHUB REPOSITORY TO COMFIRM IF THE 13 FILES ARE 
PRESENT 
YOU ARE AWESOME!!! 
PS: 
I have painstakingly written out these instructions to ensure you have a hitch free project. 
What will it cost you to follow me on Github? https://github.com/besthor
And just in case you run into errors while carrying out these instructions,
Please, Feel free to reach out to me.
It will be my pleasure to guide you.
Use this link https://github.com/besthor/besthor to get my contact information.
I am very much open for other collaborations. Million Thanks!
Happy Holidays!!! 
INSTRUCTIONS FOR PARTNER B. (collaborator to the GitHub repo) 
Carefully follow these instructions:
1. Use this link to a repo that contains solutions https://github.com/besthor/simple_shell
2. By the right hand side of your screen, click on a box icon called code
3. A drop-down menu will appear, click on https
4. Copy the https, open a sandbox or whatever terminal you often use for your ALX projects
5. Write git clone give a space and Paste the code on your terminal
6. Please DO NOT ADD YOUR TOKEN
7. Everything should look like this
8. root@c8d57ccd7f28:/# git clone https://github.com/besthor/simple_shell.git
9. Press enter
10. Rename the cloned repo to a new name called soft_copy, type in the command to rename 
11. Everything should look like this
12. root@c8d57ccd7f28:/# mv simple_shell soft_copy
13. Press enter
Instructions to bring your partner’s remote repository into your own local computer/system
1. PLEASE DO NOT CREATE ANOTHER repository 
2. Search for your PARTNER’S GitHub account
3. Click on your partner’s simple_shell repository 
4. By the right hand side of your screen
5. Click on code
6. Click on https
7. Copy the link
8. Go to your sandbox or whatever terminal you often use for your Alx projects
14. Write, git clone give a space and paste the https you copied
9. Please put in YOUR OWN TOKEN and put the @ symbol to avoid username and password 
prompts when trying to git push
10. Everything should look like this:
git clone https://ghp_dHpg0EoGa5IfEX2@github.com/partner/simple_shell.git
11. Press enter
Instructions for copying files into your parner’s simple_shell repository
1. Change your directory into the directory with the solutions 
2. cd soft_copy
3. Press enter
4. List the files in it to see the file names (you should have 25 files)
5. ls
6. Press enter
7. PLEASE CHANGE YOUR DIRECTORY OUT OF soft_copy
8. cd ..
9. Type in the command to copy the 12 files from the repository with the solutions to the 
simple_shell repository your partner created.
10. cp –r soft_copy/lists.c soft_copy/lists1.c soft_copy/main.c soft_copy/memory.c 
soft_copy/parser.c soft_copy/realloc.c soft_copy/shell.h soft_copy/sheel_loop.c 
soft_copy/string.c soft_copy/string1.c soft_copy/tokenizer.c soft_copy/var.c simple_shell
11. Press enter
12. Change your directory into simple_shell
13. cd simple_shell
14. Press enter
15. PLEASE DO A GIT PULL to bring your partner’s files into your system before you proceed
16. PLEASE DO A GIT PULL
17. git pull
18. Press enter
19. list the files to see if you actually did the right thing
20. ls
21. Press enter
22. IF you have followed these instructions correctly, you should see 25 files in your simple_shell
directory or else, please retrace your steps.
IF you can see 25 files, you are Awesome!!!
Now you are ready to add and push your files
23. PLEASE DO NOT USE git add .
24. ADD ONLY THE FILES YOU COPIED ONE AFTER THE OTHER so that you can have 12
commits in total because your partner already has 13 commits
25. BEGIN only WITH the ones YOU COPIED
26. For example
git add lists.c
git commit –m “put in your commit message here”
git push
git add lists1.c
git commit –m “put in your commit message here”
git push
git add main.c
git commit –m “put in your commit message here”
git push
REPEAT THIS SYNTAX UNTIL YOU HAVE SUCCESSFULLY ADDED ALL THE 12 FILES
CHECK YOUR PARTNER’S GITHUB REPOSITORY TO COMFIRM IF THE 12 FILES ARE 
PRESENT 
AND ENSURE YOU HAVE 25 FILES IN TOTAL
YOU ARE AWESOME!!! 
PS: 
I have painstakingly written out these instructions to ensure you have a hitch free project. 
What will it cost you to follow me on Github? https://github.com/besthor
Let’s be friends, shall we?
And just in case you run into errors while carrying out these instructions,
Feel free to reach out to me.
It will be my pleasure to guide you.
Use this link https://github.com/besthor/besthor to get my contact information.
I am very much open for other collaborations. Million Thanks!
Happy Holidays!!!
