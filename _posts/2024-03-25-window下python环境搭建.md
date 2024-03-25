---
layout: post
title:  window下python环境搭建
description: "window下python环境搭建"
tag: Python
---

### **介绍**

先来介绍下两位主角：

 **Pycharm** ：目前一款主流的 Python 集成开发环境，它带有一整套帮助我们在Python开发时提高效率的工具，比如调试、语法高亮、Project管理、代码跳转、智能提示、自动完成、单元测试、版本控制。

总的来说，Pycharm 会极大地提高我们 Python 开发的效率和体验，用过都说好。

 **Anaconda** ：主要针对 Python 的数据科学整合包，包括有 Numpy，Pandas，Sklearn等。重要的是，自带管理软件 conda，它拥有安装，更新，删除，解决包依赖关系的包管理功能。同时，conda拥有环境管理功能，能创建独立运行环境， 使各项目间包环境和版本互不冲突和影响。另外，Conda 还可以管理包括 Bowtie2，FastQC 等软件环境，甚至 R 包环境。

总之，Anaconda 就是我们在编程时的管家，一切麻烦事扔给他，我们只要关注项目本身就行。

### **安装 Pycharm**

1.网址：[https://www.**jetbrains.com/pycharm/d**ownload/#section=windows](https://link.zhihu.com/?target=https%3A//www.jetbrains.com/pycharm/download/%23section%3Dwindows)

* Professional：收费，专业版会提供扩展，比如远程调试，插件支持，版本控制等
* Community：免费，会包含常用的基础功能

这里选择专业版为例，可以先试用30天。有的学校会购买，可以咨询下学校图书馆或计算机学院。也可以去官网购买，当然网上有许多方法可以获得，自行搜索。

![](https://pic3.zhimg.com/80/v2-d5aec1fd8ac301771ed08b3ebbe28d4e_720w.webp)

2.开始安装

![](https://pic1.zhimg.com/80/v2-9403f549295b2cb76891a953092a6068_720w.webp)

3.选择安装位置，Next

> 如果有固态硬盘，可以把 Pycharm 放进去，这样会极大的减少项目构建索引，载入导入时间。

![](https://pic2.zhimg.com/80/v2-4028c4cd93fdad831bb5f6d2b465a52d_720w.webp)

4.可以根据需要来选择配置，建议全选

![](https://pic4.zhimg.com/80/v2-30b448a91c455ab98ba330de94aeb4ab_720w.webp)

5.安装

![](https://pic4.zhimg.com/80/v2-33c40989dbea1027ee7db6783988c88f_720w.webp)

6.安装完成后，点击刚刚在桌面上的快捷方式

![](https://pic4.zhimg.com/80/v2-88cd53b20115a13f9048c4d9921581b7_720w.webp)

7.同意协议

![](https://pic3.zhimg.com/80/v2-5b5b2af327b93efc6fbd09dfc62bb586_720w.webp)

8.数据是否分享，根据情况来看

![](https://pic1.zhimg.com/80/v2-67ba6875fd5e796bcddd19f71764f5a0_720w.webp)

9.选择主题，我这里选择浅色

![](https://pic2.zhimg.com/80/v2-1c8d949395778444749c5154b0bdfde9_720w.webp)

10.安装各种插件

点击Plugins，可以加入部分插件，这里安装了一个汉语插件。

![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/06ad0f57d9344719a642f7fba00e652f.png)

插件安装完成后，重启软件。
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/168bd025307c48a7b5a83abb0cdbdf8e.png)
![在这里插入图片描述](https://img-blog.csdnimg.cn/direct/68b67fb3d7b94cc48917cce721c59e63.png)
重启后，界面已变成中文界面。

### **安装 Anaconda**

1.根据系统选择合适的安装包

[https://www.**anaconda.com/products/i**ndividual#Downloads](https://link.zhihu.com/?target=https%3A//www.anaconda.com/products/individual%23Downloads)

![](https://pic1.zhimg.com/80/v2-12b325ba81a2125ddfeae52f8a7b8750_720w.webp)

2.安装

![](https://pic1.zhimg.com/80/v2-e58d7611c0104686684d5ae9c75e3a54_720w.webp)

2.同意协议

![](https://pic4.zhimg.com/80/v2-4f9ec32606ae2da4332790b4398cfd57_720w.webp)

3.Next

![](https://pic2.zhimg.com/80/v2-5f4a89f9224301b7a3e30af3493cdce1_720w.webp)

4.选择安装路径

这里路径最后放在非系统盘，后续anaconda的操作会占用硬盘空间

我平时会为每种语言建立独立的安装目录，工作目录。这样的好处是在版本更新，和项目依赖关系清晰，后续更新也方便。

![](https://pic3.zhimg.com/80/v2-71b099fc8d7cb9545f58c0e71b500e0e_720w.webp)

4.开始安装

![](https://pic2.zhimg.com/80/v2-17408e742f9a324a65327b4971f49259_720w.webp)

5.Next

![](https://pic2.zhimg.com/80/v2-d6cb6f4d0dcff3867e12cb74f81cccf1_720w.webp)

6.Next

![](https://pic2.zhimg.com/80/v2-a2faf513d7b5866d917d5133f98650c1_720w.webp)

7.安装完成

![](https://pic4.zhimg.com/80/v2-adbe898dde54e2ed223f46c5f3792a6b_720w.webp)

### **新建包含 Anaconda 的项目**

1.第一次进入Pycharm，先新建项目，进入配置界面

![](https://pic1.zhimg.com/80/v2-346943a50fc1d99ec5c3afd9a3ec5848_720w.webp)

2.配置 Python 解释器

![](https://pic1.zhimg.com/80/v2-2da1c51cdb6f7259a060bb9f7add3920_720w.webp)

为了方便管理，这里 `Location` 配置项目存放目录，该目录与 Anaconda 在同一目录下。当然，不按照这样的目录结构也可以。

![](https://pic2.zhimg.com/80/v2-c90b8792838c92ed7e84daf4f8d66b9d_720w.webp)

3.切换到 `Conda Environment` ，找到我们刚刚安装 Anaconda 的目录并设置，同时勾选为所有项目应用该配置

![](https://pic3.zhimg.com/80/v2-bb9630dc1cc1f655561dd7bd48823e36_720w.webp)

4.配置完成后，解释器被 Pycharm 识别，点击创建

![](https://pic1.zhimg.com/80/v2-3e580df69d46afadaaa5d200934d54e8_720w.webp)

5.第一次创建项目，Pycharm 有初始化工作要做，耐心等待即可

![](https://pic4.zhimg.com/80/v2-fc4760aff590db7dee73adf88d774aa3_720w.webp)

### **Anaconda 环境的使用示例**

0.工作区介绍

![](https://pic2.zhimg.com/80/v2-4061abac9fe75d9dc6974a8e9f695a91_720w.webp)

1.右键项目名，新建 Python 脚本

![](https://pic4.zhimg.com/80/v2-bebf49d7dc31982dc5582d9509ca08f3_720w.webp)

2.输入名字，注意这里不需要添加 `.py`后缀，回车后创建

![](https://pic4.zhimg.com/80/v2-e75fddb0d85a9880a05ddc894811ed0f_720w.webp)

3.编写脚本

```python
import pandas as pd
import numpy as np

dates = pd.date_range('20200501', periods=6)
df = pd.DataFrame(np.random.randn(6,4), index=dates, columns=list('ABCD'))
```

4.右键脚本名，运行，测试配置是否成功

![](https://pic2.zhimg.com/80/v2-4d6d84ab0ce3b055b7ded6699a0b67b9_720w.webp)

5.运行这个脚本，会自动激活 `Scientific Mode`，界面就像这样：

在左下输入 `df.head()`，可以直接在控制台查看数据框内容，也可以在右边点击查看。

![](https://pic3.zhimg.com/80/v2-a3f9ad0092141feb2225f983c6ec389a_720w.webp)

### **Conda 环境的使用示例**

有了 Anaconda 的支持，为什么还要 Conda 环境？

前面新建的 Anaconda 环境包含各种数据分析，机器学习等包，可以直接拿来用，并不需要再安装一遍，方便实用。

![](https://pic1.zhimg.com/80/v2-360439ae9967ed2656fded7909f94f28_720w.webp)

但是，有时候，我们并不需要这么多的包，而是需要特定版本的 Python 或者 Python 包，或是依赖冲突等问题，这就要求有一个独立运行的环境。而 Conda 建立的环境正好满足了这个需求。

1.新建包含有 Conda 环境的项目

![](https://pic3.zhimg.com/80/v2-7219d7edb1931112aeadc852e2421a86_720w.webp)

2.查看启用的环境

点击 Pycharm 下面的 `Termianl` 可以直接控制 Windows 的 CMD 命令行（这里不得不吐槽微软的 CMD 和 PowerShell 界面丑还超难用）。如果你的 Pycharm 运行在 Linux 下，这个工具会接管 Shell。

可以看到在最前面多了一个 `(example)` ，这个代表激活的 conda 环境

![](https://pic3.zhimg.com/80/v2-2e5547479b4c39b38e7087c5ccf45f3a_720w.webp)

3.查看 conda 环境里有哪些包

输入命令 `conda list`，可以查看我们建立的环境里包含哪些包。

> 学习更多 conda 的包管理，环境管理和渠道管理等技巧可以参考：[https://**blog.csdn.net/u01126225**3/article/details/88828229](https://link.zhihu.com/?target=https%3A//blog.csdn.net/u011262253/article/details/88828229)

可以看到，相对 Anaconda 整合了数以百记的包不同，这里只有几个最基础的 Python 包，之后按需添加即可。

![](https://pic2.zhimg.com/80/v2-d0afab40015560ed4025ff6d4e8eff15_720w.webp)

4.切换环境

点击右下角的 conda 环境名，可以切换环境。

这里切换后，代表我们项目目录中所有的脚本都要依赖于这个环境。

![](https://pic2.zhimg.com/80/v2-2f499eaf3330b2221ca4bbad87b3e4a5_720w.webp)

但是，需要注意，一些老鸟已经会熟练操作 Conda 了，比如像下面这样来切换环境：

![](https://pic3.zhimg.com/80/v2-2f036a945c40e38661c8ee7ef62965ee_720w.webp)

不幸的是，虽然命令行 `conda activate base` 可以将当前环境 `example` 切换为 `base`，但是这里只是将命令行的环境切换了，我们 Pycharm 项目的 conda 环境纹丝不动。

所以想切换当前项目的环境，最好点击右下角图标

5.使用 Conda 环境

这里以绘制一张热图为例来简单使用下配置好的环境

安装 `matplotlib`包

![](https://pic4.zhimg.com/80/v2-3e60d00d97705dcd50221b427071096b_720w.webp)

写代码

```python
import random
from matplotlib import pyplot as plt

# 准备数据
# 定义横纵坐标
xLabel = ['geneA', 'geneB', 'geneC', 'geneD', 'geneE']
yLabel = ['sample1', 'sample2', 'sample3', 'sample4', 'sample5']
# 定义填充数据
data = []
for i in range(5):
    temp = []
    for j in range(5):
        k = random.randint(0, 100)
        temp.append(k)
    data.append(temp)

# 开始作图
fig = plt.figure()
# 画布
ax = fig.add_subplot(111)
# 坐标刻度
ax.set_yticks(range(len(yLabel)))
ax.set_xticks(range(len(xLabel)))
ax.set_xticklabels(xLabel)
ax.set_yticklabels(yLabel)
# 作图
im = ax.imshow(data)
# 图例
plt.colorbar(im)
plt.show()
```

出图

![](https://pic3.zhimg.com/80/v2-f3d883cc0ee8256cb436f89fd2975fae_720w.webp)

这里同样也可以激活 `Scientific Mode`，可以这么来设置

![](https://pic2.zhimg.com/80/v2-ac407117340d7dc00a0e147db68d034d_720w.webp)

效果是这样的：

![](https://pic3.zhimg.com/80/v2-c69ff4fb36c85a537c4c37eebb1bcbfa_720w.webp)

如果想在 Pycharm 中使用 R 语言，可以参考这篇：

在Pycharm 中使用 R 时，效果是这样的：

![](https://pic3.zhimg.com/80/v2-f72900916cd071b56c837cba780c967a_720w.webp)

接下来，享受搭建好的环境吧！

### python项目包管理

在Python编程中，软件包（或称为库、模块、包）是提供特定功能或服务的代码集合。这些软件包可能由不同的开发者创建和维护，用于解决各种问题和任务。

pip和conda都是Python的包管理器，用于安装、升级和管理Python包。它是Python标准库之外的一个第三方工具，可以方便地下载、安装和管理各种Python包和依赖项。

直接安装软件包速度太慢，经常被中断，所以需要配置国内镜像源。

#### 配置国内镜像

##### pip设置国内镜像

01 pip国内源设为默认，做法是：

清华pip镜像

> *pip config set global.index-url* *[https://**pypi.tuna.tsinghua.edu.cn**/simple](https://link.zhihu.com/?target=https%3A//pypi.tuna.tsinghua.edu.cn/simple)*

阿里pip镜像

> *pip config set global.index-url* *[https://**mirrors.aliyun.com/pypi**/simple/](https://link.zhihu.com/?target=https%3A//mirrors.aliyun.com/pypi/simple/)*

02 临时使用

另外如果临时使用可以使用

使用pip的时候在后面加上-i参数，指定pip源：

> *pip install xxx -i* *[https://**mirrors.163.com/pypi/si**mple/](https://link.zhihu.com/?target=https%3A//mirrors.163.com/pypi/simple/)*

替换“xxx”为你需要安装的模块名称。

你可以使用 `pip install`命令来安装包。例如，下面的命令展示了如何安装numpy库：

```text
pip install numpy
```

你也可以指定要安装的包的版本。例如，下面的命令展示了如何安装numpy 1.18.5版本：

```text
pip install numpy==1.18.5
```

02 卸载包

你可以使用 `pip uninstall`命令来卸载包。例如，下面的命令展示了如何卸载numpy库：

```text
pip uninstall numpy
```

03 查看已安装的包

你可以使用 `pip list`命令来查看已安装的包及其版本。例如，下面的命令展示了如何查看已安装的所有包：

```text
pip list
```

你也可以使用 `pip show`命令来查看特定包的详细信息。例如，下面的命令展示了如何查看numpy库的详细信息：

```text
pip show numpy
```

04 升级包

你可以使用 `pip install --upgrade`命令来升级包。例如，下面的命令展示了如何升级numpy库：

```text
pip install --upgrade numpy
```

##### conda镜像

01 清华conda镜像

注：由于更新过快难以同步，我们不同步 `pytorch-nightly`,`pytorch-nightly-cpu`,`ignite-nightly`这三个包。

```text
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/main/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/
conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/cloud/pytorch/linux-64/
conda config --set show_channel_urls yes
```

接下来conda的操作可以参考

```text
#获取版本号
conda --version 或 conda -V

#检查更新当前conda
conda update conda

#查看当前存在哪些虚拟环境
conda env list 或 conda info -e

#Create env
#Create env with python 3.7 and pip
conda create --name whatwhale python=3.7 pip
#Activate env
#Activate by name

conda activate whatwhale
#Deactivate env
conda deactivate
#Removing an environment
#Remove environment by name

# remove env
#conda env remove --name whatwhale
# verify
conda env list

#查看--安装--更新--删除包

conda list：
conda search package_name# 查询包
conda install package_name
conda install package_name=1.5.0
conda update package_name
conda remove package_name
```

#### 项目包管理

`requirements.txt` 文件用来记录你的python项目所需要的所有外部的包（我们也成为依赖），这样，丹尼在新的环境中运行这个项目的时候，只需要看这个文件，就可以知道需要安装那些包裹，以及需要的版本，从而保证项目正常运行。

01 生成 `requirements.txt` 文件

`requirements.txt` 是一个文本文件，用于记录 Python 项目所依赖的第三方库及其版本信息。它通常用于管理项目的依赖关系，以确保在不同的环境中能够准确地安装相同的依赖。

在 `requirements.txt` 文件中，每一行表示一个依赖项，通常采用 `<package-name>==<version>` 的格式来指定依赖的包及其版本。例如：

```text
requests==2.25.1
numpy==1.19.4
pandas==1.1.5
```

上述示例中，`requirements.txt` 文件列出了项目所需要的三个依赖包，分别是 `requests`、`numpy` 和 `pandas`，并指定了它们的版本号。

通过执行以下命令，可以根据 `requirements.txt` 文件自动安装项目所需的依赖包：

```text
pip install -r requirements.txt
```

这样，可以确保项目在不同的环境中具有相同的依赖关系，提高了项目的可移植性和可重复性。同时，`requirements.txt` 文件也方便了团队协作，可以将项目的依赖关系进行版本控制，确保团队成员使用相同的依赖版本进行开发。

需要注意的是，`requirements.txt` 文件只是一种约定，可以根据项目的需要进行灵活调整。在实际使用时，可以根据项目的依赖关系和版本要求进行适当的编辑和维护。

02 生成指南

要生成 `requirements.txt` 文件，可以使用 `pip` 工具的 `freeze` 命令。请按照以下步骤操作：

1. 在项目的根目录下打开终端或命令提示符。
2. 确保已经安装了项目所需的所有依赖包。
3. 执行以下命令来生成 `requirements.txt` 文件：

```text
pip freeze > requirements.txt
```

该命令会将当前环境中安装的所有第三方包及其版本信息输出到 `requirements.txt` 文件中。

* 检查生成的 `requirements.txt` 文件，确保其中包含了项目所需的所有依赖包及其版本信息。

注意事项：

* 如果您使用了虚拟环境，请确保在虚拟环境中执行上述步骤，以便仅包含项目所需的依赖项。
* 如果您只想生成项目的直接依赖项，而不包括间接依赖项，可以使用 `pipreqs` 或类似的工具来生成更精简的 `requirements.txt` 文件。
