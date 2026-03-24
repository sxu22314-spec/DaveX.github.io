---
layout: default
---

<style>
  .section-title { border-bottom: 2px solid #159957; padding-bottom: 10px; margin-top: 50px; color: #159957; }
  
  /* 成员列表布局 */
  .team-container { display: flex; flex-wrap: wrap; gap: 20px; justify-content: space-between; margin-top: 20px; }
  .team-card { flex: 1; min-width: 200px; padding: 15px; border: 1px solid #eee; border-radius: 8px; text-align: center; transition: transform 0.3s; background: #f9f9f9; }
  .team-card:hover { transform: translateY(-5px); box-shadow: 0 4px 15px rgba(0,0,0,0.1); }
  .team-card h4 { margin: 10px 0 5px 0; }
  .github-link { font-size: 0.9em; color: #159957; text-decoration: none; font-weight: bold; }

  /* 模块卡片布局 */
  .module-container { display: flex; flex-direction: column; gap: 20px; margin-top: 30px; }
  .module-card { display: block; padding: 25px; border-left: 5px solid #159957; background: #fff; box-shadow: 0 2px 8px rgba(0,0,0,0.05); border-radius: 4px; text-decoration: none !important; color: inherit !important; transition: all 0.3s; }
  .module-card:hover { background: #f0fdf4; transform: translateX(10px); border-left-width: 10px; }
  .module-card h3 { margin: 0 0 10px 0; color: #159957; }
  .module-card p { margin: 0; font-size: 0.95em; color: #666; }
</style>

## 👥 团队成员
<div class="team-container">
  <div class="team-card">
    <h4>成员 A</h4>
    <p>后端开发 / 架构</p>
    <a href="https://username1.github.io" class="github-link">个人主页 →</a>
  </div>
  <div class="team-card">
    <h4>成员 B</h4>
    <p>前端开发 / UI设计</p>
    <a href="https://username2.github.io" class="github-link">个人主页 →</a>
  </div>
  <div class="team-card">
    <h4>成员 C</h4>
    <p>算法工程 / 丹青</p>
    <a href="https://username3.github.io" class="github-link">个人主页 →</a>
  </div>
  <div class="team-card">
    <h4>成员 D</h4>
    <p>产品经理 / 文档</p>
    <a href="https://username4.github.io" class="github-link">个人主页 →</a>
  </div>
</div>

<h2 class="section-title">🚀 项目模块概览</h2>
<div class="module-container">

  <a href="./modules/booking-system.html" class="module-card">
    <h3>在线预约系统</h3>
    <p>集成 Spring Boot 与 Vue 的全栈模块，支持专家排班、费用自动计算及 RESTful API 调用测试。</p>
  </a>

  <a href="./modules/interaction-design.html" class="module-card">
    <h3>交互式相机体验</h3>
    <p>基于摄像头识别的非 VR 硬件交互方案，通过图像算法实现流畅的用户手势反馈。</p>
  </a>

  <a href="./modules/image-denoising.html" class="module-card">
    <h3>图像去噪实验 (DnCNN)</h3>
    <p>展示深度卷积神经网络在 Fashion-MNIST 上的训练结果，通过模型压缩解决硬件显存限制问题。</p>
  </a>

  <a href="./modules/devops-docker.html" class="module-card">
    <h3>DevOps 与容器化</h3>
    <p>展示 Redis、MySQL 等中间件在 Docker 中的部署流程，以及如何利用 Docker Compose 快速构建环境。</p>
  </a>

  <a href="./modules/enterprise-mall.html" class="module-card">
    <h3>企业级电商复刻</h3>
    <p>基于微服务架构的项目展示，涵盖分布式权限管理、海量数据搜索及秒杀系统优化细节。</p>
  </a>

</div>
