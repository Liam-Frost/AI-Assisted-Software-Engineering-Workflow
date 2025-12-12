> **Language Usage Notice**
>
> This file contains **both English and Chinese versions** of the same template.
>
> - If you choose to use the **English version**, treat the Chinese section as comments and ignore it completely.
> - If you choose to use the **Chinese version**, treat the English section as comments and ignore it completely.
>
> **Do not mix languages when filling or updating this file.**
> Always maintain a single active language version per project.

# Design Freeze

## Purpose

This document captures the **frozen design boundaries** of the project at the end of the bootstrap phase.

It answers one question:

> “What have we decided must NOT change unless we intentionally reopen design?”

Once confirmed, this document:
- Prevents silent scope expansion
- Prevents AI from inventing new architectural assumptions
- Serves as the reference point for generating the initial document pack

---

## 1. Project Intent (Frozen)

- Core problem the project solves:
- Primary users / stakeholders:
- Core value proposition (1–2 sentences):

---

## 2. Explicit Goals (Frozen)

The project explicitly aims to achieve:

- [Goal 1]
- [Goal 2]
- [Goal 3]

These goals are considered **stable for the foreseeable future**.

---

## 3. Explicit Non-Goals (Frozen)

The project explicitly does NOT aim to:

- [Non-goal 1]
- [Non-goal 2]

These are not “later” items; they are intentionally excluded.

---

## 4. Architectural Direction (High-Level, Frozen)

At a high level, the project will follow:

- Architectural style / paradigm:
- Deployment model:
- State management approach:
- Integration boundaries:

(No low-level design details here.)

---

## 5. Key Constraints (Frozen)

The following constraints are considered binding:

- [Constraint 1]
- [Constraint 2]

(These may reference PROJECT_CONTRACT.)

---

## 6. Known Unknowns (TBD)

The following items are intentionally left unresolved:

- TBD-1:
- TBD-2:

These TBDs are acceptable at this stage and must not be silently resolved later.

---

## 7. Freeze Confirmation

- Freeze confirmed by:
- Date:
- Notes (if any):

Once confirmed, changes require:
- Explicit discussion
- A new decision record (ADR or iteration-level contract)

---

_Status: Draft / Confirmed_



> **语言使用声明**
>
> 本文件同时包含**英文版与中文版**模板内容。
>
> - 若项目采用**英文版**，请将中文版视为注释并完全忽略。
> - 若项目采用**中文版**，请将英文版视为注释并完全忽略。
>
> **禁止在同一项目中混合使用两种语言填写或更新本文件。**
> 每个项目应始终只维护一个生效语言版本。

# 设计冻结（DESIGN_FREEZE）

## 文档目的

本文档用于记录项目在启动期结束时**已冻结的设计边界**。

它回答一个问题：

> “哪些设计决策在未明确重新讨论前，不应再发生变化？”

一旦确认，本文件将：
- 防止范围悄然扩张
- 防止 AI 自动引入新的架构假设
- 作为生成初始文档包的参考基准

---

## 1. 项目意图（已冻结）

- 项目解决的核心问题：
- 主要用户 / 利益相关方：
- 核心价值主张（1–2 句话）：

---

## 2. 明确目标（已冻结）

项目明确要实现的目标包括：

- [目标 1]
- [目标 2]
- [目标 3]

这些目标在可预见周期内被视为稳定。

---

## 3. 明确非目标（已冻结）

项目明确**不打算**实现：

- [非目标 1]
- [非目标 2]

这些不是“以后再做”，而是有意排除。

---

## 4. 架构方向（高层，已冻结）

项目在高层将遵循：

- 架构风格 / 范式：
- 部署模式：
- 状态管理方式：
- 集成边界：

（不写具体实现细节。）

---

## 5. 关键约束（已冻结）

以下约束被视为必须遵守：

- [约束 1]
- [约束 2]

（必要时引用 PROJECT_CONTRACT。）

---

## 6. 已知未知（TBD）

以下问题在当前阶段被刻意保留为未决：

- TBD-1：
- TBD-2：

这些 TBD 在当前阶段是允许存在的，不得在后续悄然补全。

---

## 7. 冻结确认

- 确认人：
- 日期：
- 备注（如有）：

冻结后如需变更，必须：
- 显式讨论
- 形成新的决策记录（ADR 或迭代级 Contract）

---

_状态：Draft / Confirmed_
