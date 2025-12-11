# Pixiv Bookmark Slideshow

![Version](https://img.shields.io/badge/version-3.5.0-blue) ![License](https://img.shields.io/badge/license-MIT-green) ![GreasyFork](https://img.shields.io/badge/GreasyFork-Posted-red)

**[English](#english) | [简体中文](#简体中文)**

---

<a name="english"></a>

## 🇬🇧 English

**Pixiv Bookmark Slideshow** is a Userscript that adds a slideshow button to the Pixiv User Bookmarks page. It allows for seamless browsing of bookmarked illustrations with auto-loading of original quality images, tag filtering, and manga/group pagination.

### ✨ Key Features

- **📺 Seamless Slideshow:** Browse your bookmarks in a clean, overlay interface without opening new tabs.
- **⚡ Auto-Load Originals:** Automatically fetches and displays the highest quality (original) images.
- **📚 Manga & Group Support:** Full support for multi-page works (Manga/Image Sets). Browse individual pages within a work easily.
- **🏷️ Tag & Privacy Filtering:** Respects your current filter settings (Specific Tags, Public/Private bookmarks).
- **🚀 Smart Preloading:** Intelligently preloads next images and data blocks for a lag-free experience.
- **⌨️ Keyboard Shortcuts:** Full keyboard control for navigation and playback.
- **🌍 Multi-Language:** Supports English, Simplified Chinese, Traditional Chinese, and Japanese.

### 📥 Installation

1.  Install a userscript manager:
    - **Tampermonkey** (Recommended): [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [Firefox](https://addons.mozilla.org/firefox/addon/tampermonkey/)
    - **Violentmonkey**
2.  **[Click here to Install from GreasyFork](https://greasyfork.org/scripts/YOUR_SCRIPT_ID)**
    - _Or install manually using the `.user.js` file in this repository._

### 🎮 Usage

1.  Go to your **Pixiv Bookmarks** page (`/users/xxx/bookmarks/artworks`).
2.  Click the floating **Play Button** (blue FAB) at the bottom right of the screen.
3.  Enjoy the slideshow!

#### Keyboard Shortcuts

| Key       | Action                           |
| :-------- | :------------------------------- |
| `←` / `→` | Previous / Next **Image** (Page) |
| `↑` / `↓` | Previous / Next **Work**         |
| `Space`   | Play / Pause Auto-play           |
| `Home`    | Jump to First Work               |
| `End`     | Jump to Last Work                |
| `Esc`     | Close Slideshow                  |

### ⚙️ Settings

Click the **Settings (⚙️)** button in the overlay to configure:

- **Interval:** Time between auto-slides (seconds).
- **Display Mode:** "Contain" (Full image visible) or "Cover" (Fills screen).
- **Jump:** Quickly jump to a specific work number.

### 📸 Screenshots

![Slideshow View](https://via.placeholder.com/800x450?text=Please+Replace+With+Real+Screenshot)
_Slideshow View with Controls_

---

<a name="简体中文"></a>

## 🇨🇳 简体中文

**Pixiv 收藏夹幻灯片播放** 是一个油猴脚本（UserScript），它在 Pixiv 收藏夹页面添加了一个悬浮播放按钮。点击即可通过幻灯片模式无缝浏览收藏的插画，支持自动加载原图、标签过滤、漫画/组图翻页等功能。

### ✨ 主要功能

- **📺 沉浸式幻灯片**：无需打开新标签页，在当前页面以覆盖层形式浏览所有收藏作品。
- **⚡ 原图自动加载**：自动解析并加载最高画质（Original）的图片。
- **📚 支持漫画/组图**：完美支持多图作品（漫画/差分），可以在作品内部翻页，也可以切换到下一个作品。
- **🏷️ 过滤支持**：自动识别当前页面的过滤状态（按标签筛选、查看非公开收藏等）。
- **🚀 智能预加载**：预加载下一张图片和下一个数据块，提供丝滑的浏览体验。
- **⌨️ 快捷键支持**：支持键盘操作翻页、切换作品和控制播放。
- **🌍 多语言支持**：界面支持简体中文、繁体中文、日语和英语（自动检测）。

### 📥 安装方法

1.  首先安装脚本管理器：
    - **Tampermonkey (篡改猴)** (推荐): [Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo) | [Firefox](https://addons.mozilla.org/firefox/addon/tampermonkey/)
    - **Violentmonkey (暴力猴)**
2.  **[点击这里从 GreasyFork 安装](https://greasyfork.org/scripts/YOUR_SCRIPT_ID)**
    - _或者直接下载本仓库中的 `.user.js` 文件进行安装。_

### 🎮 使用说明

1.  进入你的 **Pixiv 收藏夹页面** (`/users/xxx/bookmarks/artworks`)。
2.  点击屏幕右下角的蓝色 **播放按钮**。
3.  开始浏览！

#### 快捷键列表

| 按键           | 功能                                  |
| :------------- | :------------------------------------ |
| `←` / `→`      | 上一张 / 下一张 **图片** (组图内翻页) |
| `↑` / `↓`      | 上一个 / 下一个 **作品**              |
| `空格 (Space)` | 播放 / 暂停                           |
| `Home`         | 跳转到第一个作品                      |
| `End`          | 跳转到最后一个作品                    |
| `Esc`          | 关闭幻灯片                            |

### ⚙️ 设置选项

点击界面左上角的 **设置 (⚙️)** 按钮可调整：

- **间隔时间**：自动播放时的切换间隔（秒）。
- **显示模式**：完整显示 (Contain) 或 充满屏幕 (Cover)。
- **跳转**：输入序号快速跳转到指定作品。

### 📸 截图展示

![播放界面](https://via.placeholder.com/800x450?text=Please+Replace+With+Real+Screenshot)

---

## 📄 License

MIT License

## ⚠️ Disclaimer

This script is a third-party extension and is not affiliated with Pixiv Inc. Please use it responsibly and in accordance with Pixiv's Terms of Service.
此脚本为第三方扩展，与 Pixiv Inc. 无关。请在遵守 Pixiv 服务条款的前提下使用。
