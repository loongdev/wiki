# Git常用命令

## 重新签名最近一次提交

```
git commit --amend --reset-author -S
```

## 显示带有GPG签名信息的提交记录

```
git log --show-signature
```

## 设置提交用户信息（仅当前仓库生效）

```
git config user.name <name>
git config user.email <email>
git config user.signingkey <key>
```

例如：

```
git config user.name longdev
git config user.email loongdev@protonmail.com
git config user.signingkey E59122EFCED557ADA1E7A89A5C693A68CA5C1856
```
