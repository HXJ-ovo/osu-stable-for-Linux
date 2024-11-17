# 适用于Linux的osu!stable
简体中文 [繁体中文](/Chinese_Traditional.md) [English](/English.md)

## 介绍
使用一键脚本来用Wine来在Linux上游玩osu!stable

## 注意
**1. 安装前你可能需要检查当前显卡是否开启了32位支持（sudo dpkg --add-architecture i386）<br><br>2. 在Deepin V20上您可能需要使用deepin-wine5运行osu!stable以避免编辑器顶栏黑条问题<br><br>3. GDI+可能会因为网络问题而安装失败**


## 依赖
* git（用于克隆仓库）
* wine（用于运行osu!stable）
* winetricks（安装GDI+等）
* zenity（创建对话框）
* unzip（如果要从sayobot下载）
* cabextract（如果要安装GDI+）

## 安装

将以下命令粘贴到终端中\
`git clone https://gitee.com/Mei_Hao_Xuan/osu_stable_for_-linux.git && cd osu_stable_for_Linux && chmod +x ./Install.sh && ./Install.sh`

如果此命令无法使用，请使用\
`git clone https://github.com/HXJ-ovo/osu_stable_for_Linux.git && cd osu_stable_for_Linux && chmod +x ./Install.sh && ./Install.sh`

## 还没解决的问题
- [ ] 或许可以试试用`Noto Sans CJK`来代替`WenQuanYi Micro Hei`
- [ ] 解决泰文不显示, 显示为方框的问题 (*需要帮助: 找不到字体, 网上查不到, 用Tahoma也不显示*)
