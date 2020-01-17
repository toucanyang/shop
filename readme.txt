…or create a new repository on the command line
echo "# shop" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/toucanyang/shop.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin https://github.com/toucanyang/shop.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
该文件是线上远程仓库的读我文件，
<<<<<<< HEAD
<<<<<<< HEAD
aaaaa
=======

这是在dev分支下操作的记录

我今天只写了一行代码

这是小A操作的文件
