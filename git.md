- centos 8

```bash
git --version

# 配置个人信息
git config --global user.name "用户名"
git config --global user.email "邮箱"
# 查看
git config --list
```

- 获得版本库

```bash
# 初始化
git init

# 克隆
git clone
```

- 版本管理

```bash
# 已修改的文件 → 暂存区
git add 文件

# 暂存区 → 已修改的文件
git rm --cached 文件

# 暂存区 → 版本库
git commit



```

- 查看信息

```bash
# 日志
git log

# 差别
git diff

# 当前状态
git status
```

- 远程协作

```bash
# 拉取
git pull

# 推送
git push
```

文件的三种状态

- modified
- staged
- committed

