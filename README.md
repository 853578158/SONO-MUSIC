# SONO MUSIC

A common music player / 一款普通的音乐播放器

## 项目简介

SONO MUSIC 是一款 macOS 原生音乐播放器。你可以导入 Mac 上的音乐文件夹，在照片墙或轮播视图中浏览专辑封面，点开一首歌，跟着播放进度看逐字歌词。连接音乐账号后，还可以浏览在线歌单。

## 快速下载

**[下载 SONO MUSIC 1.12.8 预览版（DMG）](https://github.com/853578158/SONO-MUSIC/releases/download/v1.12.8/SONO-MUSIC-1.12.8-preview-arm64.dmg)**

适用于搭载 Apple 芯片（M 系列）、运行 macOS 26.0 或更新版本的 Mac。安装播放器只需下载 DMG。开发者可以获取[本版对应源码](https://github.com/853578158/SONO-MUSIC/releases/download/v1.12.8/SONO-MUSIC-1.12.8-source.zip)，其他版本见[发行列表](https://github.com/853578158/SONO-MUSIC/releases)。

## 安装方式

1. 双击下载好的 `SONO-MUSIC-1.12.8-preview-arm64.dmg`。
2. 将 **SONO MUSIC** 拖到「应用程序」文件夹，再从「应用程序」打开。
3. 在播放器中选择本地音乐文件夹，即可浏览和播放。

此预览版采用临时签名，未经 Apple 公证。如果首次打开时 macOS 提示无法验证开发者，请先确认文件来自本仓库的发行页面。确认信任后，可前往「系统设置 → 隐私与安全性」，查看是否出现「仍要打开」。如果系统提示应用已损坏或含有恶意软件，请停止打开，并通过 [Issues](https://github.com/853578158/SONO-MUSIC/issues) 反馈系统版本和提示原文。[Apple 关于安全打开 Mac 应用的说明](https://support.apple.com/en-us/102445)

## 法律与免责声明

请使用你有权访问和播放的音乐、歌词及专辑封面。第三方内容的权利归各自权利人所有，在线功能的可用性取决于平台服务及你的账号权限。

**账号与隐私。** 登录凭据保存在当前 macOS 用户的钥匙串中。退出音乐账号后，歌单等缓存可能继续保留在本机。播放本地歌曲时，「自动寻找逐字歌词」默认开启，匹配时可能向歌词服务发送歌名、艺人名或歌曲 ID。你可以在「设置 → 歌词 → 自动寻找逐字歌词」中关闭。

本软件按现状提供。在适用法律允许的范围内，作者及贡献者不作担保。具体条款见源码包中的 `LICENSE`。

## 致谢

- **LDDC** 提供了 QQ 音乐、酷狗歌词请求以及 QRC、KRC 解码的实现参考，SONO MUSIC 将相关实现移植到了 Swift。[项目地址](https://github.com/chenmozhijin/LDDC)
- **NeteaseCloudMusicApiEnhanced** 为网易云音乐登录和请求协议的原生实现提供了参考。[项目地址](https://github.com/NeteaseCloudMusicApiEnhanced/api-enhanced)
- **QQMusicDecoder** 是 LDDC 的 QRC 解码所参考的上游项目。[项目地址](https://github.com/WXRIW/QQMusicDecoder)
- **AMLL TTML 歌词库** 为在线逐字歌词匹配提供数据。感谢制作歌词、校对时间轴和维护歌词库的贡献者。[歌词库地址](https://github.com/amll-dev/amll-ttml-db)

## 许可证

SONO MUSIC **1.12.8** 的完整程序及对应源码采用 **GNU 通用公共许可证第 3 版（仅此版本，`GPL-3.0-only`）** 分发。你可以按许可证条款运行、复制、修改和再分发本程序，包括用于商业用途。分发二进制版本时，须按许可证第 6 节向接收者提供完整对应源码。[GPLv3 完整条款](https://www.gnu.org/licenses/gpl-3.0.html)

随本版提供的图标和默认封面由项目作者原创，作为本程序的一部分分发。源码包根目录的 `LICENSE` 收录完整许可证，`THIRD_PARTY_NOTICES.txt` 和 `licenses/` 收录第三方署名、来源与许可文本。[下载本版对应源码](https://github.com/853578158/SONO-MUSIC/releases/download/v1.12.8/SONO-MUSIC-1.12.8-source.zip)
