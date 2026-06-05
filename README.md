

# IPSTP v1.0

## Knowledge Space-Time Proof Protocol

## 知识产权时空证明协议

---

## **1. 项目简介**

IPSTP（Intellectual Property Space-Time Proof Protocol，知识产权时空证明协议）是一种用于科研成果发布与知识产权证据化的结构化协议。

其核心目标是：

* 将科研成果拆分为可验证结构
* 分离“科学结论”和“实现过程”
* 构建可追溯时间戳证据链
* 支持 GitHub / arXiv / DOI / TSA 联合发布

---

## **2. 核心理念**

IPSTP基于一个基本原则：

> 科学结论应公开可验证，计算实现可以选择性保密。

因此将所有内容拆分为三层：

---

## **3. 三层结构说明**

### **A层：条件与结论层（必须公开）**

包含：

* 理论假设（C）
* 数学模型定义
* 参数体系
* 最终结论（Y）
* 可验证预测结果

👉 作用：定义“你提出了什么”

---

### **B层：约束结构层（必须公开）**

包含：

* 模型约束条件
* 不变量结构
* 稳定性条件
* 收敛性条件（非算法）

👉 作用：解释“为什么结论成立”

---

### **C层：实现层（默认保密）**

包含：

* 数值计算代码
* 仿真程序
* 工程实现路径
* 优化算法细节

👉 作用：实现“如何计算”

⚠️ C层不影响科学结论的可验证性，可选择不公开。

---

## **4. 如何使用 IPSTP**

---

## **Step 1：编写论文结构**

论文必须按照以下结构组织：

```
1. A层：模型与结论
2. B层：约束与逻辑结构
3. C层：实现说明（可选）
```

---

## **Step 2：生成时间锚点（Time Anchor）**

必须选择至少一种可信时间戳来源：

### 推荐方式：

* arXiv submission timestamp
* Zenodo DOI timestamp
* OSF Preprints timestamp
* TSA（可信时间戳服务 RFC3161）
* Git commit history
* 区块链存证（Bitcoin / Ethereum）

---

## **Step 3：生成空间锚定（Hash Binding）**

对 A层 + B层 +（可选C层）进行：

```
SHA-256 hash
```

用于确保内容不可篡改。

---

## **Step 4：形成 VDE（可验证公开事件）**

当同时满足以下条件时：

* A/B层公开
* 时间戳生成成功
* Hash绑定完成
* 可被第三方复现

定义为：

> **VDE（Verifiable Disclosure Event）可验证公开事件**

---

## **5. GitHub仓库推荐结构**

```
IPSTP/
│
├── A_layer/
│   └── paper_main.md
│
├── B_layer/
│   └── constraints.md
│
├── C_layer_private/
│   └── encrypted_code.zip
│
├── evidence/
│   ├── hash.txt
│   ├── timestamp.txt
│   └── vde_record.json
│
├── templates/
│   └── ipstp_paper_template.md
│
├── examples/
│   └── SGT_demo.md
│
└── README.md
```

---

## **6. 如何写一篇 IPSTP 论文**

在论文开头加入：

```
本文遵循 IPSTP v1.0（知识产权时空证明协议）框架发布。
```

---

## **标准论文结构：**

### 1. Introduction

* 问题背景
* CCTS系统定义

### 2. A层（模型与结论）

* 条件C
* 结论Y

### 3. B层（约束结构）

* 模型约束
* 理论稳定性解释

### 4. VDE信息

* 时间戳来源
* SHA-256哈希值
* GitHub / DOI链接

### 5. （可选）C层说明

* 是否公开
* 是否加密
* 是否保留

---

## **7. 推荐发布平台**

### 学术预印本平台（优先）

* arXiv.org（最重要）
* OSF Preprints
* Research Square
* SSRN
* Zenodo（自动生成 DOI）
* HAL（法国国家仓库）
* bioRxiv（生物）
* medRxiv（医学）
* ChemRxiv（化学）
* EarthArXiv（地球科学）
* SocArXiv（社会科学）
* engrXiv（工程）
* TechRxiv（IEEE）
* Preprints.org（多学科）

---

### 代码与证据存储平台

* GitHub（主发布）
* GitLab（备份）
* IPFS（去中心化存储）
* Arweave（永久存储）

---

### 时间戳与证据工具

* TSA可信时间戳服务（RFC3161）
* OpenTimestamps（Bitcoin）
* WIPO Proof
* Ethereum / Polygon timestamping
* 国家级电子证据平台

---

## **8. 法律与学术定位**

IPSTP不提供法律权利声明，仅提供：

* 结构化科学证据格式
* 可验证时间记录
* prior-art 记录结构
* 跨平台一致性证明机制

知识产权归属仍由现行法律体系决定。

---

## **9. 使用规则总结**

一句话总结：

> IPSTP = 科学内容结构化 + 时间锚定 + 哈希绑定 + 可验证发布事件

---

## **10. 许可证（License）**

本协议及说明文档：

* 可自由使用
* 可自由修改
* 可用于学术与工程用途
* 建议保留引用来源

---

## **11. 版本信息**

* IPSTP v1.0
* 发布方式：GitHub Open Repository
* 作者：李志军（SGT项目组）

---

## **12. 一句话核心定义**

> IPSTP的本质，是把“科研发表行为”变成“可验证的时间锚定证据事件”。

---
