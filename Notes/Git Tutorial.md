Git is used to connect with remote repositories like GitHub and GitLab

###### Basic Commands
git --version
![[Pasted image 20260329123527.png]]

###### Setting and confirming username
Set: git config --global user.name
Confirm: git config user.name
![[Pasted image 20260329125058.png|Pasted image 20260329125206.png]]

###### Creating and changing directory
mkdir cybersec (make directory)
cd cybersec (change directory)

###### Initialize git
git init
command creates .git folder to track project changes

###### List Files
ls
![[Pasted image 20260329130023.png]]

###### Staging Environment
Setting files ready for next commit
git add readme.md (staging single file)
git add --all (staging multiple file)
git restore --staged readme.md (unstage a file)

###### Commit
git commit -m "Week 0 cybersec"

###### View Commit History
git log
