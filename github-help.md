#git
*参考《GitHub入门与实践》-大塚弘记著*
#####此处省略git的安装
  ```
    //如果第一次使用git，需要设置署名和邮箱
    $ git config --global user.name "username"
    $ git config --global user.email "your email"
    
    $ ssh-keygen -t rsa -C "youremail"                       //新建sshkey，省略ssh的使用

    $ git clone git@github.com:vagabondize/Hello-World.git    //克隆github上的仓库
    
    $ git pull                                                //获取远程仓库的更新
    $ git status                                              //查看仓库上的更新状况
    $ git add hello_world.php                                 //向暂存区中添加文件hello_world/php
    $ git add .                                               //添加本地所有改变的状态
    
    $ git rm -r --cached some-directory                       //删除github中的文件夹，本地保留
    
   //保存仓库的历史记录, 引号里是提交信息，是对这次提交的一个概述
    $ git commit -m "add hello-world by php"                  
    $ git push                                                //推送到远程仓库中
    
    //接下来的三行可以让你git push的时候无需输入github的用户名和密码
    $ git remote rm origin
    $ git remote add origin git@github.com:(your github name)/(your repository name)
    $ git push -u origin master

    $ git log                                                 //查看日志
    //git log 后面加上目录名，便会只显示该目录下日志,加上 -p 就会显示文件前后的差别
    $ git log -p README.md
    $ git diff                                                 //查看当前工作树与暂存区的区别

    //分区操作
    $ git branch feature-A         //创建分支feature-A
    $ git checkout feature-A       //把当前操作切换到分支feature-A下
    $ git branch                   //查看分支   
    //下面是合并分区，注意：要在分支feature-A中执行
    $ git merge --no--ff feature-A   

    $git log --graph                //以图表形式查看分支



    $ git remote add origin git@....                  //设置为本地仓库的远程仓库           

  ```

***
* * *
- - -
#github
*来源于google，baidu搜索*
####键盘快捷键       
**任何页面按(shift + /)都会出现快捷键列表**

  * watch----------当你选择Watching，表示你以后会关注这个项目的所有动态，以后只要这个项目发生变动,你都会在自己的个人通知中心，收到一条通知消息，如果你设置了个人邮箱，那么你的邮箱也可能收到相应的邮件
  * star-----------类似书签,方便你在star列表中找到,有'tag'可以分类
  * fork-----------相当于你自己有了一份别人原项目的拷贝，自己可以修改，可以pull request
  + *关于[watch star fork](http://www.jianshu.com/p/6c366b53ea41)更详细的连接地址*
  * Issues---------**事务卡片**，类似于TODO list，可以用来报bug，提新需求，据说还能写书，功能还有很多。
  [参考](http://book.haoduoshipin.com/gitbeijing/issues.html)
  * Wiki-----------**项目的知识库**， [在GitHub上搭建自己的Wiki介绍](http://www.360doc.com/content/14/0514/12/14416931_377498145.shtml)
  * Gist-----------可以用来记录代码片段
  * Pulse-----------显示该仓库的活跃信息
  * Graphs----------以图表形式显示改仓库的各项指标。用户可以轻松了解
  * Settings--------这里可以更改当前仓库的设置。（删除仓库就在这里边）
  * 

