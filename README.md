
echo“#git”>> README.md <br/>
git init //初始化<br/>
git add README.md //添加文件<br/>
git commit -m“first commit” //加入仓库<br/>
git remote add origin https://github.com/jiayousoftstudio/git.git //仓库地址<br/>
git push -u origin master  //提交到仓库<br/>
<br/>
从命令行推送现有存储库<br/>
git remote add origin https://github.com/jiayousoftstudio/git.git<br/>
git push -u origin master<br/>

最简配制<br/>
git config --global user.name 'huangguohua'<br/>
git config --global user.email 'hgh@huangguohua.cn'<br/>
--glbal   --local    --system<br/>
<br/>
常用命令<br/>
git status //查看状态<br/>
git reset --hard //消除暂存区<br/>
git mv 旧文件名 新文件名 //文件改名