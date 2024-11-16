#Git 应用

##第一题
1. 方法1：先使用git reset 将提交的文件退回，然后使用git restore 将文件恢复到最后一次修改提交的状态。
2. 方法2：先使用git log 查看提交历史，再使用git checkout <commit> --<filename>恢复到最后一次修改提交的状态。
![图片](./2024-finalproject./git1.png)


##第二题

###不修改历史
1. 方法1：使用git reset --soft <commit>退回至上一个版本
![图片](./2024-finalproject./git2-1.png)
2. 方法2：使用git checkout <commit> --<filename>恢复到指定某一次提交时候的版本
![图片](./2024-finalproject./git2-2.png)


##第三题
1. 方法1：使用git cherry-pick 命令将指定的提交合并到当前分支。方法2：使用git rebase 命令将当前分支的改动放在指定分支的最新提交之后。
2. 方法2：使用git rebase <分支名>命令将其他分支的提交应用到当前分支上
![图片](./2024-finalproject./git3.png)
![图片](./2024-finalproject./git3-2.png)
