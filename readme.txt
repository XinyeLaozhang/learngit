Git is distributed version control system.
Git is free software distributed under the GPI.
Git is a multabe index called stage.
Git tracks changes.



改变工作去内容
add, 将工作区内容提交到暂存区
git add <files>...
checkout, 将暂存区内容覆盖工作去的内容
git checkout <files>...



改变暂存器内容
将已经提交到暂存区单还没有提交到版本库的内容撤销
git restore --staged <files>...
git reset HEAD <files>...
也可以将现在工作的内容重新提交到暂存区，覆盖原来的，也就是在commit 之前再add 一次
git add <files>...


版本回退
git reset --hard HEAD^   (或者 HEAD~n)
git reset --hard commitID


git status 内容解析
$ git status
On branch master
Changes to be committed:	////已经提交到暂存区了，但是还没有提交到版本库
  (use "git restore --staged <file>..." to unstage)
        modified:   readme.txt

Changes not staged for commit:	////工作区内容变化了，但是还没有提交到暂存区
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   readme.txt

