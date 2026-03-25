---
layout: default
title: Phase 2 - User Requirements
---

<style>
  /* 全局风格统一 */
  .main-content h2 { border-bottom: 2px solid #159957; padding-bottom: 8px; color: #159957; margin-top: 40px; }
  
  /* --- 2.1 User Journey Map: 点击放大功能 --- */
  .map-wrapper { position: relative; cursor: zoom-in; margin: 20px 0; border: 1px solid #eaecef; border-radius: 8px; overflow: hidden; }
  .map-wrapper img { width: 100%; display: block; transition: opacity 0.3s; }
  .map-wrapper:hover img { opacity: 0.9; }
  
  /* CSS-Only Modal (点击放大逻辑) */
  #map-toggle { display: none; }
  .map-overlay {
    position: fixed; top: 0; left: 0; width: 100%; height: 100%;
    background: rgba(0,0,0,0.9); display: none; z-index: 1000;
    justify-content: center; align-items: center; cursor: zoom-out;
  }
  #map-toggle:checked ~ .map-overlay { display: flex; }
  .map-overlay img { max-width: 95%; max-height: 95%; border-radius: 4px; box-shadow: 0 0 20px rgba(0,0,0,0.5); }

  /* --- 2.2 Requirements List: 交互式卡片 --- */
  .req-container { display: flex; flex-direction: column; gap: 15px; margin: 20px 0; }
  .req-card {
    padding: 20px; border-left: 5px solid #e1e4e8; background: #fff;
    box-shadow: 0 2px 5px rgba(0,0,0,0.05); border-radius: 0 8px 8px 0;
    transition: all 0.3s ease;
  }
  .req-card:hover { 
    border-left-color: #159957; background: #fdfdfd; 
    transform: translateX(8px); box-shadow: 0 5px 15px rgba(0,0,0,0.1); 
  }
  .req-card h3 { margin: 0 0 10px 0; font-size: 1.2em; color: #333; }
  .req-card p { margin: 0; font-size: 0.95em; color: #666; }
  .must-have-tag { 
    font-size: 0.7em; background: #159957; color: white; 
    padding: 2px 8px; border-radius: 10px; margin-right: 8px; vertical-align: middle;
  }

  /* --- 2.3 Evidence of Life: 2-2-1 栅格布局 --- */
  .photo-grid {
    display: grid; grid-template-columns: repeat(2, 1fr); gap: 15px; margin: 20px 0;
  }
  .photo-item { 
    position: relative; overflow: hidden; border-radius: 8px; height: 200px; 
    border: 1px solid #eaecef; background: #eee; transition: all 0.3s ease;
  }
  .photo-item img { width: 100%; height: 100%; object-fit: cover; transition: transform 0.5s; }
  .photo-item:hover img { transform: scale(1.1); }
  .photo-item:hover { box-shadow: 0 5px 15px rgba(0,0,0,0.2); }
  
  /* 最后一张占据整行 */
  .photo-item.large { grid-column: span 2; height: 300px; }
  
  .photo-caption {
    position: absolute; bottom: 0; width: 100%; background: rgba(21, 153, 87, 0.85);
    color: white; font-size: 0.8em; padding: 8px; transform: translateY(100%); transition: transform 0.3s;
  }
  .photo-item:hover .photo-caption { transform: translateY(0); }
</style>

[← Back to Roadmap](/)

# 📂 Module 2: User Requirements

## 2.1 User Journey Map
*Current pain points of seniors and children.*

<label for="map-toggle" class="map-wrapper">
  <img src="../images/User Journey Map.png" alt="User Journey Map" title="Click to enlarge">
  <div style="text-align:center; font-size: 0.8em; color: #999; padding: 10px;">🔍 Click map to enlarge</div>

<input type="checkbox" id="map-toggle">
<label for="map-toggle" class="map-overlay">
  <img src="../images/User Journey Map.png" alt="User Journey Map Enlarged">
</label>

---

## 2.2 Playful Requirements: 3 Must-Haves
*To bridge the generation gap, the system must fulfill these core playful criteria:*

<div class="req-container">
  <div class="req-card">
    <h3><span class="must-have-tag">Must-Have 1</span>Asynchronous Mini-Games</h3>
    <p>Provides low-pressure games like <b>"Idiom Solitaire"</b> or <b>"Memory Flips"</b> with integrated voice messaging, allowing generations to interact across different time zones without schedule conflicts.</p>
  </div>

  <div class="req-card">
    <h3><span class="must-have-tag">Must-Have 2</span>Collaborative Memory Puzzles</h3>
    <p>Turns old family photos into <b>interactive puzzles</b>. Solving them together unlocks "Memory Stories," turning static heritage into a playful, shared achievement for both grandparents and kids.</p>
  </div>

  <div class="req-card">
    <h3><span class="must-have-tag">Must-Have 3</span>The Digital Family Garden</h3>
    <p>A virtual ecosystem driven by <b>real-time sensor data</b> (steps/study time). It uses visual metaphors like a growing tree to symbolize family health and connection, triggering rewards when members are physically close.</p>
  </div>
</div>

---

## 2.3 Evidence of Life: Field Research
*Visual evidence from our site observation at the Suzhou Grand Canal and user interviews.*

<div class="photo-grid">
  <div class="photo-item">
    <img src="../images/evidence1.jpg" alt="Field Study 1">
    <div class="photo-caption">Observing grandparent-grandchild interactions at the Grand Canal.</div>
  </div>
  <div class="photo-item">
    <img src="../images/evidence2.jpg" alt="Field Study 2">
    <div class="photo-caption">User interview with a local senior citizen in Suzhou.</div>
  </div>

  <div class="photo-item">
    <img src="../images/evidence3.jpg" alt="Field Study 3">
    <div class="photo-caption">Testing camera-based gesture recognition in an outdoor setting.</div>
  </div>
  <div class="photo-item">
    <img src="../images/evidence4.jpg" alt="Field Study 4">
    <div class="photo-caption">Primary stakeholder (Child) testing the initial game concept.</div>
  </div>

  <div class="photo-item large">
    <img src="../images/evidence5.jpg" alt="Field Study 5">
    <div class="photo-caption">Group brainstorming session refining the User Journey Map.</div>
  </div>
</div>

<br>

[← Back to Roadmap](/)
