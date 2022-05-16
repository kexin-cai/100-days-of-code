# #100DaysOfCode Log - Round 1 - [Mr. Cai]

The log of my #100DaysOfCode challenge. Started on [May 13, Friday, 2022].
100 天编程调整记录。从 22 年五月 13 号开始。

## 计划

- 学习 V 语言
- 学习使用 neovim
- 配置 Emacs
- 写一个 cad 简单图形程序

## Log 记录

### R1D1 第一天

#### 给 Emacs 建立写 md 文档的设置

- 办公室环境是 wsl+arch

org 文件比较熟悉，现在准备改写 md 了，要学习一些新的东西。
还有要给选择是写 org 文件，把 md 改成 org。
先看看 md 怎么样吧。

- 结果是不太想学习 Emacs 了，准备拥抱 vim 怀抱了

- 在 arch 系统里 安装了 ssh 生成了 GitHub 的密钥，发到了 GitHub 网站，这样这个系统就可以 push 了。

#### 继续学习 neovim

nvchad: https://nvchad.github.io/getting-started/setup - 熟悉 lua 语法
  https://www.bilibili.com/video/BV1QL4y147VD?p=3
- 学习快捷键的设定
  应该是 nvim 的第三课，nvim from scratch 系列教程。
  keymap

### R1D2 第二天

- 在拉取的时候 git 给出提示需要设定拉取的默认规则，在本地仓库里给出设定为 rebase=false，意思是直接合并。
- 继续学习 nvim 入门教程

时间：+1h

- 继续学习 nvim：第四天的课程，是讲解插件的管理，使用的是 packer。
- 拖延症的四种表现。有一项就是准备工作。正如我在做的东西，也可以算作是一种拖延吧。

### R1D3 第三天

- 继续学习配置 nvim：今天是主题颜色，视频时长 16 分钟，
- 看了一会儿，mac M1 芯片的电脑虚拟化的教程，推荐使用 UTM 安装了软件，试了下 arch 不成功。
- 浏览 HN， 看了第三、四、五代编程语言。
- 一个网站，给初学者教授全栈的个人网站，https://thefullstackdev.net/
- 一个个人网站，只使用 html 来写， https://bjhess.com/ 可以学一下，很简单的
- 昨天看了一篇文章，一个大牛的写的关于 web 网页的糟点，认为应该重新考虑 web 的发展，从头来做。https://macwright.com/2020/08/22/clean-starts-for-the-web.html，这个网站， 看了作者是一个很厉害的人物。

### R1D4 第四天

- nvim 自动完成设置。
- 安装 org 插件
 发现了问题： 无法安装orgmode.nvim 的插件。报错是没有cc clang等的编译器。
 开始安装gcc12.1 居然没有gcc的安装我晕了。
 安装了 base-devel
 - 终于搞好了，原来是需要编译的。
