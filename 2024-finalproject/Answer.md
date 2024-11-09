1. (1)`git reset` `git checkout --`

   (2)`git restore --stage <file>` `git restore <file>`

2. `git revert` `git reset --soft` `git reset --hard`

3. 先`git checkout`，后`git rebase`，出现冲突时解决后再`git rebase`；或者，先`git log` ，然后  `git checkout` ，最后`git cherry-pick`

