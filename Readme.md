# Useful commands

## Intro
I often find my self searching for a specific command. There are so many and you cannot remember them all.
So I decided to start tracking them here. Each time that I use a command that I know I will use it another time again i will put it in the table below.

Feel free to contribute and add your most common commands as developer.

## Linux

| Command                                     | Descripton                                |
|---------------------------------------------|-------------------------------------------|
| `export NAME=VALUE`                         | Setting an Environment Variable           |
| `eval "$(ssh-agent -s)"`                    | Start the ssh-agent in the background     |
| `ssh-add  ~/.ssh/id_ed25519`                | Adding ssh key to ssh                     |
| `cat /etc/passwd`                           | List users in linux                       |
| `crontab -l`                                | Show crontabs                             |
| `crontab -e`                                | Edit crontabs                             |
| `chown -R USERNAME:GROUPNAME /PATH/TO/FILE` | Linux own a directory and subfolders      |
| `cat /etc/os-release`                       | Find linux distro                         |
| `ls -l`                                     | Find who owns a file or folder            |
| `cat /etc/group`                            | Show all linux groups                     |
| `sudo vim /etc/hosts`                       | Edit hosts file                           |
| `lsof -i tcp:80`                            | Find which process is running on port 80  |
| `kill -9 PID`                               | Kill process with PID                     |

# Git
| Command                           | Descripton          |
|-----------------------------------|---------------------|
| `git remote -v`                   | Show remote url     |
| `git remote add origin <url>`     | Add remote url      |
| `git remote set-url origin <url>` | Set remote url      |
