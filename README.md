# SDUCS 课程资料共享计划 (仅 openlab)
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-0-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

> 目前 qer 未在维护，若想拥有权限可直接联系授予，或者找hkq

前人走过的弯路，后人就不必再走。

本计划旨在维护一个公开的、易于获取的和大家能够共同完善、积累的课程共享资料宝库。

让大家不必有问题只去 CSDN，而是能够获取世一大学长学姐们留下的宝贵财富。

高效率努力学习课程知识，从我做起。

## 前言

懒得写了，抄抄其他大学的 

北航前言
> 学习从来都不是一个人的战斗，互相帮助才是集体的作战方式！
>
> 上一门课总是需要搜索答案，相关课件，相关资料，相关习题的解法，作业上交以后往往不知道自己是否正确答题。
>
> 而这些资料随着课程的完毕结束，它们对于你来说已经没有太大价值，但是对下一届的学生来说却帮助良多。
>
> 教育应该是需要传承的，不仅仅是从老师那里的传承，师兄师姐的传承也是教育精神所在。
>
> 以往的资料都在某些师兄师姐手里一代传一代，资料整理维护过程经常出现问题。
>
> 希望大家能分享你的优秀经验知识，传播给更广大的学生们。

浙江大学前言
>
> 来到一所大学，从第一次接触许多课，直到一门一门完成，这个过程中我们时常收集起许多资料和情报。
>
> 有些是需要在网上搜索的电子书，每次见到一门新课程，Google 一下教材名称，有的可以立即找到，有的却是要花费许多眼力；有些是历年试卷或者 A4 纸，前人精心收集制作，抱着能对他人有用的想法公开，却需要在各个群或者 CC98 中摸索以至于从学长手中代代相传；有些是上完一门课才恍然领悟的技巧，原来这门课重点如此，当初本可以更轻松地完成得更好……
>
> 我也曾很努力地收集各种课程资料，但到最后，某些重要信息的得到却往往依然是纯属偶然。这种状态时常令我感到后怕与不安。我也曾在课程结束后终于有了些许方法与总结，但这些想法无处诉说，最终只能把花费时间与精力才换来的经验耗散在了漫漫的遗忘之中。
>
> 我为这一年一年，这么多人孤军奋战的重复劳动感到不平。
>
> 我希望能够将这些隐晦的、不确定的、口口相传的资料和经验，变为公开的、易于获取的和大家能够共同完善、积累的共享资料。
>
> 我希望只要是前人走过的弯路，后人就不必再走。这是我的信念，也是我建立这个项目的原因。

## 如何贡献此项目？

欢迎各位同学参加贡献，你的贡献将被自动永久记录在此仓库，**若想匿名**可以发送邮件至 sdu-opencourse@outlook.com，将会有维护者代替你上传。

Issue、PR、纠错、资料、选课/考试攻略，Totally Accepts.

### 方法一

建议在网页端直接上传资料，操作步骤如下：

1. 点击右上角 Fork 本项目

2. 编辑此项目
    1. 按键盘上的 `> .` 键（问号左边那个），进入在线版的编辑器
    2. 在左侧边栏即可编辑本仓库所有目录，可创建/删除/重命名文件夹，并且拖动文件到此处进行上传
    3. 上述编辑完成后，点击左侧竖排图表中的第三个 git 分支（搜索图标下面那个）
    4. 鼠标移动至 `Changes` 一行，点击加号（悬浮会出现 Stage All Changes），在执行下一步之前，确保 `Changes` 下已经没有任何文件
    5. 执行上一步之后，在 `Message` 输入框内描述本次操作的内容，如 `编译原理: 上传了个人复习笔记`，注意是英文冒号+后接一个空格
    6. 点击上方对号，进行 `commit` 提交
3. 经历步骤2，你已经在你 `Fork` 的仓库中成功进行了修改，现在需要合并到主仓库
    1. 将地址栏中的 .dev 改为 .com，其他内容不变，跳转到你 `Fork` 的仓库
    2. `Code` 按钮下方会出现一块内容：`This branch is 1 commit ahead of sdu-openlab:main.`，点击 `Contribute` 下的 `Open pull request`
    3. 点击 `Create pull request`
    4. 描述你的修改内容或者本次合并想说的话，然后点击 `Create pull request`

大功告成！请等待维护者将你的内容合并进主仓库。

> 如果某一步出错，最简单的方法是从头开始，即删除你 Fork 的仓库，重新 Fork。

推荐一门课程的目录格式为

```markdown
- 课程资料
  - 电子版教材与参考资料（需合法）
  - slides（需合法）
- 考试
  - 往年真题回忆版
    - 2020.pdf
    - 2019.doc
    - ...
  - 其他题目
    - 毛概选择 500 道.pdf
    - 做了很有用的高数 10000 道题目.pdf
    - ...
  - 考试大纲.pdf
  - ...
- 笔记
  - xxx课期末复习笔记手写版.pdf
  - imooc 课程笔记.pdf
  - 王道考研视频随堂笔记.pdf
  - 上课笔记.pdf
  - ...
- 其他
  - 实验环境依赖包（方便你配环境）
  - 其他杂七杂八的
```

> 当然，你也可以按照老流程上传文件（但不推荐）
>
> - 新建课程目录：点击 `Add file - > Create new file` , 在 `OpenCourse/` 后面输入你的课程文件名字，然后按 `/` 即可生成目录，然后输入 `README.md`，在下方的 `Edit new file` 输入课程介绍、注意事项与心得体会等等。
>
> - 上传文件资料：进到对应目录下上传你的资料文件即可，直接把文件拖进游览器会自动上传，注意一次上传不能超过 100 个文件，且每个文件大小有 25MB 限制

### 方法二

写一个 Issue 或者发送邮件到 sdu-opencourse@outlook.com，请说明是否匿名、课程名称、资料类型，由项目维护人员进行添加

### 提醒

有些朋友在提交 PR 的时候可能会注意到自己的 Fork 和我们的主分支有数十甚至上百个不同的 commit 。如果出现这种情况，可以考虑以下两种解决方案：

- 如果对git不太熟悉，建议（在备份完成后）先删除你的项目，重新 fork 、上传并重新提交 PR 。
- 如果对git及其工作原理较为熟悉（而且愿意花费时间和流量折腾），可以尝试在 fork 出的项目上进行 rebase 以消除与主分支在历史上的冲突。


## 如何更方便的下载

有些朋友可能仅需下载部分课程资料（即部分文件夹），而无需clone整个项目
关于这种下载需求，可以访问
https://github.dev/sdu-openlab/OpenCourse
这是仓库的在线Dev页面，其UI类似于 VS Code，你可以右键单击你想要下载的目录或文件并点击Download，即可方便的下载整个目录。

## 注意事项与警告

下列内容为不适合上传的内容。如果你认为缺少这些资料将会影响资源的完整性，请优先考虑放在校内资源平台，或联系你的教师并由教师发布。建议你撰写一个 README 文档并放置一些链接或指引文字来帮助找到这些资源。

- 盗版电子书/付费电子书
- 盗版/破解版/绿色版付费软件及其安装包
- 课程/教师主页上列出的内容（请在获得教师许可后上传）

**如果你认为本仓库的一些文件侵犯了您的权益，请礼貌地向 sdu-opencourse@outlook.com 发送邮件 。我们将会从仓库中彻底清除这些文件。**

## 开发者注意事项

请查看 [维护者手册.md](/维护者手册.md)

## 致谢

### 贡献者 ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

### 建设参考

- [北京航空航天大学(北航)课程作业资料共享计划](https://github.com/TheBloodthirster/BUAA_Course_Sharing)
- [浙江大学课程攻略共享计划](https://github.com/QSCTech/zju-icicles)

### 最初灵感与论坛建设者

此仓库有前身名为 bitcross 的校内论坛(by qer, Conyrol)，但因审查原因未经上线，一年后仓库建成，承担相同职能。

## 许可

由贡献者编写部分的许可如下：

[CC-BY-NC-SA](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)：署名-非商业性使用-相同方式共享

资料仅供参考，请自己判断其适用性。

其他部分的版权归属于其各自的作者。
