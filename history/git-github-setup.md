\# Git and GitHub Setup Journey



\## Goal



My objective was to create a GitHub repository that would serve as the foundation for documenting my cybersecurity degree progress, homelab projects, notes, scripts, and future security-related work.



\---



\## Initial Understanding



Before starting, I understood that Git and GitHub were related but did not fully understand the distinction between them.



I learned:



\* Git is local version control software.

\* GitHub is a cloud platform that stores Git repositories.

\* Git allows tracking changes over time.

\* GitHub allows projects to be backed up and shared.



\---



\## Repository Creation



Created:



CyberSecurityHomelab-Learning-Projects



Initial structure:



\* README.md

\* notes/

\* labs/

\* screenshots/

\* diagrams/

\* scripts/

\* history/



\---



\## Challenges Encountered



\### Challenge 1: Git Tracking the Wrong Files



While learning Git, I accidentally initialized a repository in my Windows user directory.



When running:



git status



Git attempted to track folders such as:



\* AppData

\* Downloads

\* OneDrive



and generated multiple permission errors.



\#### What I Learned



I learned that Git tracks everything beneath the folder where `git init` is executed.



I also learned the importance of understanding directory structure before initializing repositories.



\#### Resolution



I identified the correct project location and initialized Git within the project directory instead.



\---



\### Challenge 2: Directory Navigation



I received:



"No such file or directory"



errors when attempting to change directories.



\#### What I Learned



I learned the difference between:



\* Relative paths

\* Absolute paths



and how to use:



\* pwd

\* ls

\* cd



to navigate effectively.



\---



\### Challenge 3: Git Identity Configuration



When attempting my first commit, Git returned:



"Author identity unknown"



\#### What I Learned



Git requires a configured username and email before commits can be created.



\#### Resolution



Configured:



git config --global user.name

git config --global user.email



\---



\### Challenge 4: Push Errors



While pushing to GitHub, I encountered branch and synchronization errors.



\#### What I Learned



Local repositories and remote repositories maintain separate histories.



Git requires those histories to be synchronized before pushing changes.



\#### Resolution



Configured the main branch correctly and successfully pushed the repository.



\---



\## Skills Gained



\* Basic Git commands

\* Repository management

\* Branch management

\* GitHub integration

\* File system navigation

\* Troubleshooting Git errors

\* Repository organization



\---



\## Reflection



One of the biggest takeaways from this setup process was realizing how important documentation is.



Most of the time spent was not typing commands but understanding why errors occurred and how to resolve them.



Documenting mistakes provided a better understanding of Git than simply following a tutorial.



\---



\## Next Objective



Deploy an Ubuntu Server virtual machine and begin documenting Linux administration fundamentals.



