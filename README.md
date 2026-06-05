---

# IPSTP v1.0

**Author / 作者：** Li Zhijun（李志军）
**Affiliation / 项目关联：** SGT 空能引力理论项目组（SGT Project Group）
**Email：** [lizhijun@yuantai.ac.cn](mailto:lizhijun@yuantai.ac.cn) ｜ [zhijundi@qq.com](mailto:zhijundi@qq.com)
**ORCID：** 0009-0004-8456-7107

---

# English Version

## 1. Introduction

IPSTP (Intellectual Property Space-Time Proof Protocol) is a structural protocol designed for **time-stamped intellectual property evidence generation** in theoretical research systems.

It separates:

* **Verification rights**
* **Access rights**

to enable:

> verifiable publication + protected derivation logic

without forcing full disclosure of implementation details.

This protocol is particularly designed for:

* theoretical physics
* mathematical models
* computational frameworks
* condition–conclusion systems (C → Y mappings)

---

## 2. Core Principle

IPSTP is based on three-layer separation:

### Layer A — Condition & Conclusion Layer (Public)

* Formal definition of conditions (C)
* Explicit conclusions (Y)
* Observable outputs / predictions

### Layer B — Constraint Layer (Public)

* Structural constraints
* Stability conditions
* Mapping logic description (non-code form)
* Reproducibility enabling structure

### Layer C — Implementation Layer (Private)

* Code
* Algorithms
* Numerical procedures
* Engineering details

---

## 3. Time-Space Anchoring Mechanism

IPSTP introduces dual anchoring:

### 3.1 Spatial Anchoring

* SHA-256 hash binding between Layer C and Layer A/B
* Ensures structural integrity of hidden implementation

### 3.2 Temporal Anchoring

* TSA (Trusted Timestamp Authority)
* Blockchain timestamp systems (optional)
* Preprint platform submission time (arXiv, etc.)

Result:

> A verifiable, immutable publication event

---

## 4. Evidence Structure

A valid IPSTP record requires:

1. Verifiable timestamp (external authority)
2. Hash integrity proof (SHA-256)
3. Public A+B disclosure completeness
4. Reconstructability statement (A+B sufficient for validation)

---

## 5. Priority and Attribution Logic

When similar results appear later:

* If C and Y match within tolerance → **prior disclosure assumption**
* Burden of proof shifts to later claimant
* Independent derivation must demonstrate structural independence or prior existence

This is a **forensic attribution framework**, not a legal judgment system.

---

## 6. Legal Mapping (Multi-Jurisdiction Overview)

IPSTP is designed to be compatible with:

* **China IP Law System**
* **US Copyright & Trade Secret Law**
* **UK Common Law Evidence Standards**
* **EU GDPR-compatible archival systems (data integrity layer only)**

Key mapping logic:

* Layer A/B → Public disclosure (prior art)
* Layer C → Trade secret protection
* Timestamp → Evidentiary anchor
* Hash → integrity verification

---

## 7. Usage Guide (Tools & Infrastructure)

### 7.1 Recommended Storage Platforms

**Preprint & Academic Archives**

* arXiv (Cornell University)
* SSRN
* Research Square
* Preprints.org
* OSF Preprints
* Zenodo

**Code & Version Control**

* GitHub
* GitLab
* Gitee (CN)

**Decentralized Storage**

* IPFS (InterPlanetary File System)
* Arweave (permanent storage)

---

### 7.2 Timestamp Services

* TSA (RFC 3161 compliant timestamp authority)
* OpenTimestamps
* Blockchain timestamp (Bitcoin / Ethereum anchoring)

---

### 7.3 Intellectual Property & Copyright Tools

* WIPO Proof
* Creative Commons License system
* DMCA timestamp submission systems
* National Copyright Digital Registration Centers

---

### 7.4 Layer Usage Guidelines

**Layer A (Public):**

* Publish in papers, preprints, GitHub README

**Layer B (Public):**

* Include in methodology section or appendix

**Layer C (Private):**

* Encrypt (AES-256 recommended)
* Store locally + cloud backup
* Bind hash to public document

---

## 8. Applications

IPSTP can be applied to:

* cosmology theories (e.g., SGT framework)
* mathematical conjectures
* AI model design systems
* algorithmic research
* computational physics
* proprietary scientific frameworks

---

## 9. SGT Integration

This protocol is originally developed within the context of:

> Spatial Pressure Gravitational Theory (SGT)

SGT uses IPSTP as its:

* publication structure layer
* intellectual property protection mechanism
* reproducibility + verification architecture

---

## 10. License

This protocol is released under MIT License.

Free to use, modify, and redistribute.

---

# 中文版本

## 1. 引言

IPSTP（知识产权时空证明协议）是一种用于理论研究系统的**时空证据生成协议结构**。

其核心目标是：

> 将“理论发布行为”转化为可验证的证据链结构

实现：

* 可验证公开
* 推导逻辑保护
* 时间戳确权
* 结构化归因

适用于：

* 理论物理
* 数学模型
* 计算系统
* 条件–结论型理论系统（C → Y）

---

## 2. 核心原则

IPSTP采用三层结构：

### A层（条件与结论层｜公开）

* 条件定义（C）
* 结论表达（Y）
* 可观测预测

### B层（约束结构层｜公开）

* 推导约束
* 稳定性条件
* 非代码形式逻辑结构
* 可复现支撑信息

### C层（实现层｜私有）

* 算法
* 代码
* 数值计算过程
* 工程实现细节

---

## 3. 时空锚定机制

### 空间锚定

* 使用 SHA-256 对 C/B/A 与 C 层建立唯一映射
* 防止内容篡改

### 时间锚定

* TSA时间戳认证
* 区块链存证
* arXiv / 预印本提交时间

形成：

> 不可篡改的“理论发布事件”

---

## 4. 证据结构要求

一个有效IPSTP记录必须满足：

1. 外部时间戳可验证
2. 哈希绑定不可篡改
3. A+B公开完整
4. 可重建性声明成立

---

## 5. 优先权逻辑

当后来者出现相似结果：

* 若 C 和 Y 高度一致 → 默认进入“已公开条件空间”
* 举证责任转移至后来者
* 后来者需证明独立性或时间先行性

该机制属于：

> 证据归因框架，而非法律裁决体系

---

## 6. 法律映射（跨法域）

IPSTP兼容以下体系：

* 中国知识产权法
* 美国版权与商业秘密法
* 英美普通法证据体系
* 欧盟数据完整性与存证机制

对应关系：

* A/B层 → prior art公开
* C层 → 商业秘密保护
* 时间戳 → 证据锚点
* 哈希 → 完整性证明

---

## 7. 使用指南（工具体系）

### 7.1 存档平台（必须使用）

**预印本平台**

* arXiv（核心推荐）
* SSRN
* Research Square
* Preprints.org
* OSF Preprints
* Zenodo

**代码平台**

* GitHub（核心）
* GitLab
* Gitee

**永久存储**

* IPFS
* Arweave

---

### 7.2 时间戳工具

* TSA（RFC 3161）
* OpenTimestamps
* 区块链存证（BTC / ETH）

---

### 7.3 版权与确权工具

* WIPO Proof
* Creative Commons
* 各国数字版权登记中心
* DMCA时间记录机制

---

### 7.4 分层使用方式

**A层：**
用于论文、README、公开发表

**B层：**
用于方法论说明、补充结构

**C层：**
加密存储，仅在争议或授权时使用

---

## 8. 应用领域

* 宇宙学理论（如SGT）
* 数学模型
* AI系统设计
* 算法工程
* 计算物理
* 原创理论体系保护

---

## 9. 与SGT的关系

IPSTP起源于：

> 空能引力理论（SGT）

用于支撑：

* 理论结构发布
* 证据链确权
* 推导过程保护
* 学术传播体系

---

## 10. 许可证

MIT License（开放使用）

---


