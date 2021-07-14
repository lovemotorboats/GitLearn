Git命令大全：

1、git config user.email “liyang96615@163.com”, git config user.name “liyang96615”

2、git init(初始化版本库;

3、git status(查看状态)

4、git add “file.txt”(加入到暂存区)

5、git commit -m “commit info”(将暂存区中的所有内容提交到当前分支)

6、git log(历史记录)

7、git reset —hard HEAD^(回退到上一版本)

8、git reflog(记录提交的版本)

9、git diff HEAD — readme.txt(比较工作区和分支上最新版本的不同)

10、git checkout — readme.txt(将工作区的文件回到最近一次执行add或commit时的状态)

11、git restore --stage readme.txt(将暂存区的修改回退到工作区)

12、删除文件后，也要用git rm test.txt, git commit来提交删除操作

13、git remote add origin ***.git(关联远程仓库)

14、git push -u origin master(首次提交，加上-u参数)

15、git checkout -b dev(创建并切换分支git switch -c dev)

16、git branch(查看当前分支)

17、git merge dev(合并指定分支到当前分支)

18、git branch -d dev(删除dev分支)

19、git merge —no-ff -m “merge with no-ff” dev(使用no-ff方式合并分支)

20、git stash(暂存工作现场)

21、git stash list(查看工作现场)

22、git stash pop(恢复工作现场并删除保存的现场)

23、git cherry-pick commitId(复制特定的提交到当前分支)

24、git remote -v(查看远程关联的仓库)

25、git remote rm origin(解绑与远程仓库的关联)

26、git tag v1.0(打标签)

27、git show v1.0(查看标签信息)

28、git tag -a v1.0 -m “version 1.0 released”(指定说明文字)

29、git tag -d v1.0(删除标签)

30、git push origin v1.0(推送标签)

31、git push origin —tags(推送全部尚未推送的标签)

32、git push origin :refs/tags/v1.0(删除远程的标签)

33、git remote rename origin github(重命名关联的远程仓库)

34、（测试公钥）