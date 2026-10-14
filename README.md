<div align="center">

# 🎬 lark-whiteboard

## 画板内容一键导出成图，还能用多种格式回写编辑
## Export any whiteboard as an image, or rewrite it in multiple formats

📮 **商务合作 / Business：wow.vip@foxmail.com**
🎬 **抖音 / Douyin：[v.douyin.com/07EjIDGVErY](https://v.douyin.com/07EjIDGVErY/)**

</div>

---

## 🇨🇳 中文

飞书画板技能，用于查询和编辑飞书云文档中的画板。它支持把画板导出为预览图片，供汇报或归档直接使用；也支持导出原始节点结构，方便做二次解析和迁移；写入方向则能用多种格式更新画板内容。技能开头给了快速决策与 A/B 分流：A 为只读的查看/导出（不改画板），B 为写入的创作/编辑（会改画板，命中即停），并用 Shortcuts 压缩常用路径。它明确划出边界——飞书云文档正文编辑交给 lark-doc，文档内嵌电子表格与 Base 交给 sheet / lark-base。

### ✨ 能做什么

- 查询画板内容，读取飞书云文档里的画板
- 导出画板为预览图片，直接用于汇报或归档
- 导出原始节点结构，便于二次解析与迁移
- 用多种格式写入更新画板内容
- 只读/写入分流：查看导出不改画板，创作编辑命中即停
- 边界清晰：正文编辑走 lark-doc，内嵌表格/Base 走各自技能

### 📦 包含的技能

- `lark-whiteboard` —— 见 [`lark-whiteboard/SKILL.md`](lark-whiteboard/SKILL.md)

### 🚀 安装

```bash
git clone https://github.com/yzsp-studio/lark-whiteboard.git
cp -r lark-whiteboard/* "$DSH_HOME/skills/"
```

> 技能是**纯文本说明**（`SKILL.md` + `references/`），零依赖、零 API key，用你当前 agent 的会话额度。

---

## 🇬🇧 English

A Lark Whiteboard skill for querying and editing whiteboards inside Lark cloud docs. It exports a whiteboard as a preview image you can drop straight into a report, exports the raw node structure for further parsing or migration, and writes changes back to whiteboard content in several formats. It opens with a quick decision split: A is read-only view/export that never changes the board, B is write-mode create/edit that stops for confirmation on a hit, with shortcuts for common paths. Scope is explicit — document body editing belongs to lark-doc, embedded sheets and Base belong to their own skills.

### ✨ What it does

- Query a whiteboard and read it from a Lark cloud doc
- Export the board as a preview image for reports or archives
- Export the raw node structure for parsing and migration
- Update whiteboard content using several input formats
- Read/write split: view-export never mutates, create-edit pauses on hit
- Clear scope: body text to lark-doc, embedded sheets/Base to their own skills

### 📦 Skills included

- `lark-whiteboard` — [`lark-whiteboard/SKILL.md`](lark-whiteboard/SKILL.md)

### 🚀 Install

```bash
git clone https://github.com/yzsp-studio/lark-whiteboard.git
cp -r lark-whiteboard/* "$DSH_HOME/skills/"
```

> Skills are **plain-text instructions** (`SKILL.md` + `references/`). Zero dependencies, no API keys — they run on your agent's existing session quota.

---

## 📮 联系 / Contact

| | |
|---|---|
| 🎬 **抖音 / Douyin** | [https://v.douyin.com/07EjIDGVErY/](https://v.douyin.com/07EjIDGVErY/) |
| 📮 **商务合作 / Business** | **wow.vip@foxmail.com** |
| 🐙 **GitHub** | [https://github.com/yzsp-ai](https://github.com/yzsp-ai) |
| 💖 **打赏 / Support** | [afdian.com/a/yzsp-ai](https://afdian.com/a/yzsp-ai) |

## 📄 License

[MIT](LICENSE) · © 2026 [yzsp-ai](https://github.com/yzsp-ai)
