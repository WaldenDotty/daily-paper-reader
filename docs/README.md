<div class="dpr-home-notice-card">
  <h3 class="dpr-home-notice-title">🚀 Start Here</h3>
  <ul class="dpr-home-notice-list">
    <li><a href="#/tutorial/README">使用教程</a></li>
  </ul>
</div>

## 每次日报
- 最新运行日期：2026-08-23
- 运行时间：2026-08-23 19:30:24 UTC
- 运行状态：成功
- 本次总论文数：17
- 精读区：6
- 速读区：11

### 今日简报（AI）
今日精读6篇、速读11篇，共处理17篇论文，核心聚焦航天轨道设计与LiDAR SLAM技术；最值得关注的是GARATÉA-L半解析轨道设计理论（9.0分）和HP2-SLAM自适应混合ICP方法（8.0分），前者可提升轨道优化效率，后者在鲁棒性与算力间取得平衡；建议优先精读这两篇，并顺带浏览多基地雷达自标定与GNSS拒止环境下的地图校正论文。
- 详情：[/202608/23/README](/202608/23/README)

### 精读区论文标签
1. [A Semi-Analytical Theory for Improved Orbit Design of the GARATÉA-L](/202608/23/2608.17672v1-a-semi-analytical-theory-for-improved-orbit-design-of-the-garata-l)  
   标签：评分：9.0/10、query:cislunar-dyn-nav
   evidence：月球轨道设计，包含月球引力谐波和地球三体摄动，属核心地月空间动力学
2. [HP2-SLAM: Adaptive Hybrid ICP for Robust and Efficient LiDAR SLAM](/202608/23/2608.14996v1-hp2-slam-adaptive-hybrid-icp-for-robust-and-efficient-lidar-slam)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：自适应混合ICP的鲁棒LiDAR SLAM，可直接用于月球近距自主定位与建图
3. [Improving Observability of Relative Orbit Estimation Using Bearing Measurements and Light Curves](/202608/23/2608.16135v1-improving-observability-of-relative-orbit-estimation-using-bearing-measurements-and-light-curves)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：融合方位测量与光变曲线进行相对轨道估计，支撑自主导航
4. [Orbit-Planner: Towards Latent World Models for On-Orbit Obstacle Avoidance of Satellite Agents](/202608/23/2608.16651v1-orbit-planner-towards-latent-world-models-for-on-orbit-obstacle-avoidance-of-satellite-agents)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：用于卫星在轨自主避障的潜在世界模型，与月球近距离自主导航方法高度契合
5. [Adaptive Nonlinear Control with Online Identification and Receding-Horizon Optimization](/202608/23/2608.18717v1-adaptive-nonlinear-control-with-online-identification-and-receding-horizon-optimization)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：以自主月球着陆器下降为应用，涉及滚动时域轨迹优化与控制
6. [Gravity-aware partially calibrated absolute pose estimation from affine- or rotation-covariant features](/202608/23/2608.20056v1-gravity-aware-partially-calibrated-absolute-pose-estimation-from-affine--or-rotation-covariant-features)  
   标签：评分：8.0/10、query:cislunar-dyn-nav
   evidence：视觉-惯性融合与重力感知位姿估计，可迁移至地月空间定位与导航

### 速读区论文标签
1. [Target Localization and Self-Calibration in a Multistatic Radar System](/202608/23/2608.15501v1-target-localization-and-self-calibration-in-a-multistatic-radar-system)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：多基地雷达目标定位与自标定，联合加权最小二乘，适用于多传感器定位融合
2. [Marker-Constrained Pose-Graph Correction for Cross-Platform Georeferencing in GNSS-Denied Environments](/202608/23/2608.16281v1-marker-constrained-pose-graph-correction-for-cross-platform-georeferencing-in-gnss-denied-environments)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：利用标记约束的位姿图校正实现GNSS拒止环境下的地理参考，可应用于月球自主导航
3. [Terrain-Aware Local Path Planning with Global DEM Data Integration for Autonomous UGV Navigation](/202608/23/2608.17038v1-terrain-aware-local-path-planning-with-global-dem-data-integration-for-autonomous-ugv-navigation)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：融合全球DEM与LiDAR的地形感知路径规划，适用于月球近距作业的自主导航
4. [CVSD-Reg: Cross-Modal Visual Semantic Prior Distillation for Robust LiDAR Registration](/202608/23/2608.19536v1-cvsd-reg-cross-modal-visual-semantic-prior-distillation-for-robust-lidar-registration)  
   标签：评分：7.0/10、query:cislunar-dyn-nav
   evidence：通过跨模态视觉语义先验蒸馏提升LiDAR配准鲁棒性，适用于月球导航多传感器融合
5. [Accelerating Mixed Discrete-Continuous Motion Planning via Neural Graphs of Convex Sets](/202608/23/2608.15440v1-accelerating-mixed-discrete-continuous-motion-planning-via-neural-graphs-of-convex-sets)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：利用凸集图与图注意力网络加速混合离散-连续运动规划，可迁移至航天器轨迹优化
6. [Condensed PIPG Sequential Convex Optimization for Reusable-Rocket Powered Landing with Strong Aerodynamics](/202608/23/2608.15582v1-condensed-pipg-sequential-convex-optimization-for-reusable-rocket-powered-landing-with-strong-aerodynamics)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：凝聚序贯凸优化求解动力着陆轨迹，可迁移至地月系统轨迹优化
7. [Adaptive Relative Orbit Control Considering Laser Ablation Uncertainty](/202608/23/2608.16173v1-adaptive-relative-orbit-control-considering-laser-ablation-uncertainty)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：基于高斯过程的自适应相对轨道控制，适用于模型不确定下的近距离操作
8. [DPNet: Efficient Dead-End Prediction and Avoidance for Vision-Based UAV Navigation](/202608/23/2608.16640v1-dpnet-efficient-dead-end-prediction-and-avoidance-for-vision-based-uav-navigation)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：基于轻量神经网络的自主任航避障算法，可应用于月球近距离操作
9. [Jetson-ORB-SLAM3: Accuracy-Preserving GPU Implementation for Edge Computing Devices](/202608/23/2608.17874v1-jetson-orb-slam3-accuracy-preserving-gpu-implementation-for-edge-computing-devices)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：边缘设备上的保精度ORB-SLAM3 GPU实现，支持GNSS拒止环境自主导航，可用于月球临近操作
10. [Diffractive-Sail Single-Impulse Reachable Set for Interplanetary Transfer Design](/202608/23/2608.19654v1-diffractive-sail-single-impulse-reachable-set-for-interplanetary-transfer-design)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：面向星际转移设计的可达集计算方法，可迁移至地月系统轨迹优化
11. [World-Model-Grounded LLM Planning for AUV and ASV Navigation Near Offshore Wind Farms](/202608/23/2608.19661v1-world-model-grounded-llm-planning-for-auv-and-asv-navigation-near-offshore-wind-farms)  
   标签：评分：6.0/10、query:cislunar-dyn-nav
   evidence：基于世界模型的LLM规划与MPC重规划用于自主导航，可迁移至地月空间抵近操作


<div class="dpr-home-promo-card">
  <h3 class="dpr-home-promo-title">💬 社区与支持</h3>
  <ul class="dpr-home-promo-list">
    <li>欢迎 Star / Fork / Issue / PR</li>
    <li>QQ群：583867967（欢迎交流，已有：1151人）</li>
  </ul>
</div>
