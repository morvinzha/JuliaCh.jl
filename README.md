# JuliaCh.jl

这里是[Julia.jl](http://svaksha.github.io/Julia.jl)的简体中文版本，这里收集并陈列[Julia语言](https://github.com/JuliaLang)的各种相关资源.

+ [索引](#索引)
+ [证书](#证书)
   + [镜像](#镜像)
+ [贡献你的力量](#贡献你的力量)
   + [参考](#参考)
   + [状态](#状态)
   + [错误报告和PR](#错误报告和PR)

----

# 索引

对于一些基本的程序包，先在github上的[内建程序包管理器](https://github.com/JuliaLang/METADATA.jl)里找一找有没有你要找的，或者查看METADATA中[注册的Julia程序包](http://pkg.julialang.org/)，然后使用内建的包管理器来安装某个版本。

如果你想创建一个程序包，请查看[Julia程序包开发工具](https://github.com/JuliaLang/PkgDev.jl)并且这里有一个[Julia程序包样例](https://github.com/JuliaLang/PkgDev.jl)，最新的有趣程序包统计在[Julia程序包动态](http://pkg.julialang.org/pulse.html)中。被抛弃的，不再有人维护或者不再纳入Julia开源组织的程序包将会默认被收集在[Julia Archive](https://github.com/JuliaArchive)组织中.


+ [AI.md](https://github.com/svaksha/Julia.jl/blob/master/AI.md) :: 算法, 数据挖掘, 数据结构, 隐马尔可夫模型, 机器学习, 自然语义分析, ...
+ [Astronomy.md](https://github.com/svaksha/Julia.jl/blob/master/Astronomy.md) :: 天文和图像程序包.
+ [API.md](https://github.com/svaksha/Julia.jl/blob/master/API.md) :: 其它语言的接口 - C++, Fortran, Go, Java, JavaScript, MATLAB, Perl, Python, R, ...
+ [Biology.md](https://github.com/svaksha/Julia.jl/blob/master/Biology.md) :: 生物信息, 基因组学, 农学, 食品科学, 医学, 遗传工程, 神经科学, et. al...
+ [Build-Automation.md](https://github.com/svaksha/Julia.jl/blob/master/Build-Automation.md) :: 持续交付 （CD）,持续集成（CI）工具, 封装, 工程发布 (RE), 发布管理 (RM), 软件配置管理 (SCM), 等等...
+ [Chemistry.md](https://github.com/svaksha/Julia.jl/blob/master/Chemistry.md) :: 分析化学, 化学信息学, 结晶学, 纳米化学, 核化学 ...
+ [Community.md](https://github.com/svaksha/Julia.jl/blob/master/Community.md) :: 这里列出了社区和Julia相关开发的链接，包括Julia大事件，会议, 论坛/ 聚会，新闻，等等..
+ [Computer-Graphics.md](https://github.com/svaksha/Julia.jl/blob/master/Computer-Graphics.md) :: 绘图, 图表和其它可视化工具.
+ [DataBase.md](https://github.com/svaksha/Julia.jl/blob/master/DataBase.md) :: 数据库：NoSQL, RDBMS and Middleware的接口（API）.
+ [Earth-Science.md](https://github.com/svaksha/Julia.jl/blob/master/Earth-Science.md) :: 制图学, 气候学, 地球生物学, 地球化学, 地理学, 地球空间信息学, 地质学, 地球物理, 地球科学/地理咨询系统, 地质数学, 气象学, 海洋学等相关的应用和软件...
+ [Hardware.md](https://github.com/svaksha/Julia.jl/blob/master/Hardware.md) :: 跨平台硬件和其它API库相关软件
+ [HPC.md](https://github.com/svaksha/Julia.jl/blob/master/HPC.md) :: 高性能计算，分布式计算，云计算，集群计算，网格计算，Kernels and architectures like 诸如ARM，MIPS，GPU，CUDA等的核心程序和架构...
+ [i18n-L10n.md](https://github.com/svaksha/Julia.jl/blob/master/i18n-L10n.md) :: 翻译，国际化 (i18n) 以及本土化 (L10n)
+ [IO.md](IO.md) :: 不同文件类型的输入/输出功能和相关支持
+ [Mathematics.md](Mathematics.md):: 代数，几何，... 所有和数学相关的内容.
+ [OpenData.md](https://github.com/svaksha/Julia.jl/blob/master/OpenData.md) :: OpenData，免费的数据集
+ [Physics.md](https://github.com/svaksha/Julia.jl/blob/master/Physics.md) :: 和物理相关的Julia程序包
+ [Programming-Paradigms.md](https://github.com/svaksha/Julia.jl/blob/master/Programming-Paradigms.md) :: Programming Paradigms and language concepts that are used in the type system, data types, etc..
+ [Publications.md](https://github.com/svaksha/Julia.jl/blob/master/Publications.md) :: Research Papers (journal and conference publications).
+ [QA.md](https://github.com/svaksha/Julia.jl/blob/master/QA.md) :: Test Driven Development, Sandbox, Functional/ Unit testing,... Quality-related tools.
+ [Resources.md](https://github.com/svaksha/Julia.jl/blob/master/Resources.md) :: blogs, cookbooks, cheatsheets, IJulia NoteBooks, and other non-standard resources.
+ [Statistics.md](https://github.com/svaksha/Julia.jl/blob/master/Statistics.md) :: Actuarial Science, Finance, economics, stochastic, insurance Statistics, Operations research and Benchmarks and Optimization toolkits....
+ [Utilities.md](https://github.com/svaksha/Julia.jl/blob/master/Utilities.md) :: Handy toolkits and other general utilities for your Desktop.
+ [Web-Server.md](https://github.com/svaksha/Julia.jl/blob/master/Web-Server.md) :: HPC, Distributed Computing, Cloud WWW, HTTP, Networking, Servers, etc...


**DISCLAIMER :** As a new language in the scientific computing scene it is frequently in a state of flux due to the addition of new libraries, resulting in frequent changes and page reordering. Since the **Julia.jl** repo only provides a list (of links) of Julia packages out in the wild, it should not be considered an endorsment of any particular package for software quality, technical features, coding style/organization, etc...

----

# 证书
+ COPYRIGHT © 2012-Now [SVAKSHA](http://svaksha.com/pages/Bio), All Rights Reserved.
+ This work is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License - (CC BY-NC-SA 4.0) as detailed in the [LICENSE.md](https://github.com/svaksha/Julia.jl/blob/master/LICENSE.md) file and ALL references, citations, copies and forks of this work must retain the Copyright, Licence (LICENSE.md file), this permission notice and must [attribute credit](https://en.wikipedia.org/wiki/Creative_Commons_license#Attribution).

## 镜像
+ [Bitbucket](https://bitbucket.org/svaksha/Julia.jl) :: git clone git@bitbucket.org:svaksha/Julia.jl.git
+ [GitLab](https://gitlab.com/svaksha/Julia.jl) :: git clone git@gitlab.com:svaksha/Julia.jl.git
+ [NotABug](https://notabug.org/svaksha/julia.jl) :: git clone git@notabug.org:svaksha/julia.jl.git


# 贡献你的力量
[Contributions](https://github.com/svaksha/Julia.jl/graphs/contributors) to `Julia.jl` are welcome in the form of pull requests (PR). Here are some guidelines and tips on how to submit a Bug Report (BR) and/or [PR](https://github.com/svaksha/Julia.jl/pulls):

## 参考
The Julia community has [ethical guidelines](http://julialang.org/community/standards/) aimed at respecting Copyright, Licenses and attribution standards<sup>{1} and {2}</sup> which you are requested to follow while submitting materials to be listed. Additionally, if you find any material (or code repos) that violates these ethical standards, please file a bug report for their removal from `Julia.jl`.
+ References :
   + {1} https://github.com/JuliaLang/julialang.github.com/issues/200
   + {2} https://github.com/JuliaLang/julialang.github.com/issues/194


## 状态
These [comments](https://github.com/svaksha/Julia.jl/commit/a884fe9e921d57b87d85e970c2f57b8f21025641#commitcomment-15802037) led to a [BR discussing](https://github.com/svaksha/Julia.jl/issues/55) the addition of metadata tags that will enable programmers and package users to easily distinguish the status of various Julia packages that are under various stages of development. Currently, METADATA has a tag system but not all package authors use it, making it harder for lay users to know if the package maintenance is active or not. 

Lets experiment with asking package authors and core-commiters to tag their Julia packages on the following criteria : 

On a scale of 1 to 5 (1=lowest,..5=highest), please rank your package for,

+ `Usability` : Does the package do what it says it does? is it easy to figure out? Is the package production-ready and actively maintained (issues/PRs are responded and resolved in a timely manner, and maintenance and testing is at par with Julia release cycles).
+ `Quality` : Does the package have tests? are there lots of bugs? Do you have good documentation? Can it be used in production environments that expect prompt security patches?
+ `Activity` : Should a 3rd party user bother to use your library, or is it really only intended to be used by the package author? Let's say, an experimental "throw-away toy repo" whose development has now been abandoned.
+ `License` : Which software license do you use? If you dont have a license, please state `None`. 

## 错误报告和PR
1. Add your link as per the top-level Category page within the topic sub-section(s), in _alphabetical order_, with notes (if any) in the markdown files.
2. For broken links or outdated information, submit a bug report (BR), or make the necessary changes and submit a PR. Both are welcome. Please submit separate PR's for each link or change added.
3. For Documentation and cookbooks, check if it matches the categories listed, else, list it on the [Resources.md](https://github.com/svaksha/Julia.jl/blob/master/Resources.md) page.
4. For those unable to use git, create a github account, then fork the `Julia.jl` repo on the user interface. Then edit the page by [clicking on the "pencil" icon on the markdown page](https://help.github.com/articles/editing-files-in-your-repository), then click on save and submit a PR. Github does this [automatically in 8 steps](https://help.github.com/articles/editing-files-in-another-user-s-repository).
