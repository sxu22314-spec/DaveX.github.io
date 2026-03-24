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
    <h4>Member</h4>
    <p>[Contribution]</p>
    <a href="https://username1.github.io" class="github-link">homepage →</a>
  </div>
  <div class="team-card">
    <h4>Member</h4>
    <p>[Contribution]</p>
    <a href="https://username2.github.io" class="github-link">homepage →</a>
  </div>
  <div class="team-card">
    <h4>Member</h4>
    <p>[Contribution]</p>
    <a href="https://username3.github.io" class="github-link">homepage →</a>
  </div>
</div>

<h2 class="section-title">📍 Project Roadmap</h2>
<div class="module-container">

  <a href="./modules/01-motivation.html" class="module-card">
    <div class="module-info">
      <h3>1. Motivation & Research</h3>
      <p>The "Why" behind our project, literature gap analysis of 8 sources, and defined personas for Heritage/Social/Active tracks.</p>
    </div>
    <div class="arrow">›</div>
  </a>

  <a href="./modules/02-requirements.html" class="module-card">
    <div class="module-info">
      <h3>2. User Requirements</h3>
      <p>Visual User Journey Maps, core "Playful" requirements, and field evidence from user interviews and site observations.</p>
    </div>
    <div class="arrow">›</div>
  </a>

  <a href="./modules/03-ideation.html" class="module-card">
    <div class="module-info">
      <h3>3. Ideation & Alternatives</h3>
      <p>"Crazy Eights" rapid sketching, comparison of design alternatives, and the interactive Low-Fi Figma prototype.</p>
    </div>
    <div class="arrow">›</div>
  </a>

  <a href="./modules/04-implementation.html" class="module-card">
    <div class="module-info">
      <h3>4. Technical Implementation</h3>
      <p>System architecture diagrams, High-Fi functional system URL, and a detailed breakdown of individual contributions.</p>
    </div>
    <div class="arrow">›</div>
  </a>

  <a href="./modules/05-evaluation.html" class="module-card">
    <div class="module-info">
      <h3>5. Evaluation & Reflection</h3>
      <p>Usability testing results, iterative "Before & After" refinements, and discussion on ethical AI usage.</p>
    </div>
    <div class="arrow">›</div>
  </a>

</div>
