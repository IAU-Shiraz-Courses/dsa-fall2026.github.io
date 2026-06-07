---
layout: page
title: Lectures
permalink: /lectures/
---

<style>
  .lectures-container {
    max-width: 900px;
    margin: 0 auto;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding: 0 15px;
  }

  .intro-text {
    background: linear-gradient(135deg, #3b82f6 0%, #1d4ed8 100%);
    color: white;
    padding: 30px 20px;
    border-radius: 15px;
    text-align: center;
    margin-bottom: 30px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.1);
  }

  .intro-text h2 {
    margin-top: 0;
    font-size: 2em;
    font-weight: 600;
  }

  .intro-text p {
    font-size: 1.1em;
    margin-bottom: 0;
    opacity: 0.95;
  }

  .missing-alert {
    background: #fffbeb;
    border-left: 5px solid #f59e0b;
    padding: 20px 25px;
    border-radius: 10px;
    margin-bottom: 40px;
    color: #92400e;
    box-shadow: 0 4px 15px rgba(245, 158, 11, 0.1);
    display: flex;
    align-items: center;
    gap: 15px;
  }

  .missing-alert i {
    font-size: 1.5em;
  }

  .missing-alert p {
    margin: 0;
    font-size: 1.05em;
    line-height: 1.5;
  }

  .lecture-card {
    background: white;
    border-radius: 12px;
    padding: 25px 20px;
    margin-bottom: 25px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.06);
    transition: all 0.3s ease;
    border-left: 5px solid #3b82f6;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .lecture-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.12);
  }

  .lecture-info {
    flex: 1;
  }

  .chapter-badge {
    background: #eff6ff;
    color: #1d4ed8;
    padding: 6px 16px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 700;
    display: inline-block;
    margin-bottom: 10px;
    border: 1px solid #bfdbfe;
  }

  .lecture-title {
    font-size: 1.3em;
    font-weight: 600;
    color: #1e293b;
    margin: 5px 0 0 0;
  }

  .lecture-actions {
    margin-left: 20px;
  }

  .watch-btn {
    background: linear-gradient(135deg, #ef4444 0%, #b91c1c 100%);
    color: white;
    padding: 12px 25px;
    border-radius: 30px;
    text-decoration: none;
    font-weight: 600;
    display: flex;
    align-items: center;
    gap: 8px;
    transition: all 0.3s ease;
    box-shadow: 0 4px 15px rgba(239, 68, 68, 0.3);
    white-space: nowrap;
  }

  .watch-btn:hover {
    transform: scale(1.05);
    box-shadow: 0 6px 20px rgba(239, 68, 68, 0.4);
    color: white;
  }

  /* Mobile Optimization */
  @media (max-width: 768px) {
    .lecture-card {
      flex-direction: column;
      align-items: flex-start;
      padding: 20px 15px;
    }

    .lecture-actions {
      margin-left: 0;
      margin-top: 20px;
      width: 100%;
    }

    .watch-btn {
      width: 100%;
      justify-content: center;
    }

    .lecture-title {
      font-size: 1.15em;
    }

    .missing-alert {
      flex-direction: column;
      text-align: center;
      padding: 15px;
    }
  }
</style>

<div class="lectures-container">

<div class="intro-text">
  <h2>🎥 Course Lectures</h2>
  <p>Watch the recorded lecture sessions below to review the class materials and deepen your understanding.</p>
</div>

<div class="missing-alert">
  <i>⚠️</i>
  <p><strong>Note:</strong> Unfortunately, video recordings for the initial sessions (Chapters 1, 2, and 3) are not available. The video archive starts from Chapter 4.</p>
</div>

<!-- Chapter 4 -->
<div class="lecture-card">
  <div class="lecture-info">
    <span class="chapter-badge">Chapter 4</span>
    <h3 class="lecture-title">Basic_Data_Structures</h3>
  </div>
  <div class="lecture-actions">
    <a href="https://www.aparat.com/v/jnqh9a9?playlist=25298190" class="watch-btn" target="_blank">
      ▶️ Watch Video
    </a>
  </div>
</div>

<!-- Chapter 5 -->
<div class="lecture-card">
  <div class="lecture-info">
    <span class="chapter-badge">Chapter 5</span>
    <h3 class="lecture-title">Trees</h3>
  </div>
  <div class="lecture-actions">
    <a href="https://www.aparat.com/v/dgen834?playlist=25298190" class="watch-btn" target="_blank">
      ▶️ Watch Video
    </a>
  </div>
</div>

<!-- Chapters 6, 7 & 8 -->
<div class="lecture-card">
  <div class="lecture-info">
    <span class="chapter-badge">Chapters 6, 7 & 8</span>
    <h3 class="lecture-title">Sorting_Advanced ,Disjoint Sets, Binary_Search_and_KSelect</h3>
  </div>
  <div class="lecture-actions">
    <a href="https://www.aparat.com/v/hgan76v?playlist=25298190" class="watch-btn" target="_blank">
      ▶️ Watch Video
    </a>
  </div>
</div>

<!-- Chapter 9 -->
<div class="lecture-card">
  <div class="lecture-info">
    <span class="chapter-badge">Chapter 9</span>
    <h3 class="lecture-title">Hashing</h3>
  </div>
  <div class="lecture-actions">
    <a href="https://www.aparat.com/v/mkpc63n?playlist=25298190" class="watch-btn" target="_blank">
      ▶️ Watch Video
    </a>
  </div>
</div>

<!-- Chapter 10 -->
<div class="lecture-card">
  <div class="lecture-info">
    <span class="chapter-badge">Chapter 10</span>
    <h3 class="lecture-title">Graph_Algorithms</h3>
  </div>
  <div class="lecture-actions">
    <a href="https://www.aparat.com/v/qoh88pi?playlist=25298190" class="watch-btn" target="_blank">
      ▶️ Watch Video
    </a>
  </div>
</div>

<!-- Chapters 11 & 12 -->
<div class="lecture-card">
  <div class="lecture-info">
    <span class="chapter-badge">Chapters 11 & 12</span>
    <h3 class="lecture-title">Advanced_Data_Structures , Balanced BSTs </h3>
  </div>
  <div class="lecture-actions">
    <a href="https://www.aparat.com/v/krb1kh4?playlist=25298190" class="watch-btn" target="_blank">
      ▶️ Watch Video
    </a>
  </div>
</div>

</div>
