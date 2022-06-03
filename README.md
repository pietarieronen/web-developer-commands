# **WEB DEVELOPER SHORCUTS**

Useful shortcuts for useful web developer tools.

# **A**

## **APACHE JMETER**

- Java required

| Command      | Description                                                 |
| ------------ | ----------------------------------------------------------- |
| sh jmeter.sh | open jmeter by running the command inside the bin directory |

# **B**

## **BROWSER**

| Command            | Description             |
| ------------------ | ----------------------- |
| CMD + T            | open new tab            |
| CMD + N            | open new window         |
| CMD + W            | close current tab       |
| CMD + SHIFT + T    | reopen closed tab       |
| CMD + L            | jump to search bar      |
| CTRL + TAB         | navigate tabs forward   |
| CTRL + SHIFT + TAB | navigate tabs backwords |

# **C**

# **D**

## **DISCORD**

| Command | Description |
| ------- | ----------- |
| cmd + K | search      |

## **DOCKER**

| Command                                                                                            | Description             |
| -------------------------------------------------------------------------------------------------- | ----------------------- |
| run --name <container-name> -dit -p 27017:27017 --rm mongo:4.4.1                                   | init mongo container    |
| ps                                                                                                 | see running containers  |
| exec -it <container-name> mongo                                                                    | execute container       |
| use <db-name>                                                                                      | create and name new db  |
| run --name postgress-demo -e POSTGRES_PASSWORD=mysecretpassword -p 5432:5432 -d --rm postgres:13.0 | init postgres container |
| exec -it -u postgres postgress-demo psql                                                           | execute container       |

# **E**

# **F**

## **FIGMA**

| Command         | Description           |
| --------------- | --------------------- |
| CMD + scroll    | zoom in and out       |
| SPACEBAR + move | navigate view         |
| CMD + click     | select inner element  |
| CMD + .         | hide tools            |
| SHIFT + 2       | zoom to selection     |
| CMD + +/-       | zoom in and out       |
| V               | default               |
| F               | frame                 |
| R               | rectangle             |
| I               | line                  |
| O               | ellipse               |
| C               | comment               |
| ALT + move      | duplicate             |
| CMD + D         | duplicate             |
| CMD + ALT + G   | frame selection       |
| SHIFT + A       | auto layout selection |
| CMD + ALT + K   | create component      |

# **G**

## **GIT**

| Command                                       | Description                                        |
| --------------------------------------------- | -------------------------------------------------- |
| config --list --show-origin                   | show global config                                 |
| init                                          | initialize git repo                                |
| checkout                                      | switch branch                                      |
| checkout -b `<new_branch>`                    | create and switch to new branch                    |
| fetch                                         | fetch remote branches                              |
| branch -m `<name>`                            | rename branch                                      |
| add .                                         | stage                                              |
| commit -m "commit"                            | commit                                             |
| push -u origin `<branch>`                     | push and set upstream                              |
| ssh -T git@github.com                         | test ssh pipeline                                  |
| push origin --delete `<branch>`               | delete remote branch                               |
| branch -D `<branch>`                          | force delete local branch                          |
| pull --rebase origin `<branch>`               | rebase                                             |
| git merge --strategy-option=theirs `<branch>` | merge and accept all changes                       |
| :wq                                           | write quit                                         |
| reset --soft HEAD~5                           | delete last 5 commits                              |
| config --global alias.aliasname "git command" | set an alias for a command                         |
| commit --amend -m "new commit text"           | edit last commit                                   |
| add . + commit --amend --no-edit              | stage and add to previous commit with no edits     |
| fetch origin + reset --hard origin/main       | hard reset local branch to the remote branch stage |
| log --all --graph --oneline --decorate        | git graph                                          |

# **H**

# **I**

## **INSPECTOR**

| Command         | Description          |
| --------------- | -------------------- |
| CMD + ALT + I   | open developer tools |
| CMD + SHIFT + C | inspect element      |

# **J**

# **K**

# **L**

# **M**

## **MySQL**

| Command                             | Description              |
| ----------------------------------- | ------------------------ |
| create procedure <procedure-name()> | create stored procedure  |
| call <procedure-name()>             | execute stored procedure |

# **N**

## **NODE**

| Command                                                               | Description             |
| --------------------------------------------------------------------- | ----------------------- |
| require("crypto").createHash("sha256").update("string").digest("hex") | create Hash with Crypto |
|                                                                       |                         |

# **O**

# **P**

# **Q**

# **R**

# **S**

# **T**

## **TEAMS**

| Command         | Description   |
| --------------- | ------------- |
| CMD + SHIFT + M | mute / unmute |

## **TERMINAL**

| Command                    | Description              |
| -------------------------- | ------------------------ |
| up / down arrows           | scroll commands history  |
| cd                         | go to home               |
| cd ..                      | one level up             |
| cd ../..                   | two levels up            |
| mkdir `<name>`             | create new directory     |
| rm `<name>`                | remove file              |
| mv `<old_name> <new_name>` | move or rename           |
| rm -rf                     | remove directory         |
| touch                      | create file              |
| nano                       | text editor              |
| pwd                        | print work directory     |
| ls                         | list                     |
| ls -a                      | list all                 |
| man + command              | show command manual      |
| ssh -T git@github.com      | test github SSH pipeline |
| code .                     | open folder in VS Code   |
| sudo nano /etc/paths       | edit configuration PATH  |
| echo $PATH                 | see paths                |

# **U**

# **V**

## **VS CODE**

| Command                         | Description                           |
| ------------------------------- | ------------------------------------- |
| CMD + P                         | open command line                     |
| CMD + SHIFT + P                 | open command line trigger             |
| CMD + ,                         | open settings                         |
| CMD + J                         | taggle terminal                       |
| CMD + I                         | trigger suggestions                   |
| CMD + B                         | taggle explorer                       |
| CMD + K + W                     | close all open tabs/files             |
| CMD + D                         | select same words                     |
| CMD + click                     | go to original element                |
| CMD + SHIFT + F                 | search all                            |
| CMD + SHIFT + E                 | open explorer                         |
| CMD + SHIFT + P > Shell Command | shell command: "code ."               |
| ALT + SHIFT + down              | copy line                             |
| ALT + SHIFT + left/right        | select word                           |
| CMD + SHIFT + /                 | comment line                          |
| `/** */`                        | JS Doc, adding comments to a function |
| ALT + click                     | Multiple cursors                      |
| CMD + SHIFT + K                 | Delete line                           |
| CMD + ENTER                     | Insert line above                     |
| CMD + SHIFT + ENTER             | Insert line below                     |
| ALT + Z                         | Wrap or unwrap text                   |

# **W**

# **X**

# **Y**

# **Z**
