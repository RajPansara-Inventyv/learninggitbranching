# Advanced Topics:
  ***1: Rebasing over 9000 times:***

  *Steps:*
  
  ```
  git rebase main
  git checkout side
  git rebase bugFix
  git checkout another
  git rebase side
  git branch -f main c7'
  ```
  ![l51](https://github.com/user-attachments/assets/defadb96-5427-4402-ab67-91afa0dd64e5)

  ***2: Multiple parents:***

  *Steps:*

  ```
  git branch -f bugWork HEAD~^2~
  ```
  ![l52](https://github.com/user-attachments/assets/998e3fbe-24fb-4767-9cb0-0f41a74c09e1)

  ***3: Branch Spaghetti:***

  *Steps:*

  ```
  git checkout one
  git cherry-pick C4 C3 C2
  git checkout two
  git cherry-pick C5 C4 C3 C2
  git branch -f three c2
  ```
  ![l53](https://github.com/user-attachments/assets/70214574-c2fe-48e8-b02b-0ad346222cca)

  ***4: Complition of Advance Topic:***

  ![l54](https://github.com/user-attachments/assets/9d899d12-d51e-4950-9495-cc0502f1bf36)

  
