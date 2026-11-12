# TALOS 超级大脑

TALOS 超级大脑是一套面向个人知识管理的资料库框架，包含 Obsidian 控制台与本地资料整理工具。本仓库用于发布部署测试包。

## 真实界面截图

以下是 Obsidian 中使用虚构测试资料的实际截图，展示不同页面和界面主题。截图用于展示界面；八插件分发版尚未单独完成 GUI 验收。

### 系统体检

![TALOS 系统体检：身份、灵魂与六器官](assets/screenshots/01-system-check.png)

| 数据画像 | 系统总览 |
| --- | --- |
| ![数据画像和知识图谱](assets/screenshots/02-data-profile.png) | ![系统总览和资料统计](assets/screenshots/03-system-overview.png) |

| 语音助手 | 资料工作台 |
| --- | --- |
| ![语音助手界面，麦克风关闭](assets/screenshots/04-voice-assistant.png) | ![工作台中的资料页面](assets/screenshots/05-materials-workbench.png) |

| 项目与任务 | 系统与记忆 |
| --- | --- |
| ![工作台中的项目与任务](assets/screenshots/06-projects-tasks.png) | ![工作台中的系统与记忆](assets/screenshots/07-system-memory.png) |

## 下载测试版

在 [Releases](../../releases) 下载 candidate.21 八插件分发测试包。下载 `talos-superbrain-candidate21-eight-plugins.zip`，不要使用 GitHub 自动生成的 Source code 归档。

此分发版本包含 TALOS 插件 0.4.26 和八个第三方插件；由于 Excalidraw 旧版本许可声明待澄清，本包不内置 Excalidraw。用户可自行决定是否从 Obsidian 社区插件安装。

## 测试范围

原 candidate.21 九插件候选曾在 macOS、Obsidian 1.15.0 中以虚构资料验证新建库、接入库、笔记计数、本地检索和打开资料。八插件分发版与原包的其余程序文件相同，合成资料安装与健康检查通过；其 Obsidian GUI、真实双击启动器、真人完整流程和其他平台尚未单独验收。逐像素一致亦尚未证实。

解压后阅读包内 `START-HERE.md`；使用既有资料前请保留原库与备份。此版本仍为测试版。

## 许可

TALOS 自有插件采用个人非商业源码可用许可；商业使用需要另行授权。该许可不是 OSI 批准的开源许可。第三方插件、字体、Emotion Ball 和其他组件遵循各自许可，详见部署包内的许可原文、声明和来源清单。
