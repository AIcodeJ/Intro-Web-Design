# Git
_Git is open source software (free for anyone to use) written by Linus Torvalds who also wrote the Linux operating system. It is a program for keeping track of changes over time, known in programming as version control._

### Configure Git 📋
_We will need the following steps:_

```
1. git --version (for check version)
```
Now, we configure user for git and prepare connection to Github page
```
2. git config --global user.name "<Your Name>"
3. git config --global user.email "<youremail@example.com>"
```
Next, we continue for creating a repository, using for git bash (terminal of git)
```
1. mkdir "name your folder"
2. cd "folder created"
3. git init
```
## Getting Started 🚀
_Step Creae a New File:_
We create a file call 
```
README.MD
```
_Next we check status of repository it's correct:_
```
1. git status
2. git add README.md (your file)
3. git commit -m "your commit message"
```
## Github Account ✔
We use Github page for save on repository project. Previosuly we need to create a repository on Github

_Step: Add username to Git_
```
1. git config --global user.username <UserName for Github>
```
_Step: Connect your Local to your Remote_
Now you've got an empty repository started on GitHub.com. We copy address HTTP the repository and put in terminal in git
```
1. git remote add origin <URLFROMGITHUB>
```
And now we push all repo local for Github
```
1. git push origin master
```
Now go to GitHub and refresh the page of your repository. WOAH! Everything is the same locally and remotely. Congrats on your first public repository!
## Authors ✒️
* **Alexis Pérez** - *Project Creator* - [Alexis](https://github.com/AIcodeJ)
* **2942889** - *Software Development* - 8th Semester
* Collecting information by *Manuel Alejandro García Andrade*
## License 📄
This project is under the [Alexis](https://github.com/AIcodeJ) License