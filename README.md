# 测试各种 `git` 提交命令

## 友好命令重写你的历史

```git
  git fetch
  git merge origin/main

  # if conflicts
  echo "resolve conflicts in your IDE"
  git commit -a -m "resolve conflicts"
  #end if

  git reset --soft origin/main
  git commit -a -m "my commit message"
  git push --force
```