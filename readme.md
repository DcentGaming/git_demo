Git Demo


# Commands
## First time Setup Process
1. Create a new repository on GitHub.

    - ``` git init ```
2. Create and add an ignore file

    - ``` touch .gitignore ```
    - ``` git add .gitignore ```
3. Commit the changes

    - ``` git commit -m "initial commit" ```
4. Add the remote repository

    - ``` git remote add origin <url> ```
5. Push the changes to the remote repository

    - ``` git push origin <branch_name> ```
    - ``` git push --tags```

Common commands
```
git init
git add -A          # Add all files
git checkout <tag>
git tag -a <tag_name> -m "message"
git log
git reflog
git status
git add <file>
git commit -m "message"
git remote add origin <url>
git branch
git checkout -b <branch_name>
git checkout <branch_name>
git reset --hard <commit_id>
git merge <branch_name>
git push origin <branch_name>
git push origin <branch_name> --force
```

## Continuing git notes

- ```git add -A```
- ```git commit -m "message"```
- ```git tag -a <tag_name> -m "message"```
- ```git merge <branch_name>```
- ```git push origin <branch_name>```
