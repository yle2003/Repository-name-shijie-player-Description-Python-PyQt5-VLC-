# Repository-name-shijie-player-Description-Python-PyQt5-VLC-
这是我制作的第一款软件。集合了播放音乐，视频，电视节目为一体的播放器。
# 视界播放器 (Vision Player)

---

# 软件界面
<img width="1000" height="600" alt="aa398e60a7172e7fcb3f34b933ee5580" src="https://github.com/user-attachments/assets/03f43a26-37c5-405a-9c99-92198ed531dc" />
<img width="1000" height="600" alt="2e1323c471a53dffe5bbc75ea799d369" src="https://github.com/user-attachments/assets/7823b272-ef38-42dc-99c3-2f5b244fed5c" />
一款基于 **Python + PyQt5 + VLC** 开发的桌面视频播放器。
支持 **本地视频、音乐播放、IPTV电视直播以及播放列表管理**。

界面简洁，操作方便，双击即可运行。

---

# 项目简介

**视界播放器** 是一个使用 Python 开发的桌面媒体播放器项目。

该播放器通过 **PyQt5 构建图形界面**，并使用 **VLC 媒体引擎**进行视频解码播放，
支持多种媒体格式，并能够播放 **IPTV电视直播（m3u播放列表）**。

本项目主要目标：

* 构建一个轻量级桌面播放器
* 学习 Python GUI 开发
* 实现 IPTV 电视播放
* 设计播放器架构


---

# 功能特点

* 🎬 支持本地视频播放
* 🎵 支持音乐播放
* 📺 支持 IPTV 电视直播（m3u文件）
* 📂 支持播放列表管理
* ⏩ 支持播放进度条控制
* 🔊 支持音量调节
* ⌨️ 支持快捷键操作
* 📁 支持打开本地媒体文件
* 🧩 支持大部分视频格式
* 🚀 exe版本双击即可运行（免安装）

---

# 支持格式

播放器基于 **VLC 引擎**，支持大多数常见媒体格式，例如：

* mp4
* mkv
* avi
* flv
* mp3
* m3u
* m3u8
* 网络视频流

---

# 技术架构

| 技术     | 说明      |
| ------ | ------- |
| Python | 核心开发语言  |
| PyQt5  | GUI界面开发 |
| VLC    | 视频播放引擎  |

---

# 运行方式

## 方式一：直接运行 exe

下载 **视界播放器.exe**

双击即可运行，无需安装。

---
## 快捷方式
空格键             播放/暂停
S                  停止
N                  下一
P                  上一
F                  全屏
up                 音量+
down               音量-
left               快退
right              快进
M                  静音
Ctrl+O             打开文件
L                  播放列表
Esc                退出
----

## 方式二：Python运行

安装依赖：

```
pip install PyQt5
pip install python-vlc
```

运行程序：

```
python main.py
```

---

# 使用方法

1. 打开播放器
2. 点击 **打开文件**
3. 选择视频或音乐文件
4. 点击 **播放**

如果播放电视直播：

1. 导入 **m3u播放列表**
2. 在播放列表中选择频道
3. 点击播放

---

# 项目结构示例

```
VisionPlayer
│
├─ main.py
├─ player.py
├─ icons
├─ playlist
├─ screenshot.png
├─ README.md
└─ requirements.txt
```

---

# 未来计划

* 支持字幕加载
* 支持倍速播放
* 支持视频截图
* 支持主题皮肤
* IPTV直播源自动检测
* 播放记录功能

---

# 开源协议

MIT License

---

# 作者

Vision Player Developer
