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
git branch -b side o/main
git commit
git pull --rebase
git push
```

![image](https://github.com/user-attachments/assets/e3fc2d21-fba6-43c5-81af-2bd750625cc9)

***4: Git push arguments:***

*Steps:*
```
git push origin main
git push origin foo
```

![image](https://github.com/user-attachments/assets/1e3a3636-2c19-441f-b985-dd84a9b0c484)

***5: Git push arguments -- Expanded!:***

*Steps:*
```
git push origin foo:main
git push origin main^:foo
```

![image](https://github.com/user-attachments/assets/5ea3b428-324e-4a8e-8563-b7dc89e1e223)

***6: Fetch arguments:***

*Steps:*
```
git fetch origin C3:foo
git fetch origin c6:main
git checkout foo
git merge main
```

![image](https://github.com/user-attachments/assets/066eecba-bc2e-4005-98f1-2898ea002b81)


***7: Source of nothing:***

*Steps:*
```
git push origin :foo
git fetch origin :bar
```

![image](https://github.com/user-attachments/assets/974f9e4e-dc2e-47fd-b5a0-2ceae5292d5d)

***8: Pull arguments:***

*Steps:*
```
git pull origin c3:foo
git pull origin c2:side
```

![image](https://github.com/user-attachments/assets/0248ed7d-98b8-4fa7-9372-5cef08ac842b)

***10: Complition of To Origin And Beyond -- Advanced Git Remotes!:***

![image](https://github.com/user-attachments/assets/64c98391-b75c-4a7c-824b-82a7b6caa39c)

