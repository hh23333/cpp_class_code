hello world!

## 设置用户名和邮箱
```
git config --global user.name "your name"
git config --global user.email "your email"
```

## 初始化项目
```
git init
```

## 新建文件
```
echo "Hello World!" > README.md
```
也可以手动创建文件

## 添加文件
```
git add .
```

## 提交文件
```
git commit -m "first commit"
```

## 查看状态
```
git status
```

## 查看提交历史
```
git log
```

## 查看提交历史（简洁版）
```
git log --pretty=oneline
```

## 创建分支 
```
git branch -M main
```

## 关联远程仓库
```
git remote add origin https://github.com/yourname/yourrepo.git
```

## 推送分支
```
git push -u origin main
```
