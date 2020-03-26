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
# 新增文件 工作区 === 暂存区
git add 文件

# 新增文件 暂存区删除，工作区的保留
git rm --cached 文件

# 暂存区 → 版本库
git commit -m '信息'
```

- git rm VS rm

```bash
# 完成了
# 1 删除文件 工作区文件删除 === 暂存区
git rm 文件

# 若想恢复
# 1 删除文件 暂存区 → 工作区
git reset HEAD 文件
# 2 丢弃工作区的改动
git checkout -- 文件

# 完成了 删除文件
rm
# 
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

