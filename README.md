# ISM3232 - Module 2: zsh Navigation and File Operations

## Commands Practiced 

| Command            | What it does                                      |
|--------------------|---------------------------------------------------|
| pwd                | Prints the current working directory              |
| ls                 | Lists visible files and folders                   |
| ls -la             | Lists all files including hidden ones             |
| cd                 | Changes the current directory                     |
| touch              | Creates a new empty file                          |
| echo 'text' > file | Writes text into a file, overwriting its contents |
| cat                | Prints a file's full contents to the terminal     |
| head -1            | Prints just the first line of a file              |
| cp                 | copies a file                                     |
| mv                 | Moves or renames a file                           |
| rm                 | Deletes a file permanently                        |
| code               | Opens a file or folder in VS Code                 |
| python3            | Runs a Python script                              |

## AI Use Statement 
I did not use AI for this lab. 

## Week 3: Virtual Environments and .zshrc
| Command                    |        what it does                                         |
|----------------------------|---------------------------------------------|
| python3 -m venv .venv            | creates a virtual environments in .venv/              |
| source .venv/bin/activate        | activates the venv                                    |
| deactivate                       | exists the venv. returns to python system             |
| which python3                    | shows which python interpreter is active              |
| pip list                         | lists installed packages                              |
| pip install <package>            | installs a package into the active venv               |
| pip freeze > requirenments.txt   | saves installed packages/versions to a file           |
| pip install -r requirenments.txt | reinstalls packages from a requirenments file         |
| git status                       | shows tracked/untracked/staged changes                |
| ll (ls -la)                      |  lists all files in current directory                 |
| c (clear)                        |clears the terminal screen                             |
| gs (git status)                  | shows current states of the git working directory     |
| ga  (git add)                    | stages a file or files for commit                     |
| gcmsg (git commit -m)            | commits staged chnages with a message                 |
| gp  (git push)                   | pushes committed changes to the remote repository    |
| gl (git log --online)            | shows commit histroy in a condensed, one-line-per commit format                                                                             |
| tree2 (tree -L 2)                | displays the directory structure, limited to 2 levels deep                                                                                      |
| mkcd ()                          | creates a dirctory and cds into it in one step       |
| cat <file>                       | prints file contents                                 |
 