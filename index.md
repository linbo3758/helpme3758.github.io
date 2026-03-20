---
layout: default
title: Home
---

<style>
/* 全局字体 & 颜色 */
body {
  color: #000;
}

/* 强制所有链接黑色 */
a {
  color: #000;
  text-decoration: none;
}

/* section */
.section {
  max-width: 900px;
  margin: 60px auto;
  padding: 0 20px;
}

/* 标题 */
h1 {
  font-size: 32px;
}

h2 {
  margin-bottom: 20px;
}

/* 卡片布局 */
.card-container {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 20px;
}

/* 卡片 */
.card {
  background: #f9fafb;
  padding: 18px;
  border-radius: 14px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.05);
  transition: 0.2s;
}

/* hover */
.card:hover {
  transform: translateY(-5px);
  border: 1px solid #A4D65E;
}

/* 标签 */
.tag {
  font-size: 12px;
  background: #eef8e6;
  padding: 3px 8px;
  border-radius: 6px;
  display: inline-block;
  margin-bottom: 8px;
}

/* 按钮 */
.button {
  display: inline-block;
  margin-top: 10px;
  padding: 6px 12px;
  border-radius: 8px;
  background: #A4D65E;
  font-size: 14px;
}
</style>

<div class="section">
  <h1>Hi! Welcome to my website!</h1>
  <p>This is a GCSE revision website.</p>
</div>

<!-- SCIENCE & MATH -->
<div class="section">
  <h2>📘 Science & Maths</h2>
  <div class="card-container">

    <div class="card">
      <div class="tag">Subject</div>
      <h3>Chemistry</h3>
      <a href="/chemistry" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">Subject</div>
      <h3>Physics</h3>
      <a href="/physics" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">Subject</div>
      <h3>Mathematics</h3>
      <a href="/maths" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">Subject</div>
      <h3>Further Mathematics</h3>
      <a href="/furthermaths" class="button">Open</a>
    </div>

  </div>
</div>

<!-- HUMANITIES -->
<div class="section">
  <h2>📖 Humanities</h2>
  <div class="card-container">

    <div class="card">
      <div class="tag">Subject</div>
      <h3>Geography</h3>
      <a href="/geography" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">Subject</div>
      <h3>History</h3>
      <a href="/history" class="button">Open</a>
    </div>

  </div>
</div>

<!-- ENGLISH -->
<div class="section">
  <h2>📝 English</h2>
  <div class="card-container">

    <div class="card">
      <div class="tag">English</div>
      <h3>Poetry Anthology</h3>
      <a href="PA/PoetryAnthology-menu.html" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">English</div>
      <h3>English Language</h3>
      <a href="/english" class="button">Open</a>
    </div>

  </div>
</div>

<!-- LANGUAGES -->
<div class="section">
  <h2>🌍 Languages</h2>
  <div class="card-container">

    <div class="card">
      <div class="tag">Language</div>
      <h3>Spanish</h3>
      <a href="/spanish" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">Language</div>
      <h3>Chinese</h3>
      <a href="/chinese" class="button">Open</a>
    </div>

    <div class="card">
      <div class="tag">Language</div>
      <h3>ESL</h3>
      <a href="/esl" class="button">Open</a>
    </div>

  </div>
</div>
