### 1.在命令行上创建一个新的存储库

~~~~bash
echo "# Learning" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/DongsGit/Learning.git
git push -u origin master
~~~~

### 2.从命令行推导出现有存储库

~~~
git remote add origin https://github.com/DongsGit/Learning.git
git push -u origin master
~~~

