# 科学代理技能集

> **🔔 Claude Scientific Skills 现已更名为 Scientific Agent Skills。** 技能相同，兼容性更广 — 现在可与任何支持开放 [Agent Skills](https://agentskills.io/) 标准的 AI 代理配合使用，不仅限于 Claude。

> **新增：[K-Dense BYOK](https://github.com/K-Dense-AI/k-dense-byok)** — 一款在您的桌面上运行的免费开源 AI 共同科学家，由 Scientific Agent Skills 驱动。自带 API 密钥，从 40+ 模型中选择，获得完整的研究工作区，包括网络搜索、文件处理、100+ 科学数据库，以及访问本仓库中的所有 134 个技能。您的数据保留在您的计算机上，并可通过 [Modal](https://modal.com/) 可选扩展到云端计算以处理繁重的工作负载。[从这里开始。](https://github.com/K-Dense-AI/k-dense-byok)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/LICENSE.md)
[![Skills](https://img.shields.io/badge/Skills-134-brightgreen.svg)](#whats-included)
[![Databases](https://img.shields.io/badge/Databases-100%2B-orange.svg)](#whats-included)
[![Agent Skills](https://img.shields.io/badge/Standard-Agent_Skills-blueviolet.svg)](https://agentskills.io/)
[![Works with](https://img.shields.io/badge/Works_with-Cursor_|_Claude_Code_|_Codex-blue.svg)](#getting-started)
[![X](https://img.shields.io/badge/Follow_on_X-%40k__dense__ai-000000?logo=x)](https://x.com/k_dense_ai)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-K--Dense_Inc.-0A66C2?logo=linkedin)](https://www.linkedin.com/company/k-dense-inc)
[![YouTube](https://img.shields.io/badge/YouTube-K--Dense_Inc.-FF0000?logo=youtube)](https://www.youtube.com/@K-Dense-Inc)

由 [K-Dense](https://k-dense.ai) 创建的 **134 个即用型科学和研究技能**（涵盖癌症基因组学、药物-靶点结合、分子动力学、RNA 速度、地理空间科学、时间序列预测、78+ 科学数据库等）的综合集合，适用于任何支持开放 [Agent Skills](https://agentskills.io/) 标准的 AI 代理。适用于 **Cursor、Claude Code、Codex 等**。将您的 AI 代理转变为能够跨生物学、化学、医学等领域执行复杂多步骤科学工作流程的研究助手。

---

这些技能使您的 AI 代理能够无缝地跨多个科学领域使用专业的科学库、数据库和工具。虽然代理可以自行使用任何 Python 包或 API，但这些明确定义的技能提供了精心策划的文档和示例，使其在以下工作流程中更加强大和可靠：
- 🧬 生物信息学与基因组学 - 序列分析、单细胞 RNA-seq、基因调控网络、变异注释、系统发育分析
- 🧪 化学信息学与药物发现 - 分子性质预测、虚拟筛选、ADMET 分析、分子对接、先导化合物优化
- 🔬 蛋白质组学与质谱 - LC-MS/MS 处理、肽鉴定、光谱匹配、蛋白质定量
- 🏥 临床研究与精准医学 - 临床试验、药物基因组学、变异解读、药物安全、临床决策支持、治疗规划
- 🧠 医疗保健 AI 与临床机器学习 - EHR 分析、生理信号处理、医学影像、临床预测模型
- 🖼️ 医学影像与数字病理学 - DICOM 处理、全切片图像分析、计算病理学、放射学工作流程
- 🤖 机器学习与 AI - 深度学习、强化学习、时间序列分析、模型可解释性、贝叶斯方法
- 🔮 材料科学与化学 - 晶体结构分析、相图、代谢建模、计算化学
- 🌌 物理学与天文学 - 天文数据分析、坐标转换、宇宙学计算、符号数学、物理计算
- ⚙️ 工程与仿真 - 离散事件仿真、多目标优化、代谢工程、系统建模、过程优化
- 📊 数据分析与可视化 - 统计分析、网络分析、时间序列、出版级图表、大规模数据处理、探索性数据分析
- 🌍 地理空间科学与遥感 - 卫星图像处理、GIS 分析、空间统计、地形分析、地球观测机器学习
- 🧪 实验室自动化 - 液体处理协议、实验室设备控制、工作流程自动化、LIMS 集成
- 📚 科学交流 - 文献综述、同行评审、科学写作、文档处理、海报、幻灯片、示意图、引文管理
- 🔬 多组学与系统生物学 - 多模态数据整合、通路分析、网络生物学、系统级洞察
- 🧬 蛋白质工程与设计 - 蛋白质语言模型、结构预测、序列设计、功能注释
- 🎓 研究方法学 - 假设生成、科学头脑风暴、批判性思维、基金申请写作、学者评估

**将您的 AI 编码代理转变为桌面上的"AI 科学家"！**

> ⭐ **如果您发现此仓库有用**，请考虑给它一个星标！这有助于其他人发现这些工具，并鼓励我们继续维护和扩展此集合。

> 🎬 **Scientific Agent Skills 新手？** 观看我们的 [Scientific Agent Skills 入门](https://youtu.be/ZxbnDaD_FVg) 视频以获得快速入门指南。

---

## 📦 包含内容

此仓库提供 **134 个科学和研究技能**，按以下类别组织：

- **100+ 科学与金融数据库** - 统一的数据库查找技能提供对 78 个公共数据库的直接访问（PubChem、ChEMBL、UniProt、COSMIC、ClinicalTrials.gov、FRED、USPTO 等），以及 DepMap、Imaging Data Commons、PrimeKG 和美国财政部财政数据的专用技能。多数据库包如 BioServices（~40 个生物信息学服务）、BioPython（通过 Entrez 访问 38 个 NCBI 子数据库）和 gget（20+ 基因组学数据库）进一步扩大了覆盖范围
- **70+ 优化的 Python 包技能** - 为 RDKit、Scanpy、PyTorch Lightning、scikit-learn、BioPython、pyzotero、BioServices、PennyLane、Qiskit、OpenMM、MDAnalysis、scVelo、TimesFM 等明确定义的技能 — 包含精心策划的文档、示例和最佳实践。注意：代理可以使用*任何* Python 包编写代码，不仅限于这些；这些技能只是为列出的包提供更强大、更可靠的性能
- **9 个科学集成技能** - 为 Benchling、DNAnexus、LatchBio、OMERO、Protocols.io、Open Notebook 等明确定义的技能。同样，代理不限于这些 — 任何可以从 Python 访问的 API 或平台都可以使用；这些技能是优化且预先记录的路径
- **30+ 分析与交流工具** - 文献综述、科学写作、同行评审、文档处理、海报、幻灯片、示意图、信息图表、Mermaid 图表等
- **10+ 研究与临床工具** - 假设生成、基金申请写作、临床决策支持、治疗计划、监管合规、情景分析

每个技能包括：
- ✅ 全面的文档（`SKILL.md`）
- ✅ 实用的代码示例
- ✅ 用例和最佳实践
- ✅ 集成指南
- ✅ 参考材料

---

## 📋 目录

- [包含内容](#whats-included)
- [为什么使用这个？](#why-use-this)
- [入门指南](#getting-started)
- [安全免责声明](#-security-disclaimer)
- [支持开源社区](#-support-the-open-source-community)
- [先决条件](#prerequisites)
- [快速示例](#quick-examples)
- [用例](#use-cases)
- [可用技能](#available-skills)
- [贡献](#contributing)
- [故障排除](#troubleshooting)
- [常见问题](#faq)
- [支持](#support)
- [加入我们的社区](#join-our-community)
- [引用](#citation)
- [许可证](#license)

---

## 🚀 为什么使用这个？

### ⚡ **加速您的研究**
- **节省数天的工作** - 跳过 API 文档研究和集成设置
- **生产就绪的代码** - 经过测试和验证的示例，遵循科学最佳实践
- **多步骤工作流程** - 通过单个提示执行复杂的管道

### 🎯 **全面覆盖**
- **134 个技能** - 覆盖所有主要科学领域
- **100+ 数据库** - 通过数据库查找统一访问 78+ 数据库，加上专用数据访问技能和多数据库包如 BioServices、BioPython 和 gget
- **70+ 优化的 Python 包技能** - RDKit、Scanpy、PyTorch Lightning、scikit-learn、BioServices、PennyLane、Qiskit、OpenMM、scVelo、TimesFM 等（代理可以使用任何 Python 包；这些是预先记录的、更高性能的路径）

### 🔧 **易于集成**
- **简单设置** - 将技能复制到您的技能目录并开始工作
- **自动发现** - 您的代理自动发现并使用相关技能
- **完善的文档** - 每个技能包括示例、用例和最佳实践

### 🌟 **维护与支持**
- **定期更新** - 由 K-Dense 团队持续维护和扩展
- **社区驱动** - 开源，有活跃的社区贡献
- **企业就绪** - 为高级需求提供商业支持

---

## 🎯 入门指南

使用单个命令安装 Scientific Agent Skills：

```bash
npx skills add K-Dense-AI/scientific-agent-skills
```

这是在**所有平台**上安装 Agent Skills 的官方标准方法，包括 **Claude Code**、**Claude Cowork**、**Codex**、**Gemini CLI**、**Cursor** 以及任何其他支持开放 [Agent Skills](https://agentskills.io/) 标准的代理。

**就这样！** 您的 AI 代理将自动发现技能，并在与您的科学任务相关时使用它们。您还可以通过在提示中提及技能名称来手动调用任何技能。

---

## ⚠️ 安全免责声明

> **技能可以执行代码并影响您的编码代理的行为。请审查您安装的内容。**

Agent Skills 功能强大 — 它们可以指示您的 AI 代理运行任意代码、安装包、发出网络请求和修改系统上的文件。恶意或编写不当的技能有可能引导您的编码代理产生有害行为。

我们非常重视安全性。所有贡献都经过审查流程，我们对此仓库中的每个技能运行基于 LLM 的安全扫描（通过 [Cisco AI Defense Skill Scanner](https://github.com/cisco-ai-defense/skill-scanner)）。然而，作为一个团队规模较小且社区贡献不断增长的小团队，我们无法保证每个技能都已针对所有可能的风险进行了彻底审查。

**最终由您负责审查您安装的技能并决定信任哪些技能。**

我们建议您执行以下操作：

- **不要一次性安装所有内容。** 只安装您工作实际需要的技能。虽然当 K-Dense 创建和维护每个技能时安装完整集合是合理的，但现在仓库包含许多社区贡献，我们可能没有彻底审查这些贡献。
- **安装前阅读 `SKILL.md`。** 每个技能的文档描述了它的作用、使用的包以及连接的外部服务。如果某些内容看起来可疑，请不要安装。
- **检查贡献历史。** 由 K-Dense (`K-Dense-AI`) 编写的技能已经过我们的内部审查流程。社区贡献的技能已尽我们所能进行了审查，但资源有限。
- **自己运行安全扫描器。** 在安装第三方技能之前，在本地扫描它们：
  ```bash
  uv pip install cisco-ai-skill-scanner
  skill-scanner scan /path/to/skill --use-behavioral
  ```
- **报告任何可疑内容。** 如果您发现看起来恶意或行为异常的技能，请立即[打开问题](https://github.com/K-Dense-AI/scientific-agent-skills/issues)以便我们进行调查。

---

## ❤️ 支持开源社区

Scientific Agent Skills 由全球敬业开发者和研究社区维护的 **50+ 令人惊叹的开源项目**驱动。Biopython、Scanpy、RDKit、scikit-learn、PyTorch Lightning 等项目构成了这些技能的基础。

**如果您发现此仓库有价值，请考虑支持使其成为可能的项目：**

- ⭐ 在 GitHub 上为他们的仓库**加星标**
- 💰 通过 GitHub Sponsors 或 NumFOCUS **赞助维护者**
- 📝 在您的出版物中**引用项目**
- 💻 **贡献**代码、文档或错误报告

👉 **[查看支持项目的完整列表](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/docs/open-source-sponsors.md)**

---

## ⚙️ 先决条件

- **Python**：3.11+（推荐 3.12+ 以获得最佳兼容性）
- **uv**：Python 包管理器（安装技能依赖项所需）
- **客户端**：任何支持 [Agent Skills](https://agentskills.io/) 标准的代理（Cursor、Claude Code、Gemini CLI、Codex 等）
- **系统**：macOS、Linux 或带 WSL2 的 Windows
- **依赖项**：由各个技能自动处理（检查 `SKILL.md` 文件以了解具体要求）

### 安装 uv

技能使用 `uv` 作为包管理器来安装 Python 依赖项。使用适用于您操作系统的说明进行安装：

**macOS 和 Linux：**
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```

**Windows：**
```powershell
powershell -ExecutionPolicy ByPass -c "irm https://astral.sh/uv/install.ps1 | iex"
```

**替代方案（通过 pip）：**
```bash
pip install uv
```

安装后，通过运行以下命令验证它是否工作：
```bash
uv --version
```

有关更多安装选项和详细信息，请访问[官方 uv 文档](https://docs.astral.sh/uv/)。

---

## 💡 快速示例

安装技能后，您可以要求您的 AI 代理执行复杂的多步骤科学工作流程。以下是一些示例提示：

### 🧪 药物发现管道
**目标**：寻找用于肺癌治疗的新型 EGFR 抑制剂

**提示**：
```
尽可能使用您可用的技能。查询 ChEMBL 获取 EGFR 抑制剂（IC50 < 50nM），使用 RDKit 分析构效关系，
使用 datamol 生成改进的类似物，使用 DiffDock 针对 AlphaFold EGFR 结构进行虚拟筛选，
在 PubMed 中搜索耐药机制，在 COSMIC 中检查突变，并创建可视化和综合报告。
```

**使用的技能**：ChEMBL、RDKit、datamol、DiffDock、AlphaFold DB、PubMed、COSMIC、科学可视化

*最后需要云 GPU 和出版就绪的报告？[在 K-Dense Web 上免费运行。](https://k-dense.ai)*

---

### 🔬 单细胞 RNA-seq 分析
**目标**：10X Genomics 数据的全面分析，包括公共数据整合

**提示**：
```
尽可能使用您可用的技能。使用 Scanpy 加载 10X 数据集，执行 QC 和双细胞去除，
与 Cellxgene Census 数据整合，使用 NCBI Gene 标记识别细胞类型，使用 PyDESeq2 运行差异表达，
使用 Arboreto 推断基因调控网络，通过 Reactome/KEGG 丰富通路，并使用 Open Targets 识别治疗靶点。
```

**使用的技能**：Scanpy、Cellxgene Census、NCBI Gene、PyDESeq2、Arboreto、Reactome、KEGG、Open Targets

*想要零设置的云执行和可共享的输出？[免费试用 K-Dense Web。](https://k-dense.ai)*

---

### 🧬 多组学生物标志物发现
**目标**：整合 RNA-seq、蛋白质组学和代谢组学以预测患者结果

**提示**：
```
尽可能使用您可用的技能。使用 PyDESeq2 分析 RNA-seq，使用 pyOpenMS 处理质谱数据，
整合来自 HMDB/Metabolomics Workbench 的代谢物，将蛋白质映射到通路（UniProt/KEGG），
通过 STRING 查找相互作用，使用 statsmodels 关联组学层，使用 scikit-learn 构建预测模型，
并在 ClinicalTrials.gov 中搜索相关试验。
```

**使用的技能**：PyDESeq2、pyOpenMS、HMDB、Metabolomics Workbench、UniProt、KEGG、STRING、statsmodels、scikit-learn、ClinicalTrials.gov

*此管道计算量很大。[在 K-Dense Web 上使用云 GPU 运行，免费开始。](https://k-dense.ai)*

---

### 🎯 虚拟筛选活动
**目标**：发现蛋白质-蛋白质相互作用的变构调节剂

**提示**：
```
尽可能使用您可用的技能。检索 AlphaFold 结构，使用 BioPython 识别相互作用界面，
在 ZINC 中搜索变构候选物（MW 300-500，logP 2-4），使用 RDKit 过滤，使用 DiffDock 对接，
使用 DeepChem 排序，检查 PubChem 供应商，搜索 USPTO 专利，并使用 MedChem/molfeat 优化先导化合物。
```

**使用的技能**：AlphaFold DB、BioPython、ZINC、RDKit、DiffDock、DeepChem、PubChem、USPTO、MedChem、molfeat

*跳过本地 GPU 瓶颈。[在 K-Dense Web 上免费运行虚拟筛选。](https://k-dense.ai)*

---

### 🏥 临床变异解读
**目标**：分析 VCF 文件以进行遗传性癌症风险评估

**提示**：
```
尽可能使用您可用的技能。使用 pysam 解析 VCF，使用 Ensembl VEP 注释变异，
在 ClinVar 中查询致病性，在 COSMIC 中检查癌症突变，从 NCBI Gene 检索基因信息，
使用 UniProt 分析蛋白质影响，在 PubMed 中搜索病例报告，在 ClinPGx 中检查药物基因组学，
使用文档处理工具生成临床报告，并在 ClinicalTrials.gov 中查找匹配的试验。
```

**使用的技能**：pysam、Ensembl、ClinVar、COSMIC、NCBI Gene、UniProt、PubMed、ClinPGx、文档技能、ClinicalTrials.gov

*最后需要一份精美的临床报告，而不仅仅是代码？[K-Dense Web 提供出版就绪的输出。免费试用。](https://k-dense.ai)*

---

### 🌐 系统生物学网络分析
**目标**：从 RNA-seq 数据分析基因调控网络

**提示**：
```
尽可能使用您可用的技能。查询 NCBI Gene 获取注释，从 UniProt 检索序列，
通过 STRING 识别相互作用，映射到 Reactome/KEGG 通路，使用 Torch Geometric 分析拓扑，
使用 Arboreto 重建 GRN，使用 Open Targets 评估可药性，使用 PyMC 建模，
可视化网络，并在 GEO 中搜索相似模式。
```

**使用的技能**：NCBI Gene、UniProt、STRING、Reactome、KEGG、Torch Geometric、Arboreto、Open Targets、PyMC、GEO

*想要具有可共享输出且无需设置的端到端管道？[免费试用 K-Dense Web。](https://k-dense.ai)*

> 📖 **想要更多示例？** 查看 [docs/examples.md](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/docs/examples.md) 以获取所有科学领域的综合工作流程示例和详细用例。

---

## 🚀 想要跳过设置直接进行科学研究？

**认出这些情况了吗？**

- 您花费在配置环境上的时间比运行分析的时间还多
- 您的工作流程需要本地机器不具备的 GPU
- 您需要可共享的、出版就绪的图表或报告，而不仅仅是脚本
- 您想立即运行复杂的多步骤管道，而不必先阅读包文档

如果是这样，**[K-Dense Web](https://k-dense.ai)** 就是为您构建的。它是完整的 AI 共同科学家平台：此仓库中的所有内容加上云 GPU、200+ 技能，以及您可以直接放入论文或演示文稿的输出。无需设置。

| 功能 | 此仓库 | K-Dense Web |
|---------|-----------|-------------|
| 科学技能 | 134 个技能 | **200+ 技能**（独家访问） |
| 设置 | 手动安装 | **零设置，即时工作** |
| 计算 | 您的机器 | **包含云 GPU 和 HPC** |
| 工作流程 | 提示和代码 | **端到端研究管道** |
| 输出 | 代码和分析 | **出版就绪的图表、报告和论文** |
| 集成 | 本地工具 | **实验室系统、ELN 和云存储** |

> *"K-Dense Web 让我在一个下午内从原始测序数据获得草稿图表。以前需要三天的环境设置和脚本编写，现在可以直接工作。"*
> **计算生物学家，药物发现**

> ### 💰 50 美元免费额度，无需信用卡
> 在几分钟内开始运行真实的科学工作流程。
>
> **[免费试用 K-Dense Web](https://k-dense.ai)**

*[k-dense.ai](https://k-dense.ai) | [阅读完整比较](https://k-dense.ai/blog/k-dense-web-vs-scientific-agent-skills)*

---

## 🔬 用例

### 🧪 药物发现与药物化学
- **虚拟筛选**：从 PubChem/ZINC 筛选数百万化合物对抗蛋白质靶点
- **先导化合物优化**：使用 RDKit 分析构效关系，使用 datamol 生成类似物
- **ADMET 预测**：使用 DeepChem 预测吸收、分布、代谢、排泄和毒性
- **分子对接**：使用 DiffDock 预测结合姿势和亲和力
- **生物活性挖掘**：查询 ChEMBL 获取已知抑制剂并分析 SAR 模式

### 🧬 生物信息学与基因组学
- **序列分析**：使用 BioPython 和 pysam 处理 DNA/RNA/蛋白质序列
- **单细胞分析**：使用 Scanpy 分析 10X Genomics 数据，识别细胞类型，使用 Arboreto 推断 GRN
- **变异注释**：使用 Ensembl VEP 注释 VCF 文件，在 ClinVar 中查询致病性
- **变异数据库管理**：使用 TileDB-VCF 构建可扩展的 VCF 数据库，用于增量样本添加、高效的人群规模查询和基因组变异数据的压缩存储
- **基因发现**：查询 NCBI Gene、UniProt 和 Ensembl 获取全面的基因信息
- **网络分析**：通过 STRING 识别蛋白质-蛋白质相互作用，映射到通路（KEGG、Reactome）

### 🏥 临床研究与精准医学
- **临床试验**：在 ClinicalTrials.gov 中搜索相关研究，分析资格标准
- **变异解读**：使用 ClinVar、COSMIC 和 ClinPGx 注释变异以进行药物基因组学
- **药物安全**：查询 FDA 数据库获取不良事件、药物相互作用和召回信息
- **精准治疗**：将患者变异与靶向治疗和临床试验匹配

### 🔬 多组学与系统生物学
- **多组学整合**：整合 RNA-seq、蛋白质组学和代谢组学数据
- **通路分析**：在 KEGG/Reactome 通路中富集差异表达基因
- **网络生物学**：重建基因调控网络，识别枢纽基因
- **生物标志物发现**：整合多组学层以预测患者结果

### 📊 数据分析与可视化
- **统计分析**：执行假设检验、功效分析和实验设计
- **出版图表**：使用 matplotlib 和 seaborn 创建出版质量的可视化
- **网络可视化**：使用 NetworkX 可视化生物网络
- **报告生成**：使用文档技能生成综合 PDF 报告

### 🧪 实验室自动化
- **协议设计**：创建 Opentrons 协议以进行自动液体处理
- **LIMS 集成**：与 Benchling 和 LabArchives 集成以进行数据管理
- **工作流程自动化**：自动化多步骤实验室工作流程

---

## 📚 可用技能

此仓库包含 **134 个科学和研究技能**，跨多个领域组织。每个技能都提供全面的文档、代码示例和使用科学库、数据库和工具的最佳实践。

### 技能类别

> **注意：** 下面列出的 Python 包和集成技能是*明确定义的*技能 — 经过精心策划，包含文档、示例和最佳实践，以实现更强大、更可靠的性能。它们不是上限：代理可以安装和使用*任何* Python 包或调用*任何* API，即使没有专用技能。列出的技能只是使常见工作流程更快、更可靠。

#### 🧬 **生物信息学与基因组学**（21+ 技能）
- 序列分析：BioPython、pysam、scikit-bio、BioServices
- 单细胞分析：Scanpy、AnnData、scvi-tools、scVelo（RNA 速度）、Arboreto、Cellxgene Census
- 基因组学工具：gget、geniml、gtars、deepTools、FlowIO、Polars-Bio、Zarr、TileDB-VCF
- 差异表达：PyDESeq2
- 系统发育学：ETE Toolkit、Phylogenetics（MAFFT、IQ-TREE 2、FastTree）

#### 🧪 **化学信息学与药物发现**（10+ 技能）
- 分子操作：RDKit、Datamol、Molfeat
- 深度学习：DeepChem、TorchDrug
- 对接与筛选：DiffDock
- 分子动力学：OpenMM + MDAnalysis（MD 模拟与轨迹分析）
- 云量子化学：Rowan（pKa、对接、共折叠）
- 药物相似性：MedChem
- 基准测试：PyTDC

#### 🔬 **蛋白质组学与质谱**（2 技能）
- 光谱处理：matchms、pyOpenMS

#### 🏥 **临床研究与精准医学**（8+ 技能）
- 临床数据库：通过数据库查找（ClinicalTrials.gov、ClinVar、ClinPGx、COSMIC、FDA、cBioPortal、Monarch 等）
- 癌症基因组学：DepMap（癌症依赖性评分、药物敏感性）
- 癌症影像：Imaging Data Commons（通过 idc-index 访问 NCI 放射学和病理学数据集）
- 医疗保健 AI：PyHealth、NeuroKit2、临床决策支持
- 临床文档：临床报告、治疗计划

#### 🖼️ **医学影像与数字病理学**（3 技能）
- DICOM 处理：pydicom
- 全切片成像：histolab、PathML

#### 🧠 **神经科学与电生理学**（1 技能）
- 神经记录：Neuropixels-Analysis（细胞外尖峰、硅探针、尖峰分类）

#### 🤖 **机器学习与 AI**（16+ 技能）
- 深度学习：PyTorch Lightning、Transformers、Stable Baselines3、PufferLib
- 经典机器学习：scikit-learn、scikit-survival、SHAP
- 时间序列：aeon、TimesFM（Google 的零样本单变量预测基础模型）
- 贝叶斯方法：PyMC
- 优化：PyMOO
- 图机器学习：Torch Geometric
- 降维：UMAP-learn
- 统计建模：statsmodels

#### 🔮 **材料科学、化学与物理学**（7 技能）
- 材料：Pymatgen
- 代谢建模：COBRApy
- 天文学：Astropy
- 量子计算：Cirq、PennyLane、Qiskit、QuTiP

#### ⚙️ **工程与仿真**（4 技能）
- 数值计算：MATLAB/Octave
- 计算流体动力学：FluidSim
- 离散事件仿真：SimPy
- 符号数学：SymPy

#### 📊 **数据分析与可视化**（16+ 技能）
- 可视化：Matplotlib、Seaborn、科学可视化
- 地理空间分析：GeoPandas、GeoMaster（遥感、GIS、卫星图像、空间机器学习、500+ 示例）
- 数据处理：Dask、Polars、Vaex
- 网络分析：NetworkX
- 文档处理：文档技能（PDF、DOCX、PPTX、XLSX）
- 信息图表：信息图表（AI 驱动的专业信息图表创建）
- 图表：Markdown 和 Mermaid 写作（基于文本的图表作为默认文档标准）
- 探索性数据分析：EDA 工作流程
- 统计分析：统计分析工作流程

#### 🧪 **实验室自动化**（4 技能）
- 液体处理：PyLabRobot
- 云实验室：Ginkgo Cloud Lab（无细胞蛋白质表达、通过自主 RAC 基础设施创建荧光像素艺术）
- 协议管理：Protocols.io
- LIMS 集成：Benchling、LabArchives

#### 🔬 **多组学与系统生物学**（4+ 技能）
- 通路分析：通过数据库查找（KEGG、Reactome、STRING）和 PrimeKG
- 多组学：HypoGeniC
- 数据管理：LaminDB

#### 🧬 **蛋白质工程与设计**（3 技能）
- 蛋白质语言模型：ESM
- 糖工程：糖工程（N/O-糖基化预测、治疗性抗体优化）
- 云实验室平台：Adaptyv（自动化蛋白质测试和验证）

#### 📚 **科学交流**（20+ 技能）
- 文献：论文查找（PubMed、PMC、bioRxiv、medRxiv、arXiv、OpenAlex、Crossref、Semantic Scholar、CORE、Unpaywall）、文献综述
- 高级论文搜索：BGPT 论文搜索（每篇论文 25+ 结构化字段 — 方法、结果、样本量、质量评分 — 来自全文，不仅仅是摘要）
- 网络搜索：Perplexity 搜索（具有实时信息的 AI 驱动搜索）、Parallel Web（带引用的综合摘要）
- 研究笔记本：Open Notebook（自托管 NotebookLM 替代品 — PDF、视频、音频、网页；16+ AI 提供商；多说话人播客生成）
- 写作：科学写作、同行评审
- 文档处理：XLSX、MarkItDown、文档技能
- 发布：场所模板
- 演示：科学幻灯片、LaTeX 海报、PPTX 海报
- 图表：科学示意图、Markdown 和 Mermaid 写作
- 信息图表：信息图表（10 种类型、8 种样式、色盲安全调色板）
- 引用：引文管理
- 插图：生成图像（使用 FLUX.2 Pro 和 Gemini 3 Pro (Nano Banana Pro) 的 AI 图像生成）

#### 🔬 **科学数据库与数据访问**（5 技能 → 100+ 数据库总计）
> 统一的数据库查找技能提供对所有领域 78 个公共数据库的直接 REST API 访问。专用技能涵盖专门的数据平台。多数据库包如 BioServices（~40 个生物信息学服务）、BioPython（通过 Entrez 访问 38 个 NCBI 子数据库）和 gget（20+ 基因组学数据库）进一步扩大了覆盖范围。
- 统一访问：数据库查找（78 个数据库，涵盖化学、基因组学、临床、通路、专利、经济学等 — PubChem、ChEMBL、UniProt、PDB、AlphaFold、KEGG、Reactome、STRING、ClinVar、COSMIC、ClinicalTrials.gov、FDA、FRED、USPTO、SEC EDGAR 和数十个其他）
- 癌症基因组学：DepMap（癌细胞系依赖性、药物敏感性、基因效应谱）
- 癌症影像：Imaging Data Commons（通过 idc-index 访问 NCI 放射学和病理学数据集）
- 知识图谱：PrimeKG（精准医学知识图谱 — 基因、药物、疾病、表型）
- 财政数据：美国财政部财政数据（国债、财政部声明、拍卖、汇率）

#### 🔧 **基础设施与平台**（7+ 技能）
- 云计算：Modal
- GPU 加速：GPU 优化（CuPy、Numba CUDA、Warp、cuDF、cuML、cuGraph、KvikIO、cuCIM、cuxfilter、cuVS、cuSpatial、RAFT）
- 基因组学平台：DNAnexus、LatchBio
- 显微镜：OMERO
- 自动化：Opentrons
- 资源检测：获取可用资源

#### 🎓 **研究方法学与规划**（12+ 技能）
- 构思：科学头脑风暴、假设生成
- 批判性分析：科学批判性思维、学者评估
- 情景分析：What-If Oracle（多分支可能性探索、风险分析、战略选项）
- 多视角审议：意识委员会（多样化的专家观点、魔鬼代言人分析）
- 认知分析：DHDNA 分析器（从任何文本中提取思维模式和认知特征）
- 资金：研究基金
- 发现：研究查找、论文查找（10 个学术数据库）
- 市场分析：市场研究报告

#### ⚖️ **监管与标准**（1 技能）
- 医疗器械标准：ISO 13485 认证

> 📖 **有关所有技能的完整详细信息**，请参阅 [docs/scientific-skills.md](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/docs/scientific-skills.md)

> 💡 **寻找实用示例？** 查看 [docs/examples.md](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/docs/examples.md) 以获取所有科学领域的综合工作流程示例。

---

## 🤝 贡献

我们欢迎贡献以扩展和改进此科学技能仓库！

### 贡献方式

✨ **添加新技能**
- 为额外的科学包或数据库创建技能
- 为科学平台和工具添加集成

📚 **改进现有技能**
- 通过更多示例和用例增强文档
- 添加新的工作流程和参考材料
- 改进代码示例和脚本
- 修复错误或更新过时信息

🐛 **报告问题**
- 提交带有详细重现步骤的错误报告
- 建议改进或新功能

### 如何贡献

1. **Fork** 仓库
2. **创建** 功能分支（`git checkout -b feature/amazing-skill`）
3. **遵循** 现有的目录结构和文档模式
4. **确保** 所有新技能都包含全面的 `SKILL.md` 文件
5. **彻底测试** 您的示例和工作流程
6. **提交** 您的更改（`git commit -m 'Add amazing skill'`）
7. **推送** 到您的分支（`git push origin feature/amazing-skill`）
8. **提交** 带有清晰更改描述的拉取请求

### 贡献指南

✅ **遵守 [Agent Skills 规范](https://agentskills.io/specification)** — 每个技能必须遵循官方规范（有效的 `SKILL.md` 前言、命名约定、目录结构）
✅ 保持与现有技能文档格式的一致性
✅ 确保所有代码示例都经过测试且功能正常
✅ 在示例和工作流程中遵循科学最佳实践
✅ 添加新功能时更新相关文档
✅ 在代码中提供清晰的注释和文档字符串
✅ 包含对官方文档的引用

### 安全扫描

此仓库中的所有技能都使用 [Cisco AI Defense Skill Scanner](https://github.com/cisco-ai-defense/skill-scanner) 进行安全扫描，这是一个开源工具，可检测 Agent Skills 中的提示注入、数据泄露和恶意代码模式。

如果您要贡献新技能，我们建议在提交拉取请求之前在本地运行扫描器：

```bash
uv pip install cisco-ai-skill-scanner
skill-scanner scan /path/to/your/skill --use-behavioral
```

> **注意：** 干净的扫描结果可以减少审查中的噪音，但不能保证技能完全没有风险。贡献的技能在合并之前也会经过人工审查。

### 认可

贡献者会在我们的社区中得到认可，并可能会在以下地方被提及：
- 仓库贡献者列表
- 发行说明中的特别提及
- K-Dense 社区亮点

您的贡献有助于使科学计算更加普及，并使研究人员能够更有效地利用 AI 工具！

### 支持开源

此项目建立在 50+ 令人惊叹的开源项目之上。如果您发现这些技能有价值，请考虑[支持我们依赖的项目](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/docs/open-source-sponsors.md)。

---

## 🔧 故障排除

### 常见问题

**问题：技能未加载**
- 验证技能文件夹位于正确的目录（参见[入门指南](#getting-started)）
- 每个技能文件夹必须包含 `SKILL.md` 文件
- 复制技能后重启您的代理/IDE
- 在 Cursor 中，检查设置 → 规则以确认技能已被发现

**问题：缺少 Python 依赖项**
- 解决方案：检查特定的 `SKILL.md` 文件以了解所需的包
- 安装依赖项：`uv pip install package-name`

**问题：API 速率限制**
- 解决方案：许多数据库都有速率限制。查看特定数据库文档
- 考虑实现缓存或批量请求

**问题：身份验证错误**
- 解决方案：某些服务需要 API 密钥。检查 `SKILL.md` 以了解身份验证设置
- 验证您的凭据和权限

**问题：示例过时**
- 解决方案：通过 GitHub Issues 报告问题
- 查看官方包文档以获取更新的语法

---

## ❓ 常见问题

### 一般问题

**问：这是免费使用的吗？**
答：是的！此仓库采用 MIT 许可证。但是，每个单独的技能在其 `SKILL.md` 文件的 `license` 元数据字段中都有自己的许可证 — 请务必查看并遵守这些条款。

**问：为什么将所有技能组合在一起而不是分开的包？**
答：我们相信在 AI 时代，优秀的科学本质上是跨学科的。将所有技能组合在一起使您（和您的代理）能够轻松跨越领域 — 例如，在一个工作流程中结合基因组学、化学信息学、临床数据和机器学习 — 而无需担心要安装或连接哪些单独的技能。

**问：我可以将其用于商业项目吗？**
答：仓库本身采用 MIT 许可证，允许商业使用。但是，单独的技能可能有不同的许可证 — 检查每个技能的 `SKILL.md` 文件中的 `license` 字段，以确保符合您的预期用途。

**问：所有技能都有相同的许可证吗？**
答：不。每个技能在其 `SKILL.md` 文件的 `license` 元数据字段中都有自己的许可证。这些许可证可能与仓库的 MIT 许可证不同。用户有责任查看并遵守其使用的每个单独技能的许可证条款。

**问：这个多久更新一次？**
答：我们定期更新技能以反映包和 API 的最新版本。主要更新会在发行说明中宣布。

**问：我可以将其与其他 AI 模型一起使用吗？**
答：技能遵循开放 [Agent Skills](https://agentskills.io/) 标准，可与任何兼容的代理一起使用，包括 Cursor、Claude Code 和 Codex。

### 安装与设置

**问：我需要安装所有 Python 包吗？**
答：不需要！只安装您需要的包。每个技能在其 `SKILL.md` 文件中指定其要求。

**问：如果技能不起作用怎么办？**
答：首先检查[故障排除](#troubleshooting)部分。如果问题仍然存在，请在 GitHub 上提交问题，并提供详细的重现步骤。

**问：技能可以离线工作吗？**
答：数据库技能需要互联网访问来查询 API。一旦安装了 Python 依赖项，包技能就可以离线工作。

### 贡献

**问：我可以贡献自己的技能吗？**
答：当然可以！我们欢迎贡献。请参阅[贡献](#contributing)部分以获取指南和最佳实践。

**问：如何报告错误或建议功能？**
答：在 GitHub 上打开一个问题，并提供清晰的描述。对于错误，请包括重现步骤以及预期行为与实际行为的对比。

---

## 💬 支持

需要帮助？以下是获取支持的方法：

- 📖 **文档**：检查相关的 `SKILL.md` 和 `references/` 文件夹
- 🐛 **错误报告**：[打开问题](https://github.com/K-Dense-AI/scientific-agent-skills/issues)
- 💡 **功能请求**：[提交功能请求](https://github.com/K-Dense-AI/scientific-agent-skills/issues/new)
- 💼 **企业支持**：联系 [K-Dense](https://k-dense.ai/) 获取商业支持
- 🌐 **社区**：[加入我们的 Slack](https://join.slack.com/t/k-densecommunity/shared_invite/zt-3iajtyls1-EwmkwIZk0g_o74311Tkf5g)

---

## 🎉 加入我们的社区！

**我们希望您加入我们！** 🚀

与其他使用 AI 代理进行科学计算的科学家、研究人员和 AI 爱好者联系。分享您的发现，提出问题，获得项目帮助，并与社区合作！

🌟 **[加入我们的 Slack 社区](https://join.slack.com/t/k-densecommunity/shared_invite/zt-3iajtyls1-EwmkwIZk0g_o74311Tkf5g)** 🌟

无论您是刚入门还是高级用户，我们的社区都为您提供支持。我们分享技巧，一起解决问题，展示酷炫的项目，并讨论 AI 驱动科学研究的最新发展。

**在那里见！** 💬

---

## 📖 引用

如果您在研究或项目中使用 Scientific Agent Skills，请按以下方式引用：

### BibTeX
```bibtex
@software{scientific_agent_skills_2026,
  author = {{K-Dense Inc.}},
  title = {Scientific Agent Skills: A Comprehensive Collection of Scientific Tools for AI Agents},
  year = {2026},
  url = {https://github.com/K-Dense-AI/scientific-agent-skills},
  note = {134 skills covering databases, packages, integrations, and analysis tools}
}
```

### APA
```
K-Dense Inc. (2026). Scientific Agent Skills: A comprehensive collection of scientific tools for AI agents [Computer software]. https://github.com/K-Dense-AI/scientific-agent-skills
```

### MLA
```
K-Dense Inc. Scientific Agent Skills: A Comprehensive Collection of Scientific Tools for AI Agents. 2026, github.com/K-Dense-AI/scientific-agent-skills.
```

### 纯文本
```
Scientific Agent Skills by K-Dense Inc. (2026)
Available at: https://github.com/K-Dense-AI/scientific-agent-skills
```

我们感谢在从这些技能中受益的出版物、演示文稿或项目中提供致谢！

---

## 📄 许可证

此项目采用 **MIT 许可证**。

**版权所有 © 2026 K-Dense Inc.** ([k-dense.ai](https://k-dense.ai/))

### 要点：
- ✅ **免费用于任何用途**（商业和非商业）
- ✅ **开源** - 自由修改、分发和使用
- ✅ **宽松** - 对重用的限制最少
- ⚠️ **无担保** - 按原样提供，不提供任何形式的担保

完整条款请参阅 [LICENSE.md](https://github.com/K-Dense-AI/scientific-agent-skills/blob/main/LICENSE.md)。

### 单独技能许可证

> ⚠️ **重要**：每个技能在其 `SKILL.md` 文件的 `license` 元数据字段中都有自己的许可证。这些许可证可能与仓库的 MIT 许可证不同，并且可能包含额外的条款或限制。**用户有责任查看并遵守其使用的每个单独技能的许可证条款。**

## Star 历史

[![Star History Chart](https://api.star-history.com/svg?repos=K-Dense-AI/scientific-agent-skills&type=date&legend=top-left)](https://www.star-history.com/#K-Dense-AI/scientific-agent-skills&type=date&legend=top-left)
