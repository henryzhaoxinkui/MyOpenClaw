# TOOLS.md - Local Notes

## Browser Automation

**重要规则**：所有涉及浏览器的任务（打开网址、搜索、浏览社交媒体、填表、网页采集等）必须使用 `autoglm-browser-agent` skill。这是永久规则。

## Image Recognition

所有图像识别任务优先使用 `autoglm-image-recognition` skill。

## Web Search

使用 `autoglm-websearch` skill 进行网络信息搜索。

## 信息收集与分析

- 搜索工具：autoglm-websearch（网络搜索）、autoglm-open-link（正文提取）
- 深度研究：autoglm-deepresearch（深度调研报告）
- 文档输出：reports/ 目录，格式 YYYYMMDD-<主题>

## 飞书集成

- 授权已完成，可以使用用户身份操作飞书
- 报告可通过飞书消息推送

---

Do not store passwords, API keys, tokens, or secrets here in plain text.
