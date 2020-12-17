# shell-commands

**Top 10 git commands**
```shell
➜ history -n | grep git | cut -d' ' -f -3 | sort | uniq -c | sort -k1,1nr -k2 | head -n 10

 268 git commit -am
 141 git pull
 141 git push origin
  89 git pull origin
  59 git push
  31 git branch -D
  31 git stash
  28 git mergetool
  24 git grep -e
  23 git commit
```
