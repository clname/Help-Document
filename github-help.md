#git
*参考《GitHub入门与实践》-大塚弘记著*
#####此处省略git的安装
  ```
    $ ssh -keygen -t rsa -C "youremail"                       //新建sshkey，省略ssh的使用
    $ git clone git@github.com:vagabondize/Hello-World.git    //克隆github上的仓库
    
    $ git pull                                                //获取远程仓库的更新
    $ git status                                              //查看本地仓库上的更新状况
    $ git add hello_world.php                                 //本地新建了一个文件，然后添加到本地git中
    $ git commit -m "add hello-world by php"                  //提交到本地仓库，写上备注
    $ git push                                                //推送到远程仓库中
    
    $ git log                                                 //查看日志
  ```

***
* * *
- - -
#github
*来源于google，baidu搜索*
  * watch----------当你选择Watching，表示你以后会关注这个项目的所有动态，以后只要这个项目发生变动,你都会在自己的个人通知中心，收到一条通知消息，如果你设置了个人邮箱，那么你的邮箱也可能收到相应的邮件
  * star-----------普通关注，类似点赞,有'tag'可以分类
  * fork-----------相当于你自己有了一份别人原项目的拷贝，自己可以修改，可以pull request
  + *关于[watch star fork](http://www.jianshu.com/p/6c366b53ea41)更详细的连接地址*
  * Issues---------**事务卡片**，类似于TODO list，可以用来报bug，提新需求，据说还能写书，功能还有很多，嗯嗯。。。
  [参考](http://book.haoduoshipin.com/gitbeijing/issues.html)
  * Wiki-----------**项目的知识库**， [在GitHub上搭建自己的Wiki介绍](http://www.360doc.com/content/14/0514/12/14416931_377498145.shtml)
  * Gist-----------可以用来记录代码片段
