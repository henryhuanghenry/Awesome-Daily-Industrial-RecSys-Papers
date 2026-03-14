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