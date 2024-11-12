# SETUP GIT
1. Download git
2. check git version: `git --version`
3. git setup global with username: `git config --global user.name 'username(your github username)'`
4. git setup global with emailaddress: `git config --user.email 'example@gmail.com(your github email)'`
# Setup Complete!



> [!NOTE]
> SETUP AND LINK commands(file and github repo)
1. `git status` : is for check git status
2. `git add index.html` : add index.html file(with file name)
## or
3. `git add .` : we can add all file with that . sign
4. `git commit -m "your message"` : git commit is for commited your git action and -m is for message.
5. `git log` : is stand for check the history.


> [!IMPORTANT] 
> HOW TO REVERSE PREVIOUS TO PREVIOUS COMMIT OR STATE

:rocket:  `git log` : write this command on terminal
:rocket: for example : 
```markdown
`commit 125e5c30bbf6814b621d5ea4978c778835ea9459 (HEAD -> main)
Author: navincograph179 <navin_gurung@co-graph.com>
Date:   Tue Nov 12 10:01:24 2024 +0900

    third commit

commit 647ae60c511d42f16c64163d26e6c8bc1b9beb1a (origin/main)
Author: navincograph179 <navin_gurung@co-graph.com>
Date:   Tue Nov 12 09:20:43 2024 +0900

    second commit

commit 38de4cf77a250c4961918b63c2e8d10df7dd0ac0
Author: navincograph179 <navin_gurung@co-graph.com>
Date:   Tue Nov 12 09:10:21 2024 +0900

    first commit`
```
:rocket: copy hash, for example: `647ae60c511d42f16c64163d26e6c8bc1b9beb1a`     
:rocket: `git checkout 647ae60c511d42f16c64163d26e6c8bc1b9beb1a` : paste here after **git checkout**

> [!TIP]
> FOR UNDO or getback to present state(main)

:shipit:   `git checkout main` : (replace hash)


