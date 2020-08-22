# git-command

### 正常提交
- 克隆代码 git clone http://rep.git

- 增加文件到待提交队列 git add * 
    - git add -A 提交所有变化 包括新增.修改.删除
    - git add -U  提交修改的， 只包括修改和删除，没有新增
    - git add .  提交新增和修改，不包括删除
- 提交到本地仓库 git commit -m'提交描述'

- 提交到远程仓库 git push

可以把2-3步用 git commit -am'合并提交'

### 撤回提交

- git reset #version 保持本地代码不变，退回到本地仓库状态 --如果已经提交到远程，再退回某版本，就会导致版本差异，然后提交失败，需要合并修改，再提交

- git reset #version --hard 本地代码也会返回修改前状态，退回到本地仓库状态 --如果已经提交到远程，再退回某版本，就会导致版本差异，然后提交失败，需要合并修改，再提交