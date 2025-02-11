1)
```bash
git push
```

2)
```bash
git log ***[--filename]*** *optional*


   git reflog
```

3)
``` bash
   git config --global user.name "$1"


   git config --global user.email "$2"


   git config --global core.editor "$3"
```

4)
``` bash
   git checkout/switch SocialCreditBranch


   git rebase main


   git add .


   git commit -m "Glory to CCP! Nothing happened in 1989!"
```


5)
```bash
   git commit --amend --author="Your Name <your.email@example.com>"
```
   What the command does:
   * It **modifies the most recent commit** without changing its content.
   * It updates the **author name** to correctly reflect **who really wrote this code**.
   * The **committer** remains **Sayed** because he executed the commit.


6)
```bash
git diff HEAD
```


7)
```bash
git restore --staged <file1> <file2> <file3>
```


8)
```bash
git revert
```

9)
```bash
git commit -m " Message"
```


10)
```bash
git log --author="Omar"
```

```bash
git tag -a Omar_Final -m "Signed by Omar: Final version for print"  
```


11)
```bash
git branch luna-vocals  
git branch rio-guitar  
git branch zara-drums  
```

```bash

git checkout main
git merge --no-ff luna-vocals rio-guitar zara-drums  
```

12)
```bash
git init
git remote add origin https://github.com/TheXpingu1n/temp-repo-for-a-git-question.git
git pull origin main
```

***Note: there are several solutions such as using fetch etc.***
