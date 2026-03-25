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
  Our group chose the <b>Social Track</b> because the core challenge of intergenerational relationships is not a lack of technology, but a "connection gap" characterized by declining shared language and reduced emotional synchrony. While a Technical Track might focus on the "how" of data transmission, the Social Track allows us to focus on the "why" of human interaction—prioritizing the quality of bonds between grandparents, parents, and children. 
  <br><br>
  By focusing on the Social Track, we aim to transform mobile devices from "solitary screens" into <b>social catalysts</b>. By making it a <b>neurological and emotional bridge</b>, we are enpowered to design an system where digital interactions translate into real-world empathy, ensuring that every generation feels seen, heard, and valued within the family unit.
</div>

---

## 1.2 The Gap: Literature & Market Analysis

### 📚 Academic Papers
<table class="gap-table">
  <tr>
    <th width="30%">Paper</th>
    <th width="35%">3 Things They Did Well</th>
    <th width="35%">3 Things They Missed</th>
  </tr>
  <tr>
    <td>
      <a href="https://dl.acm.org/doi/10.1145/3357236.3395460" target="_blank">
        "Relational Design for Remote Intergenerational Sensorial Play Experiences" (2020)
      </a>
    </td>
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
    <td>
      <a href="https://dl.acm.org/doi/10.1145/3313831.3376378" target="_blank">
        "Story-Me: Design of a System to Support Intergenerational Storytelling and Preservation for Older Adults" (2020)
      </a>
    </td>
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
    <td>
      <a href="https://www.mdpi.com/2071-1050/14/10/6067" target="_blank">
        "Construction of a Tangible VR-Based Interactive System for Intergenerational Learning" (2022)
      </a>
    </td>
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
  <tr>
    <td>
      <a href="https://www.mdpi.com/2071-1050/14/6/3213" target="_blank">
        "Empirical Study of VR to Promote Intergenerational Communication" (2021)
      </a>
    </td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Provided <b>quantitative data</b> on user satisfaction.</li>
        <li>Identified key "ice-breaking" mechanics in VR.</li>
        <li>Focused on mutual empathy between age groups.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>Excluded seniors with <b>moderate visual impairments</b>.</li>
        <li>The setup was too bulky for a typical living room.</li>
        <li>Over-relied on technical support during the study.</li>
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
    <td><b>FaceTime / Zoom</b><br><small>Video Conferencing Platforms</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Extreme <b>stability</b> across various network conditions.</li>
        <li>High market reach and universal user familiarity.</li>
        <li>Simple, frictionless UI for establishing basic calls.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>Passive interaction (limited to verbal/visual).</li>
        <li>"Video call fatigue" during extended sessions.</li>
        <li>Lack of <b>integrated shared playful activities</b>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Roblox (Social Play)</b><br><small>User-Generated Gaming Universe</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Infinite <b>creativity</b> and user-generated content.</li>
        <li>Highly playful mechanics and avatar-based expression.</li>
        <li>Instant real-time social interaction in 3D spaces.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li><b>Steep learning curve</b> for non-tech-savvy seniors.</li>
        <li>Complex 3D navigation and multi-button controls.</li>
        <li>Chaotic social environment unsuitable for quiet bonding.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>StorySign</b><br><small>AI-Powered Sign Language Tool</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Innovative use of <b>AI avatars</b> for real-time translation.</li>
        <li>Addresses a highly specific social niche (deaf literacy).</li>
        <li>High emotional impact on parent-child bonding.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>One-way information flow; lacks reciprocal play.</li>
        <li>Highly dependent on specific physical book titles.</li>
        <li>Lacks <b>intergenerational co-creation</b> features.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td><b>Osmo / AR Storybooks</b><br><small>Phygital Learning Systems</small></td>
    <td>
      <div class="list-good">Done Well:</div>
      <ul class="custom-list">
        <li>Excellent <b>tangible feedback</b> using physical objects.</li>
        <li>Encourages "heads-up" play instead of screen staring.</li>
        <li>Highly intuitive interaction for younger children.</li>
      </ul>
    </td>
    <td>
      <div class="list-miss">Missed:</div>
      <ul class="custom-list">
        <li>Primarily designed for <b>co-located</b> (in-person) play.</li>
        <li>High hardware dependency (requires base/reflector).</li>
        <li>Thematic content often feels too "childish" for seniors.</li>
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
