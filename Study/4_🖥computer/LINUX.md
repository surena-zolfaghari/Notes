[[COMPUTER]]
[[LINUX]]

# Start up 
this section is related to how to configure ubuntu



## About python

1. sudo apt install python3-pip
2. sudo pip3 install virtualenv
3. source bin/activate
4. source /bin/activate

run the following command for using Jupiter: jupyter lab

#python 




## command
This section pays to introduction of some command line on 
https://www.youtube.com/watch?v=s3ii48qYBxA
1. pwd
shows directory we are in.
2. ls -a
shows hidden files
3. ls -l
4. touch file.txt
just created
5. nano file2.txt
create and open file
6. cat 
for check content of file
7. cd -
shows you were in before went to this directory
8.  mv file.txt test/

9. cp file.txt test/

10. rm file
but rm dose not work for directory

11. rmdir 
for directory(actually for empty directory) if directory was full use below  command

12. rm -rf test/
this flag means recursively and forcefully (delete directory and its contents)

13.  which firefox
this command shows the path of particular programs. I actually use where is because shows multi results about library and exe file , etc.

14. whereis firefox

15. check min 17 for locate and mlocate
Locate is a package that will be installed for searching files (e.g locate physics (find any files with name of physics))

16. sudo find / -iname linux 
I want to search in root directory
/ because root directory is / symbol
iname means i don't care about low letter and caps lock just mach linux for example.(insensitively name). for using locate you've gotta install mlocate.

17. echo "Hello world"

18. printf "1\n2\n3"
this command is new version of echo. if you write this script with echo, echo print exactly. but in printf \n means go to the next line.

19. >
printf "1\n2\n3" > file.txt
the output write in file

20. cat .bashrc
is very long better use

21. less .bashrc
show less and if you press enter show new line

22. grep 'alias' .bashrc
if you find specific word or line in file 

23. head .bashrc & tail .bashrc
head -n 25 .bashrc

- history 
shows recently commands for running command for example number of 34, it's enough to enter !34. Also !! (is called bang bang) it's practical. assume you run apt update and you forgot to write sudo before it. Now you can use bang bang ( sudo !!)

24. apt update

25. sudo apt install htop
show all processes 

26. wget
wget allows to you download something

27. sudo apt update && sudo apt upgrade

28. sometimes you change a code on .bashrc, and if you want to keep on, you should close terminal and then start. But if you can use `source ~/.bashrc` instead close file and start.
29. for example I don't like a command or any situation. But assume I don't like a command for example (sudo apt update && sudo apt upgrade) now you can change it. go to .bashrc and
> alias aptup='sudo apt update && sudo apt upgrade)'
> note there isn't space between equal and beyond and before. 

#command


## Some software
- flameshot for screenshot
- gpaste for clipboard

This site introduce good software
>https://www.fossmint.com/awesome-linux-software/

#software



