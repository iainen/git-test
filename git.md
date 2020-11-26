## git常用命令

#### 将文件取消暂存
git restore --staged

#### 讲文件返回到某一个快照的版本
git restore -s HEAD~ <file>
git restore -s <91410eb9>  <file>  // 改命令指定明确的 commit id ，回退到指定的快照中

#### 讲仓库版本回到某个commit
$ git reset --soft HEAD^  // 该命令表示撤销 commit 至上一次 commit 的版本



git fetch

git rebase

git pull --rebase

git check-pick

git checkout -b

git merge

git reflog

git commit --amend



