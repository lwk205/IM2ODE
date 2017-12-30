Inverse Design of Materials by Multi-objective optimization
-----------------------------------------------------------
IMODE, 逆向材料设计软件包

Content
-------
文档的组成
在这里，IMODE的文档由3部分组成：README，DEVELOPERS’GUIDE，USERS’ GUIDE。在README里，会包含这个程序包的概述，特征，安装说明，作者清单和提供支持的邮件列表，开源协议。在USERS’ GUIDE里给出的预言不同体系的具体参数设置，程序中如何调用VASP或lammps，如何根据具体的机器环境改并行任务脚本，以及在搜索完成后如何通过后处理脚本导出预言的结构。DEVELOPERS’GUIDE（还没开始写。。。）是一份针对开发者的文档，里面给出了程序的逻辑框架，代码示例和每个函数、子程序的功能。希望这些文档能够帮助到不同需求的用户。

Required software
-----------------
Required software:
编译前需要安装的软件
* GNU make.
* Fortran compiler.

Quick compilation instructions
------------------------------
快速安装指南
    make

A short version of intruduction
-------------------------------
一个简短的介绍
人类社会的进步离不开新材料。从石器时代、青铜器时代到信息时代（硅及其相关材料的发现和应用），人类文明的跨越式发展离不开新材料的发现和应用。然而，传统的寻找新材料的手段是通过不断地尝试人类已经发现的材料，就像爱迪生百年前尝试用各种不同材料制作灯丝一样，这种通过盲目地合成材料来进行筛选的过程无疑耗时耗力。现在，随着超级计算机以及第一性远离计算方法的发展，只要给定凝聚态物质内部的原子堆垛方式，即材料的微观结构，就能通过计算得知该物质宏观的物理和化学性质。
逆向材料设计，就是从物理学和材料科学的基本原理出发，从理论上预言具有特定性质的新材料，这是科学家们长久的梦想。因此，我们有必要开发新方法来发展逆向材料设计，使得理论结构预测方法能够预言特定性质的新材料，从而起到指导实验和加快新材料发现进程的目的。
逆向材料设计软件包的开发工作就是在这一背景下开展的。软件包的全称是Inverse Design of Materials by Multi-objective Differential Evolution, 即基于多目标差分演化算法进行逆向材料设计。在确定了定量的目标性质（比如半导体的带隙和硬度等）的情况下，该软件包能够在仅仅给定化学组分的情况下将具有该性质的原子排布组合给预言出来。至今，该软件包已经被国内外众多计算物理学界同行所采用，成为逆向材料设计领域的一种重要方法。

Functions
---------
主要功能：
-**设计功能材料：**
-特定能带带隙
-超硬材料
-**设计不同维度的材料：**
-三维晶体结构
-二维层状和表面结构
-一维纳米条带结构
-零维团簇结构和复杂缺陷

Licence
-------
LGPL
IMODE程序包在General Public License (GPL) 下开源（协议的具体条款见IM2ODE协议.doc）。GPL同其它的自由软件许可证一样，许可社会公众享有：运行、复制软件的自由，发行传播软件的自由，获得软件源码的自由，改进软件并将自己作出的改进版本向社会发行传播的自由。

Method
------
逆向材料设计方法相关文献
Zhang YY, Gao WG, Chen SY, Xiang HJ, Gong XG*, "Inverse design of materials by multi-objective differential evolution", Comput. Mater. Sci., 2015, 98, 51-55.
Chen HZ, Zhang YY, Gong XG*, Xiang HJ*, "Predicting New TiO2 Phases with Low Band Gaps by a Multiobjective Global Optimization Approach", J. PHYS. Chem. C, 2014, 118, 2333-2337.

Mailing list
------------
以下邮件列表提供长期的技术服务支持
张越宇：yyzhang12@fudan.edu.cn

