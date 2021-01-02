Git 相关知识

```
ssh -T git@github.com
--首先配置config 
git config --global user.name "your name"
git config --global user.email "your_email@youremail.com"
```

```
-- 推文件
git init
git add . / 任意文件/文件夹（但必须非空）
git commit -m "    "
git remote add origin git@github.com:yourName/yourRepo.git
git push origin master 
```

```
-- 删文件
rm file --先将文件删除
git status --查看状态
git commit -m ""
git push origin master 
```

