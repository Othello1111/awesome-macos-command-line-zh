[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

[awesome-macos-command-line](https://github.com/herrbischoff/awesome-macos-command-line) 的中文翻译，翻译不妥的地方，欢迎提 issue 或者 pull request 。

翻译本教程，让我这个 Mac 小白大开眼界。

[在线预览地址](https://nusr.github.io/post/awesome-macos-command-line-zh/entry/)

> 精心为 OS X 挑选的 shell 命令和工具。
>
> _“You don’t have to know everything. You simply need to know where to find it when necessary.” (John Brunner)_

更多好用的终端工具，请参阅原作者的姐妹项目 [Awesome Command Line Apps](https://github.com/herrbischoff/awesome-command-line-apps)。

中文 | [English](https://github.com/herrbischoff/awesome-macos-command-line)

- [外形](#%E5%A4%96%E5%BD%A2)
  - [透明度](#%E9%80%8F%E6%98%8E%E5%BA%A6)
    - [菜单和窗口的透明度设置](#%E8%8F%9C%E5%8D%95%E5%92%8C%E7%AA%97%E5%8F%A3%E7%9A%84%E9%80%8F%E6%98%8E%E5%BA%A6%E8%AE%BE%E7%BD%AE)
  - [桌面背景](#%E6%A1%8C%E9%9D%A2%E8%83%8C%E6%99%AF)
    - [设置桌面背景](#%E8%AE%BE%E7%BD%AE%E6%A1%8C%E9%9D%A2%E8%83%8C%E6%99%AF)
- [应用](#%E5%BA%94%E7%94%A8)
  - [App Store](#app-store)
    - [列出所有从 App Store 下载的应用](#%E5%88%97%E5%87%BA%E6%89%80%E6%9C%89%E4%BB%8E-app-store-%E4%B8%8B%E8%BD%BD%E7%9A%84%E5%BA%94%E7%94%A8)
    - [显示调试菜单](#%E6%98%BE%E7%A4%BA%E8%B0%83%E8%AF%95%E8%8F%9C%E5%8D%95)
  - [苹果远程桌面](#%E8%8B%B9%E6%9E%9C%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2)
    - [唤醒手册](#%E5%94%A4%E9%86%92%E6%89%8B%E5%86%8C)
    - [唤醒和睡眠 ARD Agent 和 Helper](#%E5%94%A4%E9%86%92%E5%92%8C%E7%9D%A1%E7%9C%A0-ard-agent-%E5%92%8C-helper)
    - [开启和关闭远程桌面共享](#%E5%BC%80%E5%90%AF%E5%92%8C%E5%85%B3%E9%97%AD%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E5%85%B1%E4%BA%AB)
    - [删除苹果远程桌面设置](#%E5%88%A0%E9%99%A4%E8%8B%B9%E6%9E%9C%E8%BF%9C%E7%A8%8B%E6%A1%8C%E9%9D%A2%E8%AE%BE%E7%BD%AE)
  - [交流](#%E4%BA%A4%E6%B5%81)
    - [调试模式](#%E8%B0%83%E8%AF%95%E6%A8%A1%E5%BC%8F)
  - [Google](#google)
    - [卸载 Google 更新](#%E5%8D%B8%E8%BD%BD-google-%E6%9B%B4%E6%96%B0)
  - [iTunes](#itunes)
    - [键盘媒体健](#%E9%94%AE%E7%9B%98%E5%AA%92%E4%BD%93%E5%81%A5)
  - [邮件](#%E9%82%AE%E4%BB%B6)
    - [将附件显示为图标](#%E5%B0%86%E9%99%84%E4%BB%B6%E6%98%BE%E7%A4%BA%E4%B8%BA%E5%9B%BE%E6%A0%87)
    - [清空邮件索引](#%E6%B8%85%E7%A9%BA%E9%82%AE%E4%BB%B6%E7%B4%A2%E5%BC%95)
  - [Safari](#safari)
    - [改变默认字体](#%E6%94%B9%E5%8F%98%E9%BB%98%E8%AE%A4%E5%AD%97%E4%BD%93)
    - [开启开发者菜单以及网络检查](#%E5%BC%80%E5%90%AF%E5%BC%80%E5%8F%91%E8%80%85%E8%8F%9C%E5%8D%95%E4%BB%A5%E5%8F%8A%E7%BD%91%E7%BB%9C%E6%A3%80%E6%9F%A5)
    - [获取当前网页数据](#%E8%8E%B7%E5%8F%96%E5%BD%93%E5%89%8D%E7%BD%91%E9%A1%B5%E6%95%B0%E6%8D%AE)
    - [使用 Backspace/Delete 返回上一页](#%E4%BD%BF%E7%94%A8-backspacedelete-%E8%BF%94%E5%9B%9E%E4%B8%8A%E4%B8%80%E9%A1%B5)
  - [Sketch](#sketch)
    - [导出压缩 SVG](#%E5%AF%BC%E5%87%BA%E5%8E%8B%E7%BC%A9-svg)
  - [Skim](#skim)
    - [关闭自动加载弹窗](#%E5%85%B3%E9%97%AD%E8%87%AA%E5%8A%A8%E5%8A%A0%E8%BD%BD%E5%BC%B9%E7%AA%97)
  - [终端](#%E7%BB%88%E7%AB%AF)
    - [焦点跟随鼠标](#%E7%84%A6%E7%82%B9%E8%B7%9F%E9%9A%8F%E9%BC%A0%E6%A0%87)
  - [文本编辑](#%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91)
    - [将文本编辑设置为纯文本的默认打开方式 Use Plain Text Mode as Default](#%E5%B0%86%E6%96%87%E6%9C%AC%E7%BC%96%E8%BE%91%E8%AE%BE%E7%BD%AE%E4%B8%BA%E7%BA%AF%E6%96%87%E6%9C%AC%E7%9A%84%E9%BB%98%E8%AE%A4%E6%89%93%E5%BC%80%E6%96%B9%E5%BC%8F-use-plain-text-mode-as-default)
  - [Visual Studio Code](#visual-studio-code)
    - [解决 VSCode Vim 按键重复](#%E8%A7%A3%E5%86%B3-vscode-vim-%E6%8C%89%E9%94%AE%E9%87%8D%E5%A4%8D)
- [备份](#%E5%A4%87%E4%BB%BD)
  - [时间机器](#%E6%97%B6%E9%97%B4%E6%9C%BA%E5%99%A8)
    - [改变备份间隔](#%E6%94%B9%E5%8F%98%E5%A4%87%E4%BB%BD%E9%97%B4%E9%9A%94)
    - [本地备份](#%E6%9C%AC%E5%9C%B0%E5%A4%87%E4%BB%BD)
    - [防止时间机器提示将新的硬盘启动器作为本分卷](#%E9%98%B2%E6%AD%A2%E6%97%B6%E9%97%B4%E6%9C%BA%E5%99%A8%E6%8F%90%E7%A4%BA%E5%B0%86%E6%96%B0%E7%9A%84%E7%A1%AC%E7%9B%98%E5%90%AF%E5%8A%A8%E5%99%A8%E4%BD%9C%E4%B8%BA%E6%9C%AC%E5%88%86%E5%8D%B7)
    - [显示时间机器的日志](#%E6%98%BE%E7%A4%BA%E6%97%B6%E9%97%B4%E6%9C%BA%E5%99%A8%E7%9A%84%E6%97%A5%E5%BF%97)
    - [充电时切换备份](#%E5%85%85%E7%94%B5%E6%97%B6%E5%88%87%E6%8D%A2%E5%A4%87%E4%BB%BD)
    - [验证备份](#%E9%AA%8C%E8%AF%81%E5%A4%87%E4%BB%BD)
- [开发这](#%E5%BC%80%E5%8F%91%E8%BF%99)
  - [Vim](#vim)
    - [编译 Sane Vim](#%E7%BC%96%E8%AF%91-sane-vim)
    - [Neovim](#neovim)
  - [Xcode](#xcode)
    - [安装没有命令行工具的 Xcode](#%E5%AE%89%E8%A3%85%E6%B2%A1%E6%9C%89%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%B7%A5%E5%85%B7%E7%9A%84-xcode)
    - [删除所有不可用的模拟器](#%E5%88%A0%E9%99%A4%E6%89%80%E6%9C%89%E4%B8%8D%E5%8F%AF%E7%94%A8%E7%9A%84%E6%A8%A1%E6%8B%9F%E5%99%A8)
- [程序坞](#%E7%A8%8B%E5%BA%8F%E5%9D%9E)
    - [将最近使用的程序添加到程序坞](#%E5%B0%86%E6%9C%80%E8%BF%91%E4%BD%BF%E7%94%A8%E7%9A%84%E7%A8%8B%E5%BA%8F%E6%B7%BB%E5%8A%A0%E5%88%B0%E7%A8%8B%E5%BA%8F%E5%9D%9E)
    - [添加间隔符的无名文件夹](#%E6%B7%BB%E5%8A%A0%E9%97%B4%E9%9A%94%E7%AC%A6%E7%9A%84%E6%97%A0%E5%90%8D%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [添加空格](#%E6%B7%BB%E5%8A%A0%E7%A9%BA%E6%A0%BC)
    - [添加小空格](#%E6%B7%BB%E5%8A%A0%E5%B0%8F%E7%A9%BA%E6%A0%BC)
    - [根据用户最近的使用自动重排](#%E6%A0%B9%E6%8D%AE%E7%94%A8%E6%88%B7%E6%9C%80%E8%BF%91%E7%9A%84%E4%BD%BF%E7%94%A8%E8%87%AA%E5%8A%A8%E9%87%8D%E6%8E%92)
    - [图标弹跳](#%E5%9B%BE%E6%A0%87%E5%BC%B9%E8%B7%B3)
    - [锁住程序坞大小](#%E9%94%81%E4%BD%8F%E7%A8%8B%E5%BA%8F%E5%9D%9E%E5%A4%A7%E5%B0%8F)
    - [重置程序坞](#%E9%87%8D%E7%BD%AE%E7%A8%8B%E5%BA%8F%E5%9D%9E)
    - [改变程序坞大小](#%E6%94%B9%E5%8F%98%E7%A8%8B%E5%BA%8F%E5%9D%9E%E5%A4%A7%E5%B0%8F)
    - [滚动手势](#%E6%BB%9A%E5%8A%A8%E6%89%8B%E5%8A%BF)
    - [启用自动掩藏](#%E5%90%AF%E7%94%A8%E8%87%AA%E5%8A%A8%E6%8E%A9%E8%97%8F)
    - [设置自动显示和掩藏的延迟时间](#%E8%AE%BE%E7%BD%AE%E8%87%AA%E5%8A%A8%E6%98%BE%E7%A4%BA%E5%92%8C%E6%8E%A9%E8%97%8F%E7%9A%84%E5%BB%B6%E8%BF%9F%E6%97%B6%E9%97%B4)
    - [显示掩藏 APP 的图标](#%E6%98%BE%E7%A4%BA%E6%8E%A9%E8%97%8F-app-%E7%9A%84%E5%9B%BE%E6%A0%87)
    - [仅显示启动的应用程序图标](#%E4%BB%85%E6%98%BE%E7%A4%BA%E5%90%AF%E5%8A%A8%E7%9A%84%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F%E5%9B%BE%E6%A0%87)
- [文档](#%E6%96%87%E6%A1%A3)
    - [将文件转换为 HTML](#%E5%B0%86%E6%96%87%E4%BB%B6%E8%BD%AC%E6%8D%A2%E4%B8%BA-html)
- [文件、磁盘和卷](#%E6%96%87%E4%BB%B6%E7%A3%81%E7%9B%98%E5%92%8C%E5%8D%B7)
    - [创建一个空文件](#%E5%88%9B%E5%BB%BA%E4%B8%80%E4%B8%AA%E7%A9%BA%E6%96%87%E4%BB%B6)
    - [禁止突发动作感应](#%E7%A6%81%E6%AD%A2%E7%AA%81%E5%8F%91%E5%8A%A8%E4%BD%9C%E6%84%9F%E5%BA%94)
    - [弹出所有可安装的卷](#%E5%BC%B9%E5%87%BA%E6%89%80%E6%9C%89%E5%8F%AF%E5%AE%89%E8%A3%85%E7%9A%84%E5%8D%B7)
    - [修复文件权限](#%E4%BF%AE%E5%A4%8D%E6%96%87%E4%BB%B6%E6%9D%83%E9%99%90)
    - [设置启动卷](#%E8%AE%BE%E7%BD%AE%E5%90%AF%E5%8A%A8%E5%8D%B7)
    - [示所有附加的磁盘和分区](#%E7%A4%BA%E6%89%80%E6%9C%89%E9%99%84%E5%8A%A0%E7%9A%84%E7%A3%81%E7%9B%98%E5%92%8C%E5%88%86%E5%8C%BA)
    - [查看文件系统的使用率](#%E6%9F%A5%E7%9C%8B%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F%E7%9A%84%E4%BD%BF%E7%94%A8%E7%8E%87)
  - [APFS](#apfs)
    - [将卷从 HFS+ 转换为 APFS](#%E5%B0%86%E5%8D%B7%E4%BB%8E-hfs-%E8%BD%AC%E6%8D%A2%E4%B8%BA-apfs)
    - [创建新的 APFS 文件系统](#%E5%88%9B%E5%BB%BA%E6%96%B0%E7%9A%84-apfs-%E6%96%87%E4%BB%B6%E7%B3%BB%E7%BB%9F)
    - [创建快照](#%E5%88%9B%E5%BB%BA%E5%BF%AB%E7%85%A7)
    - [删除快照](#%E5%88%A0%E9%99%A4%E5%BF%AB%E7%85%A7)
    - [列出所有快照](#%E5%88%97%E5%87%BA%E6%89%80%E6%9C%89%E5%BF%AB%E7%85%A7)
    - [挂载快照](#%E6%8C%82%E8%BD%BD%E5%BF%AB%E7%85%A7)
  - [磁盘映像](#%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F)
    - [从文件内容创建磁盘映像](#%E4%BB%8E%E6%96%87%E4%BB%B6%E5%86%85%E5%AE%B9%E5%88%9B%E5%BB%BA%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F)
    - [将磁盘映像刻录为 DVD](#%E5%B0%86%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F%E5%88%BB%E5%BD%95%E4%B8%BA-dvd)
    - [禁止磁盘映像验证](#%E7%A6%81%E6%AD%A2%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F%E9%AA%8C%E8%AF%81)
    - [制作 OS X 启动卷](#%E5%88%B6%E4%BD%9C-os-x-%E5%90%AF%E5%8A%A8%E5%8D%B7)
    - [挂载磁盘映像](#%E6%8C%82%E8%BD%BD%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F)
    - [卸载磁盘映像](#%E5%8D%B8%E8%BD%BD%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F)
    - [将磁盘映像写入到卷中](#%E5%B0%86%E7%A3%81%E7%9B%98%E6%98%A0%E5%83%8F%E5%86%99%E5%85%A5%E5%88%B0%E5%8D%B7%E4%B8%AD)
- [访达](#%E8%AE%BF%E8%BE%BE)
  - [桌面](#%E6%A1%8C%E9%9D%A2)
    - [显示外部媒体](#%E6%98%BE%E7%A4%BA%E5%A4%96%E9%83%A8%E5%AA%92%E4%BD%93)
    - [显示内部媒体](#%E6%98%BE%E7%A4%BA%E5%86%85%E9%83%A8%E5%AA%92%E4%BD%93)
    - [显示可移动媒体](#%E6%98%BE%E7%A4%BA%E5%8F%AF%E7%A7%BB%E5%8A%A8%E5%AA%92%E4%BD%93)
    - [显示网络卷](#%E6%98%BE%E7%A4%BA%E7%BD%91%E7%BB%9C%E5%8D%B7)
  - [文件和文件夹](#%E6%96%87%E4%BB%B6%E5%92%8C%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [清除所有访问控制列表(ACLs)](#%E6%B8%85%E9%99%A4%E6%89%80%E6%9C%89%E8%AE%BF%E9%97%AE%E6%8E%A7%E5%88%B6%E5%88%97%E8%A1%A8acls)
    - [在访达掩藏文件夹](#%E5%9C%A8%E8%AE%BF%E8%BE%BE%E6%8E%A9%E8%97%8F%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [显示所有文件的扩展名](#%E6%98%BE%E7%A4%BA%E6%89%80%E6%9C%89%E6%96%87%E4%BB%B6%E7%9A%84%E6%89%A9%E5%B1%95%E5%90%8D)
    - [显示掩藏文件](#%E6%98%BE%E7%A4%BA%E6%8E%A9%E8%97%8F%E6%96%87%E4%BB%B6)
    - [删除保护标签](#%E5%88%A0%E9%99%A4%E4%BF%9D%E6%8A%A4%E6%A0%87%E7%AD%BE)
    - [在访达中显示全路径](#%E5%9C%A8%E8%AE%BF%E8%BE%BE%E4%B8%AD%E6%98%BE%E7%A4%BA%E5%85%A8%E8%B7%AF%E5%BE%84)
    - [取消隐藏用户文件夹](#%E5%8F%96%E6%B6%88%E9%9A%90%E8%97%8F%E7%94%A8%E6%88%B7%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [增加最近访问文件数量](#%E5%A2%9E%E5%8A%A0%E6%9C%80%E8%BF%91%E8%AE%BF%E9%97%AE%E6%96%87%E4%BB%B6%E6%95%B0%E9%87%8F)
  - [布局](#%E5%B8%83%E5%B1%80)
    - [显示退出访达按钮](#%E6%98%BE%E7%A4%BA%E9%80%80%E5%87%BA%E8%AE%BF%E8%BE%BE%E6%8C%89%E9%92%AE)
    - [平滑滚动](#%E5%B9%B3%E6%BB%91%E6%BB%9A%E5%8A%A8)
    - [橡皮筋滚动](#%E6%A9%A1%E7%9A%AE%E7%AD%8B%E6%BB%9A%E5%8A%A8)
    - [展开默认保存面板](#%E5%B1%95%E5%BC%80%E9%BB%98%E8%AE%A4%E4%BF%9D%E5%AD%98%E9%9D%A2%E6%9D%BF)
    - [桌面图标可见性](#%E6%A1%8C%E9%9D%A2%E5%9B%BE%E6%A0%87%E5%8F%AF%E8%A7%81%E6%80%A7)
    - [路径栏](#%E8%B7%AF%E5%BE%84%E6%A0%8F)
    - [滚动条可见性](#%E6%BB%9A%E5%8A%A8%E6%9D%A1%E5%8F%AF%E8%A7%81%E6%80%A7)
    - [状态栏](#%E7%8A%B6%E6%80%81%E6%A0%8F)
    - [默认保存到磁盘](#%E9%BB%98%E8%AE%A4%E4%BF%9D%E5%AD%98%E5%88%B0%E7%A3%81%E7%9B%98)
    - [当当前文件夹设置为默认搜索范围](#%E5%BD%93%E5%BD%93%E5%89%8D%E6%96%87%E4%BB%B6%E5%A4%B9%E8%AE%BE%E7%BD%AE%E4%B8%BA%E9%BB%98%E8%AE%A4%E6%90%9C%E7%B4%A2%E8%8C%83%E5%9B%B4)
    - [设置访达的默认文件夹](#%E8%AE%BE%E7%BD%AE%E8%AE%BF%E8%BE%BE%E7%9A%84%E9%BB%98%E8%AE%A4%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [设置侧边栏图标大小](#%E8%AE%BE%E7%BD%AE%E4%BE%A7%E8%BE%B9%E6%A0%8F%E5%9B%BE%E6%A0%87%E5%A4%A7%E5%B0%8F)
  - [元数据文件](#%E5%85%83%E6%95%B0%E6%8D%AE%E6%96%87%E4%BB%B6)
    - [禁止在网络卷创建元数据文件](#%E7%A6%81%E6%AD%A2%E5%9C%A8%E7%BD%91%E7%BB%9C%E5%8D%B7%E5%88%9B%E5%BB%BA%E5%85%83%E6%95%B0%E6%8D%AE%E6%96%87%E4%BB%B6)
    - [禁止在 USB 卷创建元数据文件](#%E7%A6%81%E6%AD%A2%E5%9C%A8-usb-%E5%8D%B7%E5%88%9B%E5%BB%BA%E5%85%83%E6%95%B0%E6%8D%AE%E6%96%87%E4%BB%B6)
  - [打开文件](#%E6%89%93%E5%BC%80%E6%96%87%E4%BB%B6)
    - [改变访达的工作文件夹](#%E6%94%B9%E5%8F%98%E8%AE%BF%E8%BE%BE%E7%9A%84%E5%B7%A5%E4%BD%9C%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [打开 URL](#%E6%89%93%E5%BC%80-url)
    - [打开文件](#%E6%89%93%E5%BC%80%E6%96%87%E4%BB%B6-1)
    - [打开应用程序](#%E6%89%93%E5%BC%80%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F)
    - [打开文件夹](#%E6%89%93%E5%BC%80%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [打开当前文件夹](#%E6%89%93%E5%BC%80%E5%BD%93%E5%89%8D%E6%96%87%E4%BB%B6%E5%A4%B9)
- [字体](#%E5%AD%97%E4%BD%93)
    - [清空当前用户字体缓存](#%E6%B8%85%E7%A9%BA%E5%BD%93%E5%89%8D%E7%94%A8%E6%88%B7%E5%AD%97%E4%BD%93%E7%BC%93%E5%AD%98)
    - [获取 SF Mono 字体](#%E8%8E%B7%E5%8F%96-sf-mono-%E5%AD%97%E4%BD%93)
- [函数](#%E5%87%BD%E6%95%B0)
- [硬件](#%E7%A1%AC%E4%BB%B6)
  - [蓝牙](#%E8%93%9D%E7%89%99)
  - [硬盘](#%E7%A1%AC%E7%9B%98)
    - [强制启用修剪](#%E5%BC%BA%E5%88%B6%E5%90%AF%E7%94%A8%E4%BF%AE%E5%89%AA)
  - [硬件信息](#%E7%A1%AC%E4%BB%B6%E4%BF%A1%E6%81%AF)
    - [列出所有硬件端口](#%E5%88%97%E5%87%BA%E6%89%80%E6%9C%89%E7%A1%AC%E4%BB%B6%E7%AB%AF%E5%8F%A3)
    - [剩余电池百分比](#%E5%89%A9%E4%BD%99%E7%94%B5%E6%B1%A0%E7%99%BE%E5%88%86%E6%AF%94)
    - [剩余电池时间](#%E5%89%A9%E4%BD%99%E7%94%B5%E6%B1%A0%E6%97%B6%E9%97%B4)
    - [显示已连接设备的 UDID](#%E6%98%BE%E7%A4%BA%E5%B7%B2%E8%BF%9E%E6%8E%A5%E8%AE%BE%E5%A4%87%E7%9A%84-udid)
    - [显示当前屏幕分辨率](#%E6%98%BE%E7%A4%BA%E5%BD%93%E5%89%8D%E5%B1%8F%E5%B9%95%E5%88%86%E8%BE%A8%E7%8E%87)
    - [显示 CPU 品牌信息](#%E6%98%BE%E7%A4%BA-cpu-%E5%93%81%E7%89%8C%E4%BF%A1%E6%81%AF)
  - [红外传感器](#%E7%BA%A2%E5%A4%96%E4%BC%A0%E6%84%9F%E5%99%A8)
  - [电池管理](#%E7%94%B5%E6%B1%A0%E7%AE%A1%E7%90%86)
    - [禁止电脑休眠](#%E7%A6%81%E6%AD%A2%E7%94%B5%E8%84%91%E4%BC%91%E7%9C%A0)
    - [显示所有电池设置](#%E6%98%BE%E7%A4%BA%E6%89%80%E6%9C%89%E7%94%B5%E6%B1%A0%E8%AE%BE%E7%BD%AE)
    - [15 分钟无活动后显示器睡眠](#15-%E5%88%86%E9%92%9F%E6%97%A0%E6%B4%BB%E5%8A%A8%E5%90%8E%E6%98%BE%E7%A4%BA%E5%99%A8%E7%9D%A1%E7%9C%A0)
    - [30 分钟无活动后显示器睡眠](#30-%E5%88%86%E9%92%9F%E6%97%A0%E6%B4%BB%E5%8A%A8%E5%90%8E%E6%98%BE%E7%A4%BA%E5%99%A8%E7%9D%A1%E7%9C%A0)
    - [检查系统睡眠剩余时间](#%E6%A3%80%E6%9F%A5%E7%B3%BB%E7%BB%9F%E7%9D%A1%E7%9C%A0%E5%89%A9%E4%BD%99%E6%97%B6%E9%97%B4)
    - [将系统睡眠剩余时间设置为 60 分钟](#%E5%B0%86%E7%B3%BB%E7%BB%9F%E7%9D%A1%E7%9C%A0%E5%89%A9%E4%BD%99%E6%97%B6%E9%97%B4%E8%AE%BE%E7%BD%AE%E4%B8%BA-60-%E5%88%86%E9%92%9F)
    - [完全关闭系统睡眠](#%E5%AE%8C%E5%85%A8%E5%85%B3%E9%97%AD%E7%B3%BB%E7%BB%9F%E7%9D%A1%E7%9C%A0)
    - [系统冻结时自动重启](#%E7%B3%BB%E7%BB%9F%E5%86%BB%E7%BB%93%E6%97%B6%E8%87%AA%E5%8A%A8%E9%87%8D%E5%90%AF)
    - [充电时显示铃声](#%E5%85%85%E7%94%B5%E6%97%B6%E6%98%BE%E7%A4%BA%E9%93%83%E5%A3%B0)
- [输入设备](#%E8%BE%93%E5%85%A5%E8%AE%BE%E5%A4%87)
  - [键盘](#%E9%94%AE%E7%9B%98)
    - [自动纠正](#%E8%87%AA%E5%8A%A8%E7%BA%A0%E6%AD%A3)
    - [全键盘访问](#%E5%85%A8%E9%94%AE%E7%9B%98%E8%AE%BF%E9%97%AE)
    - [按键重复](#%E6%8C%89%E9%94%AE%E9%87%8D%E5%A4%8D)
    - [按键重复频率](#%E6%8C%89%E9%94%AE%E9%87%8D%E5%A4%8D%E9%A2%91%E7%8E%87)
- [启动台](#%E5%90%AF%E5%8A%A8%E5%8F%B0)
    - [重设启动台布局](#%E9%87%8D%E8%AE%BE%E5%90%AF%E5%8A%A8%E5%8F%B0%E5%B8%83%E5%B1%80)
- [媒体](#%E5%AA%92%E4%BD%93)
  - [音频](#%E9%9F%B3%E9%A2%91)
    - [将音频文件转换为 iPhone 铃声。](#%E5%B0%86%E9%9F%B3%E9%A2%91%E6%96%87%E4%BB%B6%E8%BD%AC%E6%8D%A2%E4%B8%BA-iphone-%E9%93%83%E5%A3%B0)
    - [从文本创建音频书](#%E4%BB%8E%E6%96%87%E6%9C%AC%E5%88%9B%E5%BB%BA%E9%9F%B3%E9%A2%91%E4%B9%A6)
    - [开机禁用声音](#%E5%BC%80%E6%9C%BA%E7%A6%81%E7%94%A8%E5%A3%B0%E9%9F%B3)
    - [静音音频输出](#%E9%9D%99%E9%9F%B3%E9%9F%B3%E9%A2%91%E8%BE%93%E5%87%BA)
    - [设置音量](#%E8%AE%BE%E7%BD%AE%E9%9F%B3%E9%87%8F)
    - [播放音频文件](#%E6%92%AD%E6%94%BE%E9%9F%B3%E9%A2%91%E6%96%87%E4%BB%B6)
    - [使用系统默认声音讲述文本](#%E4%BD%BF%E7%94%A8%E7%B3%BB%E7%BB%9F%E9%BB%98%E8%AE%A4%E5%A3%B0%E9%9F%B3%E8%AE%B2%E8%BF%B0%E6%96%87%E6%9C%AC)
  - [视频](#%E8%A7%86%E9%A2%91)
    - [QuickTime 自动播放视频](#quicktime-%E8%87%AA%E5%8A%A8%E6%92%AD%E6%94%BE%E8%A7%86%E9%A2%91)
- [网络](#%E7%BD%91%E7%BB%9C)
  - [Bonjour](#bonjour)
    - [Bonjour 服务](#bonjour-%E6%9C%8D%E5%8A%A1)
  - [DHCP](#dhcp)
    - [更新 DHCP 租约](#%E6%9B%B4%E6%96%B0-dhcp-%E7%A7%9F%E7%BA%A6)
    - [显示 DHCP 信息](#%E6%98%BE%E7%A4%BA-dhcp-%E4%BF%A1%E6%81%AF)
  - [DNS](#dns)
    - [清除 DNS 缓存](#%E6%B8%85%E9%99%A4-dns-%E7%BC%93%E5%AD%98)
  - [域名](#%E5%9F%9F%E5%90%8D)
    - [设置电脑域名](#%E8%AE%BE%E7%BD%AE%E7%94%B5%E8%84%91%E5%9F%9F%E5%90%8D)
  - [网络设置](#%E7%BD%91%E7%BB%9C%E8%AE%BE%E7%BD%AE)
    - [网络位置](#%E7%BD%91%E7%BB%9C%E4%BD%8D%E7%BD%AE)
    - [设置静态 IP 地址](#%E8%AE%BE%E7%BD%AE%E9%9D%99%E6%80%81-ip-%E5%9C%B0%E5%9D%80)
  - [网络工具](#%E7%BD%91%E7%BB%9C%E5%B7%A5%E5%85%B7)
    - [查看网络地址是否可以访问](#%E6%9F%A5%E7%9C%8B%E7%BD%91%E7%BB%9C%E5%9C%B0%E5%9D%80%E6%98%AF%E5%90%A6%E5%8F%AF%E4%BB%A5%E8%AE%BF%E9%97%AE)
    - [解决路由问题](#%E8%A7%A3%E5%86%B3%E8%B7%AF%E7%94%B1%E9%97%AE%E9%A2%98)
  - [SSH](#ssh)
    - [将私钥密码永久添加到 SSH 代理](#%E5%B0%86%E7%A7%81%E9%92%A5%E5%AF%86%E7%A0%81%E6%B0%B8%E4%B9%85%E6%B7%BB%E5%8A%A0%E5%88%B0-ssh-%E4%BB%A3%E7%90%86)
    - [远程登录](#%E8%BF%9C%E7%A8%8B%E7%99%BB%E5%BD%95)
  - [TCP/IP](#tcpip)
    - [显示使用特定端口的应用程序](#%E6%98%BE%E7%A4%BA%E4%BD%BF%E7%94%A8%E7%89%B9%E5%AE%9A%E7%AB%AF%E5%8F%A3%E7%9A%84%E5%BA%94%E7%94%A8%E7%A8%8B%E5%BA%8F)
    - [显示外部 IP 地址](#%E6%98%BE%E7%A4%BA%E5%A4%96%E9%83%A8-ip-%E5%9C%B0%E5%9D%80)
  - [TFTP](#tftp)
    - [启动原生的 TFTP Daemon](#%E5%90%AF%E5%8A%A8%E5%8E%9F%E7%94%9F%E7%9A%84-tftp-daemon)
  - [Wi-Fi](#wi-fi)
    - [加入 Wi-Fi 网络](#%E5%8A%A0%E5%85%A5-wi-fi-%E7%BD%91%E7%BB%9C)
    - [扫描可用的接入点](#%E6%89%AB%E6%8F%8F%E5%8F%AF%E7%94%A8%E7%9A%84%E6%8E%A5%E5%85%A5%E7%82%B9)
    - [显示当前的 SSID](#%E6%98%BE%E7%A4%BA%E5%BD%93%E5%89%8D%E7%9A%84-ssid)
    - [显示本地 IP 地址](#%E6%98%BE%E7%A4%BA%E6%9C%AC%E5%9C%B0-ip-%E5%9C%B0%E5%9D%80)
    - [显示 Wi-Fi 的连接历史](#%E6%98%BE%E7%A4%BA-wi-fi-%E7%9A%84%E8%BF%9E%E6%8E%A5%E5%8E%86%E5%8F%B2)
    - [显示 Wi-Fi 网络密码](#%E6%98%BE%E7%A4%BA-wi-fi-%E7%BD%91%E7%BB%9C%E5%AF%86%E7%A0%81)
    - [开启 Wi-Fi 适配器](#%E5%BC%80%E5%90%AF-wi-fi-%E9%80%82%E9%85%8D%E5%99%A8)
- [包管理器](#%E5%8C%85%E7%AE%A1%E7%90%86%E5%99%A8)
- [打印](#%E6%89%93%E5%8D%B0)
    - [清除打印队列](#%E6%B8%85%E9%99%A4%E6%89%93%E5%8D%B0%E9%98%9F%E5%88%97)
    - [默认展开打印面板](#%E9%BB%98%E8%AE%A4%E5%B1%95%E5%BC%80%E6%89%93%E5%8D%B0%E9%9D%A2%E6%9D%BF)
    - [打印完成后停止打印机](#%E6%89%93%E5%8D%B0%E5%AE%8C%E6%88%90%E5%90%8E%E5%81%9C%E6%AD%A2%E6%89%93%E5%8D%B0%E6%9C%BA)
- [安全](#%E5%AE%89%E5%85%A8)
  - [应用防火墙](#%E5%BA%94%E7%94%A8%E9%98%B2%E7%81%AB%E5%A2%99)
    - [防火墙服务](#%E9%98%B2%E7%81%AB%E5%A2%99%E6%9C%8D%E5%8A%A1)
    - [将应用添加到防火墙](#%E5%B0%86%E5%BA%94%E7%94%A8%E6%B7%BB%E5%8A%A0%E5%88%B0%E9%98%B2%E7%81%AB%E5%A2%99)
  - [网关](#%E7%BD%91%E5%85%B3)
    - [添加网关异常](#%E6%B7%BB%E5%8A%A0%E7%BD%91%E5%85%B3%E5%BC%82%E5%B8%B8)
    - [删除网关异常](#%E5%88%A0%E9%99%A4%E7%BD%91%E5%85%B3%E5%BC%82%E5%B8%B8)
    - [管理网关](#%E7%AE%A1%E7%90%86%E7%BD%91%E5%85%B3)
  - [密码](#%E5%AF%86%E7%A0%81)
    - [产生安全的密码并且复制到剪贴板](#%E4%BA%A7%E7%94%9F%E5%AE%89%E5%85%A8%E7%9A%84%E5%AF%86%E7%A0%81%E5%B9%B6%E4%B8%94%E5%A4%8D%E5%88%B6%E5%88%B0%E5%89%AA%E8%B4%B4%E6%9D%BF)
  - [物理访问](#%E7%89%A9%E7%90%86%E8%AE%BF%E9%97%AE)
    - [启动屏幕保护程序](#%E5%90%AF%E5%8A%A8%E5%B1%8F%E5%B9%95%E4%BF%9D%E6%8A%A4%E7%A8%8B%E5%BA%8F)
    - [锁屏](#%E9%94%81%E5%B1%8F)
    - [屏幕锁定](#%E5%B1%8F%E5%B9%95%E9%94%81%E5%AE%9A)
    - [屏幕保护密码](#%E5%B1%8F%E5%B9%95%E4%BF%9D%E6%8A%A4%E5%AF%86%E7%A0%81)
  - [擦除数据](#%E6%93%A6%E9%99%A4%E6%95%B0%E6%8D%AE)
    - [安全删除文件](#%E5%AE%89%E5%85%A8%E5%88%A0%E9%99%A4%E6%96%87%E4%BB%B6)
    - [安全删除文件夹](#%E5%AE%89%E5%85%A8%E5%88%A0%E9%99%A4%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [安全强制删除文件夹](#%E5%AE%89%E5%85%A8%E5%BC%BA%E5%88%B6%E5%88%A0%E9%99%A4%E6%96%87%E4%BB%B6%E5%A4%B9)
- [搜索](#%E6%90%9C%E7%B4%A2)
  - [查找](#%E6%9F%A5%E6%89%BE)
    - [递归删除 .DS_Store 文件](#%E9%80%92%E5%BD%92%E5%88%A0%E9%99%A4-dsstore-%E6%96%87%E4%BB%B6)
  - [定位](#%E5%AE%9A%E4%BD%8D)
    - [建立定位数据库](#%E5%BB%BA%E7%AB%8B%E5%AE%9A%E4%BD%8D%E6%95%B0%E6%8D%AE%E5%BA%93)
    - [通过定位查询](#%E9%80%9A%E8%BF%87%E5%AE%9A%E4%BD%8D%E6%9F%A5%E8%AF%A2)
- [系统](#%E7%B3%BB%E7%BB%9F)
  - [AirDrop](#airdrop)
  - [AppleScript](#applescript)
    - [执行 AppleScript](#%E6%89%A7%E8%A1%8C-applescript)
  - [基础](#%E5%9F%BA%E7%A1%80)
    - [比较两个文件夹](#%E6%AF%94%E8%BE%83%E4%B8%A4%E4%B8%AA%E6%96%87%E4%BB%B6%E5%A4%B9)
    - [复制较大文件显示进度条](#%E5%A4%8D%E5%88%B6%E8%BE%83%E5%A4%A7%E6%96%87%E4%BB%B6%E6%98%BE%E7%A4%BA%E8%BF%9B%E5%BA%A6%E6%9D%A1)
    - [修复疯狂 Shell](#%E4%BF%AE%E5%A4%8D%E7%96%AF%E7%8B%82-shell)
    - [重启](#%E9%87%8D%E5%90%AF)
    - [关机](#%E5%85%B3%E6%9C%BA)
    - [显示 OS 版本信息](#%E6%98%BE%E7%A4%BA-os-%E7%89%88%E6%9C%AC%E4%BF%A1%E6%81%AF)
    - [开机时间](#%E5%BC%80%E6%9C%BA%E6%97%B6%E9%97%B4)
  - [剪贴板](#%E5%89%AA%E8%B4%B4%E6%9D%BF)
    - [复制数据到剪贴板](#%E5%A4%8D%E5%88%B6%E6%95%B0%E6%8D%AE%E5%88%B0%E5%89%AA%E8%B4%B4%E6%9D%BF)
    - [将剪贴板数据转换为纯文本](#%E5%B0%86%E5%89%AA%E8%B4%B4%E6%9D%BF%E6%95%B0%E6%8D%AE%E8%BD%AC%E6%8D%A2%E4%B8%BA%E7%BA%AF%E6%96%87%E6%9C%AC)
    - [将剪贴板内容中的 Tab 转换为空格](#%E5%B0%86%E5%89%AA%E8%B4%B4%E6%9D%BF%E5%86%85%E5%AE%B9%E4%B8%AD%E7%9A%84-tab-%E8%BD%AC%E6%8D%A2%E4%B8%BA%E7%A9%BA%E6%A0%BC)
    - [复制剪贴板的数据](#%E5%A4%8D%E5%88%B6%E5%89%AA%E8%B4%B4%E6%9D%BF%E7%9A%84%E6%95%B0%E6%8D%AE)
    - [删除剪贴板重复内容以及排序](#%E5%88%A0%E9%99%A4%E5%89%AA%E8%B4%B4%E6%9D%BF%E9%87%8D%E5%A4%8D%E5%86%85%E5%AE%B9%E4%BB%A5%E5%8F%8A%E6%8E%92%E5%BA%8F)
  - [文件库](#%E6%96%87%E4%BB%B6%E5%BA%93)
    - [重启自动解锁文件库](#%E9%87%8D%E5%90%AF%E8%87%AA%E5%8A%A8%E8%A7%A3%E9%94%81%E6%96%87%E4%BB%B6%E5%BA%93)
    - [文件库服务](#%E6%96%87%E4%BB%B6%E5%BA%93%E6%9C%8D%E5%8A%A1)
  - [信息/报告](#%E4%BF%A1%E6%81%AF%E6%8A%A5%E5%91%8A)
    - [产生高级系统和性能报告](#%E4%BA%A7%E7%94%9F%E9%AB%98%E7%BA%A7%E7%B3%BB%E7%BB%9F%E5%92%8C%E6%80%A7%E8%83%BD%E6%8A%A5%E5%91%8A)
  - [安装系统](#%E5%AE%89%E8%A3%85%E7%B3%BB%E7%BB%9F)
    - [创建安装启动器](#%E5%88%9B%E5%BB%BA%E5%AE%89%E8%A3%85%E5%90%AF%E5%8A%A8%E5%99%A8)
  - [内核扩展](#%E5%86%85%E6%A0%B8%E6%89%A9%E5%B1%95)
    - [展示加载的内核扩展](#%E5%B1%95%E7%A4%BA%E5%8A%A0%E8%BD%BD%E7%9A%84%E5%86%85%E6%A0%B8%E6%89%A9%E5%B1%95)
    - [加载内核扩展](#%E5%8A%A0%E8%BD%BD%E5%86%85%E6%A0%B8%E6%89%A9%E5%B1%95)
    - [卸载内核扩展](#%E5%8D%B8%E8%BD%BD%E5%86%85%E6%A0%B8%E6%89%A9%E5%B1%95)
  - [自启动服务](#%E8%87%AA%E5%90%AF%E5%8A%A8%E6%9C%8D%E5%8A%A1)
  - [自启动服务](#%E8%87%AA%E5%90%AF%E5%8A%A8%E6%9C%8D%E5%8A%A1-1)
    - [重建自启动服务数据库](#%E9%87%8D%E5%BB%BA%E8%87%AA%E5%90%AF%E5%8A%A8%E6%9C%8D%E5%8A%A1%E6%95%B0%E6%8D%AE%E5%BA%93)
  - [登录窗口](#%E7%99%BB%E5%BD%95%E7%AA%97%E5%8F%A3)
    - [设置登录窗口文本](#%E8%AE%BE%E7%BD%AE%E7%99%BB%E5%BD%95%E7%AA%97%E5%8F%A3%E6%96%87%E6%9C%AC)
  - [内存管理](#%E5%86%85%E5%AD%98%E7%AE%A1%E7%90%86)
    - [清除内存缓存](#%E6%B8%85%E9%99%A4%E5%86%85%E5%AD%98%E7%BC%93%E5%AD%98)
    - [显示内存统计](#%E6%98%BE%E7%A4%BA%E5%86%85%E5%AD%98%E7%BB%9F%E8%AE%A1)
  - [通知中心](#%E9%80%9A%E7%9F%A5%E4%B8%AD%E5%BF%83)
    - [通知中心服务](#%E9%80%9A%E7%9F%A5%E4%B8%AD%E5%BF%83%E6%9C%8D%E5%8A%A1)
  - [快速浏览](#%E5%BF%AB%E9%80%9F%E6%B5%8F%E8%A7%88)
    - [快速浏览文件](#%E5%BF%AB%E9%80%9F%E6%B5%8F%E8%A7%88%E6%96%87%E4%BB%B6)
  - [远程苹果事件](#%E8%BF%9C%E7%A8%8B%E8%8B%B9%E6%9E%9C%E4%BA%8B%E4%BB%B6)
  - [Root 用户](#root-%E7%94%A8%E6%88%B7)
  - [安全模式启动](#%E5%AE%89%E5%85%A8%E6%A8%A1%E5%BC%8F%E5%90%AF%E5%8A%A8)
  - [截图](#%E6%88%AA%E5%9B%BE)
    - [延迟截图](#%E5%BB%B6%E8%BF%9F%E6%88%AA%E5%9B%BE)
    - [保存截图到给定位置](#%E4%BF%9D%E5%AD%98%E6%88%AA%E5%9B%BE%E5%88%B0%E7%BB%99%E5%AE%9A%E4%BD%8D%E7%BD%AE)
    - [设置截图文件格式](#%E8%AE%BE%E7%BD%AE%E6%88%AA%E5%9B%BE%E6%96%87%E4%BB%B6%E6%A0%BC%E5%BC%8F)
    - [禁止截图阴影](#%E7%A6%81%E6%AD%A2%E6%88%AA%E5%9B%BE%E9%98%B4%E5%BD%B1)
    - [设置截图的默认文件名](#%E8%AE%BE%E7%BD%AE%E6%88%AA%E5%9B%BE%E7%9A%84%E9%BB%98%E8%AE%A4%E6%96%87%E4%BB%B6%E5%90%8D)
  - [软件安装](#%E8%BD%AF%E4%BB%B6%E5%AE%89%E8%A3%85)
    - [安装 PKG](#%E5%AE%89%E8%A3%85-pkg)
  - [软件更新](#%E8%BD%AF%E4%BB%B6%E6%9B%B4%E6%96%B0)
    - [更新所有可以更新的软件](#%E6%9B%B4%E6%96%B0%E6%89%80%E6%9C%89%E5%8F%AF%E4%BB%A5%E6%9B%B4%E6%96%B0%E7%9A%84%E8%BD%AF%E4%BB%B6)
    - [设置软件更新检查的时间间隔](#%E8%AE%BE%E7%BD%AE%E8%BD%AF%E4%BB%B6%E6%9B%B4%E6%96%B0%E6%A3%80%E6%9F%A5%E7%9A%84%E6%97%B6%E9%97%B4%E9%97%B4%E9%9A%94)
    - [显示所有可以更新的软件](#%E6%98%BE%E7%A4%BA%E6%89%80%E6%9C%89%E5%8F%AF%E4%BB%A5%E6%9B%B4%E6%96%B0%E7%9A%84%E8%BD%AF%E4%BB%B6)
    - [设置软件更新服务器](#%E8%AE%BE%E7%BD%AE%E8%BD%AF%E4%BB%B6%E6%9B%B4%E6%96%B0%E6%9C%8D%E5%8A%A1%E5%99%A8)
  - [软件版本](#%E8%BD%AF%E4%BB%B6%E7%89%88%E6%9C%AC)
    - [显示系统的版本号](#%E6%98%BE%E7%A4%BA%E7%B3%BB%E7%BB%9F%E7%9A%84%E7%89%88%E6%9C%AC%E5%8F%B7)
  - [聚焦](#%E8%81%9A%E7%84%A6)
    - [聚焦索引](#%E8%81%9A%E7%84%A6%E7%B4%A2%E5%BC%95)
    - [擦除聚焦索引并重建](#%E6%93%A6%E9%99%A4%E8%81%9A%E7%84%A6%E7%B4%A2%E5%BC%95%E5%B9%B6%E9%87%8D%E5%BB%BA)
    - [通过聚焦搜索](#%E9%80%9A%E8%BF%87%E8%81%9A%E7%84%A6%E6%90%9C%E7%B4%A2)
    - [显示聚焦索引元数据](#%E6%98%BE%E7%A4%BA%E8%81%9A%E7%84%A6%E7%B4%A2%E5%BC%95%E5%85%83%E6%95%B0%E6%8D%AE)
  - [系统完整性保护](#%E7%B3%BB%E7%BB%9F%E5%AE%8C%E6%95%B4%E6%80%A7%E4%BF%9D%E6%8A%A4)
    - [禁止系统完整性保护](#%E7%A6%81%E6%AD%A2%E7%B3%BB%E7%BB%9F%E5%AE%8C%E6%95%B4%E6%80%A7%E4%BF%9D%E6%8A%A4)
    - [开启系统完整性保护](#%E5%BC%80%E5%90%AF%E7%B3%BB%E7%BB%9F%E5%AE%8C%E6%95%B4%E6%80%A7%E4%BF%9D%E6%8A%A4)
  - [时间和日期](#%E6%97%B6%E9%97%B4%E5%92%8C%E6%97%A5%E6%9C%9F)
    - [列出所有时区](#%E5%88%97%E5%87%BA%E6%89%80%E6%9C%89%E6%97%B6%E5%8C%BA)
    - [设置时区](#%E8%AE%BE%E7%BD%AE%E6%97%B6%E5%8C%BA)
    - [网络时间设置时钟](#%E7%BD%91%E7%BB%9C%E6%97%B6%E9%97%B4%E8%AE%BE%E7%BD%AE%E6%97%B6%E9%92%9F)
- [终端](#%E7%BB%88%E7%AB%AF-1)
    - [Ring Terminal Bell](#ring-terminal-bell)
  - [替代终端](#%E6%9B%BF%E4%BB%A3%E7%BB%88%E7%AB%AF)
  - [Shells](#shells)
    - [Bash](#bash)
    - [fish](#fish)
    - [Zsh](#zsh)
  - [终端字体](#%E7%BB%88%E7%AB%AF%E5%AD%97%E4%BD%93)
- [词汇表](#%E8%AF%8D%E6%B1%87%E8%A1%A8)
  - [Mac OS X、OS X 以及 macOS 的版本信息](#mac-os-xos-x-%E4%BB%A5%E5%8F%8A-macos-%E7%9A%84%E7%89%88%E6%9C%AC%E4%BF%A1%E6%81%AF)
- [License](#license)

## 外形

### 透明度

#### 菜单和窗口的透明度设置

```bash
# 减小透明度
defaults write com.apple.universalaccess reduceTransparency -bool true

# 恢复默认透明度
defaults write com.apple.universalaccess reduceTransparency -bool false
```

### 桌面背景

#### 设置桌面背景

```bash
# Up to Mountain Lion
osascript -e 'tell application "Finder" to set desktop picture to POSIX file "/path/to/picture.jpg"'

# Since Mavericks
sqlite3 ~/Library/Application\ Support/Dock/desktoppicture.db "update data set value = '/path/to/picture.jpg'" && killall Dock
```

## 应用

### App Store

#### 列出所有从 App Store 下载的应用

```bash
# 通过 find
find /Applications -path '*Contents/_MASReceipt/receipt' -maxdepth 4 -print |\sed 's#.app/Contents/_MASReceipt/receipt#.app#g; s#/Applications/##'

# 通过 Spotlight
mdfind kMDItemAppStoreHasReceipt=1
```

#### 显示调试菜单

Works up to Yosemite.

```bash
# 开启
defaults write com.apple.appstore ShowDebugMenu -bool true

# 关闭 (默认)
defaults write com.apple.appstore ShowDebugMenu -bool false
```

### 苹果远程桌面

#### 唤醒手册

```bash
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -help
```

#### 唤醒和睡眠 ARD Agent 和 Helper

```bash
# 激活并且重启 ARD Agent 和 Helper
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -activate -restart -agent -console

# 睡眠并且停止远程管理服务
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -stop
```

#### 开启和关闭远程桌面共享

```bash
# 给予所有用户完全的接入权限
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -configure -allowAccessFor -allUsers -privs -all

# 关闭 ARD Agent 和删除所有用户的接入权限
sudo /System/Library/CoreServices/RemoteManagement/ARDAgent.app/Contents/Resources/kickstart -deactivate -configure -access -off
```

#### 删除苹果远程桌面设置

```bash
sudo rm -rf /var/db/RemoteManagement ; \
sudo defaults delete /Library/Preferences/com.apple.RemoteDesktop.plist ; \
defaults delete ~/Library/Preferences/com.apple.RemoteDesktop.plist ; \
sudo rm -r /Library/Application\ Support/Apple/Remote\ Desktop/ ; \
rm -r ~/Library/Application\ Support/Remote\ Desktop/ ; \
rm -r ~/Library/Containers/com.apple.RemoteDesktop
```

### 交流

#### 调试模式

```bash
# 开启
defaults write com.apple.addressbook ABShowDebugMenu -bool true

# 关闭 (默认)
defaults write com.apple.addressbook ABShowDebugMenu -bool false
```

### Google

#### 卸载 Google 更新

```bash
~/Library/Google/GoogleSoftwareUpdate/GoogleSoftwareUpdate.bundle/Contents/Resources/ksinstall --nuke
```

### iTunes

#### 键盘媒体健

This works up to Yosemite. System Integrity Protection was introduced in El Capitan which prevents system Launch Agents from being unloaded.

```bash
# 停止响应按键
launchctl unload -w /System/Library/LaunchAgents/com.apple.rcd.plist

# 响应按键 (默认)
launchctl load -w /System/Library/LaunchAgents/com.apple.rcd.plist
```

From El Capitan onwards, you can either disable SIP or resort to a kind of hack, which will make iTunes inaccessible to any user, effectively preventing it from starting itself or its helpers. Be aware that for all intents and purposes this will trash your iTunes installation and may conflict with OS updates down the road.

```bash
sudo chmod 0000 /Applications/iTunes.app
```

### 邮件

#### 将附件显示为图标

```bash
defaults write com.apple.mail DisableInlineAttachmentViewing -bool yes
```

#### 清空邮件索引

下面的 AppleScript 代码将关闭邮件，清空 SQLite 索引，然后重新打开 Mail。在一个没有优化的大型电子邮件数据库中，可以显着提高响应速度。

```applescript
(*
Speed up Mail.app by vacuuming the Envelope Index
Code from: http://web.archive.org/web/20071008123746/http://www.hawkwings.net/2007/03/03/scripts-to-automate-the-mailapp-envelope-speed-trick/
Originally by "pmbuko" with modifications by Romulo
Updated by Brett Terpstra 2012
Updated by Mathias Törnblom 2015 to support V3 in El Capitan and still keep backwards compatibility
Updated by Andrei Miclaus 2017 to support V4 in Sierra
*)

tell application "Mail" to quit
set os_version to do shell script "sw_vers -productVersion"
set mail_version to "V2"
considering numeric strings
    if "10.10" <= os_version then set mail_version to "V3"
    if "10.12" <= os_version then set mail_version to "V4"
    if "10.13" <= os_version then set mail_version to "V5"
    if "10.14" <= os_version then set mail_version to "V6"
end considering

set sizeBefore to do shell script "ls -lnah ~/Library/Mail/" & mail_version & "/MailData | grep -E 'Envelope Index$' | awk {'print $5'}"
do shell script "/usr/bin/sqlite3 ~/Library/Mail/" & mail_version & "/MailData/Envelope\\ Index vacuum"

set sizeAfter to do shell script "ls -lnah ~/Library/Mail/" & mail_version & "/MailData | grep -E 'Envelope Index$' | awk {'print $5'}"

display dialog ("Mail index before: " & sizeBefore & return & "Mail index after: " & sizeAfter & return & return & "Enjoy the new speed!")

tell application "Mail" to activate
```

### Safari

#### 改变默认字体

```bash
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2StandardFontFamily Georgia
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFontSize 16
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2FixedFontFamily Menlo
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DefaultFixedFontSize 14
```

#### 开启开发者菜单以及网络检查

```bash
defaults write com.apple.Safari IncludeInternalDebugMenu -bool true && \
defaults write com.apple.Safari IncludeDevelopMenu -bool true && \
defaults write com.apple.Safari WebKitDeveloperExtrasEnabledPreferenceKey -bool true && \
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2DeveloperExtrasEnabled -bool true && \
defaults write -g WebKitDeveloperExtras -bool true
```

#### 获取当前网页数据

其他选项: `get source`, `get text`.

```bash
osascript -e 'tell application "Safari" to get URL of current tab of front window'
```

#### 使用 Backspace/Delete 返回上一页

```bash
# 开启
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool YES

# 关闭
defaults write com.apple.Safari com.apple.Safari.ContentPageGroupIdentifier.WebKit2BackspaceKeyNavigationEnabled -bool NO
```

### Sketch

#### 导出压缩 SVG

```bash
defaults write com.bohemiancoding.sketch3 exportCompactSVG -bool yes
```

### Skim

#### 关闭自动加载弹窗

去掉弹窗并设置默认自动加载

```bash
defaults write -app Skim SKAutoReloadFileUpdate -boolean true
```

### 终端

#### 焦点跟随鼠标

```bash
# 开启
defaults write com.apple.Terminal FocusFollowsMouse -string YES

# 关闭
defaults write com.apple.Terminal FocusFollowsMouse -string NO
```

### 文本编辑

#### 将文本编辑设置为纯文本的默认打开方式 Use Plain Text Mode as Default

```bash
defaults write com.apple.TextEdit RichText -int 0
```

### Visual Studio Code

#### 解决 VSCode Vim 按键重复

```bash
defaults write com.microsoft.VSCode ApplePressAndHoldEnabled -bool false
```

## 备份

### 时间机器

#### 改变备份间隔

备份间隔改为 30 分钟，单位是秒。

```bash
sudo defaults write /System/Library/LaunchDaemons/com.apple.backupd-auto StartInterval -int 1800
```

#### 本地备份

本地备份时，时间机器备份卷不可用。

```bash
# 查看状态
defaults read /Library/Preferences/com.apple.TimeMachine MobileBackups

# 开启 (默认)
sudo tmutil enablelocal

# 关闭
sudo tmutil disablelocal
```

Since High Sierra, you cannot disable local snapshots. Time Machine now always creates a local APFS snapshot and uses that snapshot as the data source to create a regular backup, rather than using the live disk as the source, as is the case with HFS formatted disks.

#### 防止时间机器提示将新的硬盘启动器作为本分卷

```bash
sudo defaults write /Library/Preferences/com.apple.TimeMachine DoNotOfferNewDisksForBackup -bool true
```

#### 显示时间机器的日志

这个脚本将输出过去 12 个小时时间机器的备份活动。

```bash
#!/bin/sh

filter='processImagePath contains "backupd" and subsystem beginswith "com.apple.TimeMachine"'

# show the last 12 hours
start="$(date -j -v-12H +'%Y-%m-%d %H:%M:%S')"

echo ""
echo "[History (from $start)]"
echo ""

log show --style syslog --info --start "$start" --predicate "$filter"

echo ""
echo "[Following]"
echo ""

log stream --style syslog --info --predicate "$filter"
```

#### 充电时切换备份

```bash
# 查看状态
sudo defaults read /Library/Preferences/com.apple.TimeMachine RequiresACPower

# 开启 (默认)
sudo defaults write /Library/Preferences/com.apple.TimeMachine RequiresACPower -bool true

# 关闭
sudo defaults write /Library/Preferences/com.apple.TimeMachine RequiresACPower -bool false
```

#### 验证备份

从 OS X 10.11 开始，时间机器记录文件校验和，并且复制到快照。 对于早期版本的 OS X，校验和不会复制到快照。

```bash
sudo tmutil verifychecksums /path/to/backup
```

## 开发这

### Vim

#### 编译 Sane Vim

通过 Homebrew 编译出完整 Mac Vim，包括覆盖系统的 Vim。

```bash
brew install macvim --HEAD --with-cscope --with-lua --with-override-system-vim --with-luajit --with-python
```

#### Neovim

通过 Homebrew 安装现代化的 Vim 替代品。

```bash
brew install neovim
```

### Xcode

#### 安装没有命令行工具的 Xcode

```bash
xcode-select --install
```

#### 删除所有不可用的模拟器

```bash
xcrun simctl delete unavailable
```

## 程序坞

#### 将最近使用的程序添加到程序坞

```bash
defaults write com.apple.dock persistent-others -array-add '{ "tile-data" = { "list-type" = 1; }; "tile-type" = "recents-tile"; }' && \
killall Dock
```

#### 添加间隔符的无名文件夹

```bash
defaults write com.apple.dock persistent-others -array-add '{ "tile-data" = {}; "tile-type"="small-spacer-tile"; }' && \
killall Dock
```

#### 添加空格

```bash
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}' && \
killall Dock
```

#### 添加小空格

```bash
defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="small-spacer-tile";}' && \
killall Dock
```

#### 根据用户最近的使用自动重排

```bash
# 开启 (默认)
defaults write com.apple.dock mru-spaces -bool true && \
killall Dock

# 关闭
defaults write com.apple.dock mru-spaces -bool false && \
killall Dock
```

#### 图标弹跳

全局设置当唤醒应用时，是否弹跳图标。

```bash
# 开启 (默认)
defaults write com.apple.dock no-bouncing -bool true && \
killall Dock

# 关闭
defaults write com.apple.dock no-bouncing -bool false && \
killall Dock
```

#### 锁住程序坞大小

```bash
# 开启
defaults write com.apple.Dock size-immutable -bool yes && \
killall Dock

# 关闭 (默认)
defaults write com.apple.Dock size-immutable -bool no && \
killall Dock
```

#### 重置程序坞

```bash
defaults delete com.apple.dock && \
killall Dock
```

#### 改变程序坞大小

完全改变程序坞主体大小。要调整大小，将 **0** 改为整数

```bash
defaults write com.apple.dock tilesize -int 0 && \
killall Dock
```

#### 滚动手势

使用触摸板或鼠标滚轮与程序坞进行交互，允许您使用向上滚动手势打开应用。正在运行的程序也可以使用相同的手势调用程序窗口管理。

```bash
# 开启
defaults write com.apple.dock scroll-to-open -bool true && \
killall Dock

# 关闭 (默认)
defaults write com.apple.dock scroll-to-open -bool false && \
killall Dock
```

#### 启用自动掩藏

```bash
defaults write com.apple.dock autohide -bool true && \
killall Dock
```

#### 设置自动显示和掩藏的延迟时间

浮点数定义了显示和掩藏的延迟时间(单位毫秒)。

```bash
defaults write com.apple.dock autohide-time-modifier -float 0.4 && \
defaults write com.apple.dock autohide-delay -float 0 && \
killall Dock
```

#### 显示掩藏 APP 的图标

```bash
# 开启
defaults write com.apple.dock showhidden -bool true && \
killall Dock

# 关闭 (默认)
defaults write com.apple.dock showhidden -bool false && \
killall Dock
```

#### 仅显示启动的应用程序图标

```bash
# 开启
defaults write com.apple.dock static-only -bool true && \
killall Dock

# 关闭 (默认)
defaults write com.apple.dock static-only -bool false && \
killall Dock
```

## 文档

#### 将文件转换为 HTML

支持的格式有纯文本、富文本(rtf)以及微软的 Word(doc/docx)。

```bash
textutil -convert html file.ext
```

## 文件、磁盘和卷

#### 创建一个空文件

创建一个 10 GB 的空文件。

```bash
mkfile 10g /path/to/file
```

#### 禁止突发动作感应

当你使用的是 SSD 时，这个设置是无用的。

```bash
sudo pmset -a sms 0
```

#### 弹出所有可安装的卷

唯一可以向访达发送 AppleScript 命令的方法。

```bash
osascript -e 'tell application "Finder" to eject (every disk whose ejectable is true)'
```

#### 修复文件权限

不依赖图形化磁盘工具修复文件权限。

```bash
sudo diskutil repairPermissions /
```

> 从 OS X El Capitan 开始，系统文件权限将自动受到保护。 不再需要使用磁盘工具验证或修复权限。([来源](https://support.apple.com/en-us/HT201560))

#### 设置启动卷

```bash
# Up to Yosemite
bless --mount "/path/to/mounted/volume" --setBoot

# From El Capitan
sudo systemsetup -setstartupdisk /System/Library/CoreServices
```

#### 示所有附加的磁盘和分区

```bash
diskutil list
```

#### 查看文件系统的使用率

连续显示文件使用信息。

```bash
sudo fs_usage
```

### APFS

从 High Sierra 开启，没有中央程序，并且使用不一致，因为大多数功能都被卷入到`tmutil`。

#### 将卷从 HFS+ 转换为 APFS

```bash
/System/Library/Filesystems/apfs.fs/Contents/Resources/hfs_convert /path/to/file/system
```

#### 创建新的 APFS 文件系统

```bash
/System/Library/Filesystems/apfs.fs/Contents/Resources/newfs_apfs /path/to/device
```

#### 创建快照

```bash
tmutil localsnapshot
```

#### 删除快照

```bash
tmutil deletelocalsnapshots com.apple.TimeMachine.2018-01-26-044042
```

#### 列出所有快照

```bash
tmutil listlocalsnapshots /
```

#### 挂载快照

快照是只读的。

```bash
mkdir ~/mnt
/System/Library/Filesystems/apfs.fs/Contents/Resources/mount_apfs -s com.apple.TimeMachine.2018-01-26-044042 / ~/mnt
```

### 磁盘映像

#### 从文件内容创建磁盘映像

将安装的应用程序转换为二进制包。

```bash
hdiutil create -volname "Volume Name" -srcfolder /path/to/folder -ov diskimage.dmg
```

如果你想加密磁盘映像：

```bash
hdiutil create -encryption -stdinpass -volname "Volume Name" -srcfolder /path/to/folder -ov encrypted.dmg
```

打包前，你要输入密码。为了直接输入密码不弹窗：

```bash
echo -n YourPassword | hdiutil create -encryption -stdinpass -volname "Volume Name" -srcfolder /path/to/folder -ov encrypted.dmg
```

#### 将磁盘映像刻录为 DVD

这个命令可以应用在 .iso 、.img 和 .dmg 文件上。

```bash
hdiutil burn /path/to/image_file
```

#### 禁止磁盘映像验证

```bash
defaults write com.apple.frameworks.diskimages skip-verify -bool true && \
defaults write com.apple.frameworks.diskimages skip-verify-locked -bool true && \
defaults write com.apple.frameworks.diskimages skip-verify-remote -bool true
```

#### 制作 OS X 启动卷

```bash
bless --folder "/path/to/mounted/volume/System/Library/CoreServices" --bootinfo --bootefi
```

#### 挂载磁盘映像

```bash
hdiutil attach /path/to/diskimage.dmg
```

#### 卸载磁盘映像

```bash
hdiutil detach /dev/disk2s1
```

#### 将磁盘映像写入到卷中

就像磁盘工具的恢复功能。

```bash
sudo asr -restore -noverify -source /path/to/diskimage.dmg -target /Volumes/VolumeToRestoreTo
```

## 访达

### 桌面

#### 显示外部媒体

外部的 HDs 、thumb drives 等等。

```bash
# 开启
defaults write com.apple.finder ShowExternalHardDrivesOnDesktop -bool true && \
killall Finder

# 关闭 (默认)
defaults write com.apple.finder ShowExternalHardDrivesOnDesktop -bool false && \
killall Finder
```

#### 显示内部媒体

自建的 HDs 或者 SSDs。

```bash
# 开启
defaults write com.apple.finder ShowHardDrivesOnDesktop -bool true && \
killall Finder

# 关闭 (默认)
defaults write com.apple.finder ShowHardDrivesOnDesktop -bool false && \
killall Finder
```

#### 显示可移动媒体

CDs 、DVDs 、iPods 等等。

```bash
# 开启
defaults write com.apple.finder ShowRemovableMediaOnDesktop -bool true && \
killall Finder

# 关闭 (默认)
defaults write com.apple.finder ShowRemovableMediaOnDesktop -bool false && \
killall Finder
```

#### 显示网络卷

AFP 、SMB、 NFS、 WebDAV 等等。

```bash
# 开启
defaults write com.apple.finder ShowMountedServersOnDesktop -bool true && \
killall Finder

# 关闭 (默认)
defaults write com.apple.finder ShowMountedServersOnDesktop -bool false && \
killall Finder
```

### 文件和文件夹

#### 清除所有访问控制列表(ACLs)

```bash
sudo chmod -RN /path/to/folder
```

#### 在访达掩藏文件夹

```bash
chflags hidden /path/to/folder/
```

#### 显示所有文件的扩展名

```bash
defaults write -g AppleShowAllExtensions -bool true
```

#### 显示掩藏文件

```bash
# 显示所有
defaults write com.apple.finder AppleShowAllFiles true

# 恢复文件的默认显示
defaults write com.apple.finder AppleShowAllFiles false
```

#### 删除保护标签

```bash
sudo chflags -R nouchg /path/to/file/or/folder
```

#### 在访达中显示全路径

```bash
defaults write com.apple.finder _FXShowPosixPathInTitle -bool true
```

#### 取消隐藏用户文件夹

```bash
chflags nohidden ~/Library
```

#### 增加最近访问文件数量

```bash
defaults write -g NSNavRecentPlacesLimit -int 10 && \
killall Finder
```

### 布局

#### 显示退出访达按钮

显示 退出访达的默认快捷键是 <kbd>Cmd</kbd> + <kbd>Q</kbd> 。

```bash
# 开启
defaults write com.apple.finder QuitMenuItem -bool true && \
killall Finder

# 关闭 (默认)
defaults write com.apple.finder QuitMenuItem -bool false && \
killall Finder
```

#### 平滑滚动

对旧 Mac 会弄乱动画很有用。

```bash
# 开启
defaults write -g NSScrollAnimationEnabled -bool false

# 关闭 (默认)
defaults write -g NSScrollAnimationEnabled -bool true
```

#### 橡皮筋滚动

```bash
# 禁止
defaults write -g NSScrollViewRubberbanding -bool false

# 关闭 (默认)
defaults write -g NSScrollViewRubberbanding -bool true
```

#### 展开默认保存面板

```bash
defaults write -g NSNavPanelExpandedStateForSaveMode -bool true && \
defaults write -g NSNavPanelExpandedStateForSaveMode2 -bool true
```

#### 桌面图标可见性

```bash
# 掩藏图标
defaults write com.apple.finder CreateDesktop -bool false && \
killall Finder

# 显示图标(默认)
defaults write com.apple.finder CreateDesktop -bool true && \
killall Finder
```

#### 路径栏

```bash
# 显示
defaults write com.apple.finder ShowPathbar -bool true

# 掩藏 (默认)
defaults write com.apple.finder ShowPathbar -bool false
```

#### 滚动条可见性

Possible values: `WhenScrolling`, `Automatic` and `Always`.

```bash
defaults write -g AppleShowScrollBars -string "Always"
```

#### 状态栏

```bash
# 显示
defaults write com.apple.finder ShowStatusBar -bool true

# 掩藏 (默认)
defaults write com.apple.finder ShowStatusBar -bool false
```

#### 默认保存到磁盘

设置默认保存地址是本地磁盘，而不是 iCloud 。

```bash
defaults write -g NSDocumentSaveNewDocumentsToCloud -bool false
```

#### 当当前文件夹设置为默认搜索范围

```bash
defaults write com.apple.finder FXDefaultSearchScope -string "SCcf"
```

#### 设置访达的默认文件夹

```bash
defaults write com.apple.finder NewWindowTarget -string "PfLo" && \
defaults write com.apple.finder NewWindowTargetPath -string "file://${HOME}"
```

#### 设置侧边栏图标大小

将大小设置为中等大小。

```bash
defaults write -g NSTableViewDefaultSizeMode -int 2
```

### 元数据文件

#### 禁止在网络卷创建元数据文件

避免创建 `.DS_Store` 以及 AppleDouble 文件。

```bash
defaults write com.apple.desktopservices DSDontWriteNetworkStores -bool true
```

#### 禁止在 USB 卷创建元数据文件

避免创建 `.DS_Store` 以及 AppleDouble 文件。

```bash
defaults write com.apple.desktopservices DSDontWriteUSBStores -bool true
```

### 打开文件

#### 改变访达的工作文件夹

如果同时打开了多个窗口，选择最上面。

```bash
cd "$(osascript -e 'tell app "Finder" to POSIX path of (insertion location as alias)')"
```

#### 打开 URL

```bash
open https://github.com
```

#### 打开文件

```bash
open README.md
```

#### 打开应用程序

你可以加上 `-a` 打开应用程序。

```bash
open -a "Google Chrome" https://github.com
```

#### 打开文件夹

```bash
open /path/to/folder/
```

#### 打开当前文件夹

```bash
open .
```

## 字体

#### 清空当前用户字体缓存

为了清除所有用户的字体缓存，在命令前加上 `sudo`。

```bash
atsutil databases -removeUser && \
atsutil server -shutdown && \
atsutil server -ping
```

#### 获取 SF Mono 字体

你需要先下载和安装 Xcode 8 beta，之后所有应用都可以使用。

```bash
cp -v /Applications/Xcode-beta.app/Contents/SharedFrameworks/DVTKit.framework/Versions/A/Resources/Fonts/SFMono-* ~/Library/Fonts
```

对于 Sierra 之前的版本，它们包含 Terminal.app 中。

```bash
cp -v /Applications/Utilities/Terminal.app/Contents/Resources/Fonts/SFMono-* ~/Library/Fonts
```

## 函数

请看 [这个文件](functions.md).

## 硬件

### 蓝牙

```bash
# 查看状态
defaults read /Library/Preferences/com.apple.Bluetooth ControllerPowerState

# 开启 (默认)
sudo defaults write /Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 1

# 禁止
sudo defaults write /Library/Preferences/com.apple.Bluetooth ControllerPowerState -int 0 && \
sudo killall -HUP blued
```

### 硬盘

#### 强制启用修剪

从 Yosemite 开始,可以开启非苹果 SSD 的修剪。

```bash
forcetrim
```

### 硬件信息

#### 列出所有硬件端口

```bash
networksetup -listallhardwareports
```

#### 剩余电池百分比

```bash
pmset -g batt | egrep "([0-9]+\%).*" -o --colour=auto | cut -f1 -d';'
```

#### 剩余电池时间

```bash
pmset -g batt | egrep "([0-9]+\%).*" -o --colour=auto | cut -f3 -d';'
```

#### 显示已连接设备的 UDID

```bash
system_profiler SPUSBDataType | sed -n -e '/iPad/,/Serial/p' -e '/iPhone/,/Serial/p'
```

#### 显示当前屏幕分辨率

```bash
system_profiler SPDisplaysDataType | grep Resolution
```

#### 显示 CPU 品牌信息

```bash
sysctl -n machdep.cpu.brand_string
```

### 红外传感器

```bash
# 查看状态
defaults read /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled

# 开启 (默认)
defaults write /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 1

# 关闭
defaults write /Library/Preferences/com.apple.driver.AppleIRController DeviceEnabled -int 0
```

### 电池管理

#### 禁止电脑休眠

一小时内不使用不睡眠。

```bash
caffeinate -u -t 3600
```

#### 显示所有电池设置

```bash
sudo pmset -g
```

#### 15 分钟无活动后显示器睡眠

```bash
sudo pmset displaysleep 15
```

#### 30 分钟无活动后显示器睡眠

```bash
sudo pmset sleep 30
```

#### 检查系统睡眠剩余时间

```bash
sudo systemsetup -getcomputersleep
```

#### 将系统睡眠剩余时间设置为 60 分钟

```bash
sudo systemsetup -setcomputersleep 60
```

#### 完全关闭系统睡眠

```bash
sudo systemsetup -setcomputersleep Never
```

#### 系统冻结时自动重启

```bash
sudo systemsetup -setrestartfreeze on
```

#### 充电时显示铃声

当 MagSafe 连接时，播放 IOS 充电声音。

```bash
# 开启
defaults write com.apple.PowerChime ChimeOnAllHardware -bool true && \
open /System/Library/CoreServices/PowerChime.app

# 关闭 (默认)
defaults write com.apple.PowerChime ChimeOnAllHardware -bool false && \
killall PowerChime
```

## 输入设备

### 键盘

#### 自动纠正

```bash
# 禁止
defaults write -g NSAutomaticSpellingCorrectionEnabled -bool false

# 开启 (默认)
defaults write -g NSAutomaticSpellingCorrectionEnabled -bool true

# 显示状态
defaults read -g NSAutomaticSpellingCorrectionEnabled
```

#### 全键盘访问

对话框启用 Tab 。

```bash
#  仅限文本框和列表 (默认)
defaults write NSGlobalDomain AppleKeyboardUIMode -int 0

# 所有控件
defaults write NSGlobalDomain AppleKeyboardUIMode -int 3
```

#### 按键重复

禁止默认的 "press and hold" 行为。

```bash
# 开启按键重复
defaults write -g ApplePressAndHoldEnabled -bool false

# 禁止按键重复
defaults write -g ApplePressAndHoldEnabled -bool true
```

#### 按键重复频率

设置非常快的按键频率，根据个人品味调整。

```bash
defaults write -g KeyRepeat -int 0.02
```

## 启动台

#### 重设启动台布局

你需要重启程序坞，因为启动台与它紧密相连。

```bash
# Yosemite 之前的版本
rm ~/Library/Application\ Support/Dock/*.db && \
killall Dock

# El Capitan及以上的版本
defaults write com.apple.dock ResetLaunchPad -bool true && \
killall Dock
```

## 媒体

### 音频

#### 将音频文件转换为 iPhone 铃声。

```bash
afconvert input.mp3 ringtone.m4r -f m4af
```

#### 从文本创建音频书

使用 **Alex** 声音，将单纯的 UTF-8 文本文件转换为 AAC。

```bash
say -v Alex -f file.txt -o "output.m4a"
```

#### 开机禁用声音

```bash
sudo nvram SystemAudioVolume=" "
```

#### 静音音频输出

```bash
osascript -e 'set volume output muted true'
```

#### 设置音量

```bash
osascript -e 'set volume 4'
```

#### 播放音频文件

你可以播放所有 QuickTime 支持的音频格式。

```bash
afplay -q 1 filename.mp3
```

#### 使用系统默认声音讲述文本

```bash
say 'All your base are belong to us!'
```

### 视频

#### QuickTime 自动播放视频

```bash
defaults write com.apple.QuickTimePlayerX MGPlayMovieOnOpen 1
```

## 网络

### Bonjour

#### Bonjour 服务

```bash
# 禁止
sudo defaults write /System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array-add "-NoMulticastAdvertisements"

# 开启 (默认)
sudo defaults write /System/Library/LaunchDaemons/com.apple.mDNSResponder.plist ProgramArguments -array "/usr/sbin/mDNSResponder" "-launchd"
```

### DHCP

#### 更新 DHCP 租约

```bash
sudo ipconfig set en0 DHCP
```

#### 显示 DHCP 信息

```bash
ipconfig getpacket en0
```

### DNS

#### 清除 DNS 缓存

```bash
sudo dscacheutil -flushcache && \
sudo killall -HUP mDNSResponder
```

### 域名

#### 设置电脑域名

```bash
sudo scutil --set ComputerName "newhostname" && \
sudo scutil --set HostName "newhostname" && \
sudo scutil --set LocalHostName "newhostname" && \
sudo defaults write /Library/Preferences/SystemConfiguration/com.apple.smb.server NetBIOSName -string "newhostname"
```

### 网络设置

#### 网络位置

在网络设置中切换网络位置。

```bash
# 查看状态
scselect

# 切换网络位置
scselect LocationNameFromStatus
```

#### 设置静态 IP 地址

```bash
networksetup -setmanual "Ethernet" 192.168.2.100 255.255.255.0 192.168.2.1
```

### 网络工具

#### 查看网络地址是否可以访问

```bash
ping -o github.com
```

#### 解决路由问题

```bash
traceroute github.com
```

### SSH

#### 将私钥密码永久添加到 SSH 代理

> 在 macOS Sierra 之前，ssh 会弹出输入密码的对话框，并提供是否将其存储到钥匙串的选项。 这个功能之后被删除。
>
> 在 macOS Sierra 中引入了 **UseKeychain** 选项，允许用户指定是否将密码存储在钥匙串中。 默认情况下，这个选项是开启的，这会导致所有密码都存储在钥匙串中。
>
> 这不是预期的默认行为，因此在 macOS 10.12.2 更改过来。（[来源]（https://developer.apple.com/library/archive/technotes/tn2449/_index.html））

```bash
ssh-add -K /path/to/private_key
```

Then add to `~/.ssh/config`:

```bash
Host server.example.com
    IdentityFile /path/to/private_key
    UseKeychain yes
```

#### 远程登录

```bash
# 开启远程登录
sudo launchctl load -w /System/Library/LaunchDaemons/ssh.plist

# 关闭远程登录
sudo launchctl unload -w /System/Library/LaunchDaemons/ssh.plist
```

### TCP/IP

#### 显示使用特定端口的应用程序

输出所有使用 80 端口的应用程序。

```bash
sudo lsof -i :80
```

#### 显示外部 IP 地址

仅当你的 ISP 没有替换 DNS 请求(一般不会)。

```bash
dig +short myip.opendns.com @resolver1.opendns.com
```

在所有网络中都可使用的替代方法。

```bash
curl -s https://api.ipify.org && echo
```

### TFTP

#### 启动原生的 TFTP Daemon

文件将从 `/private/tftpboot` 启动。

```bash
sudo launchctl load -F /System/Library/LaunchDaemons/tftp.plist && \
sudo launchctl start com.apple.tftpd
```

### Wi-Fi

#### 加入 Wi-Fi 网络

```bash
networksetup -setairportnetwork en0 WIFI_SSID WIFI_PASSWORD
```

#### 扫描可用的接入点

创建 airport 轻松接入的符号链接。

```bash
sudo ln -s /System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport /usr/local/bin/airport
```

运行无线扫描：

```bash
airport -s
```

#### 显示当前的 SSID

```bash
/System/Library/PrivateFrameworks/Apple80211.framework/Versions/Current/Resources/airport -I | awk '/ SSID/ {print substr($0, index($0, $2))}'
```

#### 显示本地 IP 地址

```bash
ipconfig getifaddr en0
```

#### 显示 Wi-Fi 的连接历史

```bash
defaults read /Library/Preferences/SystemConfiguration/com.apple.airport.preferences | grep LastConnected -A 7
```

#### 显示 Wi-Fi 网络密码

Exchange SSID with the SSID of the access point you wish to query the password from.

```bash
security find-generic-password -D "AirPort network password" -a "SSID" -gw
```

#### 开启 Wi-Fi 适配器

```bash
networksetup -setairportpower en0 on
```

## 包管理器

- [Fink](http://www.finkproject.org) - Unix 开源软件的全部 Darwin 世界，有点过时。
- [Homebrew](https://brew.sh) - OS X 缺少的包管理器，最流行的选择，我使用这个工具。
- [MacPorts](https://www.macports.org) - 基于 X11 、Aqua 的开源软件，编译、安装和升级命令行。 非常干净的工具，原作者使用它。

## 打印

#### 清除打印队列

```bash
cancel -a -
```

#### 默认展开打印面板

```bash
defaults write -g PMPrintingExpandedStateForPrint -bool true && \
defaults write -g PMPrintingExpandedStateForPrint2 -bool true
```

#### 打印完成后停止打印机

```bash
defaults write com.apple.print.PrintingPrefs "Quit When Finished" -bool true
```

## 安全

### 应用防火墙

#### 防火墙服务

```bash
# 查看状态
sudo /usr/libexec/ApplicationFirewall/socketfilterfw --getglobalstate

# 开启
sudo /usr/libexec/ApplicationFirewall/socketfilterfw --setglobalstate on

# 关闭 (默认)
sudo /usr/libexec/ApplicationFirewall/socketfilterfw --setglobalstate off
```

#### 将应用添加到防火墙

```bash
sudo /usr/libexec/ApplicationFirewall/socketfilterfw --add /path/to/file
```

### 网关

#### 添加网关异常

```bash
spctl --add /path/to/Application.app
```

#### 删除网关异常

```bash
spctl --remove /path/to/Application.app
```

#### 管理网关

```bash
# 查看状态
spctl --status

# 开启 (默认)
sudo spctl --master-enable

# 关闭
sudo spctl --master-disable
```

### 密码

#### 产生安全的密码并且复制到剪贴板

```bash
LC_ALL=C tr -dc "[:alnum:]" < /dev/urandom | head -c 20 | pbcopy
```

### 物理访问

#### 启动屏幕保护程序

```bash
# Sierra 之前
open /System/Library/Frameworks/ScreenSaver.framework/Versions/A/Resources/ScreenSaverEngine.app

# Sierra 之后
/System/Library/CoreServices/ScreenSaverEngine.app/Contents/MacOS/ScreenSaverEngine
```

#### 锁屏

```bash
/System/Library/CoreServices/Menu\ Extras/User.menu/Contents/Resources/CGSession -suspend
```

#### 屏幕锁定

```bash
# 查看状态
defaults read com.apple.screensaver askForPasswordDelay

# 开启 (默认)
defaults write com.apple.screensaver askForPasswordDelay -int 0

# 禁止 (Integer = 锁屏的延迟秒数)
defaults write com.apple.screensaver askForPasswordDelay -int 10
```

#### 屏幕保护密码

```bash
# 查看状态
defaults read com.apple.screensaver askForPassword

# 开启
defaults write com.apple.screensaver askForPassword -int 1

# 关闭 (默认)
defaults write com.apple.screensaver askForPassword -int 0
```

### 擦除数据

注意：在 MacOS 10.9 之后，**srm** 命令已经被删除了。 [Apple 支持页面]（https://support.apple.com/en-us/HT201949）解释了原因。

> 使用 SSD 驱动器时，磁盘工具中不提供安全擦除和擦除可用空间功能。 SSD 驱动器不需要这些选项，因为标准擦除使得难以从 SSD 恢复数据。

#### 安全删除文件

```bash
srm /path/to/file
```

#### 安全删除文件夹

```bash
srm -r /path/to/folder/
```

#### 安全强制删除文件夹

```bash
srm -rf /path/to/complete/destruction
```

## 搜索

### 查找

#### 递归删除 .DS_Store 文件

```bash
find . -type f -name '*.DS_Store' -ls -delete
```

### 定位

#### 建立定位数据库

```bash
sudo launchctl load -w /System/Library/LaunchDaemons/com.apple.locate.plist
```

#### 通过定位查询

`-i`修饰符意味着搜索对大小写敏感。

```bash
locate -i *.jpg
```

## 系统

### AirDrop

```bash
# 在 Ethernet 以上版本以及不支持的 Mac 版本，开启 AirDrop
defaults write com.apple.NetworkBrowser BrowseAllInterfaces -bool true

# 开启 (默认)
defaults remove com.apple.NetworkBrowser DisableAirDrop

# 关闭
defaults write com.apple.NetworkBrowser DisableAirDrop -bool YES
```

### AppleScript

#### 执行 AppleScript

```bash
osascript /path/to/script.scpt
```

### 基础

#### 比较两个文件夹

```bash
diff -qr /path/to/folder1 /path/to/folder2
```

#### 复制较大文件显示进度条

确定你已经安装了 `pv`，并且使用适当的写入设备或者文件替换了 `/dev/rdisk2`。

```bash
FILE=/path/to/file.iso pv -s $(du -h $FILE | awk '/.*/ {print $1}') $FILE | sudo dd of=/dev/rdisk2 bs=1m
```

#### 修复疯狂 Shell

如果你的 shell 会话疯狂。（比如某些脚本或应用程序将其变成乱码）。

```bash
stty sane
```

#### 重启

```bash
sudo reboot
```

#### 关机

```bash
sudo poweroff
```

#### 显示 OS 版本信息

```bash
sw_vers
```

#### 开机时间

显示上次开机到现在过去的时间。

```bash
uptime
```

### 剪贴板

#### 复制数据到剪贴板

```bash
cat whatever.txt | pbcopy
```

#### 将剪贴板数据转换为纯文本

```bash
pbpaste | textutil -convert txt -stdin -stdout -encoding 30 | pbcopy
```

#### 将剪贴板内容中的 Tab 转换为空格

```bash
pbpaste | expand | pbcopy
```

#### 复制剪贴板的数据

```bash
pbpaste > whatever.txt
```

#### 删除剪贴板重复内容以及排序

```bash
pbpaste | sort | uniq | pbcopy
```

### 文件库

#### 重启自动解锁文件库

如果在当前卷上启用了文件库，则会绕过初始解锁，重新启动系统。 该命令可能无法在所有版本上运行。

```bash
sudo fdesetup authrestart
```

#### 文件库服务

```bash
# 查看状态
sudo fdesetup status

# 开启
sudo fdesetup enable

# 禁止 (默认)
sudo fdesetup disable
```

### 信息/报告

#### 产生高级系统和性能报告

```bash
sudo sysdiagnose -f ~/Desktop/
```

### 安装系统

#### 创建安装启动器

```bash
# Mojave
sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --nointeraction --downloadassets

# High Sierra
sudo /Applications/Install\ macOS\ High\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ macOS\ High\ Sierra.app

# Sierra
sudo /Applications/Install\ macOS\ Sierra.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ macOS\ Sierra.app

# El Capitan
sudo /Applications/Install\ OS\ X\ El\ Capitan.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ OS\ X\ El\ Capitan.app

# Yosemite
sudo /Applications/Install\ OS\ X\ Yosemite.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ OS\ X\ Yosemite.app
```

- 删除驱动器之前进行确认，删去 `--nointeraction` 选项。
- Mojave 中才可以使用 `--downloadassets` 选项。 安装过程中可能会下载资源，比如更新。
- 从 Mojave 开始，`--applicationpath` 选项以及被废弃。使用该选项会抛出错误。

### 内核扩展

#### 展示加载的内核扩展

```bash
sudo kextstat -l
```

#### 加载内核扩展

```bash
sudo kextload -b com.apple.driver.ExampleBundle
```

#### 卸载内核扩展

```bash
sudo kextunload -b com.apple.driver.ExampleBundle
```

### 自启动服务

请看 [自启动服务](launchagents.md).

### 自启动服务

#### 重建自启动服务数据库

为了做到与 OS X 版本无关，这个工具依赖 `locate` 查找 `lsregister`。 如果你还没有建立你的 `locate` 数据库，[请先创建](#创建定位数据库)。

```bash
sudo $(locate lsregister) -kill -seed -r
```

### 登录窗口

#### 设置登录窗口文本

```bash
sudo defaults write /Library/Preferences/com.apple.loginwindow LoginwindowText "Your text"
```

### 内存管理

#### 清除内存缓存

```bash
sudo purge
```

#### 显示内存统计

```bash
# One time
vm_stat

# Table of data, repeat 10 times total, 1 second wait between each poll
vm_stat -c 10 1
```

### 通知中心

#### 通知中心服务

```bash
# 关闭
launchctl unload -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist && \
killall -9 NotificationCenter

# 启动 (默认)
launchctl load -w /System/Library/LaunchAgents/com.apple.notificationcenterui.plist
```

### 快速浏览

#### 快速浏览文件

```bash
qlmanage -p /path/to/file
```

### 远程苹果事件

```bash
# 查看状态
sudo systemsetup -getremoteappleevents

# 开启
sudo systemsetup -setremoteappleevents on

# 禁止 (默认)
sudo systemsetup -setremoteappleevents off
```

### Root 用户

```bash
# 开启
dsenableroot

# 禁止
dsenableroot -d
```

### 安全模式启动

```bash
# 查看状态
nvram boot-args

# 开启
sudo nvram boot-args="-x"

# 禁止
sudo nvram boot-args=""
```

### 截图

#### 延迟截图

3 秒后截图为 JPEG 文件，并且在预览中展示。

```bash
screencapture -T 3 -t jpg -P delayedpic.jpg
```

#### 保存截图到给定位置

设置保存地址为桌面。

```bash
defaults write com.apple.screencapture location ~/Desktop && \
killall SystemUIServer
```

#### 设置截图文件格式

设置截图文件格式为 `png`，可选的格式有 `bmp`, `gif`, `jpg`, `jpeg`, `pdf`, `tiff` 。

```bash
defaults write com.apple.screencapture type -string "png"
```

#### 禁止截图阴影

```bash
defaults write com.apple.screencapture disable-shadow -bool true && \
killall SystemUIServer
```

#### 设置截图的默认文件名

截图文件名的时间戳保持不变。

```bash
defaults write com.apple.screencapture name "Example name" && \
killall SystemUIServer
```

### 软件安装

#### 安装 PKG

```bash
installer -pkg /path/to/installer.pkg -target /
```

### 软件更新

#### 更新所有可以更新的软件

```bash
sudo softwareupdate -ia
```

#### 设置软件更新检查的时间间隔

将软件更新检查的时间间隔设置为天，而不是默认的周。

```bash
defaults write com.apple.SoftwareUpdate ScheduleFrequency -int 1
```

#### 显示所有可以更新的软件

```bash
sudo softwareupdate -l
```

#### 设置软件更新服务器

这仅适用于测试或非托管的客户端。 要在网络范围内使用，请正确设置 DNS 以及 [Apple SUS 服务](http://krypted.com/mac-security/using-the-software-update-service-on-mountain-lion-server/) 并通过 OpenDirectory 绑定客户端。 或者，使用 [Reposado](https://github.com/wdas/reposado) 正确设置网络 DNS，使分辨率变得透明。 [Margarita](https://github.com/jessepeterson/margarita) 看起来也不错。

```bash
# 使用自己 SUS
sudo defaults write /Library/Preferences/com.apple.SoftwareUpdate CatalogURL http://su.example.com:8088/index.sucatalog

# 恢复苹果的默认 SUS
sudo defaults delete /Library/Preferences/com.apple.SoftwareUpdate CatalogURL
```

### 软件版本

#### 显示系统的版本号

```bash
sw_vers -productVersion
```

### 聚焦

#### 聚焦索引

```bash
# 禁止
mdutil -i off -d /path/to/volume

# 关闭 (默认)
mdutil -i on /path/to/volume
```

#### 擦除聚焦索引并重建

```bash
mdutil -E /path/to/volume
```

#### 通过聚焦搜索

```bash
mdfind -name 'searchterm'
```

#### 显示聚焦索引元数据

```bash
mdls /path/to/file
```

### 系统完整性保护

#### 禁止系统完整性保护

Reboot while holding <kbd>Cmd</kbd> + <kbd>R</kbd>, open the Terminal application and enter:

```bash
csrutil disable && reboot
```

#### 开启系统完整性保护

Reboot while holding <kbd>Cmd</kbd> + <kbd>R</kbd>, open the Terminal application and enter:

```bash
csrutil enable && reboot
```

### 时间和日期

#### 列出所有时区

```bash
sudo systemsetup -listtimezones
```

#### 设置时区

```bash
sudo systemsetup -settimezone Europe/Berlin
```

#### 网络时间设置时钟

```bash
# 查看状态
sudo systemsetup getusingnetworktime

# 开启 (默认)
sudo systemsetup setusingnetworktime on

# 关闭
sudo systemsetup setusingnetworktime off
```

## 终端

#### Ring Terminal Bell

Rings the terminal bell (if enabled) and puts a badge on it.

```bash
tput bel
```

### 替代终端

- [iTerm2](https://iterm2.com) - A better Terminal.app.
- [kitty](https://sw.kovidgoyal.net/kitty/) - Modern, GPU-accelerated terminal emulator.

### Shells

#### Bash

安装最新版本的 Bash，并且设置为用户的默认的 shell

```bash
brew install bash && \
echo $(brew --prefix)/bin/bash | sudo tee -a /etc/shells && \
chsh -s $(brew --prefix)/bin/bash
```

- [Homepage](https://www.gnu.org/software/bash/) - OS X 以及 Unix 类似系统的默认 shell 。
- [Bash-it](https://github.com/Bash-it/bash-it) - 社区驱动 Bash 框架，类似 Oh My Zsh

#### fish

安装最新版本的 fish，并且设置为用户的默认的 shell

```bash
brew install fish && \
echo $(brew --prefix)/bin/fish | sudo tee -a /etc/shells && \
chsh -s $(brew --prefix)/bin/fish
```

- [Homepage](http://fishshell.com) - 一个对 OS X 、Linux 用户友好的智能 shell,支持更多系统。
- [The Fishshell Framework](https://github.com/oh-my-fish/oh-my-fish) - 提供核心基础结构，允许您扩展或修改 shell 外观的软件包。
- [Installation & Configuration Tutorial](https://github.com/ellerbrock/fish-shell-setup-osx) - 怎样通过 Fisherman、Powerline Fonts、 iTerm2 和 Budspencer Theme 安装 Fish Shell。

#### Zsh

安装最新版本的 Zsh，并且设置为用户的默认的 shell

```bash
brew install zsh && \
sudo sh -c 'echo $(brew --prefix)/bin/zsh >> /etc/shells' && \
chsh -s $(brew --prefix)/bin/zsh
```

- [Homepage](http://www.zsh.org) - 尽管 Zsh 是一种强大的脚本语言，它是专为交互式使用而设计的 shell。
- [Oh My Zsh](http://ohmyz.sh) - 社区驱动开源框架，用于管理 Zsh 配置。
- [Prezto](https://github.com/sorin-ionescu/prezto) - 一个快速的 Zsh 框架。 使用默认值，别名，函数，自动完成和主题来丰富命令行界面环境。
- [zgen](https://github.com/tarjoilija/zgen) - 另一个管理 Zsh 配置的开源框架。 Zgen 可以兼容 oh-my-zsh 的插件和主题，并且具有自动克隆任何插件以及更快的优点。

### 终端字体

- [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro) - 四种固定宽度系列字体，适用于编程。
- [Codeface](https://github.com/chrissimpkins/codeface) - 用于开发人员的图库和等宽字体库。
- [DejaVu Sans Mono](https://dejavu-fonts.github.io/) - 基于 Vera Fonts 的字体家族。
- [Hack](http://sourcefoundry.org/hack/) - Hack 手动整理字体，是你编程字体的首选。
- [Inconsolata](http://levien.com/type/myfonts/inconsolata.html) - 一种等宽字体，专为编程设计。
- [Input](http://input.fontbureau.com) - 专为编程响应系统的字体设计。
- [Meslo](https://github.com/andreberg/Meslo-Font) - Apple's Menlo 字体的自制版本.
- [Operator Mono](https://www.typography.com/fonts/operator/overview/) - 令人惊讶的商业等宽字体。
- [Powerline Fonts](https://github.com/powerline/fonts) - Powerline 插件的修补字体仓库
- [Source Code Pro](https://adobe-fonts.github.io/source-code-pro/) - 专为用户交互以及编程的等宽字体家族。

## 词汇表

### Mac OS X、OS X 以及 macOS 的版本信息

| 版本                       | 名称               | 发布日期           | 最新版本                              |
| -------------------------- | ------------------ | ------------------ | ------------------------------------- |
| Rhapsody Developer Release | Grail1Z4 / Titan1U | August 31, 1997    | DR2 (May 14, 1998)                    |
| Mac OS X Server 1.0        | Hera               | March 16, 1999     | 1.2v3 (October 27, 2000)              |
| Mac OS X Developer Preview | n/a                | March 16, 1999     | DP4 (April 5, 2000)                   |
| Mac OS X Public Beta       | Kodiak             | September 13, 2000 | n/a                                   |
| Mac OS X 10.0              | Cheetah            | March 24, 2001     | 10.0.4 (June 22, 2001)                |
| Mac OS X 10.1              | Puma               | September 25, 2001 | 10.1.5 (June 6, 2002)                 |
| Mac OS X 10.2              | Jaguar             | August 24, 2002    | 10.2.8 (October 3, 2003)              |
| Mac OS X 10.3              | Panther            | October 24, 2003   | 10.3.9 (April 15, 2005)               |
| Mac OS X 10.4              | Tiger              | April 29, 2005     | 10.4.11 (November 14, 2007)           |
| Mac OS X 10.5              | Leopard            | October 26, 2007   | 10.5.8 (August 5, 2009)               |
| Mac OS X 10.6              | Snow Leopard       | August 28, 2009    | 10.6.8 v1.1 (July 25, 2011)           |
| Mac OS X 10.7              | Lion               | July 20, 2011      | 10.7.5 (September 19, 2012)           |
| OS X 10.8                  | Mountain Lion      | July 25, 2012      | 10.8.5 (12F45) (October 3, 2013)      |
| OS X 10.9                  | Mavericks          | October 22, 2013   | 10.9.5 (13F1112) (September 18, 2014) |
| OS X 10.10                 | Yosemite           | October 16, 2014   | 10.10.5 (14F27) (August 13, 2015)     |
| OS X 10.11                 | El Capitan         | September 30, 2015 | 10.11.6 (15G31) (July 18, 2016)       |
| macOS 10.12                | Sierra             | September 20, 2016 | 10.12.6 (16G29) (July 19, 2017)       |
| macOS 10.13                | High Sierra        | September 25, 2017 | 10.13.6 (17G65) (July 9, 2018)        |
| macOS 10.14                | Mojave             | September 24, 2018 | 10.14 (18A391) (September 24, 2018)   |

## License

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
