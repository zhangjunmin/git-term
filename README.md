# git-command

### 正常提交
<<<<<<< HEAD

=======
>>>>>>> 9045a114fc89caf67e29565b216e2ebd97cb1697
- 克隆代码 git clone http://rep.git

- 增加文件到待提交队列 git add * 
    - git add -A 提交所有变化 包括新增.修改.删除
    - git add -U  提交修改的， 只包括修改和删除，没有新增
    - git add .  提交新增和修改，不包括删除
- 提交到本地仓库 git commit -m'提交描述'

- 提交到远程仓库 git push

可以把2-3步用 git commit -am'合并提交'

### 撤回提交

- git reset #version 保持本地代码不变，退回到本地仓库状态
