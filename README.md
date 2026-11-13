# Awesome Social Media Downloader

[![GitHub stars](https://img.shields.io/github/stars/DangJin/awesome-social-media-downloader?style=flat&logo=github)](https://github.com/DangJin/awesome-social-media-downloader/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![X: JinsFavorites](https://img.shields.io/badge/X-JinsFavorites-black?logo=x)](https://twitter.com/JinsFavorites)

收录 YouTube、Bilibili、抖音等平台的媒体下载工具，以及相关的解析、录制与转写工具。

A curated list of social media downloaders and related media tools.

本仓库是工具索引，不提供统一的下载程序。安装方法、支持的平台和使用限制请查阅各工具的官方文档；免费额度、收费方式及服务可用性可能变化。

## 目录

- [下载工具](#下载工具)
  - [命令行与下载管理器](#命令行与下载管理器)
  - [桌面应用与插件](#桌面应用与插件)
  - [开源 Web 应用](#开源-web-应用)
- [在线下载服务](#在线下载服务)
- [Telegram 机器人](#telegram-机器人)
- [媒体辅助工具](#媒体辅助工具)
- [停止维护与待核实条目](#停止维护与待核实条目)
- [使用说明](#使用说明)
- [参与贡献](#参与贡献)
- [许可证](#许可证)
- [Star History](#star-history)

## 下载工具

### 命令行与下载管理器

| 工具 | 主要用途 | 说明 |
| --- | --- | --- |
| [lux](https://github.com/iawia002/lux) | 多平台视频下载 | 使用 Go 编写的命令行工具与下载库。 |
| [Gopeed](https://github.com/GopeedLab/gopeed) | 通用文件下载 | 跨平台下载管理器，支持 HTTP、BitTorrent 等协议；社交媒体下载能力需结合相应扩展。 |
| [N_m3u8DL-CLI](https://github.com/nilaoda/N_m3u8DL-CLI) | 流媒体下载 | 命令行下载器，面向 m3u8 / HLS 等流媒体地址。 |

### 桌面应用与插件

| 工具 | 主要用途 | 说明 |
| --- | --- | --- |
| [Bili23-Downloader](https://github.com/ScottSloan/Bili23-Downloader) | Bilibili 视频下载 | 跨平台工具，支持多线程下载、音视频分离和弹幕元数据获取。 |
| [YoutubeDownloader](https://github.com/Tyrrrz/YoutubeDownloader) | YouTube 视频下载 | 支持视频与播放列表下载。 |
| [wechatVideoDownload](https://github.com/qiye45/wechatVideoDownload) | 微信视频号下载 | 支持视频、直播回放、直播及图片下载。 |
| [Arroxy](https://github.com/antonio-orionus/Arroxy) | YouTube 等多平台下载 | 提供 Windows、macOS 和 Linux 桌面应用。 |
| [PowerToysRun-VideoDownloader](https://github.com/ruslanlap/PowerToysRun-VideoDownloader) | 从 PowerToys Run 下载视频 | Windows 插件，支持通过 `dl` 加视频链接发起下载。 |

### 开源 Web 应用

| 工具 | 主要用途 | 说明 |
| --- | --- | --- |
| [cobalt](https://github.com/imputnet/cobalt) | 通过链接保存公开媒体 | 提供 Web 界面与 API，仓库包含自部署文档。 |

## 在线下载服务

以下为第三方服务，支持范围以各自网站说明为准。

| 服务 | 平台示例 | 说明 |
| --- | --- | --- |
| [PullVid](https://pullvid.com) | YouTube、TikTok、Instagram、X、Facebook 等 | 提供在线下载及媒体格式转换。 |
| [curl-x](https://www.curl-x.com) | X、Instagram、TikTok、Facebook 等 | 提供网页入口与终端 `curl` 用法。 |
| [VideoSaver](https://www.free-videodownload.com) | TikTok、Instagram、X、Facebook 等 | 通过公开链接下载，提供按平台划分的入口。 |

## Telegram 机器人

| 工具 | 平台示例 | 使用入口 |
| --- | --- | --- |
| Cyber Collector | YouTube、Instagram、TikTok、X、Facebook 等 | 向 [Telegram 机器人](https://t.me/cybercollectorbot)发送媒体链接；更多信息见[官网](https://cybercollector.hitkey.io)。 |

## 媒体辅助工具

| 工具 | 主要用途 | 说明 |
| --- | --- | --- |
| [video-analyse](https://github.com/ta867070117/video-analyse) | 短视频解析 | 提供多平台短视频解析 API 相关实现。 |
| [small-video-record](https://github.com/mabeijianxi/small-video-record) | 视频录制与压缩 | 基于 FFmpeg 的视频录制及压缩处理项目。 |
| [bagaoji](https://github.com/hope0719/bagaoji) | 视频转文案与原片获取 | 提供视频转文案、链接转原片能力，适用来源见项目说明。 |

## 停止维护与待核实条目

| 工具 | 状态 | 说明 |
| --- | --- | --- |
| [downkyi](https://github.com/leiurayer/downkyi) | 已停止维护 | 官方 README 已宣布停止维护并永久关停，保留链接供历史参考。 |
| [HellDownloader](https://github.com/ArkadyYum/HellDownloader) | 待核实 | 本次整理未能确认仓库内容与可用性，暂不列入按用途分类的工具清单。 |

## 使用说明

1. 按用途选择工具，打开其官方仓库或网站。
2. 确认操作系统、目标平台、依赖和登录要求，再按官方文档安装或使用。
3. 下载失败时，先查看工具的版本说明和已知问题；工具本身的问题请反馈到对应项目。

请仅下载你有权获取和使用的内容，并遵守目标平台的服务条款。收录不代表对第三方工具的安全性、持续可用性或功能作出保证。

## 参与贡献

欢迎通过 [Issue](https://github.com/DangJin/awesome-social-media-downloader/issues) 反馈失效链接、描述错误或工具状态变化，也欢迎通过 Pull Request 补充工具。

提交条目时请：

- 优先提供官方仓库或官网，避免使用来源不明的下载链接。
- 放入对应分类，沿用表格字段，简要说明主要用途与使用方式。
- 核实支持平台、必要依赖及收费限制，避免使用未经证实的宣传性描述。
- 更新已有条目前先检查是否重复；发现停止维护或不可用的项目时注明依据。

## 许可证

本仓库采用 [MIT License](LICENSE)。收录的第三方工具与服务遵循各自的许可证及使用条款。

## Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=DangJin/awesome-social-media-downloader&type=Date)](https://star-history.dera.page/#DangJin/awesome-social-media-downloader&Date)
