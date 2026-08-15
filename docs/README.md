<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-15
- 运行时间：2026-08-15 19:48:02 UTC
- 运行状态：成功
- 本次总论文数：19
- 精读区：7
- 速读区：12

### 今日简报（AI）
今日精读7篇、速读12篇，聚焦图像压缩与视觉Transformer的效率优化。

最值得关注的是HAMP-LIC的混合精度量化（9.0分）与MergeOver的递归Transformer token合并（9.0分），均在不牺牲性能前提下大幅降低计算成本。

初学者可先看这两篇的轻量化思路，再结合速读中的剪枝与梯度优化论文，形成效率提升全景。
- 详情：[/202608/15/README](/202608/15/README)

### 精读区论文标签
1. [HAMP-LIC: Hessian-Aware Mixed-Precision Post-Training Quantization for Learned Image Compression](/202608/15/2608.12239v1-hamp-lic-hessian-aware-mixed-precision-post-training-quantization-for-learned-image-compression)  
   标签：评分：9.0/10、query:compress
   evidence：面向学习图像压缩的海森感知混合精度训练后量化
2. [MergeOver: Post-Training Token Merging for Recursive Vision Transformers](/202608/15/2608.13141v1-mergeover-post-training-token-merging-for-recursive-vision-transformers)  
   标签：评分：9.0/10、query:neural-arch
   evidence：为递归视觉Transformer提出训练后令牌合并以降低计算开销
3. [Prune Once: Retraining-Free Task-Agnostic Pruning for Vision-Language Models](/202608/15/2608.06901v1-prune-once-retraining-free-task-agnostic-pruning-for-vision-language-models)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向视觉语言模型的免重训练任务无关剪枝
4. [TEMPER: Tensorized Efficient Manifold-constrained Parameterization for Expressive Residual Routing](/202608/15/2608.07851v1-temper-tensorized-efficient-manifold-constrained-parameterization-for-expressive-residual-routing)  
   标签：评分：8.0/10、query:neural-arch
   evidence：残差路由的张量化参数化
5. [Circuit Fine-Tuning for Compute-Efficient Transformer Adaptation](/202608/15/2608.08336v1-circuit-fine-tuning-for-compute-efficient-transformer-adaptation)  
   标签：评分：8.0/10、query:neural-arch
   evidence：面向深度Transformer适配的计算高效微调框架，属于深度学习模型优化策略。
6. [Rethinking Data Efficiency in Industrial Dense Prediction: Pretraining Coherence, Not Inductive Bias, Determines ViTs Low-Data Advantage](/202608/15/2608.10590v1-rethinking-data-efficiency-in-industrial-dense-prediction-pretraining-coherence-not-inductive-bias-determines-vits-low-data-advantage)  
   标签：评分：8.0/10、query:neural-arch
   evidence：分析ViT与CNN数据效率差异并提出AlignBlock架构重校准模块
7. [Lossy Compression, Realism, and Coordination](/202608/15/2608.12222v1-lossy-compression-realism-and-coordination)  
   标签：评分：8.0/10、query:compress
   evidence：综述有损压缩中率失真-感知权衡，并将其与协调问题联系

### 速读区论文标签
1. [Domain-Aware Pruning: Sparsity and Domain Generalization via Regularized Probabilistic Masking](/202608/15/2608.08624v1-domain-aware-pruning-sparsity-and-domain-generalization-via-regularized-probabilistic-masking)  
   标签：评分：8.0/10、query:neural-arch
   evidence：通过连续概率掩码同时优化网络稀疏性与跨域泛化，是一种模型优化策略
2. [Full-bandwidth transformer](/202608/15/2608.08888v1-full-bandwidth-transformer)  
   标签：评分：8.0/10、query:neural-arch
   evidence：带潜在反馈的Transformer架构
3. [Gradient Under Microscope: Benchmarking Resource Utilization of Memory-Efficient Gradient Computation Methods](/202608/15/2608.08961v1-gradient-under-microscope-benchmarking-resource-utilization-of-memory-efficient-gradient-computation-methods)  
   标签：评分：8.0/10、query:neural-arch
   evidence：评测了梯度检查点与梯度累积等节省显存的训练策略
4. [Generalized Convexity and Smoothness via Conjugate Duality: Optimization Theory for Deep Neural Networks](/202608/15/2608.09523v1-generalized-convexity-and-smoothness-via-conjugate-duality-optimization-theory-for-deep-neural-networks)  
   标签：评分：8.0/10、query:neural-arch
   evidence：通过推广凸性与光滑性为深度网络训练提供统一优化理论
5. [ControlRef: Efficient Layout-Guided Multi-Instance Generation via Anchored 4D-RoPE](/202608/15/2608.06878v1-controlref-efficient-layout-guided-multi-instance-generation-via-anchored-4d-rope)  
   标签：评分：7.0/10、query:neural-arch
   evidence：面向扩散Transformer的多实例生成提出高效注意力设计，降低计算开销
6. [HazeSpikeMamba: Coupling Spiking-Inspired and State-Space Features for Self-Supervised Real-World Dehazing](/202608/15/2608.06886v1-hazespikemamba-coupling-spiking-inspired-and-state-space-features-for-self-supervised-real-world-dehazing)  
   标签：评分：7.0/10、query:neural-arch
   evidence：结合脉冲启发局部路径与状态空间全局路径的紧凑去雾框架
7. [ZOMP: Zeroth-Order Multi-Modal Prompt Tuning for Vision-Language Models](/202608/15/2608.08060v1-zomp-zeroth-order-multi-modal-prompt-tuning-for-vision-language-models)  
   标签：评分：7.0/10、query:neural-arch
   evidence：面向CLIP的零阶多模态提示调优，是一种免反传的模型微调优化策略
8. [Open-World Semantic Segmentation with Sensitivity Modeling](/202608/15/2608.08308v1-open-world-semantic-segmentation-with-sensitivity-modeling)  
   标签：评分：7.0/10、query:neural-arch
   evidence：开放世界语义分割与灵敏度建模
9. [Bend the Basics: Degradation-Aware Deformable Tokenization for All-in-One Image Restoration](/202608/15/2608.06832v1-bend-the-basics-degradation-aware-deformable-tokenization-for-all-in-one-image-restoration)  
   标签：评分：6.0/10、query:neural-arch
   evidence：面向图像恢复架构的退化感知可变形分词
10. [No Unique Minimizer, No Problem: On the Consistency of Robust Neural Classifiers](/202608/15/2608.08489v1-no-unique-minimizer-no-problem-on-the-consistency-of-robust-neural-classifiers)  
   标签：评分：6.0/10、query:neural-arch
   evidence：针对不可辨识神经网络的鲁棒分类器优化一致性理论
11. [SC-Diff: Semantically Calibrated Diffusion for Visible-to-Infrared Image Translation](/202608/15/2608.08555v1-sc-diff-semantically-calibrated-diffusion-for-visible-to-infrared-image-translation)  
   标签：评分：6.0/10、query:neural-arch
   evidence：对潜扩散自注意力进行语义校准以改进图像翻译
12. [Degradation-Guided Underwater Image Restoration with Task-Oriented Latent Control](/202608/15/2608.08661v1-degradation-guided-underwater-image-restoration-with-task-oriented-latent-control)  
   标签：评分：6.0/10、query:neural-arch
   evidence：提出带退化引导特征自适应与潜在控制的水下图像恢复网络，属于视觉架构改进


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
