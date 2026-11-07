# 生成式检索与推荐研究资料

整理生成式检索（Generative Retrieval）及相关工业搜索、推荐论文，提供可追溯的原文入口、固定版本与中文阅读线索。

当前版本包含原创目录、简要阅读导航和许可说明，**不包含论文全文、全文译本或完整研究报告**。各论文的结论及实验结果以原文为准。

## 论文目录

| 简称 | 论文 | 固定版本 | 阅读重点 |
| --- | --- | --- | --- |
| GENRE | [Autoregressive Entity Retrieval](https://arxiv.org/abs/2010.00904v3) | 2010.00904v3 | 通过自回归生成实体名称完成实体检索。 |
| OneRec | [OneRec: Unifying Retrieve and Rank with Generative Recommender and Iterative Preference Alignment](https://arxiv.org/abs/2502.18965v1) | 2502.18965v1 | 统一召回与排序，结合会话级生成和偏好对齐。 |
| OneSearch | [OneSearch: A Preliminary Exploration of the Unified End-to-End Generative Framework for E-commerce Search](https://arxiv.org/abs/2509.03236v5) | 2509.03236v5 | 电商端到端生成式搜索中的商品编码、用户行为与偏好优化。 |
| PLUM | [PLUM: Adapting Pre-trained Language Models for Industrial-scale Generative Recommendations](https://arxiv.org/abs/2510.07784v1) | 2510.07784v1 | 将预训练语言模型、语义 ID、持续预训练和推荐微调衔接起来。 |
| GBS | [Generative Retrieval for Book search](https://arxiv.org/abs/2501.11034v1) | 2501.11034v1 | 图书的层级结构、多种信息和训练数据增强。 |
| ICEGR | [ICEGR: An Intent-Coherent End-to-End Generative Retrieval Framework for E-commerce Search](https://arxiv.org/abs/2608.29652v3) | 2608.29652v3 | 在语义 ID、监督训练和偏好优化中保持查询意图一致。 |
| UniGD | [UniGD: A Unified Generative-Discriminative Framework for Industrial Retrieval](https://arxiv.org/abs/2608.03150v1) | 2608.03150v1 | 在同一模型中统一生成式召回与判别式相关性评分。 |
| TSGR | [TSGR: Taobao Search Generative Retrieval](https://arxiv.org/abs/2607.18796v2) | 2607.18796v2 | 兼顾查询相关性与业务价值的商品表示和候选排序。 |
| DOME | [Model Editing for New Document Integration in Generative Information Retrieval](https://arxiv.org/abs/2603.02773v2) | 2603.02773v2 | 通过面向文档 ID 的模型编辑接入新文档。 |

链接指向 arXiv 指定版本页面，可从页面进入原文 PDF。固定版本用于复现阅读和引用，并不代表该论文的最新版本。

## 阅读路线

以下是本目录的阅读建议，不是原作者给出的统一评价：

1. **建立基本概念**：先读 GENRE，理解从“匹配候选”转向“生成标识符”的思路。
2. **比较推荐与搜索**：阅读 OneRec、PLUM，再读 OneSearch，区分用户兴趣建模与显式查询约束。
3. **关注工业目标**：对比 ICEGR、UniGD、TSGR 如何处理相关性、偏好与业务目标。
4. **检查可维护性**：用 GBS 理解复杂文档结构，再用 DOME 思考新增文档和更新成本。

阅读每篇时，可记录：生成目标、标识符构造、训练信号、解码约束、数据更新方式、线上指标及延迟成本。不同论文的数据集、基线和实验设置不相同，不宜直接按涨幅排名。

## 文件说明

- `README.md`：论文目录和原创阅读导航。
- `papers.json`：便于检索和后续整理的结构化论文元数据。
- `RIGHTS.md`：逐篇许可核查与传播边界。

## 引用与使用

论文版权及其许可归原作者或权利人。公开可读不等于可以任意转载、翻译或重新授权。请先查看 [RIGHTS.md](RIGHTS.md) 与原文页面上的许可，再决定如何使用。

元数据与许可核查日期：2026-11-07。
