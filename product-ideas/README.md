# Product Ideas Lab

> 坑坑的产品创意实验室 - 用 GStack 把灵感变成方案

## How it works

```
灵感 → 记录 idea → CEO 评审 → 工程评审 → 设计评审 → 方案输出
         ideas/    /plan-ceo   /plan-eng   /design     validated/
```

## Quick Start

1. 复制模板创建新 idea：
   ```bash
   cp templates/idea-template.md ideas/$(date +%Y-%m-%d)-你的idea名称.md
   ```

2. 填写 idea 内容

3. 用 GStack 评估：
   - `/plan-ceo-review` - 商业价值评估
   - `/plan-eng-review` - 技术可行性评估
   - `/office-hours` - 模拟投资人问答

## Idea Status

| Idea | 状态 | 日期 | 评审 |
|------|------|------|------|
| *(还没有 idea，快来添加第一个！)* | | | |

## Directory

```
ideas/       原始创意
validated/   通过评估的方案
archived/    归档的创意
templates/   模板文件
reviews/     评审记录
```

---

*Powered by [GStack](https://github.com/garrytan/gstack)*
