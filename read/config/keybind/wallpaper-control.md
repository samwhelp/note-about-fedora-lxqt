---
title: 桌面圖片
nav_order: 5050
has_children: false
parent: 按鍵綁定
grand_parent: 設定
---


# 桌面圖片

* [設定片段](https://github.com/samwhelp/fedora-lxqt-adjustment/tree/main/prototype/main/lxqt-config/Main/asset/overlay/etc/skel/.config/openbox/helper/share/gen/openbox-gen-rc/Section/Keybind/Wallpaper.php#L3)

| 按鍵組合         | 功能                 | 執行指令                                         |
| ---------------- | -------------------- | ------------------------------------------------ |
| `Alt + w`        | 隨機更換新的桌面圖片 | `feh --bg-fill --randomize ~/Pictures/Wallpaper` |
| `Alt + Ctrl + w` | 更換成預設的桌面圖片 | `feh --bg-fill ~/Pictures/Wallpaper/default.jpg` |


## 參考連結

* Arch Wiki / [Feh](https://wiki.archlinux.org/title/Feh)
