## 利用Github Page建立自己的Website

本文不用下载Git命令也不用下载Github Destop等，直接网页操作即可完成对网站的部署。

### 准备材料

- Github账号
- 预先准备的域名(可以不准备)
  - 针对想把username.github.io重定向为你自己的域名才需要，比如搜索username.github.io可以跳转到网页中。如果想搜索xxx.com也可以跳转到网页中则需要准备一个域名，推荐各个云平台非常便宜。一般的域名也就几块钱一年。
- HTML文件(可以不准备)
  - 针对于想美化网页可以准备一个模板
  - 没有的可以网盘下载
    - 链接：https://pan.baidu.com/s/1pLOJXfwzNlUoDaqXFbworA  提取码：as0q 
    - 里面有两个资源文件，注意后面要用到。

### 正式开始

#### :pig: 建立网页

######  :pen: First Step 建仓库

进入账户创建仓库(repo)

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328175345.png)

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328181346.png)

（由于我已经创建了所以提示我已经存在）

创建完成之后，在浏览器中直接输入username.github.io即可跳转到你的初始readme.md文件【md文件会转成HTML文件】

---

###### :pen: Second Step 选择主题

进入刚刚建立的repo，选择Settings

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/Snipaste_2020-03-28_18-20-33.png)

鼠标往下滑动找到 **Github Pages** 核对下图红框部分是否正确，应该显示http://username.github.io [我这里显示Https://xuanskyone.xyz/]是因为我绑定了域名。 如果正确选择Change Theme选择一个好看的主题即可。

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328182425.png)

此时稍等几分钟，再次进入username.github.io显示的应为选择的主题的框架+Readme.md文件的内容。

---

###### :pen: Third Step 启用Https

https和http的区别在于，http的内容不经加密传输，而Https则是经过加密传输。

直接勾选上图中的Enforece HTTPS即可，

如果https运行成功这里则是一个小锁的状态，如下图，

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328184123.png)

如果https未运行成功，则显示不安全的状态。

---

**至此** ，搜索username.github.io应该可以搜索到你自己的网址，下面步骤进行网站优化

---

#### :pig: 绑定域名

###### :pen: First Step 在服务商方面设置

进入域名管理平台，直接添加记录 注意注意修改主机记录，记录类型，记录值，其余默认即可。

> 在记录类型中可以选择A类型，就是另外一种设置，即定向到Github的ip地址，这里只教CHAME类型

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328183502.png)

---

###### :pen: Second Step 在Github方面设置

同样在repo的Setting中找到Github Page，设置其中的Custom domain为你的域名即可，如下图所示。

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328183828.png)

---

**至此** 稍等几分钟等部署完毕之后，在搜索框中输入domain name即可进入到username.github.io地址。

---

#### :pig: 美化网页

###### :pen: First Step 下载资源文件

HTML资源文件在开始的准备材料中。

###### :pen: Second Step 上传至仓库

将下载到的资源文件1上传至username.github.io

> 上传是点击Upload files。对于文件夹 可以直接拖动文件夹传至Github
>
> 上传完成后理应如下图所示【最初的README.md文件可以删掉了】

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328192853.png)

---

**至此** 稍等一会，6min左右，搜索domain或者username.github.io均可应直接跳转到index.html文件

---

#### :cat: 托管多个网页

###### :pencil: 建立文件夹

 在username.github.io下直接创建文件，命名为Page[随意命名]

###### :pencil: 上传资源文件到文件夹中

同上，将资源文件2上传到Page[刚刚创建的]目录下，上传完成后如下图所示

![](https://cdn.jsdelivr.net/gh/s1119858711/picture-host//ndata/20200328193437.png)

###### :dog: 进入网站

在搜索框搜索username.github.io/Page即可进入到第二次托管的网页

---

**至此** 托管多个网页完成。







