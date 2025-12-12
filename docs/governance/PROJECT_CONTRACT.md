> **Language Usage Notice**
>
> This file contains **both English and Chinese versions** of the same template.
>
> - If you choose to use the **English version**, treat the Chinese section as comments and ignore it completely.
> - If you choose to use the **Chinese version**, treat the English section as comments and ignore it completely.
>
> **Do not mix languages when filling or updating this file.**
> Always maintain a single active language version per project.

# Project Contract

## Purpose

This document defines the **hard constraints** of the project.

It serves as the project’s constitutional layer:
- What must never change
- What is explicitly forbidden
- What all future decisions and implementations must comply with

If there is any conflict between:
- code
- discussions
- iteration documents
- AI suggestions

**This document takes precedence.**

---

## 1. Invariants (Must Always Hold)

The following actions are explicitly forbidden unless this document is formally updated:

- Mixing English and Chinese content within the same active project files
  (violating the Language Usage Notice of bilingual templates).
- [Invariant 1 — describe precisely]
- [Invariant 2]
- [Invariant 3]

Notes:
- Invariants are stable properties of the system.
- If an invariant needs to change, that is a **project-level decision**, not an iteration-level change.

---

## 2. Forbidden Actions (Explicitly Disallowed)

The following actions are explicitly forbidden unless this document is formally updated:

- [Forbidden action 1]
- [Forbidden action 2]
- [Forbidden action 3]

Examples (replace with project-specific rules):
- Changing public APIs without a major version bump
- Altering persisted data schema without migration strategy
- Introducing a new runtime dependency category

---

## 3. Non-Goals (Permanent)

The project explicitly does **not** aim to support or provide:

- [Non-goal 1]
- [Non-goal 2]

These are not “out of scope for now” items; they are intentionally excluded.

---

## 4. Stability Expectations

This project prioritizes:

- [ ] Long-term maintainability
- [ ] Backward compatibility
- [ ] Deterministic behavior
- [ ] Explicit over implicit behavior

(Check and adapt as appropriate.)

---

## 5. How This Document Changes

- Changes to this document are **rare**.
- Any change requires:
  - An explicit decision record (ADR)
  - A clear migration or impact plan
- Iteration-level documents must not override this contract.

---

_Last updated: YYYY-MM-DD_



> **语言使用声明**
>
> 本文件同时包含**英文版与中文版**模板内容。
>
> - 若项目采用**英文版**，请将中文版视为注释并完全忽略。
> - 若项目采用**中文版**，请将英文版视为注释并完全忽略。
>
> **禁止在同一项目中混合使用两种语言填写或更新本文件。**
> 每个项目应始终只维护一个生效语言版本。

# 项目宪章（Project Contract）

## 文档目的

本文档定义项目的**硬约束（Hard Constraints）**。

它是项目的“宪法层”，用于明确：
- 什么永远不能变
- 什么被明确禁止
- 所有后续决策和实现必须遵守的边界

当以下内容发生冲突时：
- 代码
- 聊天讨论
- 迭代文档
- AI 的建议

**以本文件为最高优先级。**

---

## 1. 不变量（必须始终成立）

以下不变量在任何情况下都不得被破坏：

- [不变量 1 —— 精确定义]
- [不变量 2]
- [不变量 3]

说明：
- 不变量是系统的稳定属性
- 如果需要修改不变量，属于**项目级决策**，而不是普通迭代修改

---

## 2. 明确禁止的行为

除非正式修改本文件，以下行为被明确禁止：

- 在同一项目的生效文件中混合使用中英文内容
  （违反双语模板中的语言使用声明）。
- [禁止行为 1]
- [禁止行为 2]
- [禁止行为 3]

示例（请替换为项目实际规则）：
- 未进行版本升级即破坏公共 API
- 未提供迁移方案即修改持久化数据结构
- 引入新的运行时依赖类型

---

## 3. 永久性非目标（Non-Goals）

本项目明确**不打算**支持或提供以下内容：

- [非目标 1]
- [非目标 2]

这些不是“暂不支持”，而是有意排除。

---

## 4. 稳定性预期

本项目优先考虑：

- [ ] 长期可维护性
- [ ] 向后兼容性
- [ ] 行为确定性
- [ ] 显式优于隐式

（按项目需要勾选或补充。）

---

## 5. 修改规则

- 本文档的修改应当非常少见
- 任何修改必须：
  - 有明确的架构/决策记录（ADR）
  - 有清晰的影响或迁移说明
- 任何迭代文档不得覆盖本宪章的约束

---

_最后更新：YYYY-MM-DD_
