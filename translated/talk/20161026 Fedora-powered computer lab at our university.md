我们大学的机房使用 Fedora 系统
==========

![Fedora-powered computer lab at our university](https://cdn.fedoramagazine.org/wp-content/uploads/2016/10/fedora-powered-computer-lab-945x400.png)

在[塞尔维亚共和国诺维萨德大学的自然科学系和数学与信息学系][5]，我们教学生很多东西。从编程语言的入门到机器学习，所有开设的课程最终目的是让我们的学生能够像专业的开发者和软件工程师一样思考。课程时间紧凑而且学生众多，所以我们必须对现有可利用的资源进行合理调整以满足正常的教学。最终我们决定将机房电脑系统换为 Fedora。

### 以前的设置

我们过去的解决方案是在 Ubuntu 系统上面安装 Windows [虚拟机][4]并在虚拟机下安装好教学所需的开发软件。这在当时看起来是一个很不错的主意。然而，这种方法有很多弊端。首先，因为运行虚拟机导致了严重的计算机性能的浪费。因为运行虚拟机导致计算机性能利用率不高和操作系统的运行速度降低。此外，虚拟机有时候会在另一个用户会话里面同时运行。这会导致计算机工作效率的严重降低。我们有限的宝贵时间不应该花费在启动电脑和启动虚拟机上。最后，我们意识到我们的大部分教学所需软件都有对应的 Linux 版本。虚拟机不是必需的。我们不得不寻找一个更好的解决办法。

### 进入 Fedora!

![Computer lab in Serbia powered by Fedora](https://cdn.fedoramagazine.org/wp-content/uploads/2016/10/jxXtuFO-1024x576.jpg)

默认运行 Fedora 工作站版本的一个机房的照片

我们思考过暂时替代以前的安装 Windows 虚拟机方案。我们最终决定使用 Fedora 有很多原因。

#### 发展的前沿

在我们所教授的课程中，我们会用到很多各种各样的开发工具。因此，我们能及时获取到最新的、最好用的开发工具很重要。在 Fedora 下，我们发现我们用到的开发工具有 95% 都能够在官方的软件仓库中找到。只有少量的一些工具，我们不得不手动安装。这在 Fedora 下很简单，因为你能获取到几乎所有的能开箱即用的开发工具。

我们意识到在这个过程中我们使用了大量自由、开源的软件和工具。这些软件总是能够及时更新并且可以用来做大量的工作而不仅仅局限于 Fedora 平台。

#### 硬件兼容性

我们选择 Fedora 用作机房的第二个原因是硬件兼容性。机房现在的电脑还是比较崭新的。过去比较低的内核版本总有些问题。在 Fedora 下，我们发现我们总能获得最新的内核版本。正如我们预期的那样，一切运行完美，没有任何差错。

我们决定我们最终会使用带有 [GNOME 桌面环境][2]的 Fedora [工作站版本][3]。学生群体通过使用这个版本的 Fedora 会发现很容易、直观、快速的上手。学生有一个简单舒适的环境对我们很重要，这样他们会更多的关注自己的任务和课程本身而不是一个复杂的或者运行缓慢的用户界面。

#### 自主的技术支持

最近，我们院系给予自由、开放源代码的软件很高的评价。通过使用这些软件，学生们即便在毕业后和工作的时候，仍然能够继续自由地使用它们。在这个过程中，他们通常也对 Fedora 和自由、开源的软件有一定了解。

### 转换机房

我们将机房的一台电脑完全手动安装。包括准备所有必要的脚本和软件，设置远程控制权限和一些其他的重要组成部分。我们也为每一门课程单独设置一个用户以方便学生存储他们的文件。

一台电脑安装配置好后，我们使用一个强大的、免费的、开源的叫做 [CloneZilla][1] 的工具。 CloneZilla 能够让我们为硬盘镜像做备份。镜像大小约为 11 G。我们用一些带有高速 USB 3.0 接口的闪存来还原磁盘镜像到剩余的电脑。我们仅仅利用若干个闪存设备花费了 75 分钟设置好剩余的 24 台电脑。

### 将来的工作

我们机房现在所有的电脑都完全使用 Fedora （没有虚拟机）。剩下的工作是设置一些管理脚本方便远程安装软件，电脑的开关等等。

我们由衷地感谢所有 Fedora 的维护人员，包制作人员和其他贡献者。我们希望我们的工作能够鼓励其他的学校和大学像我们一样将机房电脑的操作系统转向 Fedora。我们很高兴地确认了 Fedora 完全适合我们同时我们也担保 Fedora 同样适合你。

--------------------------------------------------------------------------------

via: https://fedoramagazine.org/fedora-computer-lab-university/

作者：[Nemanja Milošević][a]

译者：[WangYueScream](https://github.com/WangYueScream)[LemonDemo](https://github.com/LemonDemo)

校对：[校对者ID](https://github.com/校对者ID)

本文由 [LCTT](https://github.com/LCTT/TranslateProject) 原创编译，[Linux中国](https://linux.cn/) 荣誉推出

[a]: https://fedoramagazine.org/author/nmilosev/
[1]:http://clonezilla.org/
[2]:https://www.gnome.org/
[3]:https://getfedora.org/workstation/
[4]:https://en.wikipedia.org/wiki/Virtual_machine
[5]:http://www.dmi.rs/



















