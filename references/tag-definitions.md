# 标签定义和已知标签

本文件定义了论文标签的分类体系，并记录已处理的论文信息。

## 标签分类体系

### 场景标签 (Scene Tags)
- 电商 (E-commerce) - 电商平台推荐
- 短视频 (Short Video) - 短视频内容推荐
- 广告 (Ads) - 广告推荐系统
- 搜索 (Search) - 搜索引擎推荐
- 外卖/本地生活 (Food Delivery) - 外卖和本地生活服务
- 社交/内容 (Social/Content) - 社交媒体内容推荐
- 新闻/资讯 (News) - 新闻资讯推荐
- 音乐/播客 (Music/Podcast) - 音视频内容推荐
- 通用Agent (General Agent) - 通用智能体系统
- 企业知识库 (Enterprise KB) - 企业级知识管理系统

### 技术标签 (Technology Tags)
- 双塔检索 (Two-tower Retrieval) - 双塔架构检索
- 生成式检索 (Gen. Retrieval) - 生成式检索技术
- 序列推荐 (SeqRec) - 序列化推荐
- 图神经网络 (GNN) - 图神经网络技术
- 知识图谱 (Knowledge Graph) - 知识图谱应用
- 对比学习 (Contrastive Learning) - 对比学习方法
- 多目标预估 (Multi-task) - 多任务学习
- 跨域推荐 (Cross-domain) - 跨域推荐
- 语义ID (Semantic ID) - 语义标识符
- 多模态融合 (Multimodal Fusion) - 多模态融合
- RAG - 检索增强生成
- 强化学习 (RL) - 强化学习
- 知识蒸馏 (Distillation) - 知识蒸馏
- 记忆增强 (Memory Augmentation) - 记忆增强
- Agent系统 (Agent System) - 智能体系统
- 量化 (Quantization) - 模型量化技术

- 分布估计 (Distribution Estimation) - 分布参数估计技术
- 信号去偏 (Signal Debiasing) - 推荐信号偏差校正
- 时长偏差 (Duration Bias) - 视频时长导致的偏差
- 多向量检索 (Multi-vector Retrieval) - 多向量后期交互检索
- 后期交互 (Late Interaction) - ColBERT式后期交互机制
- 组合表示 (Compositional Embedding) - 组合向量表示学习
- 白盒规则 (White-box Rules) - 可解释白盒决策规则
- 知识库构建 (KB Construction) - 结构化知识库构建
- 几何建模 (Geometric Modeling) - 微分几何/纤维丛推荐建模
- 离线索引推理 (Index-time Reasoning) - 推理移至离线索引阶段

### 问题标签 (Problem Tags)
- CTR预估 (CTR Pred.) - 点击率预测
- 时长预测 (Duration Pred.) - 观看时长预测
- 排序优化 (Ranking Opt.) - 排序优化
- 召回优化 (Recall Opt.) - 召回优化
- 冷启动 (Cold-start) - 冷启动问题
- 长尾推荐 (Long-tail) - 长尾商品推荐
- 多语言/多市场 (Multilingual) - 多语言多市场
- item ID量化 (ID Quantization) - 商品ID量化
- 端到端优化 (E2E Opt.) - 端到端优化
- SID量化 (SID Quant.) - 语义ID量化
- 检索公平性 (Fairness) - 检索公平性
- 结构化数据检索 (Structured Retrieval) - 结构化数据检索
- Agent经验学习 (Agent Self-improvement) - 智能体自我学习

- 企业多模态检索 (Enterprise Multimodal Retrieval) - 企业级多模态检索
- 金融交易理解 (Transaction Understanding) - 金融交易数据理解
- 零样本迁移 (Zero-shot Transfer) - 跨任务零样本迁移
- 地理定向 (Geo-targeting) - 位置感知广告定向
- 推荐可解释性 (Explainability) - 推荐系统可解释性分析
- 信息茧房量化 (Filter Bubble Quant.) - 信息茧房的量化方法
- 特征工程自动化 (AutoFE) - 自动化特征工程
- 嵌入盲点诊断 (Embedding Blind-spot) - 嵌入表示盲点分析
- 长链推理验证 (Long-horizon Reasoning) - 长链推理的验证与优化
- 多跳问答 (Multi-hop QA) - 多跳问答推理

### 星标标签 (Star Tags)
- LLM&Rec - 使用大语言模型的推荐系统
- 生成式推荐 (Generative Rec) - 生成式推荐模型
- 长序列建模 (Long Seq. Modeling) - 长序列建模
- 多模态&Rec (Multimodal) - 多模态推荐
- Rec Scaling - 推荐系统扩展

## 已知标签表

| 论文ID | 场景 | 技术 | 问题 | 星标 | 线上AB | 方法 | 亮点 |
|--------|------|------|------|------|--------|------|------|
| 2603.11486 | 短视频 (Short Video) | 生成式检索 (Gen. Retrieval), 语义ID (Semantic ID), 量化 (Quantization) | 端到端优化 (E2E Opt.), SID量化 (SID Quant.) | 生成式推荐 (Generative Rec) | 是 | 用FP8后训练量化和优化推理基础设施解决了生成式推荐模型中OneRec-V2的量化推理问题 | 实现了49%的端到端推理延迟减少和92%的吞吐量提升，同时保持在线指标稳定 |
| 2603.02999 | 广告 (Ads) | 生成式检索 (Gen. Retrieval), 序列推荐 (SeqRec), 语义ID (Semantic ID) | 端到端优化 (E2E Opt.), 召回优化 (Recall Opt.), 多目标预估 (Multi-task) | 生成式推荐 (Generative Rec), LLM&Rec | 是 | 用价值感知多任务解耦架构和粗细粒度目标感知机制解决了生成式广告推荐中兴趣目标与商业价值目标不一致的问题 | 在微信视频号广告系统全量部署，实现了GMV-Normal +1.34%的显著提升，建立了生成式广告推荐的新范式 |
| 2603.14422 | 短视频 (Short Video) | 多目标预估 (Multi-task), 分布估计 (Distribution Estimation) | 时长偏差 (Duration Bias), 信号去偏 (Signal Debiasing), 冷启动 (Cold-start) | — | 是 | 在MTML模型中新增分布估计分支同时学习上下文μ和σ²，通过z-score/百分位数构建无偏相对偏好分数(RPS) | 统一框架覆盖物品/用户/模型三类偏差，计算开销<5%，时长相关系数从0.35降至0.003 |
| 2603.13537 | 企业搜索 (Enterprise Search) | 多向量检索 (Multi-vector Retrieval), 多模态融合 (Multimodal Fusion), 后期交互 (Late Interaction) | 企业多模态检索 (Enterprise Multimodal Retrieval) | 多模态&Rec (Multimodal) | 否 | 两阶段后期交互检索：并行Token级ANN+Per-Document Top-M MaxSim近似；GPU加速精确MaxSim重排序；父子文档结构统一文本/图像/视频嵌入 | 在标准Apache Solr生产部署，ColQwen3.0 nDCG@10=58.1 |
| 2603.13997 | 搜索广告 (Search Ads) | Embedding, 组合表示 (Compositional Embedding), CRF语义解析 | 地理定向 (Geo-targeting), 长尾查询 (Long-tail), 冷启动 (Cold-start) | — | 否 | worLd2vec家族联合学习查询/位置/广告/语义片段嵌入；CRF提取语义片段后向量加法组合 | lw2vCRF+解决45%稀有本地查询冷启动，precision@K最高+20% |
| 2603.15459 | 金融风控 (FinTech/Risk) | RAG, 知识库构建 (KB Construction), 白盒规则 (White-box Rules) | 金融交易理解 (Transaction Understanding), 零样本迁移 (Zero-shot Transfer) | — | 否 | 检索优先框架将原始交易转换为3层语义KB，AutoWoE生成白盒规则，推理时检索最多20条规则形成结构化提示 | 零样本LLM MCC翻倍(0.19→0.38)，指令微调后达到专用模型SOTA(0.48) |
| 2603.16088 | 通用推荐 (General Rec) | 图神经网络 (GNN), 序列推荐 (SeqRec), 几何建模 (Geometric Modeling) | 推荐可解释性 (Explainability), 信息茧房量化 (Filter Bubble Quant.) | — | 否 | 用微分几何纤维丛理论解耦推荐系统的拓扑协同结构与语义演化，提出几何偏差指数(GBI)量化信息茧房 | 首次用纤维丛理论统一解释协同聚合（平行传输）和偏好演化（和乐变换）；GBI与香农熵强负相关 |
| 2603.15713 | 金融风控 (FinTech/Risk) | RAG, Agent系统 (Agent System), 序列推荐 (SeqRec) | 特征工程自动化 (AutoFE), 嵌入盲点诊断 (Embedding Blind-spot) | LLM&Rec | 否 | 用LLM驱动的自反式特征生成代理（Alignment分数+Utility分数）弥合事件序列嵌入与可解释特征的鸿沟 | 首次嵌入感知AutoFE；弱嵌入NTP提升+19.3%，强嵌入CoLES提升+5.8% |
| 2603.15726 | 通用Agent (General Agent) | Agent系统 (Agent System), 强化学习 (RL), 记忆增强 (Memory Augmentation) | Agent经验学习 (Agent Self-improvement), 长链推理验证 (Long-horizon Reasoning) | — | 否 | 用Local Verifier（步级验证）+Global Verifier（轨迹审计）+GRPO强化学习实现重型长链推理 | BrowseComp 88.2 SOTA；Local Verifier将难题交互步数降至1/6，Pass@1+26.4pp |
| 2603.16415 | 企业知识库 (Enterprise KB) | RAG, 记忆增强 (Memory Augmentation), 离线索引推理 (Index-time Reasoning) | 召回优化 (Recall Opt.), 多跳问答 (Multi-hop QA) | LLM&Rec | 否 | 将跨文档推理移至离线索引阶段，为共享实体的跨文档对生成桥接事实作为独立可检索单元 | 平均F1超Naive RAG +4.6分；延迟与Naive RAG持平(0.30s)，比HippoRAG快10倍 |