# 苏格拉底导师

## 这是什么

一个结合bloom和苏格拉底式提问的学习方法。

---

## 支持的 AI 模型

打开应用后点击顶部模型按钮进入设置，支持：

| 提供商 | 模型 | 获取 Key |
|--------|------|----------|
| Anthropic | Claude Sonnet/Opus/Haiku | console.anthropic.com |
| OpenAI | GPT-4o, GPT-4o Mini, o1 | platform.openai.com |
| Google | Gemini 2.0 Flash, 1.5 Pro | aistudio.google.com |
| DeepSeek | DeepSeek Chat (V3), R1 | platform.deepseek.com |

**API Key 仅存储在用户本地浏览器（localStorage），不经过任何中间服务器。**

---

## 文件结构

```
index.html    ← 所有代码在这一个文件里，无需其他依赖
README.md     ← 本说明
```

所有依赖均通过 CDN 加载：
- React 18 (cdnjs)
- Babel Standalone (cdnjs)
- Mammoth.js — DOCX 解析 (cdnjs)
- PDF.js — PDF 解析 (cdnjs，按需加载)
- Google Fonts

---

## 学习模式说明

### 新学模式（推荐第一次接触内容时使用）
1. **激活先验** — AI 先问你对主题已有什么了解
2. **分块阅读** — AI 把内容拆成 3-5 块，逐块呈现，每块后通过苏格拉底式提问帮你消化
3. **高阶深化** — 读完后从 Bloom 应用层开始递进（应用→分析→评估→创造）

### 复习模式（已读过，想深化理解）
从 Bloom 记忆层开始，严格按六层递进提问

---

## 常见问题

**Q: 为什么链接抓取有时失败？**
A: 部分网站有防爬虫保护。此时请将页面内容复制后用"文本粘贴"模式。

**Q: API Key 安全吗？**
A: Key 仅保存在你自己的浏览器 localStorage 中，不会发送到除对应 AI 服务商之外的任何地方。建议部署时用自己的服务器或本地运行。

**Q: 支持移动端吗？**
A: 支持，但建议横屏使用以获得最佳体验。
