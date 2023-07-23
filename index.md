## 简介
> 这是一份文档博客搭建工具指南，同时也是一个docsify博客网站最完整的架子，建议直接Clone到本地自己修改定制。
 	
 - 您是否曾为项目文档的编写和维护而苦恼？是不是觉得传统的文档工具繁琐不易上手，让文档变得冗长乏味？那么，让我们为您介绍一个简单高效的解决方案——Docsify！

 - 什么是Docsify？
  Docsify是一款强大且易用的文档生成工具，它可以帮助您将Markdown文件快速转换为漂亮、响应式的文档网站。无需复杂的配置和安装，只需专注于文档内容本身，Docsify将为您自动生成漂亮的文档界面。

为什么选择Docsify？

 - 简单易用：Docsify的安装和配置非常简单，您只需几分钟即可搭建起属于自己的文档网站，不再为繁琐的设置而烦恼。

 - 优雅美观：Docsify提供多种内置主题和插件，让您的文档网站拥有时尚、优雅的外观，给用户留下深刻印象。

 - 响应式布局：无论是在桌面端、平板还是手机上访问，Docsify的文档都能自动适配，让用户随时随地轻松浏览文档。

 - 全文搜索：Docsify支持全文搜索功能，让用户可以快速找到所需信息，提高文档查阅效率。

 - 多语言支持：如果您的项目面向国际用户，Docsify的多语言支持功能能够满足不同语种用户的需求。

如何开始使用Docsify？
使用Docsify非常简单！您只需三步即可上手：

 - Step 1：安装Docsify
 - 在GitHub上找到Docsify的仓库，并根据文档中的指引，轻松完成安装步骤。

 - Step 2：编写文档
 - 使用Markdown语法编写您的项目文档，结构清晰、易读易懂的文档将会更吸引用户。

 - Step 3：运行Docsify
 - 在命令行中输入几行简单的指令，Docsify将为您生成文档网站，并提供一个本地服务器进行预览。

若您在使用过程中遇到任何问题或需要更多帮助，请查阅[Docsify](https://github.com/topics/docsify)详细文档或参与活跃的社区讨论。我们相信Docsify会成为您项目的得力助手，让文档维护不再是一项繁重的任务！

## 如何使用

- clone本仓库到本地[github地址](https://github.com/andy-brain/BSdocsify)，打开docs文件夹
  - 修改index.html中的仓库为你的github仓库
  - 修改/docs/cover.md封面
  - 修改/docs/index.md主页
  - 修改/docs/sidebar.md侧边栏导航
  - 修改/docs/navbar.md顶部菜单（如果需要）
  
- 全局安装docsify脚手架

  `npm i docsify-cli -g`，首先保证已安装npm包管理工具

- 本地预览
  - docs文件夹下执行`docsify serve docs`
  - 或者执行全局命令`npm run doc`，该配置在package.json的scripts中

