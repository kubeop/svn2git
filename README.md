# SVN迁移到GIT

感谢@gabrys，在大神的基础上修改而来。



## 依赖

* `python3.5 +`
* `svn`
* `git`
* `git svn` (usually packaged separately from git!)
* `tar`



## 用法

将svn仓库迁移到git

```
./svn2git.py import git@xxxx:groupname/projectname.git svn://xxxx/groupname/projectname
```

更新git仓库

```
./svn2git.py update git@xxxx:groupname/projectname.git
```

