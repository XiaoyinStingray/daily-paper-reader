<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-05
- 运行时间：2026-08-05 21:35:48 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今日精读聚焦图像编码与全高清视频识别，速读覆盖扩散变换器、低功耗视觉Transformer加速及多模态跟踪压缩。

最值得关注：Hadamard域量化提升学习图像编码效率，HiResNets用中央凹残差流实现原生全高清视频识别。

下一步可优先尝试多模态跟踪的蒸馏与剪枝协同方案，兼顾模型紧凑性与精度。
- 详情：[/202608/05/README](/202608/05/README)

### 精读区论文标签
1. [Hadamard-Domain Model Quantization for Learned Image Coding](/202608/05/2608.01653v1-hadamard-domain-model-quantization-for-learned-image-coding)  
   标签：评分：9.0/10、query:compress
   evidence：针对学习型图像编码中的模型量化问题，用哈达玛重参数化提升率失真性能。
2. [HiResNets: Native Full-HD Video Recognition with Foveal Residual Streams](/202608/05/2608.02140v2-hiresnets-native-full-hd-video-recognition-with-foveal-residual-streams)  
   标签：评分：9.0/10、query:neural-arch
   evidence：提出具有对数平方增长的残差网络，用于高效高分辨率视频识别
3. [GVCCTurbo: Rate-Compute Quality Scheduling for Codebook Driven Generative Compression](/202608/05/2608.03517v1-gvccturbo-rate-compute-quality-scheduling-for-codebook-driven-generative-compression)  
   标签：评分：9.0/10、query:compress
   evidence：直接面向图像压缩，为码本驱动的生成式压缩提供率-计算质量调度
4. [Interpretability-Guided Soft Pruning of Attention Heads in Vision Transformers](/202608/05/2608.00264v1-interpretability-guided-soft-pruning-of-attention-heads-in-vision-transformers)  
   标签：评分：8.0/10、query:neural-arch
   evidence：可解释性引导的视觉Transformer注意力头软剪枝
5. [Channel-Agnostic Semantic Compression for Bandwidth-Limited Visual Communication](/202608/05/2608.00394v1-channel-agnostic-semantic-compression-for-bandwidth-limited-visual-communication)  
   标签：评分：8.0/10、query:compress
   evidence：提出残差量化实现可扩展离散语义表示，并细粒度控制率失真折中
6. [Streamable Neural Video Compression: A Mixed Precision Approach for Cross-Platform Deployment](/202608/05/2608.00483v1-streamable-neural-video-compression-a-mixed-precision-approach-for-cross-platform-deployment)  
   标签：评分：8.0/10、query:compress
   evidence：利用混合精度量化解决神经编解码器跨平台部署问题，与压缩流程中的量化策略高度相关。
7. [Test-Time Curriculum for Open-Set AIGC Detection](/202608/05/2608.00559v1-test-time-curriculum-for-open-set-aigc-detection)  
   标签：评分：8.0/10、query:neural-arch
   evidence：测试时课程自训练作为一种性能提升技术

### 速读区论文标签
1. [UDT: Reconciling U-Nets and Diffusion Transformers with Data-Adaptive Token Reduction](/202608/05/2608.01298v1-udt-reconciling-u-nets-and-diffusion-transformers-with-data-adaptive-token-reduction)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向扩散Transformer的数据自适应令牌缩减，提升视觉生成中的表示质量与效率
2. [DeVIT: Low-Power Vision Transformer Acceleration Using Delta Computation](/202608/05/2608.01343v1-devit-low-power-vision-transformer-acceleration-using-delta-computation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：基于增量计算的低功耗视觉Transformer加速
3. [Towards Compact Unified Multimodal Tracking: Synergizing Knowledge Distillation with Structural Pruning](/202608/05/2608.01488v1-towards-compact-unified-multimodal-tracking-synergizing-knowledge-distillation-with-structural-pruning)  
   标签：评分：8.0/10、query:neural-arch
   evidence：结合知识蒸馏与结构剪枝，压缩多模态跟踪模型
4. [GraphIR: Architecture-Level Search States for LLM-Guided Neural Architecture Evolution](/202608/05/2608.01633v1-graphir-architecture-level-search-states-for-llm-guided-neural-architecture-evolution)  
   标签：评分：8.0/10、query:neural-arch
   evidence：提出架构感知中间表示支持LLM引导的神经架构搜索，直接服务于高效架构设计。
5. [ENCORE: Event-Assisted Complementary Motion Refinement for Learned Video Compression](/202608/05/2607.28020v1-encore-event-assisted-complementary-motion-refinement-for-learned-video-compression)  
   标签：评分：7.0/10、query:compress
   evidence：学习式视频压缩中的运动精化与率失真优化
6. [ReToken: One Token to Improve Vision-Language Models for Visual Retrieval](/202608/05/2607.28627v1-retoken-one-token-to-improve-vision-language-models-for-visual-retrieval)  
   标签：评分：7.0/10、query:neural-arch
   evidence：一个可学习的检索目标令牌从KV缓存中选择相关视觉令牌，提升VLM准确率与效率
7. [Domain-Adaptive Deep Joint Source-Channel Coding for Image Classification](/202608/05/2607.28907v1-domain-adaptive-deep-joint-source-channel-coding-for-image-classification)  
   标签：评分：7.0/10、query:compress
   evidence：端到端学习信源信道编码与学习式图像压缩及率失真优化在概念上一致
8. [RayViT: Ray-Conditioned Visual Representations for Viewpoint-Robust Imitation Learning](/202608/05/2607.29622v1-rayvit-ray-conditioned-visual-representations-for-viewpoint-robust-imitation-learning)  
   标签：评分：7.0/10、query:neural-arch
   evidence：向ViT注入几何信息的视觉架构改进
9. [Noise-Free One-Step LoRA for Task-Driven Image Restoration with Diffusion Priors](/202608/05/2607.25390v1-noise-free-one-step-lora-for-task-driven-image-restoration-with-diffusion-priors)  
   标签：评分：6.0/10、query:neural-arch
   evidence：LoRA适配参数优化策略用于图像恢复
10. [Beyond Token-Level Cross-Entropy: Fréchet Distributional Post-Training for Autoregressive Image Generation](/202608/05/2608.00562v1-beyond-token-level-cross-entropy-frchet-distributional-post-training-for-autoregressive-image-generation)  
   标签：评分：6.0/10、query:neural-arch
   evidence：为自回归图像生成器提出分布级后训练目标，属于性能提升技术。
11. [Proteus: A Truncation-Robust Entropy Model for Progressive LiDAR Compression](/202608/05/2608.00687v1-proteus-a-truncation-robust-entropy-model-for-progressive-lidar-compression)  
   标签：评分：6.0/10、query:compress
   evidence：面向LiDAR压缩的学习熵模型，与率失真相关，可迁移到图像压缩
12. [Coverage-Driven Adaptive Keyframe Selection for Video Understanding](/202608/05/2608.00714v1-coverage-driven-adaptive-keyframe-selection-for-video-understanding)  
   标签：评分：6.0/10、query:neural-arch
   evidence：自适应关键帧选择降低推理开销


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
