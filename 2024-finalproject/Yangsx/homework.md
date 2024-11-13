#Git 应用

##第一题
1. 方法1：先使用git reset 将提交的文件退回，然后使用git restore 将文件恢复到最后一次修改提交的状态。
2. 方法2：先使用git log 查看提交历史，再使用git checkout <commit> --<filename>恢复到最后一次修改提交的状态。


##第二题

###不修改历史
1. 方法1：使用git reset --soft <commit>退回至上一个版本
2. 方法2：使用git checkout <commit> --<filename>恢复到指定某一次提交时候的版本
![图片](./home./ysx./图片./git1.png)

###修改历史
1. 
2. 

##第三题
1. 方法1：使用git cherry-pick 命令将指定的提交合并到当前分支。方法2：使用git rebase 命令将当前分支的改动放在指定分支的最新提交之后。
2. 
