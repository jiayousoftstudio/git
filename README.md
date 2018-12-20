在命令行上创建一个新的存储库<br/>
echo“#git”>> README.md 
git init 
git add README.md 
git commit -m“first commit” 
git remote add origin https://github.com/jiayousoftstudio/git.git
 git push -u origin master

从命令行推送现有存储库
git remote add origin https://github.com/jiayousoftstudio/git.git
 git push -u origin master
