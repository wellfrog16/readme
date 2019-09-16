## git 命令

```bash

# 简约查看日志
git log --pretty=oneline

# 查看修改内容
git status

# 放弃修改
git checkout filepath

# 跳转到指定提交，回复上一次的commit（不保留最后一次的代码）
git reset --hard id

# 撤销上一次commit，保留修改
git reset --soft HEAD^

# 回滚到指定提交
git revert id

# 比较当前分支和指定分支(dev)的不同
git diff dev

# 子仓库
git subtree push --prefix=dist origin gh-pages

# 清理不存在的远程目录
git remote prune origin

git rm -rf .

```