# To Origin And Beyond -- Advanced Git Remotes!

***1: Push Main!:***

*Steps:*
```
git checkout main
git pull
git checkout side1
git rebase main
git checkout side2
git rebase side1
git checkout side3
git rebase side2
git checkout main
git rebase side3
git push
```

![image](https://github.com/user-attachments/assets/c55162f1-d6f8-4ff9-9744-1198d20a64b1)

***2: Merging with remotes:***

*Steps:*
```
git checkout main
git pull
git merge side1
git merge merge side2
git merge side2
git merge side3
git push
```

![image](https://github.com/user-attachments/assets/6585c500-ecb9-4d15-b4f4-81c5032b2133)


***3: Remote Tracking:***

*Steps:*
```

```
