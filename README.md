# 🧠 AI Learning Notes

我的 AI 学习笔记仓库，记录学习过程中的理解、实验和思考。

## 📁 目录结构

```
ai-learning-notes/
├── MCP/                              # Model Context Protocol
├── cc-suite/                         # Claude ↔ Codex 协作
├── Git/                              # Git 版本控制 · 学习地图
├── command-line/                     # 命令行工具 · 学习地图
├── Claude-Code/                      # Claude Code 参数 · 学习地图
├── testing/                          # 基于测试的开发流程 · 学习地图
├── mindset-generation-prompt-template/   # 生成学习地图用的提示词模板
└── README.md
```

## 📝 文章列表

### MCP（Model Context Protocol）
| 文章 | 简介 | 日期 |
|------|------|------|
| [MCP 三层解释：从简单到专家](./MCP/MCP三层解释-从简单到专家.md) | 从12岁小孩到专家级，三个层次理解 MCP | 2026-03 |
| [我是怎么在一天内搞懂 MCP 的](./MCP/我是怎么在一天内搞懂MCP的.md) | 实践笔记，通过 Codex Octopus 和 VMark MCP 上手体验 | 2026-06 |

### cc-suite（Claude ↔ Codex 协作）
| 文章 | 简介 | 日期 |
|------|------|------|
| [我是怎么用 cc-suite 把 Claude 和 Codex 接起来的](./cc-suite/我是怎么用cc-suite把Claude和Codex接起来的.md) | 实践笔记，走完 init → audit → implement → verify 一整套流程 | 2026-07 |

### Git 版本控制
| 文章 | 生成模型 | 日期 |
|------|------|------|
| [Git 版本控制 · 学习地图](<./Git/Git版本控制-mindset（Opus 5）.md>) | Claude Opus 5 | 2026-08 |
| [Git 版本控制基础](<./Git/Git 版本控制基础（Claude code）.md>) | Claude Code | 2026-08 |
| [Git 版本控制基础](<./Git/Git版本控制基础（codex）.md>) | Codex | 2026-08 |
| [Git 版本控制学习地图](<./Git/Git版本控制学习地图（ChatGPT）.md>) | ChatGPT | 2026-08 |

### 命令行工具
| 文章 | 生成模型 | 日期 |
|------|------|------|
| [命令行工具基础 · 学习地图](<./command-line/命令行工具基础-mindset（Opus 5）.md>) | Claude Opus 5 | 2026-08 |
| [命令行工具基础 · 学习地图](<./command-line/命令行工具基础-mindset（Claude code）.md>) | Claude Code | 2026-08 |
| [命令行工具基础 · 心智模型](<./command-line/命令行工具基础-心智模型（chatgpt）.md>) | ChatGPT | 2026-08 |
| [命令行工具基础](<./command-line/命令行工具基础（codex）.md>) | Codex | 2026-08 |

### Claude Code
| 文章 | 生成模型 | 日期 |
|------|------|------|
| [Claude 命令最重要的参数 · 学习地图](<./Claude-Code/Claude命令最重要的参数-mindset（Opus 5）.md>) | Claude Opus 5 | 2026-08 |
| [claude CLI 常用参数](<./Claude-Code/claude-cli-常用参数（Claude code）.md>) | Claude Code | 2026-08 |
| [Claude 命令最重要参数](<./Claude-Code/Claude命令最重要参数（codex）.md>) | Codex | 2026-08 |

### 基于测试的开发流程
| 文章 | 生成模型 | 日期 |
|------|------|------|
| [基于测试的开发流程 · 学习地图](<./testing/基于测试的开发流程-mindset（Opus 5）.md>) | Claude Opus 5 | 2026-08 |

## 🗺️ 关于「学习地图」系列

`Git/`、`command-line/`、`Claude-Code/`、`testing/` 这几个目录，用的是同一套方法：

- 提示词模板放在 [`mindset-generation-prompt-template/`](./mindset-generation-prompt-template/)
- 核心假设是**具体操作交给 AI**，所以不从安装、命令、语法讲起
- 目标是建立 **Mental Model（心智模型）** 与 **World Model（世界模型）**：它是什么、为什么存在、什么时候该想到它
- 同一个主题会用**不同模型各生成一份**（Opus 5 / Claude Code / Codex / ChatGPT），横向对比各家的理解差异——这本身也是一种学习

## 🚀 关于这个仓库

- 笔记以中文为主
- 内容来自实际使用和学习过程，不是搬运
- 持续更新中

---

> 学 AI 最好的方式，就是用 AI 学 AI。
