# SONO MUSIC

A common music player / 一款普通的音乐播放器

<img width="2864" height="1784" alt="image" src="https://github.com/user-attachments/assets/d1a1bafa-12ce-48cf-a878-90b6ee9b0438" />
<img width="2848" height="1768" alt="image" src="https://github.com/user-attachments/assets/841b4682-8b7c-4293-987c-30d28d7089c3" />
<img width="2868" height="1788" alt="image" src="https://github.com/user-attachments/assets/22fa5314-8afa-4e99-8f44-4ffd48953901" />

## 项目简介

SONO MUSIC 是一款 macOS 原生音乐播放器。支持本地音频、网易云、QQ音乐。

## 快速下载

**[下载 SONO MUSIC 1.12.8(9) 预览版（DMG）](https://github.com/853578158/SONO-MUSIC/releases/download/v1.12.8-(9)/SONO-MUSIC-1.12.8-build9-preview-arm64.dmg)**

适用于搭载 Apple 芯片（M 系列）、运行 macOS 26.0 或更新版本的 Mac。安装播放器只需下载 DMG。
开发者可以获取[本版对应源码]([https://github.com/853578158/SONO-MUSIC/releases/download/v1.12.8/SONO-MUSIC-1.12.8-source.zip)，其他版本见[发行列表](https://github.com/853578158/SONO-MUSIC/releases](https://github.com/853578158/SONO-MUSIC/releases/download/v1.12.8-(9)/SONO-MUSIC-1.12.8-build9-source.zip))。

## 安装方式

1. 双击下载好的 `SONO-MUSIC-1.12.8-preview-arm64.dmg`。
2. 将 **SONO MUSIC** 拖到「应用程序」文件夹，然后从访达打开它。
3. 在播放器中选择本地音乐文件夹，即可浏览和播放。

### 首次打开时提示「无法验证开发者」

1.12.8 预览版采用临时签名，未经 Apple 公证。如果出现此提示，请先确认安装包来自本仓库的发行页面，并用随附的 `SHA256SUMS.txt` 核对下载文件。确认信任后，可任选以下一种方式。

#### 方式一 · 在终端中操作

根据 `SONO MUSIC.app` 的实际位置，复制并运行对应的一条命令，然后从访达重新打开应用。

**应用位于「应用程序」文件夹**

```sh
xattr -d com.apple.quarantine "/Applications/SONO MUSIC.app"
```

**应用位于「下载」文件夹**

```sh
xattr -d com.apple.quarantine "$HOME/Downloads/SONO MUSIC.app"
```

#### 方式二 · 在系统设置中允许打开

1. 从「应用程序」尝试打开 **SONO MUSIC**，关闭提示框。
2. 打开「系统设置 → 隐私与安全性」，向下找到「安全性」。
3. 如果看到针对 **SONO MUSIC** 的「仍要打开」按钮，点按它并按系统提示确认。

如果 macOS 提示应用已损坏或含有恶意软件，请停止打开，并通过 Issues 反馈系统版本和提示原文。[提交反馈](https://github.com/853578158/SONO-MUSIC/issues) · [Apple 关于安全打开 Mac 应用的说明](https://support.apple.com/en-us/102445)

## 法律与免责声明

请使用你有权访问和播放的音乐、歌词及专辑封面。第三方内容的权利归各自权利人所有，在线功能的可用性取决于平台服务及你的账号权限。
本仓库及其源代码仅供个人学习、技术交流与非营利测试使用。

## 致谢

特别感谢以下开源项目：

- [chenmozhijin/LDDC](https://github.com/chenmozhijin/LDDC)
- [NeteaseCloudMusicApiEnhanced](https://github.com/NeteaseCloudMusicApiEnhanced/api-enhanced)
- [WXRIW/QQMusicDecoder](https://github.com/WXRIW/QQMusicDecoder)

- [AMLL TTML 逐字歌词库](https://github.com/amll-dev/amll-ttml-db) 

## 许可证

`GPL-3.0-only`
