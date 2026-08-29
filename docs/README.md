<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-29
- 运行时间：2026-08-29 02:28:17 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：5
- 速读区：12

### 今日简报（AI）
今日共读17篇论文，精读5篇、速读12篇，重点聚焦高效模型与优化方法。最值得关注的是两篇8分工作：自适应对数空间量化实现内存高效优化器，以及无标签软最大转线性适配ViT用于目标检测。建议优先跟进视觉Transformer轻量化与训练显存优化方向，兼顾生成视频压缩和图神经网络分布式训练。
- 详情：[/202608/29/README](/202608/29/README)

### 精读区论文标签
1. [Beyond Dense Adam States: Adaptive Log-Space Quantization for Memory-Efficient Optimizers](/202608/29/2608.22322v2-beyond-dense-adam-states-adaptive-log-space-quantization-for-memory-efficient-optimizers)  
   标签：评分：8.0/10、query:neural-arch
   evidence：自适应对数空间量化用于优化器状态，属于深度学习模型优化策略，也可启发量化设计。
2. [DiD It in 87 Minutes: A Label-Free Softmax-to-Linear Adaptation of Vision Transformers for Object Detection](/202608/29/2608.22368v1-did-it-in-87-minutes-a-label-free-softmax-to-linear-adaptation-of-vision-transformers-for-object-detection)  
   标签：评分：8.0/10、query:neural-arch
   evidence：将ViT骨干从Softmax注意力无标签转换为线性注意力以适配目标检测
3. [RS$^3$-Prune: Read-Sparse, Store-Sparse Token Pruning for Video Object Segmentation](/202608/29/2608.22526v1-rs3-prune-read-sparse-store-sparse-token-pruning-for-video-object-segmentation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向视频目标分割的无训练token剪枝，降低视觉模型延迟和内存，属于高效架构技术
4. [MoTE: Mixture of Task Experts for Multi-Task Video Understanding](/202608/29/2608.24763v1-mote-mixture-of-task-experts-for-multi-task-video-understanding)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向多任务视频理解的任务专家路由解码器架构，属于架构改进技术
5. [Successive Capacity Growth: Task-Complexity-Driven Width and Depth Expansion for Vision Transformer Encoders in JEPA World Models](/202608/29/2608.27367v1-successive-capacity-growth-task-complexity-driven-width-and-depth-expansion-for-vision-transformer-encoders-in-jepa-world-models)  
   标签：评分：8.0/10、query:neural-arch
   evidence：任务复杂度驱动的宽度与深度扩展方法，用于高效视觉Transformer编码器

### 速读区论文标签
1. [DiffVC-ONE: Diffusion-based Generative Video Compression with One-Step Video Diffusion Transformer](/202608/29/2608.20515v1-diffvc-one-diffusion-based-generative-video-compression-with-one-step-video-diffusion-transformer)  
   标签：评分：7.0/10、query:compress
   evidence：基于潜在压缩器和一步视频扩散Transformer的神经视频压缩，可迁移至学习图像压缩
2. [Two-level domain-decomposition AdaGrad method for scalable training of graph neural networks](/202608/29/2608.22575v1-two-level-domain-decomposition-adagrad-method-for-scalable-training-of-graph-neural-networks)  
   标签：评分：7.0/10、query:neural-arch
   evidence：面向GNN训练的可扩展AdaGrad优化与区域分解
3. [Keep-or-Drop? Adaptive Tokenizer for Compact Video Representation](/202608/29/2608.24293v1-keep-or-drop-adaptive-tokenizer-for-compact-video-representation)  
   标签：评分：7.0/10、query:compress
   evidence：基于Transformer变分自编码器的自适应令牌选择紧凑视频表示，与自编码器图像压缩方法高度相关
4. [Pruning Binarized Neural Networks: A Dedicated Framework and Globally Weighted Algorithms](/202608/29/2608.26233v1-pruning-binarized-neural-networks-a-dedicated-framework-and-globally-weighted-algorithms)  
   标签：评分：7.0/10、query:neural-arch
   evidence：面向二值神经网络的剪枝框架与全局加权算法，是深度学习模型优化的直接策略。
5. [FAN-LoRA: A Fourier-Adaptive Nonlinear Low-Rank Adaptor for Medical Foundation Model Domain Adaptation](/202608/29/2608.26531v1-fan-lora-a-fourier-adaptive-nonlinear-low-rank-adaptor-for-medical-foundation-model-domain-adaptation)  
   标签：评分：7.0/10、query:neural-arch
   evidence：面向医学基础模型域自适应的参数高效微调适配器
6. [LeVJEPA: Efficient & Scalable Video Pretraining without the Heuristics](/202608/29/2608.27395v1-levjepa-efficient--scalable-video-pretraining-without-the-heuristics)  
   标签：评分：7.0/10、query:neural-arch
   evidence：高效自监督视频预训练架构与免坍塌正则化，属于通用CV深度学习方法
7. [Learning how to Forget: Fine-tuning for Long-Context Sparse Attention](/202608/29/2608.19920v1-learning-how-to-forget-fine-tuning-for-long-context-sparse-attention)  
   标签：评分：6.0/10、query:neural-arch
   evidence：面向长上下文稀疏注意力的微调方法以压缩KV缓存
8. [Bern2Edge: A Neurosymbolic Compiler for Edge Deployment via Bernstein Polynomial Networks](/202608/29/2608.20497v1-bern2edge-a-neurosymbolic-compiler-for-edge-deployment-via-bernstein-polynomial-networks)  
   标签：评分：6.0/10、query:neural-arch
   evidence：面向边缘部署的端到端神经网络压缩与编译框架
9. [LHMCF-Net: A Learned Hyperbolic Mean Curvature Flow Network for Medical Images Segmentation](/202608/29/2608.20942v1-lhmcf-net-a-learned-hyperbolic-mean-curvature-flow-network-for-medical-images-segmentation)  
   标签：评分：6.0/10、query:neural-arch
   evidence：基于双曲平均曲率流提出新型医学图像分割网络架构
10. [Jacobian-guided Noise Injection for Quantization Robustness in Large Language Models](/202608/29/2608.20988v1-jacobian-guided-noise-injection-for-quantization-robustness-in-large-language-models)  
   标签：评分：6.0/10、query:neural-arch
   evidence：提出训练时噪声注入策略以增强量化神经网络的鲁棒性
11. [μNet: Ultra-Low-Memory and Low-Complexity Speech Enhancement for Embedded Digital Signal Processors](/202608/29/2608.21155v1-net-ultra-low-memory-and-low-complexity-speech-enhancement-for-embedded-digital-signal-processors)  
   标签：评分：6.0/10、query:neural-arch
   evidence：面向嵌入式DSP的超低内存低复杂度DNN设计，可迁移至高效模型优化
12. [Benchmarking Composable Compression Techniques in Mixture-of-Experts LLMs](/202608/29/2608.21693v1-benchmarking-composable-compression-techniques-in-mixture-of-experts-llms)  
   标签：评分：6.0/10、query:neural-arch
   evidence：混合专家大语言模型中量化与剪枝等可组合压缩技术的基准评测


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
