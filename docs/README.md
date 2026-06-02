<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-06-02
- 运行时间：2026-06-02 21:51:24 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今天对19篇论文进行了分类筛选，7篇精读、12篇速读，重点关注通道向量量化与图像压缩领域的最新进展。最值得关注的两篇高分精读是通道级向量量化（9.0）及小波域Transformer注意力图像压缩ChWDTA（9.0），在模型效率与压缩性能上各有创新。建议优先阅读这两篇，尤其适合关注模型压缩或图像处理的读者，能获得实用的技术思路。
- 详情：[/202606/02/README](/202606/02/README)

### 精读区论文标签
1. [Channel-wise Vector Quantization](/202606/02/2605.26089v2-channel-wise-vector-quantization)  
   标签：评分：9.0/10、query:compress
   evidence：提出通道级向量量化用于图像标记化
2. [ChWDTA: Channel-wise Wavelet-Domain Transformer Attention and Entropy Modeling for Learned Image Compression](/202606/02/2606.00111v1-chwdta-channel-wise-wavelet-domain-transformer-attention-and-entropy-modeling-for-learned-image-compression)  
   标签：评分：9.0/10、query:compress
   evidence：通道级小波变换用于学习图像压缩
3. [Training-Free Continuous Bitrate Control for Scalable Image Coding for Humans and Machines](/202606/02/2606.00158v1-training-free-continuous-bitrate-control-for-scalable-image-coding-for-humans-and-machines)  
   标签：评分：9.0/10、query:compress
   evidence：直接针对图像压缩中量化步长调整实现连续码率控制
4. [Exploiting Semantic and Pixel Representations for Ultra-Low Bitrate Image Compression](/202606/02/2606.01608v1-exploiting-semantic-and-pixel-representations-for-ultra-low-bitrate-image-compression)  
   标签：评分：9.0/10、query:compress
   evidence：超低比特率图像压缩，使用扩散模型，优化率失真感知平衡
5. [DVSM: Decoder-only View Synthesis Model Done Right](/202606/02/2605.29891v1-dvsm-decoder-only-view-synthesis-model-done-right)  
   标签：评分：8.0/10、query:neural-arch
   evidence：仅解码器架构在视图合成中优于编码器-解码器
6. [TASER: Task-Aware Stein Regularisation for Geometry-Driven Robustness](/202606/02/2605.30601v1-taser-task-aware-stein-regularisation-for-geometry-driven-robustness)  
   标签：评分：8.0/10、query:neural-arch
   evidence：任务感知Stein正则化用于鲁棒性
7. [Inconsistency-Aware Minimization: Improving Generalization with Unlabeled Data](/202606/02/2605.31324v1-inconsistency-aware-minimization-improving-generalization-with-unlabeled-data)  
   标签：评分：8.0/10、query:neural-arch
   evidence：局部不一致性泛化度量

### 速读区论文标签
1. [LASER: Loss-Aware Singular-value Decomposition and Rank Allocation for Efficient Low-Precision Vision-Language Models](/202606/02/2606.00573v1-laser-loss-aware-singular-value-decomposition-and-rank-allocation-for-efficient-low-precision-vision-language-models)  
   标签：评分：8.0/10、query:neural-arch
   evidence：损失感知的低秩分解用于视觉语言模型效率
2. [Scaling Parallel Sequence Models to Foundation-Scale Vision Encoders](/202606/02/2606.00746v1-scaling-parallel-sequence-models-to-foundation-scale-vision-encoders)  
   标签：评分：8.0/10、query:neural-arch
   evidence：具有近线性复杂度的基础视觉编码器
3. [Beyond $\ell_2$-norm and $\ell_\infty$-norm: A Curvature-Inspired $\ell_p$-Norm Scheme for Deep Neural Networks](/202606/02/2606.02078v1-beyond-ell2-norm-and-ellinfty-norm-a-curvature-inspired-ellp-norm-scheme-for-deep-neural-networks)  
   标签：评分：8.0/10、query:neural-arch
   evidence：基于曲率的深度神经网络优化器方案
4. [Tensor Memory: Fixed-Size Recurrent State for Long-Horizon Transformers](/202606/02/2605.27686v1-tensor-memory-fixed-size-recurrent-state-for-long-horizon-transformers)  
   标签：评分：7.0/10、query:neural-arch
   evidence：面向长序列Transformer的固定大小循环3D记忆
5. [AsymVLM: Asymmetric Token Pruning for Efficient Vision-Language Model Inference](/202606/02/2605.29535v1-asymvlm-asymmetric-token-pruning-for-efficient-vision-language-model-inference)  
   标签：评分：7.0/10、query:neural-arch
   evidence：非对称token剪枝实现高效视觉语言模型推理
6. [PRISM: Progressive Reasoning through Iterative Slot Memory for Vision](/202606/02/2605.30942v1-prism-progressive-reasoning-through-iterative-slot-memory-for-vision)  
   标签：评分：7.0/10、query:neural-arch
   evidence：基于槽记忆的迭代细化视觉架构
7. [Augmented Lagrangian Predictive Coding](/202606/02/2605.31022v1-augmented-lagrangian-predictive-coding)  
   标签：评分：7.0/10、query:neural-arch
   evidence：使用局部学习替代反向传播训练深度网络
8. [Toward Identifiable Sparse Autoencoders](/202606/02/2605.31245v1-toward-identifiable-sparse-autoencoders)  
   标签：评分：7.0/10、query:neural-arch
   evidence：改进稀疏自编码器训练以获得稳定表示
9. [MAIL++: Multi-Modal Bi-directional Agent Layer for Vision-Language Models](/202606/02/2605.25479v1-mail-multi-modal-bi-directional-agent-layer-for-vision-language-models)  
   标签：评分：6.0/10、query:neural-arch
   evidence：针对视觉语言模型的参数高效微调，与计算机视觉通用方法相关
10. [Event-to-Video Reconstruction using Spatio-Temporal and Frequency-Enhanced Deep Neural Networks](/202606/02/2605.25804v1-event-to-video-reconstruction-using-spatio-temporal-and-frequency-enhanced-deep-neural-networks)  
   标签：评分：6.0/10、query:neural-arch
   evidence：用于事件到视频重建的时空和频率增强深度神经网络
11. [Max-Window Scale Estimation for Near-Lossless HiF8 W8A8 Quantization-Aware Training](/202606/02/2605.26189v1-max-window-scale-estimation-for-near-lossless-hif8-w8a8-quantization-aware-training)  
   标签：评分：6.0/10、query:neural-arch
   evidence：针对大语言模型的高比特量化感知训练，识别并处理amax饱和与灾难性遗忘失败模式
12. [MRT: Masked Region Transformer for Layered Image Generation and Editing at Scale](/202606/02/2605.27235v1-mrt-masked-region-transformer-for-layered-image-generation-and-editing-at-scale)  
   标签：评分：6.0/10、query:neural-arch
   evidence：大规模掩码区域扩散模型用于分层图像生成


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
