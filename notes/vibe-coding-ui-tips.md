# 4个方法提升 Vibe Coding UI 质量

> 来源：小红书 [@万有引力AI](https://www.xiaohongshu.com/user/profile/5bed1046b490ef00017ee36f)  
> 采集时间：2026-03-07  
> 标签：#vibecoding #cursor #claudecode #小红书科技AMA #大模型 #开发 #产品经理

---

## 引言

近半年基本上已经离不开 Cursor 和 Claude code。尽管肉眼可见的模型能力的迭代，让代码能力更强，能生成更好的后端，说实话……**目前 AI 生成的 UI 确实有点丑**。

千篇一律，带着那种浓重的"AI 味"，逃不掉的紫蓝配色，一眼就能认出来。

经过大量的试错，总结出了几个真正能打破这种 AI 生成渐变 UI 的技巧：

---

## 方法 1：别从文字开始，从产品原型开始

当你只是输入"做一个落地页或仪表盘"时，AI 会猜测太多东西。

**做法**：用 [Excalidraw](https://excalidraw.com) 快速画一个线框图。画出方块、按钮的位置、图片应该放在哪里。然后导出这张图，交给 AI，并说：**"严格按照这个结构来。"**

💡 **进阶**：如果有设计背景，可以直接用 Figma，然后连 MCP，还原率 90%+。

---

## 方法 2：用截图作为参考

AI 很擅长模仿，但不擅长凭空想象。

别只说"做得简洁一点"。去 [Pinterest](https://pinterest.com)、[Behance](https://behance.net) 这样的网站，或者找一个你觉得好看的真实网站。

截取你喜欢的特定部分（比如导航栏或定价卡片），把截图粘贴到对话中，让 AI 复制那个风格或结构。

**不同工具的操作**：
- **Cursor**：直接上传截图即可
- **Claude Code**：复制图片后，按 **Ctrl + V**（不要 Command + V）

---

## 方法 3：使用情绪版（Mood Board）

向 AI 描述一种"氛围"真的很难。它通常会默认生成那种无聊的"AI 蓝"。

**做法**：用 AIGC 快速生成一个情绪板。把那张图喂给 AI，然后说：**"参考这个情绪板的配色和风格。"** 出来的效果会独特很多。

**推荐工具**：
- 可灵、即梦、Lovart、Nano（AI 生成情绪板）
- [uicolors.app](https://uicolors.app)（免费替代方案）
  - 选择一个喜欢的颜色/渐变
  - 可以生成一套 UI/UX 组件
  - 亲测喂给 AI 后 UI 质量显著上升

---

## 方法 4：使用 "UI/UX Pro Max" Skill

GitHub 开源工具：[ui-ux-pro-max-skill](https://github.com)

它强制你的 AI（Cursor/Claude）在写代码之前先使用**"推理引擎"**。

它不会瞎猜，而是根据特定行业规则（比如金融科技 vs. 医疗中心）生成一套完整的设计系统。

最棒的是，它内置了**"反模式"规则**，明确禁止那些泛滥的 AI 渐变效果。

---

## 关键要点总结

| 问题 | 解决方案 |
|------|----------|
| AI 乱猜布局 | 先画线框图/原型 |
| AI 默认"AI 蓝" | 用截图或情绪板给定风格 |
| 描述不清氛围 | 用 AIGC 生成情绪板参考 |
| 千篇一律渐变 | 用 UI/UX Pro Max Skill 规范 |

---

## 相关工具链接

- **Excalidraw**：https://excalidraw.com
- **Figma**：https://figma.com
- **uicolors.app**：https://uicolors.app
- **Pinterest**：https://pinterest.com
- **Behance**：https://behance.net

---

*原文点赞 273 · 收藏 408 · 评论 1 · 分享 61*
