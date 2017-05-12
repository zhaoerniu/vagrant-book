# 介绍

你是一名开发者（或将要成为一名开发者），平时工作用的电脑的操作系统是 Windows 或者 macOS。在做某些开发工作时，有些东西只能在 Linux 系统上运行，或者你开发的产品最终会运行在 Linux 类型的操作系统上，你想模拟一下开发的应用真正运行的环境。这时，你可以去创建一台 Linux 系统的虚拟机，然后在上面去运行你需要的东西，比如 Web 服务器，数据库等等。

Linux 是一种类型的操作系统，有很多不同的版本，比如 CentOS，Ubuntu 等等。服务器用的操作系统多数都属于 Linux 。作为一名开发者，了解一种 Linux 操作系统是非常必要的。这本书不要求你懂 Linux ，会出现一些简单的命令，我会解释是什么意思，你也很容易能明白。

在电脑上创建虚拟机需要安装一些虚拟机软件，比如 Virtualbox，VMware 等等。随便选择一款虚拟机软件，然后就可以去创建虚拟机，你可以为虚拟机指定并且安装不同类型的操作系统。创建的虚拟机会共享主机（你的电脑）的一些资源，CPU，内存，硬盘等等。也可以通过某种方式共享你的网络，也就是在你的虚拟机里面也是可以连接互联网的。

每次你去创建一台虚拟机，都要做一些重复的工作。比如你要为虚拟机安装操作系统，还要做很多配置。你需要一种更好的创建与管理虚拟机的方法，这就需要用到 Vagrant。它可以让你在一个文件里写好关于虚拟机的所有的配置，比如使用的操作系统，网络的类型，IP 地址，共享的目录等等。然后你用一条命令启动以后，你就拥有了一台可以使用的虚拟机了。使用这个配置文件稍做修改，你可以为自己的不同的项目分别去创建不同的虚拟机。不再需要的虚拟机，你也很容易把它们销毁掉。

这本书，我们会通过一系列的可操作的练习，让你明白 Vagrant 是什么，怎么使用它。书中会出现一些跟 Linux 系统相关的东西，都相当简单，这也是避免不了的。了解了使用 Vagrant 创建与管理虚拟机以后，你可以再专门找一种 Linux 系统，然后去学一下。![](/assets/vagrant-book.png)

![](/assets/vagrant-book.png)

![](/assets/vagrant-book.png)

![](/assets/vagrant-book.png)

![](/assets/vagrant-book.png)

![](/assets/vagrant-book.png)



