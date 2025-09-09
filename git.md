# Git

Git is a version control system that helps you track changes in your files and collaborate with others. It allows you to save different versions of your work, go back to previous versions if needed, and merge changes from multiple people. Git is commonly used for managing source code in software projects, but it can be used for any type of file.

Git provides thus a way to synchronize files between a server and local stored files. Other servers can host the webpage (the Jupyter Book) by requesting the files and utilizing a build script.

Both GitHub and GitLab provide an online integrated development environment: an online version of VSC. This approach is advised for those new to git, python, and programming.

## GitHub
GitHub is a web-based platform for hosting and collaborating on Git repositories. Owned by Microsoft, GitHub offers tools for code review, issue tracking, and project management, making it popular for open-source and private projects alike. One valuable feature is GitHub Pages, which allows you to publish static websites directly from a repository, making it easy to share documentation, portfolios, or project pages.

## Gitlab 
TU Delft hosts a local server with GitLab software, which is an implementation of git with a lot of useful extensions. Anyone with a TU Delft netid can get a GitLab account, simply by logging in on https://gitlab.tudelft.nl. You can then be added to projects or start your own project.[^TI]

[^TI]: Text from [](https://doi.org/10.59490/tb.73)

## Git desktop
GitHub Desktop is a graphical application that simplifies working with Git repositories, making it easier to synchronize your files with platforms like GitHub or GitLab. Instead of using command-line instructions, you can perform common tasks—such as committing changes, pushing to remote repositories, and resolving merge conflicts—through an intuitive interface. This is especially helpful for beginners or those who prefer a visual workflow.

Alternatively, Visual Studio Code (VSC) includes built-in Git functionality. With VSC, you can stage, commit, and push changes directly from the editor, view diffs, and manage branches without leaving your coding environment. This integration streamlines your workflow and reduces the need to switch between multiple tools.

## Comparing the two versions of git

GitHub and GitLab have both advantages and disadvantages. GitLab is advised by TUD unless many external users are involved. However, as GitLab disable pages a Jupyter Book should be build locally.

| | Positive | Negatives |
|---|---|---| 
|Github | GitHub pages enables to see content in website | Is property of MicroSoft
| | Allows users out side TUD to easily engage| No backup at TUD |
| | Github actions | Not standard reachable by TUD (i.c.o. conflicts, e.g. copyrights)|
| | Massive storage | |
| Gitlab | Is hosted by TUD | Is terminated when one leaves TUD |
| | Accessible by colleagues | Harder for outside collaborators |
| | CI/CD | Pages disabled |
| | Storage limited by TUD | TUD Backups |
| | | Is more often down compared to GitHub|