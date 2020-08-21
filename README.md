# Spring Cloud 培训教程
这是一本 Spring Cloud 快速入门教程，目的是为完成《[Spring Boot 培训教程](https://github.com/gyzhang/SpringBootCourse)》学习后或已经能够使用 Spring Boot 生态技术栈进行开发的中级 Java 开发人员提供在微服务系统构建方面的指导和实战，向高级开发人员进阶。

本教程从2020年4月1日开始写作，希望能够在2020年8月31日完成。

> 4月1日，是个开工的好日子。
>
> 在技术的路上保持活力，
>
> **Stay Hungry, Stay Foolish.**
>
> 有啥不好？
>
> --Kevin Zhang

- 本教程使用的 Spring Cloud 版本是 Hoxton.SR3, 对应的 Spring Boot 版本是 2.2.6.RELEASE, 最新版新鲜带劲儿，等你学完了，学会了，这个版本就变成你在项目工作中使用的稳定版了；

- 本教程的每一章节，尽量聚焦在当前讨论的知识点范围内，示例也设计为最简，并循序渐进介绍知识，不介绍项目经验，那些有用的经验是在项目中踩坑踩出来的，不是通过教程/书籍学出来的；

- 本教程不涉及 Spring Cloud 组件的深层次实现机制，那是你公司或项目的架构组要考虑的事儿；

- 已经能够熟练使用 Spring Cloud 进行开发或架构设计的同学，请绕道，这份教程不适用于你。

如何将本书编译成 pdf、epub 等电子书格式？

1. 先到 [https://nodejs.org/en/](https://nodejs.org/en/) 下载 node.js LTS（[node-v12.16.0-x64.msi](https://nodejs.org/dist/v12.16.0/node-v12.16.0-x64.msi)） 版，安装；
2. 打开命令行窗口输入命令 `npm i -g gitbook-cli` 安装 gitbook 环境；
3. 然后到 [https://calibre-ebook.com/](https://calibre-ebook.com/) 下载 [calibre 3.40.1](https://download.calibre-ebook.com/3.40.1/calibre-64bit-3.40.1.msi) 并安装。需要注意的是最新版本和 gitbook 不兼容；
4. 将本教程的版本库下载或克隆到本地；
5. 打开命令行窗口，进入 SpringCloudCourse 版本库目录；
6. 执行 `gitbook install` 安装 gitbook 插件；
7. 执行 `gitbook pdf` 生成本书的 pdf 版本；
8. 执行 `gitbook epub` 生成本书的 epub 电子书。

写作历程：

1. 2020-4-27，花费了近1个月，完成所有目录的规划，完事开头难啊。好消息是在疫情期间一直坚持锻炼身体，体重下降5Kg，肌肉量上升脂肪率下降，经常进入“基础代谢率”正常区间，值得庆贺；
2. 2020-8-21，食言了。最近各种忙，根本没有时间，也没有静下心来写作，还是保持在完成目录的状态，Spring Boot 版本已经更新到`2.3.3.RELEASE`了。今天，孩子去军训了，我也又想起写作这事儿，先更新一下状态吧，十有八九还是没有时间坚持写作下去。