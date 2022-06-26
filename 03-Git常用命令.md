[toc]

# Git命令

|                命令名                |       作用       |
| :----------------------------------: | :--------------: |
| git config --global user.name 用户名 |   设置用户签名   |
| git config --global user.email 邮箱  |   设置用户签名   |
|             **git init**             |   初始化本地库   |
|              git status              |  查看本地库状态  |
|            git add 文件名            | 添加文件到暂存区 |
|   git commit -m “日志信息” 文件名    |   提交到本地库   |
|              git reflog              |   查看历史纪录   |
|       git reset – hard 版本号        |     版本穿梭     |

## 设置用户签名

> ​	签名的作用是区分不同操作者身份。
>
> ​	用户的签名信息在每一个版本的提交信息中能够看到，以此确认本次提交是谁做的。
>
> ​	Git 首次安装必须设置一下用户签名，否则无法提交代码。
>
> ​	**※注意：**这里设置用户签名和将来登录 GitHub（或Gitee）的账号没有任何关系。

![git-demo1](D:\Tools\Typora\image\git-demo1.png)

## 初始化本地库

进入到项目的目录下，通过鼠标右键进入到 Git 中，使用命令。

<img src="D:\Tools\Typora\image\git-demo2.png" alt="git-demo2"  />

## 查看本地库状态

![git-demo3](D:\Tools\Typora\image\git-demo3.png)

​					 之后若在项目文件夹中添加了文件，则如下显示：

![git-demo4](D:\Tools\Typora\image\git-demo4.png)

​				 	之后添加至暂存区时：

![git-demo6](D:\Tools\Typora\image\git-demo6.png)

## 添加文件到暂存区

![git-demo5](D:\Tools\Typora\image\git-demo5.png)

## 提交到本地库

![git-demo7](D:\Tools\Typora\image\git-demo7.png)

![git-demo8](D:\Tools\Typora\image\git-demo8.png)

## 修改文件

![git-demo9](D:\Tools\Typora\image\git-demo9.png)

## 版本穿梭

![git-demo10](D:\Tools\Typora\image\git-demo10.png)