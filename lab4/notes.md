1.--global: It applies your name and email to every Git project on your laptop, rather than just the current folder.
2.ls -a vs ls: The hidden .git folder appeared. This is where Git secretly stores all the version history and settings for the project.
3.Untracked files: Git offered to track two items (README.md and week02). Since you didn't have a .venv folder, everything there was your own work.
4.The .gitignore effect: Nothing disappeared from your clean folder, but the .gitignore file itself showed up in the untracked list.
5.Committing .gitignore: You should definitely commit it. That way, if other TAs or students clone your repository, their Git will ignore the exact same junk files as yours.
6.The README movement: It moved from "Untracked files" to "Changes to be committed." In Git terms, it moved from the working directory into the staging area.
7.The commit output: Git outputted the commit message and confirmed that 3 files were changed.
8.The 7 characters: It's called a commit hash (or commit ID). It acts as a unique fingerprint so Git can track and find that exact version of your project later.
Here are the 2-3 sentence answers for Questions 9 through 14 that you can copy right into your lab4/notes.md file:

9.The four steps of the Git loop are modifying a file, checking the status with git status, staging the file with git add, and saving the snapshot to history with git commit.

10.README.md gets a special name and placement because it acts as the "shop window" of your project. When people visit your repository on GitHub, this file is automatically displayed so they can quickly understand what the project is about.

11.The gh auth login command securely linked your terminal to your GitHub account using an authentication token. This allows Git to verify your identity automatically behind the scenes so you never have to type your password to push code.

12.The README.md file is showing on the front page of the repository. GitHub is programmed to automatically find and render this specific file to introduce visitors to the project.

13.No, pushing did not change the local history at all. Pushing simply copied the exact local commit history up to the GitHub cloud repository.

14.A private repository exists securely on GitHub's servers, providing a cloud backup and the ability to selectively invite collaborators like the TAs. If it didn't exist on GitHub at all, it would only live on your local laptop, with no backup and no way for others to grade it.
