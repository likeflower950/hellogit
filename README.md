# hellogit
首次练习使用githut

你好，这是github的branch-bug分支，我在这里面做一些改动。

### window环境下检出Github项目到本地

进入github官网网站，找到想要检出的项目，点击clone or download，在弹出的选项卡里面选择open in desktop
这样的话，浏览器将会调用github的客户端程序，然后下载下来就OK了

### 初始化全局账号密码

Git安装好了之后，为避免每次下载工程都需要用户名和密码，需要给Git设置全局的账号和邮箱，打开Git Bash，输入如下命令：
```

git config --global user.name "likeflower950"
git config --global user.email "likeflower950@163.com"

```

> 注意git config命令的–-global参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，当然也可以对某个仓库指定不同的用户名和Email地址。