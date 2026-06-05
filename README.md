# Intellectual Property Space-Time Proof Protocol (IPSTP)

## Protocol Repository

**Author:** Li Zhijun
**ORCID:** 0009-0004-8456-7107

---

# 1. Repository Purpose

This repository defines and maintains the **Intellectual Property Space-Time Proof Protocol (IPSTP)**.

IPSTP is a structured framework for organizing scientific and theoretical outputs into verifiable, time-stamped, and tamper-evident evidence chains.

It is not a scientific theory itself, but a **meta-level protocol for publishing, storing, and attributing theoretical work**.

Primary objectives:

* Establish verifiable publication timestamps
* Separate verification rights from access rights
* Preserve proprietary implementation while enabling reproducibility
* Provide structured evidence for authorship attribution
* Support cross-platform archival (GitHub, arXiv, OSF, etc.)

---

# 2. Core Design Principle

IPSTP is built on a dual-axis model:

### Spatial Anchoring (Content Integrity)

* Hash-based binding of documents
* Ensures content immutability after publication
* Enables cryptographic verification of originality

### Temporal Anchoring (Publication Time)

* External timestamp services (TSA, blockchain, preprint servers)
* Establishes verifiable publication chronology
* Prevents retroactive modification of authorship claims

Together, they form a **Space–Time Evidence Grid** for intellectual output.

---

# 3. Three-Layer Structure

All IPSTP-compliant works are organized into three layers:

### Layer A — Condition & Conclusion Layer (Public)

* Formal definitions of conditions (C)
* Final results / conclusions (Y)
* Minimal reproducibility description

### Layer B — Constraint Layer (Public)

* Structural constraints
* Invariance conditions
* Validity domains
* Non-algorithmic derivation logic

### Layer C — Implementation Layer (Private / Encrypted)

* Full computational procedures
* Numerical algorithms
* Source code and engineering details
* Stored separately with cryptographic protection

Layer C is not required for validation.

---

# 4. Evidence Chain Model

A valid IPSTP record must include:

* External timestamp (TSA / arXiv / OSF / blockchain)
* Hash binding of published content
* Explicit Layer A + B disclosure
* Optional Layer C encrypted archival reference

This forms a **verifiable evidence chain**, not merely a publication record.

---

# 5. Repository Contents

```text
/protocols/
    IPSTP specification documents
    TAP / IPSTP derivatives

/papers/
    Works published under IPSTP framework

/evidence/
    Hash records, timestamps, archival proofs

/archives/
    Encrypted Layer C materials

/appendix/
    Technical notes and extended derivations

/docs/
    Protocol documentation and usage guidelines
```

---

# 6. Usage Scope

IPSTP applies to:

* Deterministic theoretical systems
* Condition–conclusion mapping models
* Mathematical or physical frameworks with reproducible outputs

IPSTP does NOT apply to:

* Pure experimental studies
* Black-box machine learning models
* Non-reproducible empirical claims
* Pure mathematical proofs without computational structure

---

# 7. External Archival Strategy

IPSTP is designed for multi-platform synchronization:

* GitHub (version control + distribution)
* arXiv (academic timestamping)
* OSF / Preprints (open dissemination)
* Blockchain timestamp services (immutability layer)
* Local encrypted backups (Layer C preservation)

---

# 8. Legal Positioning

IPSTP does not create new legal rights.

It functions as a **structured evidence generation protocol**.

Legal interpretation depends on applicable jurisdiction and existing intellectual property laws.

---

# 9. Citation

Li, Z.

Intellectual Property Space-Time Proof Protocol (IPSTP)

GitHub Repository

---

# 10. Contact

Email:

* [lizhijun@yuantai.ac.cn](mailto:lizhijun@yuantai.ac.cn)
* [zhijundi@qq.com](mailto:zhijundi@qq.com)

ORCID:
0009-0004-8456-7107

---

---

# 中文版本

# 知识产权时空证明协议（IPSTP）

## 协议型仓库说明

**作者：李志军**

---

# 1. 仓库用途

本仓库用于定义与维护**知识产权时空证明协议（IPSTP）**。

IPSTP是一套用于科学理论与技术成果的结构化发布与存证框架。

其本质不是某一科学理论，而是：

> 用于理论发布、存证、归因与证据链构建的元协议系统。

核心目标：

* 建立可验证时间戳体系
* 分离验证权与访问权
* 保留实现细节同时保证可复现性
* 支持跨平台存证
* 提供可用于归因争议的结构化证据链

---

# 2. 核心设计原则

IPSTP基于双轴结构：

### 空间锚定（内容完整性）

* 哈希绑定确保内容不可篡改
* 保证发布内容唯一性

### 时间锚定（发布时间）

* 通过第三方时间戳系统建立时间记录
* 防止事后篡改发布时间

两者共同构成：

> 空间–时间证据网格体系

---

# 3. 三层结构

所有IPSTP内容分为三层：

### A层：条件与结论（公开）

* 理论条件C
* 结论Y
* 最小可复现信息

### B层：约束框架（公开）

* 不变量结构
* 适用条件
* 结构性约束

### C层：实现层（保密）

* 算法细节
* 数值实现
* 工程代码

C层不影响基础验证成立。

---

# 4. 证据链结构

完整IPSTP证据链包含：

* 外部时间戳
* 内容哈希绑定
* A+B层完整公开
* C层加密存证（可选）

形成：

> 可验证的证据链，而非单纯论文发表记录

---

# 5. 适用范围

适用于：

* 确定性理论系统
* 条件–结论映射模型
* 可复现计算体系

不适用于：

* 纯实验研究
* 黑箱AI模型
* 不可复现经验性结论

---

# 6. 法律说明

IPSTP不创设法律权利。

其作用是：

> 提供结构化证据生成与存证机制

最终法律效力依赖现行司法体系认定。

---

# 7. 引用方式

Li, Z.

IPSTP Protocol Repository

GitHub
