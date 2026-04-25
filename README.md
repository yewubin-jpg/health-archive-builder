# Health Archive Builder · 个人健康百科构建师

> 由**易效能创始人 叶武滨**设计的个人健康档案 AI 教练。
> 通过对方口述病史 + 上传体检报告，AI 自动生成一份结构化、循证、可追踪的《个人健康百科全书》，并附带定制版"全天高能量节律方案"。

---

## 🚀 一分钟选对文件（按平台对号入座）

| 你用的平台 | 推荐下载文件 | 使用方式 |
| :--- | :--- | :--- |
| 🟣 **Kimi**（月之暗面） | [`健康百科构建师_完整指令_脱敏版.md`](./健康百科构建师_完整指令_脱敏版.md) | 单文件，全文复制粘贴到 Kimi 对话框 |
| 🟢 **ChatGPT**（普通版） | [`健康百科构建师_完整指令_脱敏版.md`](./健康百科构建师_完整指令_脱敏版.md) | 单文件，全文复制粘贴或上传为知识库 |
| 🟢 **ChatGPT GPTs**（自定义 GPT） | [`健康百科构建师_完整指令_脱敏版.md`](./健康百科构建师_完整指令_脱敏版.md) | 粘贴到 GPT 的 Instructions 字段 |
| 🟠 **DeepSeek / 豆包 / 通义千问** | [`健康百科构建师_完整指令_脱敏版.md`](./健康百科构建师_完整指令_脱敏版.md) | 单文件，全文复制粘贴 |
| 🔵 **Claude.ai**（Projects） | [`健康百科构建师_完整指令_脱敏版.md`](./健康百科构建师_完整指令_脱敏版.md) | 上传到 Project Knowledge |
| 🟡 **Claude Skills**（Anthropic Skills） | 整个仓库的 `SKILL.md + references/ + templates/` | 下载完整仓库作为 Skill 目录导入 |
| 🟡 **Manus** | 整个仓库（含 `SKILL.md`） | 下载完整仓库作为 Skill 安装 |
| 🟡 **OpenClaw** | 整个仓库（含 `SKILL.md`） | 通过 `/install` 命令一键安装 |

> **简单口诀**：
> - **聊天框 / 单段提示词** 类平台 → 只下 1 个文件 (`健康百科构建师_完整指令_脱敏版.md`)
> - **支持 Skill 目录结构** 类平台（Claude Skills / Manus / OpenClaw）→ 下载整个仓库

---

## 📂 仓库文件说明

| 文件 / 目录 | 用途 | 适用平台 |
| :--- | :--- | :--- |
| `健康百科构建师_完整指令_脱敏版.md` | **单文件汇总版**：人设 + 工作流 + 输出骨架 + 判读规则 | Kimi / ChatGPT / DeepSeek / Claude.ai 等聊天框平台 |
| `SKILL.md` | Skill 主指令文件（Anthropic Skill 格式） | Claude Skills / Manus / OpenClaw |
| `references/coaching_guide.md` | 体检项目清单、设备推荐、AI 协同指南 | Skill 平台引用 |
| `templates/archive_template.md` | 标准健康百科档案骨架模板 | Skill 平台引用 |
| `templates/initial_prompt.md` | 首次建档对话脚本 | Skill 平台引用 |
| `templates/update_prompt.md` | 复查更新对话脚本 | Skill 平台引用 |
| `LICENSE` | MIT 开源协议 | — |

---

## 🟣 Kimi / ChatGPT / DeepSeek 用户：3 步上手

1. **下载**：点击 [`健康百科构建师_完整指令_脱敏版.md`](./健康百科构建师_完整指令_脱敏版.md) → 右上角 `Raw` → 全选复制
2. **粘贴**：在 Kimi（或其他平台）新建对话，把全文粘贴进去发送
3. **对话**：直接输入"开始"，AI 会主动引导你上传体检报告并生成专属健康百科

> 💡 **进阶用法（Kimi 智能体）**：在 Kimi 中创建一个"智能体"，把这份指令贴到 System Prompt 里，可以反复调用。

---

## 🟡 Claude Skills / Manus / OpenClaw 用户：导入完整 Skill

### 方式 A：OpenClaw 一键安装（最简单）

在 OpenClaw 聊天框中输入：
```
/install https://github.com/yewubin-jpg/health-archive-builder
```

或在终端：
```bash
clawhub install https://github.com/yewubin-jpg/health-archive-builder
```

### 方式 B：手动导入（Manus / Claude Skills）

```bash
git clone https://github.com/yewubin-jpg/health-archive-builder.git
```

或点击仓库右上角 `Code → Download ZIP`，解压后将整个目录作为 Skill 导入对应平台。

### 触发方式

安装完成后，在对话框中输入以下任意一句话即可触发：
- "帮我整理体检报告"
- "建立我的健康档案"
- "对比我的历史体检数据"
- "更新最新复查指标"

---

## 🌟 它能为你做什么？

- ✅ **资料结构化**：把零散的体检报告、复查单、穿戴数据整理成一份《个人健康百科全书》
- ✅ **历史对比**：所有指标用"原值 🆚 现值"格式呈现，直观看到改善轨迹
- ✅ **循证建议**：基于第一性原理 + 性价比矩阵，输出睡眠、运动、饮食、控糖的执行级方案
- ✅ **3 个月预测**：基于当前指标，预测健康行为坚持后的指标改善
- ✅ **全天能量节律**：从起床到入睡的 17 小时高能量时间表，告别"累、困、饿、犯困"

---

## 🛡 隐私与安全

- 本仓库所有文件**完全脱敏**，不含任何真实姓名、机构、个人数据
- 你与 AI 对话生成的健康百科**仅存在于你的对话记录中**，不会上传到本仓库
- 建议在私密环境使用，敏感数据请遵守对应 AI 平台的隐私协议

---

## 📜 协议与署名

- **作者**：叶武滨（易效能 Yixiaoneng 创始人）
- **协议**：MIT License
- **欢迎 Star、Fork、二次开发**，使用时请保留作者署名

---

> 🌱 **慢就是快。健康是 1，其他都是 0。**
> —— 叶武滨
