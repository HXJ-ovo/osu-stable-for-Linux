# 適用於Linux的osu!stable
[简体中文](/README.md) 繁体中文 [English](/English.md)

## 介紹

使用一鍵腳本來用Wine來在Linux上遊玩osu!stable

## 注意

**1. 安裝前你可能需要檢查當前顯卡是否開啟了32比特支持（sudo dpkg --add-architecture i386）<br><br>2. 在Deepin V20上您可能需要使用deepin-wine5運行osu！ stable以避免編輯器頂欄黑條問題<br><br>3. GDI+可能會因為網絡問題而安裝失敗**

## 依賴

* git（用於尅隆倉庫）

* wine（用於運行osu！stable）

* winetricks（安裝GDI+等）

* zenity（創建對話方塊）

* unzip（如果要從sayobot下載）

* cabextract（如果要安裝GDI+）

## 安裝

將以下命令粘貼到終端中\
`git clone https://github.com/HXJ-ovo/osu_stable_for_Linux.git && cd osu_stable_for_Linux && chmod +x ./ Install.sh && ./Install.sh`

## 還沒解决的問題

- [ ]或許可以試試用`Noto Sans CJK`來代替`WenQuanYi Micro Hei`

- [ ]解决泰文不顯示，顯示為方框的問題（*需要幫助：找不到字體，網上查不到，用Tahoma也不顯示*）
