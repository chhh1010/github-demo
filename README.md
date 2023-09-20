# github-demo
a github demo

# 说明文档
## 一.项目描述

上传分支
```
git push origin main
```

在本地创建一个main分支跟踪远程仓库的分支
```
git checkout  -b main --track origin/main
```

把master分支推送给main
```
git push origin master:main
git push origin head:main

```

把master分支推送给远程仓库的master分支
```
git push origin master
git push origin master:master
```

配置上游分支
```
git config push.default upstream
```
