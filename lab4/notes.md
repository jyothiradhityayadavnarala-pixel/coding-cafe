1.--global: It applies your name and email to every Git project on your laptop, rather than just the current folder.
2.ls -a vs ls: The hidden .git folder appeared. This is where Git secretly stores all the version history and settings for the project.
3.Untracked files: Git offered to track two items (README.md and week02). Since you didn't have a .venv folder, everything there was your own work.
4.The .gitignore effect: Nothing disappeared from your clean folder, but the .gitignore file itself showed up in the untracked list.
5.Committing .gitignore: You should definitely commit it. That way, if other TAs or students clone your repository, their Git will ignore the exact same junk files as yours.
6.The README movement: It moved from "Untracked files" to "Changes to be committed." In Git terms, it moved from the working directory into the staging area.
7.The commit output: Git outputted the commit message and confirmed that 3 files were changed.
8.The 7 characters: It's called a commit hash (or commit ID). It acts as a unique fingerprint so Git can track and find that exact version of your project later.
