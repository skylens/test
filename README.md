# test
##学习如何使用github

(windows : GitHub + Atom 更方便 )

###1、如何创建github仓库

+ 选择 New repository 按钮
+ 添加 Repository name（及仓库名）
+ 添加 Description（及仓库介绍）
+ 选择 Public （pravite 是私有的，付费用户才可以用）
+ 选择 Initialize this repository with a READM （初始化仓库时自动创建一个READM文件）
+ 选择 Create repository 按钮 （完成仓库的创建）

###2、在主分支下创建一个子目录

+ 选择 create new file
+ 在主分支后输入子目录名，以 “/” 结尾
+ 这样就可以在主分支下创建一个子目录了
+ 以此类推，就可以在任何目录下创建子目录
+

## 在 linux 下使用 github

(Debian/ubuntu)

###1、安装 git

```
$ sudo apt-get install git
```

###2、配置 git

```
$ git config --global user.name "your_github_name"
$ git config --global user.email "your_github_email"
$ mkdir github/
$ cd github/
```

###3、为 github 账号添加 ssh keys

```
$ ssh-keygen -t rsa -C "your_github_email"
$ cd ~/.ssh/id_rsa/
$ cat id_rsa.pub
```

把 cat 的内容复制 ,粘贴到 github.com 的 SSH keys 中 ,并测试 ```ssh -T git@github.com```

###4、终端下 git 的一些操作

```
$ mkdir github/
$ git init
$ git clone http://github.com/your_github_name/your_github_repositorie_name.git
$
```

###5、linux 下的一次简单的提交

```
$ git clone https://github.com/tux116/linux.git
$ cd linux/
$ git pull //从github上拉取最新的版本
$ vim 日记
今天是x月x日
$ git status //查看git状态
$ git add 日记 //添加文件
$ git status //查看git状态
$ git commit //进行提交
$ git stauts //查看git状态
$ git push //把本地的版本推送到github上
```

###6、