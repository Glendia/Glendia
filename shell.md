# git 提交命令
**新建初始化仓库**  
```shell
echo "# Docusaurus" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/lumivoider/Docusaurus.git
git push -u origin main
```
**已有仓库进行提交**  
```shell
git remote add origin https://github.com/lumivoider/Docusaurus.git
git branch -M main
git push -u origin main
```