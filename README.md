# 灵动音 MusicFlow

灵动音 MusicFlow 是一个 Windows 桌面悬浮音乐控制条，可以读取 Windows 系统媒体会话，展示当前播放歌曲、封面、进度和声波动效，并提供播放 / 暂停 / 上一首 / 下一首控制。

> 当前版本：v0.1.0-beta  
> 当前状态：早期公开测试版  
> 支持平台：Windows 10 / Windows 11

## 立即下载

[下载灵动音 MusicFlow v0.1.0-beta](https://github.com/wzmwillwin-lab/musicflow-desktop/releases/tag/v0.1.0-beta)

如果你觉得这个小工具有意思，可以给仓库点一个 Star 支持一下。

## 下载

请到 Releases 页面下载最新版本：

- `MusicControllerPortable-v0.1.0.zip`
- `MusicController-version.json`
- `SHA256SUMS.txt`

说明：当前 beta 包内部文件名仍为 `MusicController`，后续版本会统一改为 `MusicFlow`。

## 功能

- 桌面悬浮控制条
- 播放 / 暂停 / 上一首 / 下一首
- 当前歌曲标题、歌手和播放进度展示
- 基础封面展示
- 霓虹声波视觉效果
- 绿色版 zip，解压后运行

## 计划适配

灵动音优先通过 Windows 系统媒体会话读取当前播放状态，目标适配：

- QQ 音乐
- 网易云音乐
- Spotify
- 酷狗音乐
- 酷我音乐
- Apple Music
- 其他支持 Windows 系统媒体控制的播放器

不同播放器和版本的兼容性可能不同。如果你发现某个播放器不可用，欢迎反馈系统版本、播放器版本和复现步骤。

## 使用方式

1. 下载并解压 `MusicControllerPortable-v0.1.0.zip`。
2. 打开你常用的音乐播放器并开始播放。
3. 双击运行 `MusicController.exe`。
4. 使用桌面悬浮条查看歌曲、控制播放或切歌。

## 已知问题

- 部分播放器可能无法显示封面或进度。
- 多屏和高 DPI 场景还需要更多测试。
- 当前是绿色版，不是正式安装程序。
- 自动更新 manifest 已指向本次 GitHub Release，后续版本会继续完善更新体验。

## 隐私说明

灵动音只读取本机系统提供的媒体会话信息，用于展示歌曲标题、歌手、封面、播放状态和进度。

灵动音不会读取或保存音乐平台账号、密码、cookie，也不提供音乐下载、会员破解或版权绕过功能。

## 支持

如果你喜欢这个小工具，可以给仓库点一个 Star。  
这个作品还很早期，Star 和反馈都会让我知道它值得继续做下去。

## 免责声明

灵动音 MusicFlow 是独立开发的小工具，不隶属于 QQ 音乐、网易云音乐、Spotify 或其他音乐平台。平台名称仅用于说明兼容性。
