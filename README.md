This file is permitted to modify. You may add your first experience in creating your repo.

My First GitHub Repo!

This is what i have learned rather still learning (not that easy atleast for me).

Below lines helped me to build my first repo!

1.Generate a New SSH Key
  ssh-keygen -t ed25519 -C "your_email@example.com"
  (usually ~/.ssh/id_ed25519 or ~/.ssh/id_rsa)
  
2.Start the SSH Agent
  eval "$(ssh-agent -s)"
  
3.Add Your SSH Key to the SSH Agent
  ssh-add ~/.ssh/id_ed25519

4.Copy Your SSH Public Key
  cat ~/.ssh/id_ed25519.pub

5.Add Your SSH Key to Your GitHub Account.

6.Test Your SSH Connection
  ssh -T git@github.com

7.git init

8.git clone......

9.git checkout -b <brance name>

10.git add .

11.git commit -m "Initial commit: My first portfolio website"

12.git push -u origin main

<br>
<br>
### Git and GitHub make me go like :exploding_head: <br>
### However, I've learned so much! <br>
For example: <br>

- gh: short for GitHub
- git branch -d <branch name> : delete the named branch
- gh pr list : shows a list of the open pull requests
- gh pr diff : shown the differences between the files versions
- gh pr review --approve : approve a pull request (by the way, you cannot approve your own pull request)

<br>

## Good to know that if you need to undo a change you can use the following:
- git reset <file-name>
- git checkout -- <file-name>
- git reset --soft HEAD~1
- git reset --hard HEAD~1
