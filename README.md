# wired-brain-recipes



https://github.com/charles-robert-amita/wired-brain-recipes.git



echo "# wired-brain-recipes" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/charles-robert-amita/wired-brain-recipes.git

git push -u origin main



git remote add origin https://github.com/charles-robert-amita/wired-brain-recipes.git

git branch -M main

git push -u origin main



Git Bash / Terminal Commands

| Command               | What it does                      | Easy mental shortcut   |

| --------------------- | --------------------------------- | ---------------------- |

| `pwd`                 | Shows your current directory      | \*\*Where am I?\*\*        |

| `ls`                  | Lists files/folders               | \*\*What's here?\*\*       |

| `cd folder`           | Enters a folder                   | \*\*Go into this\*\*       |

| `cd ..`               | Goes up one directory             | \*\*Go back/up\*\*         |

| `cd \~`                | Goes to your home directory       | \*\*Go home\*\*            |

| `mkdir folder`        | Creates a directory               | \*\*Make folder\*\*        |

| `touch file.txt`      | Creates an empty file             | \*\*Make file\*\*          |

| `rm file.txt`         | Deletes a file                    | \*\*Remove file\*\*        |

| `rm -r folder`        | Deletes a folder and its contents | \*\*Remove folder\*\*      |

| `echo "text"`         | Prints text                       | \*\*Say this\*\*           |

| `echo "text" > file`  | Writes/replaces file contents     | \*\*Write this to file\*\* |

| `echo "text" >> file` | Appends text to a file            | \*\*Add this to file\*\*   |

| `clear`               | Clears the terminal screen        | \*\*Clean screen\*\*       |

| `cat file.txt`        | Displays file contents            | \*\*Show me this file\*\*  |



Git Commands — THE IMPORTANT ONES

| Command                   | What it does                                         | Easy mental shortcut            |

| ------------------------- | ---------------------------------------------------- | ------------------------------- |

| `git --version`           | Shows installed Git version                          | \*\*Is Git installed?\*\*           |

| `git help`                | Shows commonly used Git commands                     | \*\*Git cheat sheet\*\*             |

| `git help <command>`      | Opens detailed documentation                         | \*\*Explain this command\*\*        |

| `git init`                | Creates a Git repository in the current directory    | \*\*Start tracking this project\*\* |

| `git status`              | Shows current Git state                              | \*\*What's going on?\*\*            |

| `git add file`            | Stages a specific file                               | \*\*Prepare this file\*\*           |

| `git add .`               | Stages changes in the current directory              | \*\*Prepare everything\*\*          |

| `git commit -m "message"` | Creates a commit from staged changes                 | \*\*Save this snapshot\*\*          |

| `git log`                 | Shows commit history                                 | \*\*Show history\*\*                |

| `git log --oneline`       | Shows compact commit history                         | \*\*Show history, briefly\*\*       |

| `git diff`                | Shows unstaged changes                               | \*\*What did I change?\*\*          |

| `git restore file`        | Restores a file's working-tree changes               | \*\*Undo this file's changes\*\*    |

| `git rm --cached file`    | Removes a file from staging while keeping it on disk | \*\*Unstage this\*\*                |



Git + GitHub Commands

| Command                       | What it does                                        | Easy mental shortcut         |

| ----------------------------- | --------------------------------------------------- | ---------------------------- |

| `git remote -v`               | Shows connected remote repositories                 | \*\*Where is my GitHub repo?\*\* |

| `git remote add origin <URL>` | Connects local repo to a remote repo                | \*\*Connect local → GitHub\*\*   |

| `git push`                    | Sends local commits to remote                       | \*\*Upload my commits\*\*        |

| `git push -u origin main`     | Pushes to `main` and remembers the upstream         | \*\*First push\*\*               |

| `git pull`                    | Downloads remote changes and integrates them        | \*\*Get latest changes\*\*       |

| `git fetch`                   | Downloads remote information without integrating it | \*\*Check what's remote\*\*      |

| `git clone <URL>`             | Downloads an existing remote repository             | \*\*Copy GitHub repo locally\*\* |



Branch Commands

| Command              | What it does                                | Mental shortcut               |

| -------------------- | ------------------------------------------- | ----------------------------- |

| `git branch`         | Lists branches                              | \*\*What branches exist?\*\*      |

| `git branch name`    | Creates a branch                            | \*\*Make branch\*\*               |

| `git switch name`    | Switches to a branch                        | \*\*Move to branch\*\*            |

| `git switch -c name` | Creates + switches to a branch              | \*\*Make and enter branch\*\*     |

| `git merge name`     | Combines another branch into current branch | \*\*Bring branch changes here\*\* |



⚠️ Commands I'd be careful with



Command			Why

\--------------------------------------------------------------------

rm -r folder		Deletes folders/files

git reset		Can change staging/history depending on options

git restore		Can discard changes

git clean		Can delete untracked files

git push --force	Can overwrite remote history



MOST IMPORTANT WORKFLOW

\-------------------------------

1\. Make/change files

2\. git status

3\. git add .

4\. git status

5\. git commit -m "message"

6\. git log --oneline



LOCAL → GITHUB

\-------------------------------

git remote add origin <URL>

git push





