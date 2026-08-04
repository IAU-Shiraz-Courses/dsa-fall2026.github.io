---
layout: page
title: Exercises
permalink: /exercises/
---

<style>
  .exercises-container {
    max-width: 900px;
    margin: 0 auto;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    padding: 0 15px;
  }

  .intro-text {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 30px 20px;
    border-radius: 15px;
    text-align: center;
    margin-bottom: 40px;
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

  .exercise-card {
    background: white;
    border-radius: 12px;
    padding: 25px 20px;
    margin-bottom: 25px;
    box-shadow: 0 5px 15px rgba(0,0,0,0.08);
    transition: all 0.3s ease;
    border-left: 5px solid #667eea;
  }

  .exercise-card:hover {
    transform: translateY(-5px);
    box-shadow: 0 8px 25px rgba(0,0,0,0.15);
  }

  .exercise-header {
    margin-bottom: 15px;
  }

  .week-badge {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 600;
    display: inline-block;
    margin-bottom: 10px;
  }

  .exercise-title {
    font-size: 1.2em;
    font-weight: 600;
    color: #2d3748;
    margin: 10px 0;
    line-height: 1.4;
    word-wrap: break-word;
    overflow-wrap: break-word;
  }

  .due-date {
    background: #f7fafc;
    color: #4a5568;
    padding: 8px 15px;
    border-radius: 8px;
    font-size: 0.9em;
    display: inline-flex;
    align-items: center;
    font-weight: 500;
    margin-top: 10px;
  }

  .due-date::before {
    content: "📅";
    margin-right: 8px;
    font-size: 1.2em;
  }

  .download-links {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 12px;
    margin-top: 15px;
  }

  .download-btn {
    padding: 12px 15px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
    text-align: center;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    font-size: 0.9em;
    white-space: nowrap;
  }

  .exercise-btn {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    box-shadow: 0 4px 10px rgba(102, 126, 234, 0.3);
  }

  .exercise-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 15px rgba(102, 126, 234, 0.4);
    color: white;
  }

  .solution-btn {
    background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
    color: white;
    box-shadow: 0 4px 10px rgba(245, 87, 108, 0.3);
  }

  .solution-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 15px rgba(245, 87, 108, 0.4);
    color: white;
  }

  .code-btn {
    background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    color: white;
    box-shadow: 0 4px 10px rgba(79, 172, 254, 0.3);
  }

  .code-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 15px rgba(79, 172, 254, 0.4);
    color: white;
  }

  .additional-practice {
    background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
    border-radius: 12px;
    padding: 30px 20px;
    margin-top: 50px;
    color: white;
  }

  .additional-practice h2 {
    margin-top: 0;
    font-size: 1.8em;
    font-weight: 600;
  }

  .practice-links {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
    margin-top: 20px;
  }

  .practice-link {
    background: rgba(255,255,255,0.2);
    backdrop-filter: blur(10px);
    padding: 15px;
    border-radius: 10px;
    text-decoration: none;
    color: white;
    font-weight: 600;
    text-align: center;
    transition: all 0.3s ease;
    border: 2px solid rgba(255,255,255,0.3);
  }

  .practice-link:hover {
    background: rgba(255,255,255,0.3);
    transform: scale(1.05);
    color: white;
  }

  .note-box {
    background: #fffaf0;
    border-left: 4px solid #ed8936;
    padding: 20px;
    border-radius: 8px;
    margin-top: 20px;
    font-style: italic;
    color: #744210;
  }

  /* Mobile Optimization */
  @media (max-width: 768px) {
    .exercises-container {
      padding: 0 10px;
    }

    .intro-text {
      padding: 20px 15px;
    }

    .intro-text h2 {
      font-size: 1.5em;
    }

    .intro-text p {
      font-size: 1em;
    }

    .exercise-card {
      padding: 20px 15px;
    }

    .exercise-title {
      font-size: 1.05em;
      line-height: 1.5;
    }

    .week-badge {
      font-size: 0.8em;
      padding: 4px 12px;
    }

    .download-links {
      grid-template-columns: 1fr;
      gap: 10px;
    }

    .download-btn {
      width: 100%;
      font-size: 0.85em;
      padding: 12px 10px;
    }

    .additional-practice {
      padding: 20px 15px;
    }

    .additional-practice h2 {
      font-size: 1.4em;
    }

    .practice-links {
      grid-template-columns: 1fr;
    }

    .note-box {
      padding: 15px;
      font-size: 0.9em;
    }
  }

  @media (max-width: 480px) {
    .exercise-title {
      font-size: 0.95em;
    }

    .week-badge {
      font-size: 0.75em;
    }

    .download-btn {
      font-size: 0.8em;
      padding: 10px 8px;
      gap: 5px;
    }
  }
</style>

<div class="exercises-container">

<div class="intro-text">
  <h2>📚 Weekly Exercises</h2>
  <p>Download the weekly exercise sheets and their solution keys below. Make sure to attempt the problems before checking the solutions!</p>
</div>

<div class="additional-practice">
  <h2>🚀 Additional Practice</h2>
  <div class="practice-links">
    <a href="https://leetcode.com/" class="practice-link" target="_blank">
      💻 LeetCode<br><small>Online coding problems</small>
    </a>
    <a href="https://www.hackerrank.com/" class="practice-link" target="_blank">
      🎯 HackerRank<br><small>Practice exercises</small>
    </a>
    <a href="https://codeforces.com/" class="practice-link" target="_blank">
      🏆 Codeforces<br><small>Competitive programming</small>
    </a>
  </div>
  
