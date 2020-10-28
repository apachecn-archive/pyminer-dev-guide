# PyMiner 开发者指南

MATLAB 和 Mathematica、Maple 并称为三大数学软件。它在数学类科技应用软件中在数值计算方面首屈一指。MATLAB 可以进行矩阵运算、绘制函数和数据、实现算法、创建用户界面、连接其他编程语言的程序等。

前一段时间 MATLAB 进入实体清单实践，也让部分国内开发者有了危机意识，今天介绍的这款项目就是试图打造「开源界的 MATLAB」，目前项目刚刚起步，还需要更多热爱开源或 MATLAB\PyQt\Python 的技术大牛加入。

**项目名称**：PyMiner

**项目作者**：py2cn

**开源许可协议**：GPL-3.0

**项目地址**：https://gitee.com/py2cn/pyminer

**官方网站**：[www.py2cn.com](http://py2cn.com/)

## 项目简介

PyMiner 是一款数据处理、数据分析、数据建模、数据评估、数据可视化的工具,基本目的是使pandas、sklearn的操作进行可视化，用更加易于操作的形式完成数据科学家相关工作。

项目开发环境基于Window 10 x64，使用  **Python3.8+PyQt5.15+Pycharm** 进行技术开发。

## 项目预览

![做开源界的MATLAB，这个项目需要更多热爱开源的你加入](https://img-blog.csdnimg.cn/img_convert/cf251748e2d097620532c17b2607ef4e.png)

![做开源界的MATLAB，这个项目需要更多热爱开源的你加入](https://img-blog.csdnimg.cn/img_convert/84fe552baada6ced942ab4be5bf59086.png)

![做开源界的MATLAB，这个项目需要更多热爱开源的你加入](https://img-blog.csdnimg.cn/img_convert/8268c24ea16369edac4dfa769367bd66.png)

![做开源界的MATLAB，这个项目需要更多热爱开源的你加入](https://img-blog.csdnimg.cn/img_convert/bb61aa7deab1d219c690464d894707a5.png)

## 项目说明：

**为什么要做这个项目？目的是什么？**

2020年6月6日开始，哈工大等中国高校被禁用MATLAB。在此之前我们发现在工业软件、行业软件除了MATLAB以外，还有SAS、SPSS、FICO、Adobe等都是我们高度依赖且无法替代的行业软件。 为此，这个项目的根本目标就是实现MATLAB替代，短期内至少是实现在某一方面的替代，并逐步实现超越MATLAB，并以抛转引玉的形式，让更多人加入到国产替代的行列中!PyMiner坚持对标国际一流，实现面向未来的设计，以自主创新为战略基石，积极吸收凝聚国内外各种优势资源和创新要素，致力于突破掌握一批数据算法模型以及仿真领域研制关键技术！

**为什么是用python开发，为什么不选C++ C# java或者其他？**

在选定python之前，我们考虑过包括c++、c#、java、eletron等多种开发方案去实现国产的MATLAB，甚至我们在曾经使用c#开发过一段时间后又重新启用python来完成这项工作。 python有丰富而成熟的外部扩展，开发者数量众多，且代码结构清晰，开发效率高等优点，为了尽快实现国产开源的matlab，能够进行实际使用，并在之后吸引广大的开发者、算法工程师、数据科学家参与进来，我们选择使用python，并且我们将支持c++等语言进行扩展提高产品性能。 需要说明的是，我们团队中也有很多C++大牛，也有C++项目小分队，如果你在C++领域并希望参与到项目中来并贡献自己的一份力量，我们殷切欢迎！

**有没有高校或者机构跟你们合作？**

我们很希望能够跟高校或机构进行合作，但是目前为止，除了开发组QQ群中以个人身份参与的学生或者老师，暂时没有任何高校或机构与本项目进行合作。

**你们有没有考虑过做仿真或Simulink?**

项目从最初构想时就已经规划开发仿真系统，但是限于开发组人员有限，目前虽已成立仿真开发小组，但目前进度非常有限，希望更多有志之士能够加入!

**你们的方向是怎么样的？**

我们方向是先做通用型的类MATLAB工具，比如我们会优先实现MATLAB中使用频率最高的功能，在通用模块（数据处理、数据分析、数据可视化等）基础上，逐步添加有行业针对性的功能模块。

**目标用户群体是怎样的？**

我们的目标群体是MATLAB的浅度用户和python数据科学家相关用户，例如数据相关行业的基本用户（医疗分析、金融、制造等行业的数据分析师、数据科学家等），在此基础上，我们希望不断添加行业特有的功能模块实现逐个行业方向的实现并替代MATLAB。

**目标使用场景是怎样的？**

在产品开发初期，我们设想的使用场景是行业通用的数据处理和数据分析，例如公司内部用户数据的处理分析、金融行业的用户风险分析、医疗行业的数据分析等基本数据科学相关场景。

**为什么叫PyMiner?**

目前为止这已经是该项目的第5个名字，从之前的PythonEnv、PandaStudio、PyStudio、Patata到现在的PyMiner。总体上可以看出是基于Python以及是平台化跟挖掘数据价值相关的项目。PyMiner的意思我自己解释为一个将Python作为工具的淘金者。

**项目的中文名叫什么？**

PyMiner项目的中文名暂定为泊宇（po yu）项目，即根据PyMiner首字母做的拼音化转义，另外，也有像宇宙开船，向更广阔的天地前进的意思，而且也有“迫于***”的含义，表达了作者希望牢记使命，不断进取的理念！

## 项目计划

**目前我们已经做了哪些内容？**

目前我们已经确定了整体的架构形式python+pyqt，完成了界面重构(例如ribbon菜单，dockwidget控件改造)，编辑器、控制台、插件管理器、工作空间等核心内容的开发建设。

**下一步的工作计划是什么？**

下一步我们将首先继续完成并优化插件管理器的窗口化设计，进一步优化workspace工作区间的可视化设计与实现。 此外：

1. 在下一个里程碑计划中，预计我们将实现核心功能插件的demo，例如数据处理，数据分析。

2. 我们将和更多算法工程师一起基于numpy构建我们的基础算法库。

3. 我们将基于gitbook建立社区文档管理系统，让开发者、算法工程师、数据科学家一起丰富产品文档内容。

4. 我们将基于官网py2cn.com,建立插件商店，让用户能够上传插件，查询插件。

**里程碑计划**

· V1 里程碑是2020.09.30，核心组件全部构建完成，UI框架确定，两个插件demo（数据分析，数据处理）

· V1.1里程碑是2020.10.30，完善核心功能，数据处理完成常见场景插件，数据分析完成至少2个demo（描述统计+t检验或其他）插件，数据可视化相关功能完成至少两个demo(2D，3D)，算法模型插件完成至少一个demo

· V1.2里程碑是2020.11.30，完善核心功能，数据分析完成常见场景插件，数据可视化相关功能完成全部常见场景，算法模型插件完成常见场景

· V1.3里程碑是2020.12.30，完善核心功能，补充完成数据处理、数据分析、数据可视化、数据建模、模型评估常见场景

· V2 里程碑是2021.01.30，基本功能实现，接口文档齐全，可以支持跨行业插件开发

## 开发者说

PyMiner 的落地，离不开广大的算法工程师的群智，而目前国内搞算法这一块的，基本上Python 语言是主流的，C++ 速度确实是快，当然我本身就是搞 C++ 的，但是它入门门槛略高，开发效率慢，而且更重要的一点是，如果代码质量良莠不齐，速度其实也很一般。现在PyMiner 刚刚起步，缺技术人才的支持，更缺做事的人，在这种情况下，我们只能给各个行业的精英，起到搭建起我们的平台，给牛人发挥的舞台的作用，因此，能起到最便捷的桥梁作用的，就是 Python 了。当然，后期是否用 C++ 重构，则要看多方面因素了。我们 PyMiner 团队希望就 PyMiner 抛个砖，能吸引更多技术人才和做事的人共同实现国产开源 MATLAB 的目标。

## 如何参与项目？

**前言**

为了更便于推进项目，需要了解各位擅长的工作内容，请各位群友修改自己的备注为：方向+昵称，例如pyqt_tom_coffce

**加入小组**

目前开发组已经有pyqt、算法、仿真、插件、网站、c++、项目管理多个小分队，有意向在任意领域进行参与贡献的小伙伴请直接加入小分队QQ群！

· PyMiner开发者QQ总群：945391275

· pyqt小分队：907932713

· 算法小分队：605160230

· 仿真小分队：915736652

· 插件小分队：689417488

· C++小分队：205591506

· 网站小分队：1131420577

· 项目管理小分队：827058366

**参与贡献**

要真正的参与项目，除了需要了解自身特长之外，还需要了解这个项目的基本情况。在Wiki的“  **项目说明**  ”我们有对项目的背景做一些介绍，在“  **项目计划**  ”中我们对当前我们正在做的事情以及下一步的项目计划做了概要性描述。

如果你是偏产品经理和需求分析师方面的，想要为项目做些贡献，我们希望你能对matlab多一些认识，毕竟我们的目标是进行matlab替代。在此基础上，希望你能帮助我们进行需求分解，将matlab的功能模块按照重要性、优先级进行细化分解，以便我们能够更专注于细节进行实现。

如果你是偏qt pyqt python 方向的，想要在PyMiner的界面UI或功能方面进行参与，我们也很希望你能真正的参与到项目的代码贡献当中。在这之前你可能还需要了解我们的代码结构（在wiki的“  **开发者指南**  ”中我们会有相应介绍），编码规范（在wiki的“  **编程规范**  ”中）。

如果你是仿真方向或对Sumlink有所研究，除了项目基础信息之外，你还需要了解项目的插件系统，目前在PyMiner中，更多功能将以插件的形式进行提供。而插件我们支持使用Python或c++等多种方式进行开发。

如果你是算法工程师，你将是这个项目的非常重要参与者，甚至可以说，我们的未来非常依赖你们的参与，而在PyMiner中，算法工程师的贡献，也将主要通过插件的形式进行完成，为此我们需要算法工程师和其他开发者齐心协力进行合作，  **由算法进行后台计算并设计输入参数和输出形式，而pyqt开发者进行插件化改造实现 ，最终将算法以插件的形式对外提供**。

## TODO

在 PyMiner 发布稳定版本后，将[数据科学](https://github.com/apachecn/apachec-ds-zh)和[深度学习](https://github.com/apachecn/apachec-dl-zh)译文集改写为 PyMiner 实现，作为官方教程集。
