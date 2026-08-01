<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-01
- 运行时间：2026-08-01 20:33:47 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今日精读与速读共19篇论文，重点聚焦生成式视频压缩与图像编码评估数据集。最值得关注的是《Generative Video Compression with Adaptive Score Distillation》（8.0）提出的自适应分数蒸馏方法，以及《JPEG AIC2026》（8.0）构建的大规模细粒度图像编码评估基准。建议普通读者优先了解这两个方向，后续可关注长尾分类的损失函数设计与视觉生成的矩匹配进展。
- 详情：[/202608/01/README](/202608/01/README)

### 精读区论文标签
1. [Generative Video Compression with Adaptive Score Distillation](/202608/01/2607.22772v1-generative-video-compression-with-adaptive-score-distillation)  
   标签：评分：8.0/10、query:compress
   evidence：面向压缩的视频扩散模型与自适应分数蒸馏，实现超低码率压缩
2. [JPEG AIC2026: A large-scale dataset for fine-grained assessment of image coding](/202608/01/2607.22783v1-jpeg-aic2026-a-large-scale-dataset-for-fine-grained-assessment-of-image-coding)  
   标签：评分：8.0/10、query:compress
   evidence：面向图像编码细粒度评估的大规模数据集，覆盖传统和学习型编解码器，是图像压缩研究的核心资源
3. [AdaKAN: A dual-branch adaptive Kolmogorov-Arnold network for medical image segmentation](/202608/01/2607.22891v1-adakan-a-dual-branch-adaptive-kolmogorov-arnold-network-for-medical-image-segmentation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：提出AdaKAN，一种用于医学图像分割的双分支自适应Kolmogorov-Arnold网络，结合高效注意力
4. [Structured Redundancy Modeling for Efficient Visual Token Pruning in High-Resolution MLLMs](/202608/01/2607.23046v1-structured-redundancy-modeling-for-efficient-visual-token-pruning-in-high-resolution-mllms)  
   标签：评分：8.0/10、query:neural-arch
   evidence：单前向视觉token剪枝，提升高分辨率MLLM视觉架构效率
5. [A Motion-Aware Vector Quantization Framework with Centroid Reuse for Efficient VLA Inference](/202608/01/2607.24148v1-a-motion-aware-vector-quantization-framework-with-centroid-reuse-for-efficient-vla-inference)  
   标签：评分：8.0/10、query:neural-arch
   evidence：提出运动感知向量量化与质心复用，通过减少内存访问加速视觉-语言-动作模型推理
6. [WHTMix: Efficient Stereo Depth Estimation via Walsh-Hadamard Token Mixing](/202608/01/2607.25234v2-whtmix-efficient-stereo-depth-estimation-via-walsh-hadamard-token-mixing)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向立体视觉Transformer的高效Walsh-Hadamard令牌混合
7. [SepPrune:A Separator-based Pruning Framework for Efficient Multimodal Large Language Models](/202608/01/2607.25818v1-sepprunea-separator-based-pruning-framework-for-efficient-multimodal-large-language-models)  
   标签：评分：8.0/10、query:neural-arch
   evidence：提出SepPrune，一种基于分隔符的免训练视觉令牌剪枝方法，降低多模态大语言模型计算开销

### 速读区论文标签
1. [Beyond Static Costs: Learning-Dynamics Aware Loss Functions for Long-Tailed Classification](/202608/01/2607.25830v1-beyond-static-costs-learning-dynamics-aware-loss-functions-for-long-tailed-classification)  
   标签：评分：8.0/10、query:neural-arch
   evidence：利用学习动态调整长尾分类损失，属于视觉模型训练性能优化。
2. [Amortized Moment Matching for Visual Generation](/202608/01/2607.26860v1-amortized-moment-matching-for-visual-generation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：提出摊销矩匹配与AMFD损失作为训练目标，提升视觉生成质量
3. [Towards joint scaling laws with optimal batch size schedules](/202608/01/2607.27731v1-towards-joint-scaling-laws-with-optimal-batch-size-schedules)  
   标签：评分：8.0/10、query:neural-arch
   evidence：提出深度学习训练中的联合缩放定律与批量大小最优调度，直接对应模型优化策略
4. [Simplifying Neural Networks During Training](/202608/01/2607.27854v1-simplifying-neural-networks-during-training)  
   标签：评分：8.0/10、query:neural-arch
   evidence：借助神经坍缩简化训练过程，属于深度网络模型优化策略。
5. [Twins: Learn to Predict Unified Representations with Focal Loss](/202608/01/2607.22531v1-twins-learn-to-predict-unified-representations-with-focal-loss)  
   标签：评分：7.0/10、query:neural-arch
   evidence：级联ViT与VAE特征并用焦点损失稳定多模态训练，属于视觉架构优化技术。
6. [Low-light Image Enhancement via Multi-scale Attention combined with Fourier Transform](/202608/01/2607.24002v1-low-light-image-enhancement-via-multi-scale-attention-combined-with-fourier-transform)  
   标签：评分：7.0/10、query:neural-arch
   evidence：多尺度注意力与傅里叶融合的U型低光增强网络，是视觉架构改进
7. [MXAttention: Data-Free Optimal Scaling and Pre-Normalization Quantization for MXFP4 Attention](/202608/01/2607.24377v1-mxattention-data-free-optimal-scaling-and-pre-normalization-quantization-for-mxfp4-attention)  
   标签：评分：7.0/10、query:neural-arch
   evidence：针对注意力机制的数据无关后训练量化框架，属于模型推理效率优化策略。
8. [OrthKD: Extracting Generalized Clinical Knowledge from Heterogeneous Teachers for Lightweight Deployment](/202608/01/2607.25545v1-orthkd-extracting-generalized-clinical-knowledge-from-heterogeneous-teachers-for-lightweight-deployment)  
   标签：评分：7.0/10、query:neural-arch
   evidence：多教师知识蒸馏，属于深度学习模型优化策略
9. [The Entropic Bound for Transformers: Why Static Rank Fails and Attention-Native Rank Recovers](/202608/01/2607.23050v1-the-entropic-bound-for-transformers-why-static-rank-fails-and-attention-native-rank-recovers)  
   标签：评分：6.0/10、query:neural-arch
   evidence：用熵界与内在秩分析指导Transformer容量设计，是架构设计实践
10. [Exploring Budgeted Image Classification with Content-Sensitive Resource Allocation](/202608/01/2607.23997v1-exploring-budgeted-image-classification-with-content-sensitive-resource-allocation)  
   标签：评分：6.0/10、query:neural-arch
   evidence：基于内容敏感资源分配的自适应图像分类优化
11. [GenSplatCodec: Feed-Forward Gaussian Splatting Compression via One-Step Diffusion](/202608/01/2607.24403v1-gensplatcodec-feed-forward-gaussian-splatting-compression-via-one-step-diffusion)  
   标签：评分：6.0/10、query:compress
   evidence：面向低码率压缩的前馈高斯编解码器，利用单步扩散生成
12. [MedARC: Training-Free Adaptive Redundancy Compression of Visual Tokens for 3D Medical Vision-Language Models](/202608/01/2607.26554v1-medarc-training-free-adaptive-redundancy-compression-of-visual-tokens-for-3d-medical-vision-language-models)  
   标签：评分：6.0/10、query:neural-arch
   evidence：面向视觉-语言模型的免训练标记压缩方法，与神经网络性能提升技术相关


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
