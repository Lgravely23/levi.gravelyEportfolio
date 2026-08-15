---
title: "Levi Gravely — Computer Science Professional"
layout: default
---
# **Levi Gravely — Computer Science Professional**
### Showcasing my skills in multiple discplines.

Welcome to my E-portfolio. Explore my projects, professional self assessment , and code review ---

## **Core Competencies**
- Software Design and Engineering  
- Algorithms and Data Structure 
- Databases 
 
---
## ** Languages i prefer **

- Python
- C++
- Terraform
- Yaml
- HTML/CSS

---

[View All Projects](projects.md)

---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Your Name - Portfolio</title>
  <style>
    /* Dark Theme Palette */
    :root {
      --bg-color: #0d1117;
      --card-bg: #161b22;
      --border-color: #30363d;
      --text-main: #c9d1d9;
      --text-muted: #8b949e;
      --accent: #58a6ff;
      --accent-hover: #1f6feb;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
      background-color: var(--bg-color);
      color: var(--text-main);
      line-height: 1.6;
      padding: 2rem 1rem;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    /* Header Section */
    header {
      margin-bottom: 3rem;
      border-bottom: 1px solid var(--border-color);
      padding-bottom: 1.5rem;
    }

    h1 {
      font-size: 2.2rem;
      color: #ffffff;
      margin-bottom: 0.5rem;
    }

    .subtitle {
      font-size: 1.1rem;
      color: var(--text-muted);
      margin-bottom: 1rem;
    }

    .social-links a {
      color: var(--accent);
      text-decoration: none;
      margin-right: 1rem;
      font-weight: 500;
    }

    .social-links a:hover {
      text-decoration: underline;
    }

    /* Sections */
    section {
      margin-bottom: 3rem;
    }

    h2 {
      font-size: 1.5rem;
      color: #ffffff;
      margin-bottom: 1.2rem;
      border-bottom: 1px solid var(--border-color);
      padding-bottom: 0.5rem;
    }

    /* Projects Grid */
    .projects-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 1.5rem;
    }

    .card {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      border-radius: 8px;
      padding: 1.5rem;
      transition: transform 0.2s ease, border-color 0.2s ease;
    }

    .card:hover {
      transform: translateY(-3px);
      border-color: var(--accent);
    }

    .card h3 {
      color: #ffffff;
      margin-bottom: 0.5rem;
    }

    .card p {
      color: var(--text-muted);
      font-size: 0.95rem;
      margin-bottom: 1rem;
    }

    .tags {
      display: flex;
      flex-wrap: wrap;
      gap: 0.5rem;
      margin-bottom: 1rem;
    }

    .tag {
      background-color: rgba(88, 166, 255, 0.1);
      color: var(--accent);
      padding: 0.2rem 0.6rem;
      border-radius: 12px;
      font-size: 0.8rem;
    }

    .card-link {
      color: var(--accent);
      text-decoration: none;
      font-size: 0.9rem;
      font-weight: 600;
    }

    /* Skills Badges */
    .skills-list {
      display: flex;
      flex-wrap: wrap;
      gap: 0.75rem;
    }

    .skill-badge {
      background-color: var(--card-bg);
      border: 1px solid var(--border-color);
      padding: 0.4rem 0.8rem;
      border-radius: 6px;
      font-size: 0.9rem;
    }

    /* Footer */
    footer {
      text-align: center;
      color: var(--text-muted);
      font-size: 0.85rem;
      margin-top: 4rem;
      padding-top: 2rem;
      border-top: 1px solid var(--border-color);
    }
  </style>
</head>
<body>

  <div class="container">
    <!-- Header -->
    <header>
      <h1>Alex Developer</h1>
      <p class="subtitle">Software Engineer & Open Source Contributor</p>
      <div class="social-links">
        <a href="https://github.com/yourusername" target="_blank">GitHub</a>
        <a href="https://linkedin.com/in/yourusername" target="_blank">LinkedIn</a>
        <a href="mailto:your.email@example.com">Email</a>
      </div>
    </header>

    <!-- About Section -->
    <section id="about">
      <h2>About Me</h2>
      <p>
        I am a software engineer focused on building fast, scalable web applications and intuitive interfaces. 
        Passionate about open-source software, clean architecture, and modern web tech.
      </p>
    </section>

    <!-- Projects Section -->
    <section id="projects">
      <h2>Projects</h2>
      <div class="projects-grid">
        
        <!-- Project 1 -->
        <div class="card">
          <h3>Project One</h3>
          <p>A full-stack application built to solve real-world scheduling problems with high real-time throughput.</p>
          <div class="tags">
            <span class="tag">TypeScript</span>
            <span class="tag">Node.js</span>
            <span class="tag">PostgreSQL</span>
          </div>
          <a href="#" class="card-link">View Repository &rarr;</a>
        </div>

        <!-- Project 2 -->
        <div class="card">
          <h3>Project Two</h3>
          <p>An open-source CLI tool designed to simplify cloud deployment configurations.</p>
          <div class="tags">
            <span class="tag">Go</span>
            <span class="tag">Docker</span>
            <span class="tag">CLI</span>
          </div>
          <a href="#" class="card-link">View Repository &rarr;</a>
        </div>

      </div>
    </section>

    <!-- Skills Section -->
    <section id="skills">
      <h2>Skills</h2>
      <div class="skills-list">
        <span class="skill-badge">JavaScript / TypeScript</span>
        <span class="skill-badge">Python</span>
        <span class="skill-badge">React</span>
        <span class="skill-badge">Node.js</span>
        <span class="skill-badge">PostgreSQL</span>
        <span class="skill-badge">Docker</span>
        <span class="skill-badge">Git</span>
      </div>
    </section>

    <!-- Footer -->
    <footer>
      <p>&copy; 2026 Alex Developer. Powered by GitHub Pages.</p>
    </footer>
  </div>

</body>
</html>


