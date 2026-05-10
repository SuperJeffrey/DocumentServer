[![License](https://img.shields.io/badge/License-GNU%20AGPL%20V3-green.svg?style=flat)](https://www.gnu.org/licenses/agpl-3.0.en.html) [![Release](https://img.shields.io/github/v/tag/ONLYOFFICE/DocumentServer?sort=semver&style=flat&label=Release&color=blue)](https://github.com/ONLYOFFICE/DocumentServer/tags)

## 欢迎来到 ONLYOFFICE Docs 仓库！

[ONLYOFFICE Docs](https://www.onlyoffice.com/office-suite.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS)* 是一套免费的在线协同办公套件，包含文本文档、电子表格、演示文稿、表单、PDF 和图表的查看器与编辑器。它完全兼容 Office Open XML 格式（.docx、.xlsx、.pptx），并支持实时协同编辑。

ONLYOFFICE Docs 可以作为 [ONLYOFFICE DocSpace](https://www.onlyoffice.com/docspace.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubCS) 和 [ONLYOFFICE Workspace](https://www.onlyoffice.com/workspace.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubCS) 的一部分使用，也可以与 [第三方同步与共享解决方案](https://www.onlyoffice.com/all-connectors.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) 集成，例如 Odoo、Moodle、Nextcloud、ownCloud、Seafile 等，从而在它们的界面中启用协同编辑。

ONLYOFFICE Docs 提供三种版本以满足不同需求：[社区版、企业版和开发者版](#onlyoffice-docs-版本)。

\* 从 6.0 版本开始，Document Server 以新名称 ONLYOFFICE Docs 发布。

![ONLYOFFICE Docs](./screenshots/ONLYOFFICE%20Docs.png)

## 你会喜欢的功能 ✨

充分利用 ONLYOFFICE Docs 中强大的编辑器：

* [ONLYOFFICE 文档编辑器](https://www.onlyoffice.com/document-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDS)
* [ONLYOFFICE 电子表格编辑器](https://www.onlyoffice.com/spreadsheet-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDS)
* [ONLYOFFICE 演示文稿编辑器](https://www.onlyoffice.com/presentation-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDS)
* [ONLYOFFICE 表单创建器](https://www.onlyoffice.com/form-creator.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDS)
* [ONLYOFFICE PDF 编辑器](https://www.onlyoffice.com/pdf-editor.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDS)
* [ONLYOFFICE 图表查看器](https://www.onlyoffice.com/diagram-viewer.aspx?utm_source=GitHub&utm_medium=social&utm_campaign=GitHubDS)

这些编辑器支持创建、编辑、保存和导出文本文档、电子表格、演示文稿和 PDF，支持创建和填写 PDF 表单、打开图表，并提供更多高级功能：

* [协同编辑](https://www.onlyoffice.com/seamless-collaboration.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) 🤝
* [AI 助手](https://www.onlyoffice.com/ai-assistants.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) 🤖
* 审阅 📝
* 拼写检查 🔍
* [无障碍访问](https://www.onlyoffice.com/accessibility.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) 👩‍💻
* 可缩放的界面选项（包括深色模式 🌓）
* [安全工具和服务](https://www.onlyoffice.com/security.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) 🔒

## 本地化 🌐

ONLYOFFICE 持续改进编辑器的本地化，让全球用户都能更方便地使用这套办公套件。

* 界面支持 46 种语言
* 支持从右到左书写语言
* 支持象形文字 🈴

## 插件 🧩

ONLYOFFICE Docs 支持插件，开发者可以为编辑器添加与 OOXML 格式本身无直接关系的特定功能。更多信息请参阅 [我们的 API](https://api.onlyoffice.com/docs/plugin-and-macros/get-started/overview/)，或访问 [GitHub 插件仓库](https://github.com/ONLYOFFICE/onlyoffice.github.io)。

想详细了解已有插件？欢迎访问我们的 [Marketplace](https://www.onlyoffice.com/app-directory?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS)。

## 组件 📦

ONLYOFFICE Docs 包含以下组件：

* [server](https://github.com/ONLYOFFICE/server) - 后端服务器软件层，是 ONLYOFFICE Docs 所有其他组件的基础。
* [core](https://github.com/ONLYOFFICE/core) - ONLYOFFICE Docs 的服务器核心组件，用于在常见办公文档格式之间进行转换（DOC、DOCX、ODT、RTF、TXT、PDF、HTML、EPUB、XPS、DjVu、XLS、XLSX、ODS、CSV、PPT、PPTX、ODP）。
* [sdkjs](https://github.com/ONLYOFFICE/sdkjs) - ONLYOFFICE Docs 的 JavaScript SDK，包含所有组件客户端交互所需的 API。
* [web-apps](https://github.com/ONLYOFFICE/web-apps) - ONLYOFFICE Docs 的前端，用于构建程序界面，并允许用户通过文档编辑器的通用界面创建、编辑、保存和导出文本文档、电子表格和演示文稿。
* [dictionaries](https://github.com/ONLYOFFICE/dictionaries) - ONLYOFFICE Docs 拼写检查使用的多语言词典。

## ONLYOFFICE Docs 版本

ONLYOFFICE 提供多个版本的在线文档编辑器，可部署在你自己的服务器上。

ONLYOFFICE Docs（以 Document Server 形式打包）：

* 社区版 🆓（`onlyoffice-documentserver` 包）- 适合小团队和个人使用。
* 企业版 🏢（`onlyoffice-documentserver-ee` 包）- 面向企业，提供高级功能和支持。
* 开发者版 ⚙️（`onlyoffice-documentserver-de` 包）- 面向需要将文档编辑能力集成到应用中的集成商。

下表可帮助你选择合适的版本。

| 定价和许可 | 社区版 | 企业版 | 开发者版 |
| ------------- | ------------- | ------------- | ------------- |
| | [立即获取](https://www.onlyoffice.com/download-community.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS#docs-community) | [开始免费试用](https://www.onlyoffice.com/download.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS#docs-enterprise) | [开始免费试用](https://www.onlyoffice.com/download-developer.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS#docs-developer) |
| 费用 | 免费 | [前往定价页面](https://www.onlyoffice.com/docs-enterprise-prices.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) | [前往定价页面](https://www.onlyoffice.com/developer-edition-prices.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS) |
| 同时连接数 | 最多 100 个 | 按所选定价方案 | 按所选定价方案 |
| 用户数量 | 建议最多 20 个 | 按所选定价方案 | 按所选定价方案 |
| 集群化 | - | + | + |
| 许可证 | GNU AGPL v.3 | 专有 | 专有 |
| **支持** | **社区版** | **企业版** | **开发者版** |
| 文档 | [帮助中心](https://helpcenter.onlyoffice.com/docs/installation/community) | [帮助中心](https://helpcenter.onlyoffice.com/docs/installation/enterprise) | [帮助中心](https://helpcenter.onlyoffice.com/docs/installation/developer) |
| 标准支持 | [GitHub](https://github.com/ONLYOFFICE/DocumentServer/issues) 或付费支持 | 包含一年或三年支持 | 包含一年支持 |
| 高级支持 | [联系我们](mailto:sales@onlyoffice.com) | [联系我们](mailto:sales@onlyoffice.com) | [联系我们](mailto:sales@onlyoffice.com) |
| **服务** | **社区版** | **企业版** | **开发者版** |
| 转换服务 | + | + | + |
| Document Builder 服务 | + | + | + |
| **界面** | **社区版** | **企业版** | **开发者版** |
| 标签式界面 | + | + | + |
| 深色主题 | + | + | + |
| 125%、150%、175%、200% 缩放 | + | + | + |
| 白标 | - | - | + |
| 集成测试示例（node.js） | + | + | + |
| 移动端网页编辑器 | - | +** | +** |
| **插件和宏** | **社区版** | **企业版** | **开发者版** |
| 插件 | + | + | + |
| 宏 | + | + | + |
| **协作能力** | **社区版** | **企业版** | **开发者版** |
| 两种协同编辑模式 | + | + | + |
| 评论 | + | + | + |
| 内置聊天 | + | + | + |
| 审阅和修订跟踪 | + | + | + |
| 修订跟踪显示模式 | + | + | + |
| 版本历史 | + | + | + |
| **文档编辑器功能** | **社区版** | **企业版** | **开发者版** |
| 字体和段落格式 | + | + | + |
| 插入对象 | + | + | + |
| 添加内容控件 | + | + | + |
| 编辑内容控件 | + | + | + |
| 布局工具 | + | + | + |
| 目录 | + | + | + |
| 导航面板 | + | + | + |
| 邮件合并 | + | + | + |
| 文档比较 | + | + | + |
| **电子表格编辑器功能** | **社区版** | **企业版** | **开发者版** |
| 字体和段落格式 | + | + | + |
| 插入对象 | + | + | + |
| 函数、公式和方程 | + | + | + |
| 表格模板 | + | + | + |
| 数据透视表 | + | + | + |
| 数据验证 | + | + | + |
| 条件格式 | + | + | + |
| 迷你图 | + | + | + |
| 工作表视图 | + | + | + |
| **演示文稿编辑器功能** | **社区版** | **企业版** | **开发者版** |
| 字体和段落格式 | + | + | + |
| 插入对象 | + | + | + |
| 切换效果 | + | + | + |
| 动画 | + | + | + |
| 演讲者模式 | + | + | + |
| 备注 | + | + | + |
| 幻灯片母版 | + | + | + |
| **表单创建器功能** | **社区版** | **企业版** | **开发者版** |
| 添加表单字段 | + | + | + |
| 表单预览 | + | + | + |
| 另存为 PDF | + | + | + |
| 字段角色匹配颜色 | + | + | + |
| **PDF 编辑器功能** | **社区版** | **企业版** | **开发者版** |
| 文本编辑和协同编辑 | + | + | + |
| 页面操作（添加、删除、旋转） | + | + | + |
| 插入对象（形状、图片、超链接等） | + | + | + |
| 文本批注（高亮、下划线、删除线、图章） | + | + | + |
| 评论 | + | + | + |
| 手绘 | + | + | + |
| 表单填写 | + | + | + |
| **安全功能** | **社区版** | **企业版** | **开发者版** |
| 通过私有房间实现端到端加密*** | + | + | - |
| | [立即获取](https://www.onlyoffice.com/download-community.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS#docs-community) | [开始免费试用](https://www.onlyoffice.com/download.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS#docs-enterprise) | [开始免费试用](https://www.onlyoffice.com/download-developer.aspx?utm_source=github&utm_medium=cpc&utm_campaign=GitHubDS#docs-developer) |

\** 如果 DMS 支持  
\*** 通过私有房间实现端到端加密需要 ONLYOFFICE Workspace

## 🚀 快速开始：如何在本地服务器安装

安装 ONLYOFFICE Docs 最简单的方式是使用 **Docker 镜像** 👉 [查看官方源码](https://github.com/ONLYOFFICE/Docker-DocumentServer)

查看以下分步指南：

* [安装 ONLYOFFICE Docs Docker](https://helpcenter.onlyoffice.com/installation/docs-community-install-docker.aspx)
* [在 Linux 上安装 ONLYOFFICE Docs](https://helpcenter.onlyoffice.com/installation/docs-community-install-ubuntu.aspx)
* [在 Windows 上安装 ONLYOFFICE Docs](https://helpcenter.onlyoffice.com/installation/docs-community-install-windows.aspx)

## 如何构建 🛠

你可以在我们的 [帮助中心](https://helpcenter.onlyoffice.com/docs/installation/docs-community-compile.aspx) 找到从源代码在本地服务器构建 ONLYOFFICE Docs 的详细说明。

## 许可证 📄

ONLYOFFICE Docs 基于 GNU Affero Public License 3.0 版本授权，确保其透明性，并体现对开源社区的承诺。

更多信息请参阅 [LICENSE](https://onlyo.co/38YZGJh)。

## 💡 需要帮助？用户反馈和支持

如果你在使用 ONLYOFFICE Docs 时遇到问题或有任何疑问，请访问我们的官方论坛：[forum.onlyoffice.com](https://forum.onlyoffice.com/)。

也欢迎你在 [Stack Overflow](https://stackoverflow.com/questions/tagged/onlyoffice) 上提问和回答 ONLYOFFICE 开发相关问题，并在 [feedback.onlyoffice.com](https://feedback.onlyoffice.com/forums/966080-your-voice-matters) 分享想法和建议。

加入 [我们的 Discord 社区](https://discord.gg/Hcgtf5n4uF)，与其他开发者交流。

使用 ONLYOFFICE Docs 更好地协作！🌟
