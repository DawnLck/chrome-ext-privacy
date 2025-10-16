---
title: WeChat Article Reading Assistant Privacy Policy
extension_name: WeChat Article Reading Assistant
layout: policy
permalink: /wechat-reader/
last_updated: 2024-01-01
---

# Privacy Policy | 隐私政策

## English Version

### Introduction

Thank you for using **WeChat Article Reading Assistant** (the "Extension"). We are committed to protecting your privacy and being transparent about our data practices. This Privacy Policy explains how we handle your information when you use our Extension.

### Our Privacy Commitment

**We do NOT collect, transmit, or store any personal information or browsing data on external servers.**

All data processing happens locally within your browser. Your reading habits, highlights, notes, and preferences remain entirely on your device under your control.

### Information We Store Locally

The Extension stores the following data **locally in your browser only** using Chrome's storage APIs and IndexedDB:

#### 1. User Preferences

- **What**: Language preference for AI summaries (Chinese/English/Japanese), feature toggles, UI settings, custom domain whitelist
- **Where**: Chrome local storage (chrome.storage.local)
- **Purpose**: Personalize your reading experience according to your preferences
- **Control**: You can clear this data anytime through Chrome's extension settings

#### 2. Reading Highlights and Notes

- **What**: Text selections you highlight, colors used, notes you add, timestamps
- **Where**: Local IndexedDB database in your browser
- **Purpose**: Save your annotations for future reference when you revisit articles
- **Control**: You can delete individual highlights/notes through the extension interface or clear all data by uninstalling the extension

#### 3. AI Summary Cache

- **What**: AI-generated article summaries (text only)
- **Where**: Local IndexedDB with automatic expiration
- **Purpose**: Improve performance and reduce redundant API calls when revisiting articles
- **Retention**: Cached summaries expire automatically after a set period

#### 4. Session State

- **What**: Current tab URL, domain whitelist status
- **Where**: Chrome session storage (chrome.storage.session)
- **Purpose**: Synchronize sidebar panel with current article page
- **Retention**: Cleared automatically when browser session ends

### Permissions We Use

#### scripting

- **Purpose**: Inject reading assistance features (TOC, highlights, progress tracker) into article pages
- **Scope**: Only activated on article pages you visit
- **Data Access**: Reads article content to extract text for summarization and generate table of contents. No data is transmitted externally.

#### tabs

- **Purpose**: Detect when you switch tabs or update pages to provide context-aware features
- **Data Access**: Reads current tab URL to check domain whitelist. No browsing history is collected.

#### storage

- **Purpose**: Save your preferences, highlights, and notes locally
- **Data Access**: All stored data remains in your browser and is never transmitted to external servers

#### sidePanel

- **Purpose**: Display reading assistant panel in Chrome's sidebar
- **Data Access**: Only displays data already stored locally in your browser

#### Host Permissions (http://*/* and https://*/*)

- **Purpose**: Enable reading features across various article platforms (WeChat, Medium, Zhihu, personal blogs, etc.)
- **Data Access**: Only processes content on pages you actively visit. No background data collection occurs.

### Chrome AI API Usage

The Extension uses **Chrome's built-in AI Summarization API** to generate article summaries:

- **Processing**: All AI processing happens locally in your browser using Chrome's built-in AI capabilities
- **No External Servers**: Article content is NOT sent to any external AI service or our servers
- **Trial Tokens**: We use Chrome's Origin Trial tokens to access experimental AI features. These tokens only identify our extension to Chrome, not individual users.

### Data We Do NOT Collect

✅ We do NOT collect:

- Browsing history or URLs you visit
- Personal identifiable information (name, email, address, etc.)
- User behavior analytics or tracking data
- IP addresses or device identifiers
- Cookies for tracking purposes
- Any data from pages you visit beyond what's necessary for reading enhancement

✅ We do NOT:

- Transmit any data to external servers
- Share data with third parties
- Use data for advertising or marketing
- Sell or monetize user data in any form
- Track you across websites

### Data Security

- **Local Storage Only**: All data remains in your browser's secure storage
- **No Network Transmission**: The Extension does not communicate with external servers (except Chrome's built-in AI API, which operates locally)
- **User Control**: You have full control to delete all stored data by uninstalling the extension or clearing browser data

### Third-Party Services

This Extension does NOT use any third-party services, analytics tools, or external APIs (except Chrome's built-in features).

### Children's Privacy

This Extension does not knowingly collect any information from children under 13 years of age. The Extension is designed for general article reading and does not target children.

### Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify users of any material changes by updating the "Last Updated" date at the top of this policy. Continued use of the Extension after changes constitutes acceptance of the updated policy.

### Your Rights

You have the right to:

- Access all data stored by the Extension (through the extension interface)
- Delete your data at any time (by removing highlights/notes or uninstalling)
- Opt-out of features (by disabling them in settings)
- Request information about our data practices (contact us below)

---

## 中文版本

### 简介

感谢您使用**公众号文章阅读助手**（以下简称"本扩展"）。我们致力于保护您的隐私，并对我们的数据处理方式保持透明。本隐私政策说明我们在您使用本扩展时如何处理您的信息。

### 我们的隐私承诺

**我们不会在外部服务器上收集、传输或存储任何个人信息或浏览数据。**

所有数据处理都在您的浏览器本地进行。您的阅读习惯、高亮、笔记和偏好设置完全保留在您的设备上，由您控制。

### 我们在本地存储的信息

本扩展使用 Chrome 的存储 API 和 IndexedDB **仅在您的浏览器本地**存储以下数据：

#### 1. 用户偏好设置

- **内容**：AI 摘要的语言偏好（中文/英文/日文）、功能开关、界面设置、自定义域名白名单
- **位置**：Chrome 本地存储（chrome.storage.local）
- **目的**：根据您的偏好个性化您的阅读体验
- **控制**：您可以随时通过 Chrome 的扩展设置清除这些数据

#### 2. 阅读高亮和笔记

- **内容**：您高亮的文本选择、使用的颜色、添加的笔记、时间戳
- **位置**：浏览器本地 IndexedDB 数据库
- **目的**：保存您的标注以便在重新访问文章时参考
- **控制**：您可以通过扩展界面删除单个高亮/笔记，或通过卸载扩展清除所有数据

#### 3. AI 摘要缓存

- **内容**：AI 生成的文章摘要（仅文本）
- **位置**：本地 IndexedDB，自动过期
- **目的**：提升性能，减少重复访问文章时的 API 调用
- **保留期限**：缓存的摘要在设定期限后自动过期

#### 4. 会话状态

- **内容**：当前标签页 URL、域名白名单状态
- **位置**：Chrome 会话存储（chrome.storage.session）
- **目的**：同步侧边栏面板与当前文章页面
- **保留期限**：浏览器会话结束时自动清除

### 我们使用的权限

#### scripting（脚本注入）

- **目的**：在文章页面注入阅读辅助功能（目录、高亮、进度追踪器）
- **范围**：仅在您访问的文章页面激活
- **数据访问**：读取文章内容以提取文本用于摘要和生成目录。不会向外部传输任何数据。

#### tabs（标签页）

- **目的**：检测您何时切换标签页或更新页面，以提供上下文感知功能
- **数据访问**：读取当前标签页 URL 以检查域名白名单。不收集浏览历史。

#### storage（存储）

- **目的**：在本地保存您的偏好设置、高亮和笔记
- **数据访问**：所有存储的数据都保留在您的浏览器中，不会传输到外部服务器

#### sidePanel（侧边栏）

- **目的**：在 Chrome 侧边栏显示阅读助手面板
- **数据访问**：仅显示已在您浏览器本地存储的数据

#### 主机权限（http://*/* 和 https://*/*）

- **目的**：在各种文章平台（微信、Medium、知乎、个人博客等）上启用阅读功能
- **数据访问**：仅处理您主动访问的页面内容。不进行后台数据收集。

### Chrome AI API 使用

本扩展使用 **Chrome 内置的 AI 摘要 API** 生成文章摘要：

- **处理方式**：所有 AI 处理都在您的浏览器本地使用 Chrome 内置 AI 功能进行
- **无外部服务器**：文章内容不会发送到任何外部 AI 服务或我们的服务器
- **试验令牌**：我们使用 Chrome 的 Origin Trial 令牌访问实验性 AI 功能。这些令牌仅向 Chrome 标识我们的扩展，不标识个人用户。

### 我们不收集的数据

✅ 我们不收集：

- 浏览历史或您访问的 URL
- 个人身份信息（姓名、电子邮件、地址等）
- 用户行为分析或追踪数据
- IP 地址或设备标识符
- 用于追踪目的的 Cookie
- 访问页面中除阅读增强必需之外的任何数据

✅ 我们不会：

- 向外部服务器传输任何数据
- 与第三方共享数据
- 将数据用于广告或营销
- 以任何形式出售或变现用户数据
- 跨网站追踪您

### 数据安全

- **仅本地存储**：所有数据都保留在您浏览器的安全存储中
- **无网络传输**：本扩展不与外部服务器通信（除 Chrome 内置 AI API，其在本地运行）
- **用户控制**：您可以通过卸载扩展或清除浏览器数据来完全删除所有存储的数据

### 第三方服务

本扩展不使用任何第三方服务、分析工具或外部 API（Chrome 内置功能除外）。

### 隐私政策变更

我们可能会不时更新本隐私政策。我们会通过更新本政策顶部的"最后更新"日期来通知用户任何重大变更。变更后继续使用本扩展即表示接受更新后的政策。

### 您的权利

您有权：

- 访问本扩展存储的所有数据（通过扩展界面）
- 随时删除您的数据（通过删除高亮/笔记或卸载）
- 选择退出功能（通过在设置中禁用）
- 请求有关我们数据处理方式的信息（通过下方联系我们）

## Compliance | 合规性

This Privacy Policy complies with:

- Chrome Web Store Developer Program Policies
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)
- Other applicable privacy laws and regulations

本隐私政策符合以下规定：

- Chrome 网上应用店开发者计划政策
- 欧盟通用数据保护条例（GDPR）
- 加州消费者隐私法（CCPA）
- 其他适用的隐私法律法规

---

**By using this Extension, you acknowledge that you have read and understood this Privacy Policy.**

**使用本扩展即表示您已阅读并理解本隐私政策。**