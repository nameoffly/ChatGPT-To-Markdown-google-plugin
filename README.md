# 🚀 AI对话导出工具 (AI Chat Exporter)

<div align="center">
  <h3>轻松将AI对话导出为标准Markdown格式</h3>
  <p>支持 ChatGPT, Grok 和 Gemini 平台</p>
  
  ![License](https://img.shields.io/badge/License-MIT-blue.svg)
  ![Version](https://img.shields.io/badge/Version-5.5-green.svg)
  ![Platform](https://img.shields.io/badge/Platform-Chrome-orange.svg)
</div>

## ✨ 功能特点

- 🔄 **多平台支持**：同时支持 **ChatGPT**, **Grok** 和 **Gemini** 三大AI平台
- 📝 **完整内容保留**：精确导出所有对话内容，包括**代码块**、**数学公式**、**链接**和**格式化文本**
- 🎨 **标准Markdown格式**：输出符合标准的Markdown格式，确保最佳兼容性
- 💾 **双重导出选项**：支持直接下载.md文件或复制到剪贴板
- 📦 **图片自动下载** (v5.5新增)：导出时自动下载对话中的所有图片，打包为ZIP文件
  - 图片自动保存在`images/`文件夹中
  - 使用序号命名（image_001.png, image_002.jpg等）
  - Markdown中使用相对路径引用，完美兼容Typora
- 🖼️ **Typora完美兼容**：特别优化以确保在Typora等Markdown编辑器中正确显示
- 🔘 **界面控制**：可以通过弹窗开关控制页面上导出按钮的显示
- 🛠️ **对应Google插件**：提供[Chrome插件](https://chromewebstore.google.com/detail/chatgpt-to-markdown-plus/gcocgmkjaagjcijfmocbjghbpinamnhp?hl=zh-CN&utm_source=ext_sidebar)版本，方便在Google平台上使用，插件市场搜索 **ChatGPT to MarkDown plus**

## 🛠️ 安装步骤

### 步骤 1: 下载代码库

克隆或下载本仓库到本地电脑。

### 步骤 2: 加载插件

![image-20240208173306163-1707387378543-1](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/5a371f83-1a2a-422e-99c0-7317074f434f)

1. 打开Chrome浏览器，进入扩展程序页面（chrome://extensions/）
2. 开启右上角的"开发者模式"
3. 点击"加载已解压的扩展程序"
4. 选择下载的仓库文件夹，点击确认

### 步骤 3: 使用插件

![image-20240208173337825](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/3e75a5bb-4a3d-459c-bfff-7a695a88a431)

当您打开支持的AI平台网站时（ChatGPT, Grok或Gemini），您将在页面上看到绿色的"Export Chat"按钮。

使用方法:
1. 浏览您想要导出的对话
2. 点击绿色的"Export Chat"按钮自动下载ZIP压缩包（包含Markdown文件和所有图片）
3. 解压ZIP文件，使用Typora等编辑器打开.md文件即可查看完整对话（包含图片）
4. 或者点击插件图标，选择"Copy to Clipboard"将内容复制到剪贴板（纯文本，不含图片）

**注意**：导出包含图片时会下载为.zip文件，解压后可在Typora中正常显示图片。

## 📦 图片导出功能详解 (v5.5新功能)

导出带图片的对话时，插件会：

1. **自动检测图片**：扫描对话中的所有图片（用户上传的和AI生成的）
2. **下载图片文件**：将图片从URL下载到本地
3. **智能命名**：按序号命名（image_001.png, image_002.jpg等），自动识别图片格式
4. **打包ZIP**：将markdown文件和images文件夹打包成chat-export.zip
5. **相对路径引用**：markdown中使用 `./images/image_001.png` 格式引用图片

**ZIP文件结构**：

```text
chat-export.zip
├── chat-export.md          # Markdown对话文件
└── images/                 # 图片文件夹
    ├── image_001.png
    ├── image_002.jpg
    └── ...
```

**使用提示**：

- 解压ZIP后，直接用Typora打开.md文件即可看到所有图片
- 图片和markdown文件的相对位置不要改变
- 如果对话中没有图片，仍会导出为ZIP格式

## 📋 导出效果

导出的.md文件可以完美在Typora等Markdown编辑器中打开:

![image-20240208173402018](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/f7a8d7fa-2edd-4118-92d8-72e920cdbfbf)

![image-20240208173511856](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/d1b4a046-76e9-4330-803e-6188d1cf91df)

## 🌐 支持的平台

| 平台 | 状态 | 支持的功能 |
|------|------|------------|
| ChatGPT | ✅ 完全支持 | 代码块、数学公式、链接、列表、表格等 |
| Grok | ✅ 完全支持 | 代码块、数学公式、链接、格式化文本等 |
| Gemini | ✅ 支持 | 代码块、链接、列表、表格等 |

## 📜 许可证

本项目采用MIT许可证。详情请参阅LICENSE文件。

---

# 🚀 AI Chat Exporter

<div align="center">
  <h3>Easily Export AI Conversations to Standard Markdown Format</h3>
  <p>Support for ChatGPT, Grok, and Gemini platforms</p>
  
  ![License](https://img.shields.io/badge/License-MIT-blue.svg)
  ![Version](https://img.shields.io/badge/Version-5.5-green.svg)
  ![Platform](https://img.shields.io/badge/Platform-Chrome-orange.svg)
</div>

## ✨ Features

- 🔄 **Multi-platform Support**: Works with **ChatGPT**, **Grok**, and **Gemini**
- 📝 **Complete Content Preservation**: Accurately exports all conversation content, including **code blocks**, **mathematical formulas**, **links**, and **formatted text**
- 🎨 **Standard Markdown Format**: Outputs compliant Markdown format for optimal compatibility
- 💾 **Dual Export Options**: Download .md files directly or copy to clipboard
- 📦 **Automatic Image Download** (v5.5 New): Automatically downloads all images in conversations and packages them into a ZIP file
  - Images are saved in the `images/` folder
  - Named with sequential numbers (image_001.png, image_002.jpg, etc.)
  - Markdown uses relative paths for perfect Typora compatibility
- 🖼️ **Typora Compatibility**: Specially optimized for correct display in Typora and other Markdown editors
- 🔘 **Interface Control**: Toggle the export button visibility through popup settings

## 🛠️ Installation

### Step 1: Download Repository

Clone or download this repository to your local computer.

### Step 2: Load Extension

![image-20240208173306163-1707387378543-1](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/5a371f83-1a2a-422e-99c0-7317074f434f)

1. Open Chrome browser and go to the extensions page (chrome://extensions/)
2. Enable "Developer mode" in the top right corner
3. Click "Load unpacked"
4. Select the downloaded repository folder and confirm

### Step 3: Use Extension

![image-20240208173337825](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/3e75a5bb-4a3d-459c-bfff-7a695a88a431)

When you open a supported AI platform (ChatGPT, Grok, or Gemini), you'll see the green "Export Chat" button on the page.

Usage:
1. Browse the conversation you want to export
2. Click the green "Export Chat" button to automatically download a ZIP package (containing Markdown file and all images)
3. Extract the ZIP file and open the .md file with Typora or other editors to view the complete conversation (with images)
4. Or click the extension icon and choose "Copy to Clipboard" to copy the content (plain text, no images)

**Note**: Exports with images will be downloaded as .zip files. After extraction, images will display correctly in Typora.

## 📋 Export Results

The exported .md files can be perfectly opened in Markdown editors like Typora:

![image-20240208173402018](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/f7a8d7fa-2edd-4118-92d8-72e920cdbfbf)

![image-20240208173511856](https://github.com/thisisbaiy/ChatGPT-To-Markdown-google-plugin/assets/96861449/d1b4a046-76e9-4330-803e-6188d1cf91df)

## 🌐 Supported Platforms

| Platform | Status | Supported Features |
|----------|--------|-------------------|
| ChatGPT | ✅ Full Support | Code blocks, math formulas, links, lists, tables, etc. |
| Grok | ✅ Full Support | Code blocks, math formulas, links, formatted text, etc. |
| Gemini | ✅ Supported | Code blocks, links, lists, tables, etc. |

## 📜 License

This project is licensed under the MIT License. See the LICENSE file for details.
