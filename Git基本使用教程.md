##### Git基本使用教程

---

+ Git上传文件基本流程

  本地新建一个文件夹，右键点击文件夹选择 ```Git Bash Here```

  若是新手上传初次使用，输入以下代码

  ```
  git config --global user.name "自己注册时候的用户名"
  git config --global user.email 自己注册时候的邮箱
  ```

 然后输入以下命令行：

```c
git init   #初始化仓库
git add .  #将本目录下的文件模拟添加到缓冲栈中
git commit -m "" #""中是对于自己上传文件的描述
git remote add origin url  #url指的是自己GitHub仓库的SSH
git push --set-upstream origin master  #输入 git push会提示
```



+ Git下载文件基本流程

  先搜索自己想要下载的开源代码，点击进入，然后点击```clone or download```,复制URL。

本地新建一个文件夹，右键点击文件夹选择 ```Git Bash Here```

然后输入以下命令行

```c
git init  #初始化仓库
git clone URL #就是上述复制的URL
```

