<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-09
- 运行时间：2026-08-09 20:35:20 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今日精读与速读共19篇论文，覆盖优化器、超分、深度估计、MoE训练与目标检测等方向。  
最值得关注的是《AOS》提出的基于训练状态信号的优化器自适应切换，以及《PixelSR》针对屏幕内容的高效超分方案，二者分别提升收敛效率与图像质量。  
建议优先精读AOS与PixelSR，速读可关注YOLOv14跨域检测和XiDepth轻量深度估计，后续可跟踪这些方法在实际任务中的落地效果。
- 详情：[/202608/09/README](/202608/09/README)

### 精读区论文标签
1. [AOS: Adaptive Optimizer Switching via Training-State Signals for Faster Convergence and Better Generalization](/202608/09/2608.01997v1-aos-adaptive-optimizer-switching-via-training-state-signals-for-faster-convergence-and-better-generalization)  
   标签：评分：9.0/10、query:neural-arch
   evidence：基于训练状态信号的自适应优化器切换，加速收敛并提升泛化，属于模型优化策略。
2. [PixelSR: Efficient Screen Content Super-Resolution via Pixel Classification](/202608/09/2608.00646v1-pixelsr-efficient-screen-content-super-resolution-via-pixel-classification)  
   标签：评分：8.0/10、query:neural-arch
   evidence：通过像素分类和内容注意力实现高效屏幕内容超分辨率，符合高效神经网络架构设计需求
3. [Role-Decoupled Attention Residuals: Separating Matching and Content Retrieval Across Depth](/202608/09/2608.01075v1-role-decoupled-attention-residuals-separating-matching-and-content-retrieval-across-depth)  
   标签：评分：8.0/10、query:neural-arch
   evidence：Transformer残差架构改进
4. [Linear Multi-Timescale Retention as a Memory-Efficient Vision-Language Bridge](/202608/09/2608.01614v1-linear-multi-timescale-retention-as-a-memory-efficient-vision-language-bridge)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向视觉-语言模型的内存高效线性注意力模块，属于神经网络架构性能提升技术。
5. [Token Radius Attention for Efficient Video Generation](/202608/09/2608.02504v1-token-radius-attention-for-efficient-video-generation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：无需训练的令牌半径注意力降低视频扩散Transformer注意力开销
6. [GVCCTurbo: Rate-Compute Quality Scheduling for Codebook Driven Generative Compression](/202608/09/2608.03517v1-gvccturbo-rate-compute-quality-scheduling-for-codebook-driven-generative-compression)  
   标签：评分：8.0/10、query:compress
   evidence：基于BPP驱动的率-计算调度，实现码本驱动生成压缩的率失真优化。
7. [SlimVLM: Sensitivity-aware Dynamic Structured Pruning with Adaptive Visual Token Selection for Efficient Vision-Language Models](/202608/09/2608.03580v1-slimvlm-sensitivity-aware-dynamic-structured-pruning-with-adaptive-visual-token-selection-for-efficient-vision-language-models)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向视觉语言模型的结构化剪枝与视觉令牌选择，提升模型效率

### 速读区论文标签
1. [XiDepth: a Lightweight and Efficient Network for Self-supervised Monocular Depth Estimation](/202608/09/2608.03666v1-xidepth-a-lightweight-and-efficient-network-for-self-supervised-monocular-depth-estimation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：XiDepth面向自监督单目深度估计设计轻量高效网络，关注资源高效的架构设计。
2. [MESH: Memory-Efficient Sinkhorn Optimization for Mixture-of-Experts Training](/202608/09/2608.04407v1-mesh-memory-efficient-sinkhorn-optimization-for-mixture-of-experts-training)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向MoE训练的内存高效Sinkhorn优化器，属于模型优化策略
3. [YOLOv14:Unified Cross-Domain Real-Time Object Detectionwith Adaptive Multi-View Representation](/202608/09/2608.04720v1-yolov14unified-cross-domain-real-time-object-detectionwith-adaptive-multi-view-representation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：YOLOv14提出可变形区域注意力、游戏到真实域适配和多视图条件设定，提升跨域目标检测鲁棒性。
4. [StaticSegFormer: An Efficient High-Performance Semantic Segmentation Based on Static Structured Pruning](/202608/09/2608.04811v1-staticsegformer-an-efficient-high-performance-semantic-segmentation-based-on-static-structured-pruning)  
   标签：评分：8.0/10、query:neural-arch
   evidence：结构化剪枝以提升神经网络效率
5. [Mask-Based Priors Are More Persistent than Query-Key Initializations](/202608/09/2608.00418v1-mask-based-priors-are-more-persistent-than-query-key-initializations)  
   标签：评分：7.0/10、query:neural-arch
   evidence：向Transformer注意力注入显式结构先验以修正归纳偏置
6. [Beyond Symmetric Fusion: Exploiting Task-Dependent Modality Strengths for RGB-Event Small Object Detection](/202608/09/2608.01302v1-beyond-symmetric-fusion-exploiting-task-dependent-modality-strengths-for-rgb-event-small-object-detection)  
   标签：评分：7.0/10、query:neural-arch
   evidence：针对小目标检测的RGB与事件模态任务相关非对称融合
7. [SMM Transformer: Leveraging Spiking Neural Networks for Multimodal Tasks](/202608/09/2608.01622v1-smm-transformer-leveraging-spiking-neural-networks-for-multimodal-tasks)  
   标签：评分：7.0/10、query:neural-arch
   evidence：提出SNN多模态Transformer，设计新型神经元和注意力替代模块。
8. [Estimating SSIM from MSE for DCT-Based Compressed Images](/202608/09/2608.02549v1-estimating-ssim-from-mse-for-dct-based-compressed-images)  
   标签：评分：7.0/10、query:compress
   evidence：面向DCT压缩图像的SSIM估计
9. [Hybrid-Domain Posterior Sampling for Inverse Problems via Latent Flow Matching](/202608/09/2608.00537v1-hybrid-domain-posterior-sampling-for-inverse-problems-via-latent-flow-matching)  
   标签：评分：6.0/10、query:compress
   evidence：探讨自编码器瓶颈和压缩潜空间导致的高频信息丢失，与基于自编码器的图像压缩方法相关
10. [SparseKAN: Compressing Kolmogorov--Arnold Networks Across Basis Functions, Neurons, and Bits](/202608/09/2608.00859v1-sparsekan-compressing-kolmogorov--arnold-networks-across-basis-functions-neurons-and-bits)  
   标签：评分：6.0/10、query:neural-arch
   evidence：Kolmogorov-Arnold网络的多轴压缩与量化
11. [Rethinking Video Token Compression with a Global Codebook: Learning Once, Compressing Everywhere](/202608/09/2608.01271v1-rethinking-video-token-compression-with-a-global-codebook-learning-once-compressing-everywhere)  
   标签：评分：6.0/10、query:neural-arch
   evidence：利用全局码本将视频令牌压缩离线化以降低推理成本
12. [Prompt-Driven Simulation with Feature Perturbation for Cross-Domain Few-Shot Object Detection](/202608/09/2608.01348v2-prompt-driven-simulation-with-feature-perturbation-for-cross-domain-few-shot-object-detection)  
   标签：评分：6.0/10、query:neural-arch
   evidence：采用提示驱动模拟与特征扰动，提升跨域少样本目标检测性能。


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
