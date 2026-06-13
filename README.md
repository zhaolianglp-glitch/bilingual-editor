# Bilingual Editor

> 英文 ↔ 中文对照翻译 + 批注工具，纯前端，即开即用
- English-Mandarin对照，快速修改AI产出的英文脚本 以添加批注的方式给AI进一步润色

## ✨ 功能

- **双语对照编辑** — 左侧英文原文，右侧中文翻译，拖拽调整分栏宽度
- **一键翻译** — 支持 Google Translate（免费）和 OpenAI/DeepSeek API
- **段落批注** — 选中任意行，右键或点击按钮添加批注（callout 格式）
- **高亮联动** — 点击任意段落，左右两侧同步高亮并自动滚动对齐
- **导出** — 一键导出带批注的英文原文 / Markdown
- **暗色模式** — 自动跟随系统 light/dark 主题
- **撤回** -- ctrl+z撤回编辑

## 🚀 在线使用

👉 **[https://zhaolianglp-glitch.github.io/bilingual-editor/](https://zhaolianglp-glitch.github.io/bilingual-editor/)**

## 🖥️ 本地使用

直接用浏览器打开 `bilingual-editor3.html` 即可，无需安装任何东西。

## 🔧 翻译设置

| 服务 | 说明 |
|------|------|
| Google Translate | 免费，无需 API Key，默认选项 |
| OpenAI / DeepSeek | 需填写 API Key 和地址，翻译质量更高 |

点击右上角 ⚙️ 图标进行设置，设置保存在浏览器本地。

## 📋 快捷键

| 操作 | 方式 |
|------|------|
| 添加批注 | 选中行 → 右键 → 输入批注内容 |
| 关闭弹窗 | Esc |

## 🗺️ 路线图

| 状态 | 功能 | 说明 |
|------|------|------|
| ✅ 已完成 | 双语对照编辑 | 左右分栏，拖拽调整宽度 |
| ✅ 已完成 | 一键翻译 | Google / OpenAI / DeepSeek |
| ✅ 已完成 | 段落批注 | Callout 格式，右键添加 |
| ✅ 已完成 | 高亮联动 | 点击段落两侧同步高亮 |
| 📌 愿景 | [逐句对照](https://github.com/zhaolianglp-glitch/bilingual-editor/issues/1) | 原文与新译文逐句配对高亮，快速定位对应关系 |

## 🛠 技术栈

纯 HTML/CSS/JS，零依赖，单文件。
