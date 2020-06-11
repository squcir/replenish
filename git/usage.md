[TOC]

### 回滚

#### reset

```shell
git reset --hard commitId #回滚到某个提交
git push -f
```

#### revert

```shell
git revert commitId
git revert commitIdA..commitIdB #抵消commitIdA到commitIdB之间的提交
-n --no-commit 默认不提交
-m 合并提交revert时需要指定(一般为: -m 1)
```

