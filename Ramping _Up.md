***Ramping Up:***
  1. ***Detach yo' HEAD:***

     *Steps:*
     ```
     git checkout C4
     ```
      ![l21](https://github.com/user-attachments/assets/c2e94893-51a9-4267-80f8-5d87916f1367)
  2. ***Relative Refs (^):***

     *Steps:*
     ```
     git checkout bugFix^
     ```
     ![l22](https://github.com/user-attachments/assets/6097c710-6a80-4509-afc7-6236597948c8)
  3. ***Relative Refs #2 (~):***

     *Steps:*
     ```
     git branch -f main C6
     git checkout HEAD~1
     git branch -f bugFix HEAD~1  
     ```
     ![l23](https://github.com/user-attachments/assets/d9264d4b-49c9-484e-afad-9fd8ad906195)
  4. ***Reversing Changes in Git:***

      *Steps:*
     ```
     git reset HEAD~1
     git checkout pushed
     git revert pushed 
     ```
     ![l24](https://github.com/user-attachments/assets/ab485f26-ea59-49db-ba35-625fc22d4c9f)
  5. ***Complition of Ramping Up:***
       ![l25](https://github.com/user-attachments/assets/7de387a8-964f-4ceb-98ff-ac0eb02fc0dc)
