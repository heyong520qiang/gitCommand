# gitCommand
git常用命令

# master分支的代码领先自己的分支,git 如何把master分支代码合并到自己的分支

1.首先切换到主分支

git checkout master

2.使用git pull 把领先的主分支代码pull下来

git pull

3.切换到自己的分支

git checkout xxx(自己的分支)

4.把主分支的代码merge到自己的分支

git merge master

5.git push推上去ok完成,现在 你自己分支的代码就和主分支的代码一样了

git push
