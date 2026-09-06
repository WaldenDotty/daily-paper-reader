<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-09-06
- 运行时间：2026-09-06 21:59:51 UTC
- 运行状态：成功
- 本次总论文数：13
- 精读区：4
- 速读区：9

### 今日简报（AI）
今日精读13篇，聚焦三体问题航天器动力学与低推力轨迹优化，另有传感器融合及月球高程估计等速读内容。最值得关注的是N体问题推进剂计算新方法（9.0分），以及量子计算结合凸优化求解低推力轨迹（8.0分）。若想入门，建议优先浏览评分9.0的三体问题论文，其对深空任务设计有直接参考价值。
- 详情：[/202609/06/README](/202609/06/README)

### 精读区论文标签
1. [Nechvile-Transformed Spacecraft Dynamics and Propellant Computation in the 3-Body Problem](/202609/06/2608.29271v1-nechvile-transformed-spacecraft-dynamics-and-propellant-computation-in-the-3-body-problem)  
   标签：评分：9.0/10、query:cislunar-dyn-nav
   evidence：研究限制性三体问题中的Nechvile变换航天器动力学，并给出加力与推进剂计算修正，直接对应CR3BP需求。
2. [Low-Thrust Trajectory Optimization with Quantum Computing and Sequential Convex Programming](/202609/06/2609.00861v1-low-thrust-trajectory-optimization-with-quantum-computing-and-sequential-convex-programming)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：使用序列凸规划与量子QUBO重构求解低推力轨迹优化，可迁移至地月系统轨迹优化
3. [Families of relative periodic orbits in the planar three-body problem via consecutive alignments](/202609/06/2609.01585v1-families-of-relative-periodic-orbits-in-the-planar-three-body-problem-via-consecutive-alignments)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：提出三体问题相对周期轨道族数值计算与稳定性分析，可为地月系统周期轨道与NRHO研究提供方法论支撑
4. [Low-energy ring particle accretion as the origin of Pan's equatorial ridge](/202609/06/2609.03060v1-low-energy-ring-particle-accretion-as-the-origin-of-pans-equatorial-ridge)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：使用CR3BP并分析L1与L2颈部穿越的低能吸积轨道，与低能转移和不变流形需求相关。

### 速读区论文标签
1. [A Sliding Window Filter on the Galilean Group for Consistent Aided Inertial Navigation with Unknown Measurement Delays](/202609/06/2608.29514v1-a-sliding-window-filter-on-the-galilean-group-for-consistent-aided-inertial-navigation-with-unknown-measurement-delays)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：伽利略群滑动窗滤波联合估计导航状态与未知传感器时延，可支撑地月空间多传感器融合定位授时。
2. [Efficient Sensor Fusion Through Covariance-Constrained Observation Decimation (CCOD)](/202609/06/2609.02010v1-efficient-sensor-fusion-through-covariance-constrained-observation-decimation-ccod)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：利用协方差约束观测抽取实现高效传感器融合
3. [Adapting a Foundation Model for Lunar Surface Height Estimation](/202609/06/2609.02448v1-adapting-a-foundation-model-for-lunar-surface-height-estimation)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：月面高程估计是着陆危险检测和近月自主导航的关键支撑，该文用基础模型适配实现月面DEM估计。
4. [GPU-Accelerated Astrodynamics World Models for Spacecraft Rendezvous and Proximity Operations](/202609/06/2609.03067v1-gpu-accelerated-astrodynamics-world-models-for-spacecraft-rendezvous-and-proximity-operations)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：基于世界模型实现航天器交会与近距操作的自主规划与轨迹预测，可迁移至月球近距操作自主导航
5. [Can Julia land on the Moon? On the development of a GNC simulation framework for the Argonaut lunar lander](/202609/06/2609.03843v1-can-julia-land-on-the-moon-on-the-development-of-a-gnc-simulation-framework-for-the-argonaut-lunar-lander)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：月球着陆GNC仿真框架ATLAS，用于月球自主导航算法验证
6. [Transversality Conditions for Boundary Constraints Defined by Differential Equations](/202609/06/2609.04084v1-transversality-conditions-for-boundary-constraints-defined-by-differential-equations)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：面向N体系统轨迹优化的横截条件推导
7. [Design and Implementation of a Kalman Filter-Infused Algorithm for Tilt Estimation](/202609/06/2609.00730v1-design-and-implementation-of-a-kalman-filter-infused-algorithm-for-tilt-estimation)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：演示基于卡尔曼滤波的多传感器融合实现倾角估计，是可用于导航系统的通用传感器融合方法
8. [Real-Time Model Predictive Control Algorithms for Autonomous Spacecraft Guidance](/202609/06/2609.00927v1-real-time-model-predictive-control-algorithms-for-autonomous-spacecraft-guidance)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：面向自主交会制导的实时模型预测控制涉及在线轨迹优化与动力学稳定性分析，可作为地月系统轨迹优化与稳定性研究的方法参考。
9. [Vision-Based Leader-Follower Formation Control for Cooperative UAVs in GPS-Degraded Environments](/202609/06/2609.01420v1-vision-based-leader-follower-formation-control-for-cooperative-uavs-in-gps-degraded-environments)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：面向GPS失效环境的视觉与深度融合相对定位方法，可迁移至月球临近操作中的自主导航


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
