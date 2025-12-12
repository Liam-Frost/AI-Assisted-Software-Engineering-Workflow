> **Language Usage Notice**
>
> This file contains **both English and Chinese versions** of the same template.
>
> - If you choose to use the **English version**, treat the Chinese section as comments and ignore it completely.
> - If you choose to use the **Chinese version**, treat the English section as comments and ignore it completely.
>
> **Do not mix languages when filling or updating this file.**
> Always maintain a single active language version per project.

# Smoke Checklist

## Purpose

This checklist defines the **minimum safety checks** that must pass after any change.

Its goal is not completeness, but to ensure:
- The system still runs
- Core paths are not broken
- No obvious regression was introduced

---

## When to Run

- After any PR is merged
- Before tagging a release
- Before starting a new iteration (optional but recommended)

---

## Smoke Checks

### Environment & Startup

- [ ] Project builds successfully
- [ ] Application starts without fatal errors
- [ ] Required environment variables are documented and present

---

### Core Functionality

- [ ] Primary user flow works end-to-end
- [ ] No runtime exceptions in common paths
- [ ] Basic error handling behaves as expected

---

### Data & State (if applicable)

- [ ] No unexpected data loss
- [ ] Existing data remains readable
- [ ] State transitions are sane

---

### Observability (if applicable)

- [ ] Logs are emitted for key actions
- [ ] Errors are visible and understandable

---

## Notes

- Passing smoke checks does NOT imply acceptance criteria are met
- Smoke checks are intentionally shallow
- Add checks sparingly; keep this list lightweight



> **语言使用声明**
>
> 本文件同时包含**英文版与中文版**模板内容。
>
> - 若项目采用**英文版**，请将中文版视为注释并完全忽略。
> - 若项目采用**中文版**，请将英文版视为注释并完全忽略。
>
> **禁止在同一项目中混合使用两种语言填写或更新本文件。**
> 每个项目应始终只维护一个生效语言版本。

# Smoke 检查清单

## 文档目的

本清单定义每次变更后必须通过的**最低安全检查**。

目标不是覆盖所有情况，而是确保：
- 系统还能运行
- 核心路径没有被破坏
- 没有明显的回归问题

---

## 运行时机

- 每次 PR 合并后
- 发布版本前
- 开始新一轮迭代前（可选但推荐）

---

## Smoke 检查项

### 环境与启动

- [ ] 项目可以成功构建
- [ ] 应用可正常启动，无致命错误
- [ ] 所需环境变量已记录且存在

---

### 核心功能

- [ ] 主要用户流程可端到端运行
- [ ] 常见路径下无运行时异常
- [ ] 基本错误处理符合预期

---

### 数据与状态（如适用）

- [ ] 未发生意外的数据丢失
- [ ] 现有数据仍可正常读取
- [ ] 状态流转合理

---

### 可观测性（如适用）

- [ ] 关键操作有日志输出
- [ ] 错误可被发现且可理解

---

## 备注

- 通过 smoke 检查 ≠ 通过验收
- smoke 检查刻意保持浅层
- 谨慎添加条目，保持清单轻量
