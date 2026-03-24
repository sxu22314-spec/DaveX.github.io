---
layout: default
title: Phase 1 - Motivation & Research
---

<style>
  /* 全局样式优化 */
  .main-content h2 { border-bottom: 2px solid #159957; padding-bottom: 8px; color: #159957; margin-top: 40px; }
  
  /* 1.1 The Why - 框内展示 */
  .motivation-box {
    background-color: #f8f9fa;
    border-left: 8px solid #159957;
    padding: 25px;
    border-radius: 4px;
    box-shadow: inset 0 0 10px rgba(0,0,0,0.02);
    margin: 20px 0;
    line-height: 1.7;
    font-style: italic;
    color: #34495e;
  }

  /* 1.2 The Gap - 表格优化 */
  .gap-table { width: 100%; border-collapse: collapse; margin: 20px 0; font-size: 0.9em; }
  .gap-table th { background-color: #159957; color: white; padding: 12px; text-align: left; }
  .gap-table td { border: 1px solid #e1e4e8; padding: 12px; vertical-align: top; }
  .gap-table tr:nth-child(even) { background-color: #fcfcfc; }
  .list-good { color: #28a745; font-weight: bold; margin-bottom: 5px; }
  .list-miss { color: #d73a49; font-weight: bold; margin-bottom: 5px; }
  ul.custom-list { list-style: none; padding-left: 0; margin: 0; }
  ul.custom-list li::before { content: "• "; margin-right: 5px; }

  /* 1.3 Stakeholders - 左右布局 */
  .persona-container { display: flex; gap: 20px; flex-wrap: wrap; margin-top: 20px; }
  .persona-card { 
    flex: 1; 
    min-width: 300px; 
    border: 1px solid #eaecef; 
    border-top: 5px solid #159957; 
    border-radius: 8px; 
    padding: 20px; 
    background: #fff;
    transition: transform 0.3s ease;
  }
  .persona-card:hover { transform: translateY(-5px); box-shadow: 0 8px 20px rgba(0,0,0,0.1); }
  .persona-header { display: flex; align-items: center; margin-bottom: 15px; }
  .persona-avatar { width: 60px; height: 60px; background: #e6f6ed; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 30px; margin-right: 15px; }
  .persona-title h3 { margin: 0; color: #222; font-size: 1.2em; }
  .persona-tag { font-size: 0.8em; color: #159957; font-weight: bold; text-transform: uppercase; }
  .persona-body b { color: #159957; }
</style>

# 📂 Module 1: Motivation & Research

## 1.1 The Why: Choosing the Social Track

<div class="motivation-box">
  Our group chose the <b>Social Track</b> because the "Generation Gap" is no longer just a difference in values, but a profound <b>Digital Divide</b>. While Gen Z navigates immersive visual media, the elderly are often isolated in static, text-heavy digital environments. We believe social interaction should not be a technical hurdle. 
  <br><br>
  By focusing on the Social Track, we aim to design a <b>Playful Experience (PxD)</b> that utilizes accessible camera-based interactions to create a "shared playground." This approach transforms intergenerational communication from a mundane video call into an active, collaborative game, proving that technology can be a bridge for emotional resonance rather than a barrier to connection.
</div>

---

## 1.2 The Gap: Literature & Market Analysis

### 📚 Academic Papers
<table class="gap-table">
  <tr>
    <th width="30%">Paper Focus</th>
    <th width="35%">3 Things They Did Well</th>
    <th width="35%">3 Things They Missed</th>
  </tr>
  <tr>
    <td><b>Intergenerational Play & Joy</b></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Strong theoretical framework</li>
        <li>Defined "shared joy" metrics</li>
        <li>Long-term impact analysis</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>High hardware costs</li>
        <li>Ignored low-literacy users</li>
        <li>Limited scalability</li>
      </ul>
    </td>
  </tr>
  <td><b>Relational Design for Sensorial Play</b><br><small>Focus: Multi-sensory (Touch/Sound) Remote Play</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Emphasized <b>non-verbal bonding</b> through tactile feedback.</li>
        <li>Reduced "performance anxiety" in conversation.</li>
        <li>Created a "third space" beyond simple video screens.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>Required <b>specialized hardware</b> (sensors) not found in homes.</li>
        <li>High latency issues for real-time synchronization.</li>
        <li>Short-term engagement; lacked a narrative "hook."</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Story-Me System</b><br><small>Focus: Storytelling & Digital Preservation</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Strong focus on <b>long-term heritage</b> and legacy.</li>
        <li>Scaffolded prompts to help seniors recall memories.</li>
        <li>Validated the emotional value of "being heard."</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li><b>Passive for youth:</b> Grandkids were often just "listeners."</li>
        <li>High cognitive load for uploading/organizing media.</li>
        <li>Lack of "Playfulness" (too much like an interview).</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Tangible VR-Based System (2022)</b><br><small>Focus: Immersive VR & Co-Learning</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Combined <b>physical objects</b> with virtual environments.</li>
        <li>Enhanced spatial presence (feeling "together").</li>
        <li>Used gamification to drive the learning process.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li><b>VR Sickness:</b> Physical discomfort for many elderly users.</li>
        <li>Isolation: High-end headsets hide facial expressions.</li>
        <li>Unnatural interaction: Controllers were too complex.</li>
      </ul>
    </td>
  </tr>
</table>

### 🛠 Commercial Products
<table class="gap-table">
  <tr>
    <th width="30%">Product Name</th>
    <th width="35%">3 Things They Did Well</th>
    <th width="35%">3 Things They Missed</th>
  </tr>
  <tr>
    <td><b>FaceTime / Zoom</b></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Extreme stability</li>
        <li>High market reach</li>
        <li>Simple UI for calls</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>Passive interaction</li>
        <li>"Video call fatigue"</li>
        <li>No shared activities</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Roblox (Social Play)</b></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Infinite creativity</li>
        <li>Highly playful mechanics</li>
        <li>Real-time interaction</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>Steep learning curve for seniors</li>
        <li>Complex navigation</li>
        <li>Chaotic social environment</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>StorySign (by Huawei/Aardman)</b><br><small>Focus: AI Sign Language Translation</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Innovative <b>real-time AI avatars</b> for sign language.</li>
        <li>Focuses on a highly <b>specific niche</b> (deaf children).</li>
        <li>Strong emotional impact on family literacy.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li><b>One-way flow:</b> Lacks reciprocal play mechanics.</li>
        <li>Limited library: Only works with specific physical books.</li>
        <li>Lacks "Intergenerational" <b>shared controls</b>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Osmo / Various AR Storybooks</b><br><small>Focus: Phygital (Physical + Digital) Play</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Excellent <b>tangible feedback</b> using physical tiles/drawings.</li>
        <li>Encourages "heads-up" play away from the screen.</li>
        <li>Highly intuitive for children (Low learning curve).</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li><b>Remote Isolation:</b> Primarily designed for co-located play.</li>
        <li>Hardware dependent: Requires <b>specific mirrors/reflectors</b>.</li>
        <li>Over-simplistic for seniors (may feel too "childish").</li>
      </ul>
    </td>
  </tr>
</table>

---

## 1.3 The Stakeholders

<div class="persona-container">
  <div class="persona-card">
    <div class="persona-header">
      <div class="persona-avatar">👴</div>
      <div class="persona-title">
        <span class="persona-tag">Primary User</span>
        <h3>Grandpa Chen (72)</h3>
      </div>
    </div>
    <div class="persona-body">
      <p><b>Background:</b> Retired engineer living in Suzhou. Values family but feels "left behind" by fast apps.</p>
      <p><b>Pain Points:</b> Finds modern UI "scary"; lonely during weekdays; distracted by tech complexity.</p>
      <p><b>Goal:</b> A simple, dignified way to "play" with his grandkids without needing a manual.</p>
    </div>
  </div>

  <div class="persona-card">
    <div class="persona-header">
      <div class="persona-avatar">👦</div>
      <div class="persona-title">
        <span class="persona-tag">Secondary User</span>
        <h3>Leo (9)</h3>
      </div>
    </div>
    <div class="persona-body">
      <p><b>Background:</b> Tech-native student. Loves Minecraft and interactive visual content.</p>
      <p><b>Pain Points:</b> Finds traditional video calls "boring"; has nothing to talk about with elders.</p>
      <p><b>Goal:</b> Wants to "do something fun" with Grandpa, making the call feel like a shared game.</p>
    </div>
  </div>
</div>

<br>

[← Back to Roadmap](/)
