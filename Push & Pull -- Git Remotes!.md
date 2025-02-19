# Push & Pull -- Git Remotes!

***1: Clone Intro:***

*Steps:*
```
git clone
```

![image](https://github.com/user-attachments/assets/666c88bc-62e4-4940-9c55-c8226d5ed323)

***2: Remote Branches:***

*Steps:*
```
git commit
git checkout o/main
git commit
```

![image](https://github.com/user-attachments/assets/c54e00cd-776a-4892-82f6-68fed4b58ffe)

***3: Git Fetchin':***

*Steps:*
```
git fetch
```

![image](https://github.com/user-attachments/assets/0ccd0a75-5f94-44aa-bb58-b012f50a71eb)

***4: Git Pullin':***

*Steps:*
```
git pull
```

![image](https://github.com/user-attachments/assets/75b4080f-6323-4b57-8812-7e9b41c53150)

***5: Faking Teamwork:***

*Steps:*
```
git fakeTeamwork main 2
git commit
git pull
```

![image](https://github.com/user-attachments/assets/29e13429-2dee-4275-9fb4-95ff2ce46ee8)

***6: Git Pushin':***

*Steps:*
```
git commit
git commit
git push
```

![image](https://github.com/user-attachments/assets/2a39fc78-cc79-4599-a12e-abd13c95c021)

***7: Diverged History:***

*Steps:*
```
git fakeTeamwork 1
git commit
git pull --rebase
git push
```

![image](https://github.com/user-attachments/assets/3776ee2a-900c-430b-9b40-9ec68a267d36)

***8: Locked Main:***

*Steps:*
```
git branch -f main C1
git branch -f feature C2
git checkout feature
git push
```

![image](https://github.com/user-attachments/assets/8d5575e8-c2b2-45d1-99f6-7e433e9eb3e0)

***9:Complition of push pull and remote:***

![image](https://github.com/user-attachments/assets/f8d7d2aa-ccf2-4357-a787-bbdd1d4c2964)
