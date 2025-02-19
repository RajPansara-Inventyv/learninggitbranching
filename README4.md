# A Mixed Bag:
  ***1: Grabbing Just 1 Commit:***

  *Steps:*
  ```
  git checkout main
  git cherry-pick C4
  ```
  ![l41](https://github.com/user-attachments/assets/13da2204-52f6-4944-847b-84403839593b)


 ***2: Juggling Commits:***

  *Steps:*
  ```
  git rebase -i HEAD~2
  git rebase -i HEAD~1
  git rebase -i HEAD~2
  git branch -f main C3''
  ```
  ![l42](https://github.com/user-attachments/assets/66b3eff3-4418-4ee7-abdc-216bbb265d60)

  ***3: Juggling Commits #2:***

  *Steps:*
  ```
  git checkout main
  git cherry-pick C2
  git rebase -i HEAD~1
  git cherry-pick C3
  ```
  ![l43](https://github.com/user-attachments/assets/b3e43ea8-4245-4885-8a7a-84091c39710f)

  ***4: Git Tags:***

  *Steps:*
  ```
  git tag v1 C2
  git tag v0 C1
  git checkout C2
  ```
  ![l44](https://github.com/user-attachments/assets/2a5c500e-d228-49cc-9a6a-5a83de59219b)

  ***5: Git Describe:***

  *Steps:*
  ```
  git commit
  ```
  ![l45](https://github.com/user-attachments/assets/2f50bfbe-5537-434d-9db3-020712116ecf)

  ***6: Compilition of A Mixed Bag:***
  ![l46](https://github.com/user-attachments/assets/f67fdb20-5311-4995-9b7c-db3900f02f07)

  




