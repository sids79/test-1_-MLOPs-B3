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

Kaushik Mukhopadhyay ↓ 2303951 12:17
Can you pl put the git clone command

Nikhil Kulkarni ↓ 2304085 12:17
