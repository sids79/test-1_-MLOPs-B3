# test-1_-MLOPs-B3
This is the repository hosted on the Github servers for Academic purpose.

This is the first change I'm making using GITHUB.

For ssh based cloning in Github.
steps to create SSH key in Git bash to link your GitHub.
Open Git bash
1. ssh-keygen -t ed25519  ( it will generate 2 key public and private, ed is type of key use the same)
--> you have to apply a "Passphrase" and remember it.(very Important)

2. cd "/c/Users/Dell/.ssh/"
3. ls
4. cat id_ed25519.pub
5. copy the public key
6.you go to github and in your profile under setting "SSh and GPG Keys" and add ssh public key that you copied into github
7. go to your repository in git hub and copy the {ssh clone url} for clone.
8. go to git bash
9. go to the necessary path where you want to clone
10. git clone {ssh clone url}

Yograj ↓ TS 12:21
Correct.
We can also combine steps 2, 3, 4
>> ls /c/Users/Dell/.ssh/
>> cat /c/Users/Dell/.ssh/id_ed25519.pub

--------

#Git commands for public/private reposiroty
#Everytime you will create a new repository follow the below steps:
1. ssh-keygen -t ed25519 # this is command used to generate the ssh key
3. Enter passphrase
4. re-enter the passphrase
5. cd "<to the path where the 2 files have created>"
6. ls
7. cat id_ed25519.pub
   - copy the conent to GIT hub under the add SSH Key
8. cd back to the directory where you want to work
9. execute the git clone <use the ssh link copied from the git hub repository>
   - there might be prompt to enter the passphrase
10. git pull # To get the latest/updated code from the repository
11. make the required changed the files.
11. git add <>
12. git commit -d ""
13. git push # To push the data from local to the Github repository

#Git commands for local repository
1. get init <directory name>
   - eg: git init trial
2. git add <new file>
3. git commit -m "<add your comment>"

Arundhathi P V ↥ 2303616  to  Everyone 14:53
#Git commands for public/private reposiroty
#Everytime you will create a new repository follow the below steps:
1. ssh-keygen -t ed25519 # this is command used to generate the ssh key
3. Enter passphrase
4. re-enter the passphrase
5. cd "<to the path where the 2 files have created>"
6. ls
7. cat id_ed25519.pub
   - copy the conent to GIT hub under the add SSH Key
8. cd back to the directory where you want to work
9. execute the git clone <use the ssh link copied from the git hub repository>
   - there might be prompt to enter the passphrase
10. git pull # To get the latest/updated code from the repository
11. make the required changed the files.
11. git add <>
12. git commit -d ""
13. git push # To push the data from local to the Github repository

#Git commands for local repository
1. get init <directory name>
   - eg: git init trial
2. git add <new file>
3. git commit -m "<add your comment>"
