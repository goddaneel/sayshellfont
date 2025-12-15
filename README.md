# SayshellFont


## 浅克隆 submodule 特定版本
```shell
git clone --depth=1 --filter=blob:none <url>
```
或
```shell
git clone --depth=1 <url>
git fetch --unshallow --filter=blob:none <remote>
```

```shell
git pull --depth=1 "origin"
```

```shell
git branch <release/tag> <tag>
git checkout <release/tag>
```
