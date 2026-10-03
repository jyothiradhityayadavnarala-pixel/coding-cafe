1. What did `pwd` print?
It printed the absolute path of my current working directory.This tells me where i am in the filesystem.
2. What did `ls -a` show that plain `ls` did not?
Is -a also showded hidden files and directories, whose names normally begin with a dot.plain is does not display those hidden entries
3. Pick one line from `ls -l`. What do you think the first column means?
The first column shows the file type and permissions.it indicates whether the entry is a file or directory and who can read ,wrrite,or execute it.
4. Why does that work from where you are standing? Which kind of path is `coding-cafe/week02`? Absolute or Relative?
it works because i am standing in the home folder,which is the parent of coding-cafe.coding-cafe/week02 is a relative path because it is interpreted starting from my current directory
5. mv did two different jobs above.what were they ?
mv was first used to move README-backup.md from coding-cafe into week01.it was then used to rename README-backup.md to old-readme.md inside week01
6. How many folders are on your `PATH`?
The exact number depends on the PATH printed by my terminal,because each system can have a different PATH.I count the folders seperated by colons
7. **Write down exactly where your `python3` lives.
The exact location is whatever is printed by which python3 on my machine.for example, on a typical WSL installation it may be .i should use my terminals actual output rather than assume a path
8. Compare your answer to 7 with the person next to you. Are they the same? If not, why might that be?
They may not be the same because differnt computers can have different python installations and path configurations.operating systems,installation methods ,and user settings can change where python3 is located 
9. What exactly did the shell say? Explain the error in your own words, using the word **PATH**.
The shell should reoport something like python3 .command not found .this means it could not find a program named python3 in any of the folders listed listed in path ,in this case the commands is also mispelled 
10. venv did not appear with plain is .why not?
the directory is named .venv, so it begins with a dot and is hidden .plain is does not show hidden entries is-a does 
11. What changed about your prompt?
The prompt changed to show (.venv) at the beginning .this indicates that the virtual environment is currently activated 
12. it should normally be different inside the virtual environment,which python3 points to the python exaculate in .venv .this shows that activate changed path so the virtual environments bin directory is searched before the system python location.
13. What is in the second list that was not in the first?
The second pip list contains requests, which was installed with pip install requests .its dependencies may also appear if they were installed as part of the installations 
14. Where does `python3` point now?
After deactive ,python3 points back to the normal python installations outside the virtual environment .the exact path is the output of which python3 after deactivation.
15. Find what `ls -h` does. Write it in your own words.
the -h option makes file sizes easier for humans to read when used with a long listing such as is -lh .it displays sizes using such as k ,m ,g instead of only raw byte counts.
16. What is the difference between what Ctrl + C and Ctrl + D did?
ctr+c interupts the currently runnly processing,which stops the running python session in this exercise .ctrl+D sends an end of input signal,at a terminal prompt it can signal that input is finished and can exit the shell or program when approriate