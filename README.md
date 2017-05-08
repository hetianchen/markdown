
GitHub 是一个面向开源及私有软件项目的托管平台，因为只支持 Git 作为唯一的版本库格式进行托管，故名 GitHub。
# git是什么  
版本管理系统


Git是一个开源的分布式版本控制系统，可以有效、高速的处理从很小到非常大的项目版本管理。[2]  Git 是 Linus Torvalds 为了帮助管理 Linux 内核开发而开发的一个开放源码的版本控制软件。

# GitHub的好处
1GitHub是一个非常万能的工具。对于任何大小的项目，他都是理想的工具；他也是伟大的web工作流工具。首先，他可以作为一个版本控制系统和协作工具，用它来发布工作
。
2利用GitHub，你可以将项目存档，与其他人分享交流，并让其他开发者帮助你一起完成这个项目。优点在于，他支持多人共同完成一个项目，因此你们可以在同一页面对话交流。
3创建自己的项目，并备份，代码不需要保存在本地或者服务器，GitHub做得非常理想。
4学习Git也有很多好处。他被视为一个预先维护过程，你可以按自己的需要恢复、提交出现问题,或者您需要恢复任何形式的代码，可以避免很多麻烦。Git最好的特性之一是能够跟踪错误，这让使用Github变得更加简单。Bugs可以公开，你可以通过Github评论，提交错误。
5在GitHub页面，你可以直接开始，而不需要设置主机或者DNS。

# GitHub的优势
 GitHub 只支持 Git 格式的版本库托管，而不像其他开源项目托管平台还对CVS、SVN、Hg 等格式的版本库进行托管。GitHub 的哲学很简单，既然 Git 是最好的版本控制系统之一（对于很多喜欢 Git 和 GitHub 的人没有之一），没有必要为兼顾其他版本控制系统而牺牲 Git 某些独有特性。因此没有支持其他版本控制系统的历史负担，是 GitHub 成功的要素之一。

    GitHub 对 Git 版本库提供了完整的协议支持，支持 HTTP 智能协议、Git-daemon、SSH 协议。

    GitHub 提供在线编辑文件的功能，不熟悉 Git 的用户也可以直接通过浏览器修改版本库里的文件。

    将社交网络引入项目托管平台是 GitHub 的创举。用户可以关注项目、关注其他用户进而了解项目和开发者动态。

    项目的 Fork 和 Pull Request 构成 GitHub 最独具一格的工作模式。对提交代码的逐行评注及 Pull Request 构成 GitHub 特色的代码审核。

    GitHub 通过私有版本库托管、面向企业的版本库托管和项目管理平台、人员招聘等付费服务获得了商业上的成功，这种成功使得 GitHub 不必以页面中嵌入广告的方式维持运营，最大的受益者还是用户。
    GitHub 网站采用 Ruby on Rails 架构，在 Web 设计中运用了大量的 JavaScript、AJAX、HTML5 等技术，支持对使用 Markdown 等标记语言的内容进行渲染和显示等。关注细节使得 GitHub 成为了项目托管领域的后起之秀。



通过github年度报告让你记忆最深刻的信息有哪些
JavaScript还是世界上最受欢迎的编程语言
微软的开源贡献人数最多
中国的新用户占比最多



# github上有可以个人账号
还可以有（企业组织 ）账号

# github上面的两个组成要素是什么     
仓库，个人主页
# github上两个重要页面
个人主页，动态页面
# 主页菜单都包含什么   
overview repository stars follow
# 仓库的心跳线代表什么 
仓库更新活跃程度
# star的作用是？   
收藏项目
# fork的作用是？   
希望去参与该项目
# watch的作用是？  
项目如果有更新会发给你邮件
# 搜索结果分别有哪些类别
用户搜索类别，仓库搜索类别，代码搜索类别
# 你在github上挖到什么宝

# 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？

# 如何能将仓库中的html文件直接解析成页面？
	新建一个gh-pages分支，然后就可以在 yourname.github.com/repo 地址查看gh-pages的页面了。
# 如何删除仓库
	给你翻译一下 On GitHub, navigate to the main page of the repository. 去到你的仓库的主页 In the repository's right sidebar, click  Settings. 在右边的工具栏点击设置 Under Danger Zone, click Delete this repository. 选择危险操作,点击删除仓库 To verify that you're deleting the correct repository, type the name of the repository you want to delete. 有个弹出会让你确认是不是要删除这个仓库 Click I understand the consequences, delete this repository. 点击 I understand the consequences, delete this repository.这段内容.删除完毕 下面是截图:     这里让你输入一下仓库的名称确认一下  然后我自己试验了一下  成功删除

# Bash是什么操作系统的命令
	 liux
# Pwd是什么命令
	显示工作目录的路径名称
# Cd是什么命令
	改变目录
增加参数
# Echo是什么命令
	打印输出 
# 配置git用户名的命令
	git config --global user.name "youname"

# 配置邮箱的命令
	git config --global user.email "youeamil@email.com"
# 命令行换行方式
	\
# 命令行终结方式
	Ctrl+c
# 使用命令行比GUI方式有何优势
	命令行有些独特的好处：
一是错误提示非常详细，详细到你知道错哪了，正确的用法是什么，一来二去很快就能熟悉
二是写自动化脚本的时候，只能用命令行啊，比如自动测试和部署脚本，无论是shell脚本还是py脚本，GUI没法用的
提交到本地仓库时为什么有暂存区
	可以使多个文件分批提交，方便更改个别提交
# 新建代码仓库的命令
	git init
# git clone [url] 这个命令的作用是
	复制到指定文件夹
# 16.添加指定文件到暂存区的命令
git add 文件
# 17.删除工作区文件，并且将这次删除放入暂存区的命令
Git rm 文件
# 18.改名文件，并且将这个改名文件放入暂存区的命令
  Git mv 文件
# 19.提交暂存区到仓库的命令
Git commit - m
# 20.直接从工作区提交到仓库的命令
Git commit –a-m
# 显示变更信息的命令
	git 
# 查看历史信息的命令
	git fetch
# Commit的意义是
	comiit 是n将本地修改保存到本地仓库中
# Pull的意义是
	取回远程主机某个分支的更新,再与本地的指定分支合并。
# Push的意义是
	将本地仓库修改推送到服务器上
	
# markdown 是什么

Markdown是一种可以使用普通文本编辑器编写的标记语言，通过简单的标记语法，它可以使普通文本内容具有一定的格式。

# markdown的特点
纯文本内容，兼容所有的文本编辑器与字处理软件
可以放到版本管理系统中，追踪历史变更
轻松导出HTML，PDF和本身的.md文件
简介，高效，可读，直观，学习成本低
专注你的文字内容而不是排版样式，安心写作


# markdown的用途
IT人士：写日志，技术文稿，记录代码片段，撰写文档
科研人员/学生：撰写科技论文，记笔记
求职者：制作求职简历
其他：撰写博文，在线编辑文章

# markdown的编辑工具有哪些
Mac OS X：Mou，ulysses,haroopad
Windows：Markdownpad，Markpad
Linux：Retext
web：简书，GitHub，有道云笔记

# markdown的区块元素和区段元素分别是哪些

段落与换行，标题，区块引用，列表，代码区块，分隔线

连接，强调，行内标记，图片，
