<p align="center">
  <img src="https://github.com/GabrielSoaresCeravolo/Git-and-Github/blob/main/Git-and-Github.png" alt="Capa do Repositório">
</p>

<h1 align="center"> Git and GitHub Essentials: Boosting Your Daily Workflow </h1>

![Badge - Status do projeto](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=yellow&style=for-the-badge)

Description about the repository: 

The purpose of this repository is to learn basic functionalities and tips to enhance my day-to-day experience with Git and GitHub. The repository is open for anyone interested in the same topic to access as well

<hr>

<h3> 🛠️ Global configuration commands for Git </h3>

```
git config --global user.name "Github Name"
git config --global user.email "Github Email"
```

The first command sets your global Git username to “GitHub Name”. When you commit changes to a Git repository, this username will be associated with your commits. The next command sets your global Git email address to "Github Email". Your email address is used for identification purposes in your Git commits

<hr>

<h3> commands to push the files to the GitHub repository </h3>

```
git clone (Repository Path)
```
The Git version control system will attempt to clone a Git repository located at the specified "Repository Path" to their local machine

```
git add (File.exe or .)
git commit -m "Your Commit"
git push
```
After you finish updating your codes, you can use the following commands to:

<br>

• Add new files with git add

• Create a description of what was changed in your code with git commit

• Commit to remote repository using git push

<hr>

<h3> Basic Commands Used </h3>

```
git log
  or
git log --oneline
```

These commands display a concise summary of all commits made to the repository

```
git pull (Repository Path)
```
The "git pull" command is used to update the local repository with the changes that were made in the remote repository


```
git status
```

The "git status" command is useful for checking the current state of your project

```
git push origin main
```

The "push origin main" command is used to push changes from the local branch called "main" to the remote repository called "origin"

<hr>

<h3> Mistakes that happened to me and how to fix them </h3>

Error: Repository Unsafe (To set git settings that the directory is safe)

```
git config --global --add safe.directory 'Directory Path'
```
