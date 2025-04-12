# DevOps Daily Command Reference

This file contains essential Git and Linux commands frequently used by DevOps engineers.

---

## 🔧 Git Commands

### git clone <repo_url>
Clone a remote Git repository to your local machine.

### git status
Show the working tree status.

### git add <file> / git add .
Add file(s) to the staging area.

### git commit -m "message"
Commit staged changes with a message.

### git push origin <branch>
Push changes to a remote repository.

### git pull origin <branch>
Fetch and merge changes from the remote branch.

### git branch
List all local branches.

### git checkout <branch>
Switch to the specified branch.

### git checkout -b <new_branch>
Create and switch to a new branch.

### git merge <branch>
Merge a branch into the current branch.

### git log
Display the commit history.

### git stash / git stash pop
Temporarily save and restore changes.

### git rebase <branch>
Reapply commits on top of another branch.

### git reset --hard <commit>
Reset the current HEAD to a specific commit.

---

## 🐧 Linux Commands

### ls -la
List files and directories with detailed information.

### pwd
Print the current working directory.

### cd <directory>
Change the current directory.

### mkdir <name>
Create a new directory.

### touch <filename>
Create a new file.

### rm <file> / rm -rf <dir>
Remove a file or directory forcefully.

### cp <source> <destination>
Copy files or directories.

### mv <source> <destination>
Move or rename files/directories.

### cat <file>
Display the content of a file.

### tail -f <file>
View real-time updates of a file (commonly used with logs).

### grep "pattern" <file>
Search for a string in a file.

### find . -name "<pattern>"
Find files in the current directory hierarchy.

### df -h
Display disk space usage in human-readable format.

### du -sh <dir>
Show the size of a directory.

### top / htop
Display Linux processes in real time.

### ps aux | grep <process>
Display information about running processes.

### chmod 755 <file>
Change file permissions.

### chown user:group <file>
Change file ownership.

### systemctl status <service>
Check the status of a service.

### journalctl -xe
View logs from the system journal.

### curl <url>
Make HTTP requests from the command line.

### scp user@host:/path /local/path
Securely copy files between hosts.
