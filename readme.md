#测试代码

---

```
# 添加用户名
git --global user.name "username"

# 添加邮箱
git --global user.email "email"

# 绑定目录
git init mycode

# 添加文件
git add readme.md

# 提交到git仓库
git commit -m "提交说明：说明更改状态"

# 关联git远程仓库
git remote add origin https://github.com/用户名/仓库名.git

# 第一次推送到git远程仓库
git remote -u origin master
```