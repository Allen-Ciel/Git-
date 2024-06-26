# Git-

## 设置git

```powershell
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```

## 第一次上传
…or create a new repository on the command line

echo "# Git-" >> README.md

```powershell
# 在本地的项目文件下
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Allen-Ciel/Git-.git
git push -u origin main
```
如果报错 ```错误：远程 origin 已经存在```

首先删除现有的origin远程仓库别名:
```powershell
git remote remove origin
```
然后添加新的远程仓库地址:
```powershell
git remote add origin https://github.com/Allen-Ciel/Allen-Ciel.github.io.git
```
…or push an existing repository from the command line

```powershell
git remote add origin https://github.com/Allen-Ciel/Git-.git
git branch -M main
git push -u origin main
```

## 后续更新方法

```powershell
cd path/to/your/repository           # 切换到你的本地仓库目录
git add .                            # 添加所有更改过的文件到暂存区
git status                           # 查看git状态
git commit -m "Your commit message"  # 提交更改，并附上提交信息
git push origin main                 # 推送本地的更改到远程的main分支
```


