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
  }

  .intro-text {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 30px;
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
    padding: 25px 30px;
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
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 15px;
    flex-wrap: wrap;
  }

  .exercise-title {
    font-size: 1.4em;
    font-weight: 600;
    color: #2d3748;
    margin: 0;
  }

  .week-badge {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 5px 15px;
    border-radius: 20px;
    font-size: 0.85em;
    font-weight: 600;
    margin-right: 10px;
  }

  .due-date {
    background: #f7fafc;
    color: #4a5568;
    padding: 8px 15px;
    border-radius: 8px;
    font-size: 0.95em;
    display: inline-flex;
    align-items: center;
    font-weight: 500;
  }

  .due-date::before {
    content: "📅";
    margin-right: 8px;
    font-size: 1.2em;
  }

  .download-links {
    display: flex;
    gap: 15px;
    margin-top: 15px;
    flex-wrap: wrap;
  }

  .download-btn {
    flex: 1;
    min-width: 200px;
    padding: 12px 20px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: 600;
    text-align: center;
    transition: all 0.3s ease;
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    font-size: 0.95em;
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

  .additional-practice {
    background: linear-gradient(135deg, #fa709a 0%, #fee140 100%);
    border-radius: 12px;
    padding: 30px;
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
    grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
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

  @media (max-width: 768px) {
    .exercise-header {
      flex-direction: column;
      align-items: flex-start;
    }
    
    .due-date {
      margin-top: 10px;
    }

    .download-links {
      flex-direction: column;
    }

    .download-btn {
      min-width: 100%;
    }
  }
</style>

<div class="exercises-container">

<div class="intro-text">
  <h2>📚 Weekly Exercises</h2>
  <p>Download the weekly exercise sheets and their solution keys below. Make sure to attempt the problems before checking the solutions!</p>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 1</span>Sorting</h3>
    <span class="due-date">March 17, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week01_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week01_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 2</span>Complexity_Analysis_of_Algorithms</h3>
    <span class="due-date">April 7, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week02_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week02_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 2.5</span>Complexity_Analysis_of_Algorithms</h3>
    <span class="due-date">April 21, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week02_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week02_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 3</span>Complexity_Analysis_of_Algorithms & Basic_Data_Structures & Tree_Storage_and_Traversal</h3>
    <span class="due-date">April 21, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week03_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week03_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 4</span>Trees & BST & Trie & Heap</h3>
    <span class="due-date">May 5, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week04_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week04_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 5</span>Sorting_Advanced</h3>
    <span class="due-date">May 5, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week05_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week05_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 6</span>Disjoint_Sets & Binary_Search_and_KSelect</h3>
    <span class="due-date">May 12, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week06_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week06_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 7</span>Hashing</h3>
    <span class="due-date">May 19, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week07_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week07_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 8</span>Hashing & Graph_Algorithms</h3>
    <span class="due-date">May 26, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week08_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week08_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 9</span>Graph_Algorithms & Advanced_Data_Structures</h3>
    <span class="due-date">TBA, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week09_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week09_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
</div>

<div class="exercise-card">
  <div class="exercise-header">
    <h3 class="exercise-title"><span class="week-badge">Week 10</span>Balanced_BSTs</h3>
    <span class="due-date">TBA, 2026</span>
  </div>
  <div class="download-links">
    <a href="/static_files/exercises/week10_exercise.pdf" class="download-btn exercise-btn">
      📄 Exercise Sheet
    </a>
    <a href="/static_files/exercises/week10_solution.pdf" class="download-btn solution-btn">
      📋 Solution Key
    </a>
  </div>
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
  
  <div class="note-box">
    <strong>⚠️ Note:</strong> Solutions are provided for self-study. Try to solve problems independently before consulting the answer keys!
  </div>
</div>

</div>
