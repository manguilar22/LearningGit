# Learning Git <img src="https://github.com/manguilar22/icons/blob/master/Octocat.png" width="100" height="100"/>

* Git Basics
* Tags, Branching, Merging and Reverting
* Logging and Auditing 
* Pull Request 
* GitLab - Installation, Confirguration, and Use
<a href="http://git-school.github.io/visualizing-git/#free"> Visualize Git</a> 
<a href="https://git-scm.com/book/en/v2">Free Git Book</a> :closed_book: 
<a href="https://www.webpagefx.com/tools/emoji-cheat-sheet/">emoji-cheat-sheet</a> :octocat:

#### Starting Projects with Git 
```bash
git init project_name 
git init --bare project_name
```

#### Using Git Config
```bash 
git config --global user.name "Kenny...x"
git config --global user.email "kenny1@email.com"
git config --list
```

#### Using Git Status
```bash
git status 
git status -s
git status -v 
```

#### Adding Files to a Project 
```bash 
git add . 
```

#### Commit changes to Project 
```bash 
git commit 
git commit -m "Commit changes with a comment" 
```

#### Creating a *development* branch
```bash
git checkout -b development 
```
