<div align="center">

# spring-skills

**Spring Boot ecosystem skills — Boot, Cloud, AI, Security, Data JPA**

[![GitHub](https://img.shields.io/badge/github-full--stack--skills%2Fspring-skills-green.svg)](https://github.com/full-stack-skills/spring-skills)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Agent Skills](https://img.shields.io/badge/Agent%20Skills-兼容-purple.svg)](https://agentskills.io)

[English](./README.md) | 简体中文

[简介](#-简介) ·
[安装](#-安装) ·
[技能列表](#-技能列表) ·
[支持的智能体](#-支持的智能体) ·
[生态](#-生态)

</div>

---

## 📖 简介

**Spring Boot 技能** 是一组 AI 编码智能体技能，属于 [Full Stack Skills](https://github.com/partme-ai/full-stack-skills) 生态，由 [PartMe.AI](https://github.com/partme-ai) 维护。

本包包含 **7 个技能**。每个技能是一个独立的 `SKILL.md` 文件，AI 智能体按需加载。

## 📦 安装

```bash
npx skills add full-stack-skills/spring-skills
```

或按需安装特定技能：

```bash
npx skills add full-stack-skills/spring-skills --skill <skill-name>
```

## 🎯 技能列表 (7)

| 技能 | 描述 |
|------|------|
| `spring-ai-alibaba` | Provides comprehensive guidance for Spring AI Alibaba including Alibaba Cloud AI services integration, model APIs, an... |
| `spring-ai` | Provides comprehensive guidance for Spring AI including AI model integration, prompt templates, vector stores, and AI... |
| `spring-boot` | Provides comprehensive guidance for Spring Boot development including project creation, auto-configuration, dependenc... |
| `spring-cloud-alibaba` | Provides comprehensive guidance for Spring Cloud Alibaba including Nacos, Sentinel, RocketMQ, and Alibaba Cloud integ... |
| `spring-cloud` | Provides comprehensive guidance for Spring Cloud microservices including service discovery, configuration management,... |
| `spring-data-jpa` | Provides comprehensive guidance for Spring Data JPA including repositories, entity management, query methods, and dat... |
| `spring-security` | Provides comprehensive guidance for Spring Security including authentication, authorization, OAuth2, JWT, and securit... |

## 🤖 支持的智能体

适用于 [Claude Code](https://code.claude.com)、[Codex](https://developers.openai.com/codex)、[Cursor](https://cursor.com)、[OpenCode](https://opencode.ai)、[Gemini CLI](https://geminicli.com)、[GitHub Copilot](https://github.com/features/copilot)、[Windsurf](https://codeium.com/windsurf) 及 [70+ 其他平台](https://agentskills.io/clients)。

### Claude Code 安装

**方式一：npx skills CLI（推荐）**

```bash
npx skills add full-stack-skills/spring-skills
```

**方式二：手动安装**

```bash
git clone https://github.com/full-stack-skills/spring-skills.git
cp -r spring-skills/skills/* .claude/skills/
```

更多详情请参阅 [Claude Code 技能指南](https://code.claude.com/docs/en/skills) 和 [Agent Skills 规范](https://agentskills.io/)。

## 🌐 生态

| 资源 | 链接 |
|------|------|
| **Full Stack Skills** | [github.com/partme-ai/full-stack-skills](https://github.com/partme-ai/full-stack-skills) |
| **全部技能组** | [github.com/full-stack-skills](https://github.com/full-stack-skills) |
| **Agent Skills 规范** | [agentskills.io](https://agentskills.io) |
| **Skills CLI** | [github.com/vercel-labs/skills](https://github.com/vercel-labs/skills) |

## 📄 许可证

Apache 2.0 — 详见 [LICENSE](LICENSE)。
