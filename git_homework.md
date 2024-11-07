1 (1)git reset HEAD <file>
  (2)git checkout -- <file>
  (3)git reset --hard
     git clean -df
2 (1)git reset-soft
 （2)git reset-hard
3(1)git checkout feature-branch
   git rebase main
 (2)git checkout feature-branch
   git pull origin main
