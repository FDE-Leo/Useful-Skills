---
name: "quick-init-project"
description: "快速初始化项目环境：安装配置 context-engineer 并下载 skill-creator 参考文档。当用户需要搭建项目知识库基础设施或初始化开发环境时调用。"
---

# Quick Init Project

快速初始化项目的标准流程，包含两步：安装配置 context-engineer，以及下载 skill-creator 参考文档。

## 步骤 1：安装并配置 context-engineer

阅读 `https://github.com/FDE-Leo/Useful-Skills/blob/main/Context-Engineer/SKILL.md`，并按照其中的说明安装和配置 context-engineer。

## 步骤 2：下载 skill-creator 参考文档

完成步骤 1 后，下载 `https://github.com/anthropics/skills/blob/main/skills/skill-creator/SKILL.md`，并保存到 `context-engineer/references` 目录中。

## 步骤 3：用户引导
完成步骤 2 后，向用户说明你现在能做什么（即 context-engineer 提供的各项能力）。

并告诉用户一个创建 context 仓库示例，例如向 AI 说"帮我搭一个 context 仓库，我是做 xxx 的。"