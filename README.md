# Health Archive Builder (个人健康档案全程教练)

这是一个帮助你从零搭建个人健康管理系统的 AI 技能。它不仅是一个"档案整理员"，更是一个"健康教练"，能指引你完成从体检规划、数据采集、档案建立到日常 AI 协同分析的全流程。

## 适用人群

- 想要系统管理自己健康数据的人。
- 想要了解如何科学体检、如何配置智能穿戴设备的人。
- 想要将零散的体检报告转化为结构化《个人健康百科全书》的人。

## 核心功能

1. **体检与复查指引**：按重要性排序推荐必查项目。
2. **苹果健康数据导出**：指导你如何导出并利用日常穿戴数据。
3. **智能穿戴设备配置**：推荐 Apple Watch、CGM 动态血糖仪、智能体脂秤。
4. **AI 协同管理**：教你如何结合 Kimi、Manus、PlanClaw 进行日常健康管理。
5. **结构化建档**：将你的体检报告和穿戴数据整理成一份《个人健康百科全书》。
6. **持续更新与预测**：每次更新数据后，提供对比分析和 3 个月行动预测。

## 🚀 如何安装与使用

### 方式一：通过 ClawHub 安装 (推荐)

如果你使用的是 **OpenClaw** 个人智能助理，可以通过 ClawHub 直接安装本技能：

**在 OpenClaw 聊天框中输入：**
```text
/install https://github.com/yewubin-jpg/health-archive-builder
```

**或者在终端中运行：**
```bash
clawhub install https://github.com/yewubin-jpg/health-archive-builder
```

### 方式二：手动导入 Manus 等工具

1. 下载本仓库的 ZIP 包并解压。
2. 将解压后的文件夹导入到支持 Agent Skills 格式的 AI 工具中（如 Manus）。

### 触发方式

安装完成后，在对话框中输入以下任意一句话触发技能：
- "帮我整理体检报告"
- "建立我的健康档案"
- "对比我的历史体检数据"
- "更新最新复查指标"

按照 AI 助手的引导，上传你的体检报告（PDF或图片）、苹果健康数据截图，或者直接语音留言你的健康状况。接收你的专属《个人健康百科全书》。

## 目录结构

- `SKILL.md`：技能的主入口，包含核心构建原则和工作流。
- `references/coaching_guide.md`：教练指南，包含体检项目清单、设备推荐与 AI 协同指南。
- `templates/archive_template.md`：标准档案模板。
- `templates/initial_prompt.md`：初始对话脚本模板。
- `templates/update_prompt.md`：更新对话脚本模板。
