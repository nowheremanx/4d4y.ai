# 4d4y.ai - 新一代智能论坛助手

![Tampermonkey必备](https://img.shields.io/badge/-Tampermonkey-%234a4a4a?style=flat-square)
![MIT协议](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![OCR支持](https://img.shields.io/badge/OCR-中英识别-blue?style=flat-square)

## 📖 概述
4d4y.ai 是一款专为 AI 环境下的论坛助手而设计的插件。它旨在提供一个高效、便捷且易于使用的工具，帮助您在各种论坛环境中实现智能问答和内容生成。稍加修改便可用于Discuz!、Discourse等论坛环境。

前期发布于[greasyform.com](https://greasyfork.org/zh-CN/scripts/526951-4d4y-ai)，现已更新至v5.1.0版本。

## 🌟 核心升级亮点
- **UI设置界面**：右键打开设置界面（Tampermonkey > 4d4y.ai > Edit Script Settings），不用再为切换模式而烦恼
- **双引擎架构**：本地Ollama + 云端API双模式自由切换
- **智能触发机制**：本地智能判断触发时机，减少无效请求
- **双击TAB完成**：短补全自动提示，双击TAB触发完整补全
- **上下文增强**：支持图片文字融合分析（Tesseract.js v4）
- **流光状态反馈**：Apple Intelligence风格进度指示器
- **摒弃富文本编辑器**：默认将回复/引用按钮变成快速回复，保持AI上下文

## 🖥️ 交互体验升级
### 智能补全流程
1. **输入监听**：实时分析文本语义密度（≥3有效字符触发）
2. **标点感知**：智能跳过无意义断句位置
3. **内容净化**：移除think过程，回复更加流畅自然
4. **内联提示**：编辑器内“幽灵字”式补全体验

### OCR增强模块
- **快速预检**：无明显文字的图片自动跳过OCR
- **有效性校验**：过滤无意义/噪声文本
- **缓存加速**：识别结果缓存，降低重复OCR成本

## 🛠️ 安装指南
1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 扩展
2. 访问[自动更新地址](https://update.greasyfork.org/scripts/526951/4d4yai.user.js)
3. 根据需求配置本地模型或云端API
4. 打开4d4y论坛体验智能回复！

## 📌 注意事项
- 本地模式需部署 [Ollama](https://ollama.ai/) 服务
- 图片识别效果取决于图像清晰度
- 建议NVIDIA显卡加速本地推理
- 双击TAB触发完整补全，日常输入仅提供短补全提示


> "让AI理解论坛文化，而不仅仅是回复文字" - 开发团队愿景
