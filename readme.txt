��or create a new repository on the command line

echo "# blog" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/mhkz/blog.git
git push -u origin master
��or push an existing repository from the command line

git remote add origin https://github.com/mhkz/blog.git
git push -u origin master
��or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

Import code


启动方式
node app.js
后台：admin
管理员账户设置：打开mongodb 更改字段isAdmin 为true