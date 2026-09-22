<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Harsh Lagwal — AI Developer</title>
<style>
  :root {
    --bg: #0d1117;
    --card: #161b22;
    --border: #30363d;
    --text: #c9d1d9;
    --heading: #f2f6fc;
    --pink: #f472b6;
    --purple: #8b5cf6;
    --cyan: #06b6d4;
  }
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body {
    background: var(--bg);
    color: var(--text);
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    line-height: 1.6;
    padding-bottom: 40px;
  }
  .container { max-width: 980px; margin: 0 auto; padding: 0 16px; }
  .banner img { width: 100%; display: block; border-radius: 0 0 12px 12px; }
  .center { text-align: center; }

  h2 {
    color: var(--heading);
    font-size: 1.5em;
    margin: 48px 0 20px;
    padding-bottom: 8px;
    border-bottom: 1px solid var(--border);
    display: flex;
    align-items: center;
    gap: 10px;
  }
  .badge-row { display: flex; flex-wrap: wrap; gap: 10px; justify-content: center; align-items: center; }
  a { text-decoration: none; }
  img { max-width: 100%; }

  .code-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 20px 24px;
    overflow-x: auto;
    font-family: "Fira Code", Consolas, monospace;
    font-size: 14.5px;
    line-height: 1.7;
  }
  .code-card .kw { color: #ff7b72; }
  .code-card .cls { color: #ffa657; }
  .code-card .str { color: #a5d6ff; }
  .code-card .arr { color: #79c0ff; }
  .code-card .cmt { color: #8b949e; }

  .stack-section { margin: 22px 0; }
  .stack-section h3 {
    color: var(--heading);
    font-size: 1.05em;
    margin-bottom: 10px;
    letter-spacing: .3px;
  }

  .projects-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    gap: 16px;
  }
  .project {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 22px;
    transition: transform .15s ease, border-color .15s ease;
  }
  .project:hover { transform: translateY(-3px); border-color: var(--purple); }
  .project h3 { color: var(--heading); font-size: 1.15em; margin-bottom: 4px; }
  .project .tag { color: var(--pink); font-size: .85em; font-weight: 600; margin-bottom: 10px; display: block; }
  .project p { font-size: .92em; margin-bottom: 14px; }
  .chips { display: flex; flex-wrap: wrap; gap: 6px; margin-bottom: 14px; }
  .chip {
    background: #21262d;
    border: 1px solid var(--border);
    color: var(--text);
    font-family: "Fira Code", Consolas, monospace;
    font-size: .75em;
    padding: 3px 9px;
    border-radius: 20px;
  }
  .repo-btn {
    display: inline-flex;
    align-items: center;
    gap: 7px;
    background: #21262d;
    border: 1px solid var(--border);
    color: var(--heading);
    padding: 6px 14px;
    border-radius: 6px;
    font-size: .85em;
    font-weight: 600;
  }
  .repo-btn:hover { border-color: var(--cyan); }

  .stats-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(340px, 1fr)); gap: 16px; margin-bottom: 16px; }
  .stats-grid img { width: 100%; border: 1px solid var(--border); border-radius: 10px; }

  .divider { border: none; border-top: 1px solid var(--border); margin: 44px 0; }
  .typing { margin: 8px 0 4px; }
  .typing img { width: 100%; max-width: 650px; }

  .note {
    background: #161b22;
    border: 1px solid #30363d;
    border-left: 3px solid var(--cyan);
    border-radius: 8px;
    padding: 14px 18px;
    font-size: .88em;
    color: #8b949e;
    margin-top: 40px;
  }
</style>
</head>
<body>

<div class="banner">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:06b6d4,50:8b5cf6,100:f472b6&height=180&section=header&text=HARSH%20LAGWAL&fontSize=45&fontColor=ffffff&fontAlignY=35&desc=AI%20Developer%20%E2%80%A2%20Full-Stack%20Engineer%20%E2%80%A2%20Himachal%2C%20India&descAlignY=58&descSize=16" alt="Harsh Lagwal banner">
</div>

<div class="container">

  <!-- TYPING + SOCIAL -->
  <div class="center">
    <p class="typing"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=F472B6&center=true&vCenter=true&random=false&width=650&lines=Building+AI+systems+with+real-world+impact+%F0%9F%A4%96;RAG+pipelines+%7C+LLM+apps+%7C+ML+models;Turning+ideas+into+shipped+products+%E2%9C%A8" alt="Typing animation"></p>

    <div class="badge-row" style="margin: 14px 0 6px;">
      <a href="https://www.linkedin.com/in/harshlagwal"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
      <a href="mailto:harshlagwal123@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
      <a href="https://github.com/harshlagwal"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
    </div>

    <img src="https://komarev.com/ghpvc/?username=harshlagwal&label=Profile+Views&color=f472b6&style=flat-square" alt="Profile views">
  </div>

  <hr class="divider">

  <!-- ABOUT -->
  <h2>👨‍💻 About Me</h2>
  <div class="code-card">
<span class="kw">class</span> <span class="cls">HarshLagwal</span>:<br>
&nbsp;&nbsp;&nbsp;&nbsp;location&nbsp;&nbsp;&nbsp;&nbsp;= <span class="str">"Hamirpur, Himachal Pradesh, India 🏔️"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;role&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;= <span class="str">"AI Developer"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;focus&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;= [<span class="str">"GenAI"</span>, <span class="str">"RAG Pipelines"</span>, <span class="str">"LLM Applications"</span>, <span class="str">"Full-Stack Web"</span>]<br>
&nbsp;&nbsp;&nbsp;&nbsp;stack&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;= [<span class="str">"TypeScript"</span>, <span class="str">"React"</span>, <span class="str">"FastAPI"</span>, <span class="str">"Node.js"</span>, <span class="str">"Python"</span>]<br>
&nbsp;&nbsp;&nbsp;&nbsp;building&nbsp;&nbsp;&nbsp;&nbsp;= <span class="str">"AI platforms, developer tools & products people actually use"</span><br>
&nbsp;&nbsp;&nbsp;&nbsp;fun_fact&nbsp;&nbsp;&nbsp;&nbsp;= <span class="str">"From DevTools that visualize code to AI that writes diagnostic reports"</span> <span class="cmt"># 32 public repos</span>
  </div>

  <hr class="divider">

  <!-- TECH STACK -->
  <h2>🧰 Tech Stack</h2>

  <div class="stack-section">
    <h3>Languages</h3>
    <img src="https://skillicons.dev/icons?i=ts,js,python,html,css,sql&perline=6" alt="Languages">
  </div>

  <div class="stack-section">
    <h3>AI / Machine Learning</h3>
    <img src="https://skillicons.dev/icons?i=pytorch,tensorflow&perline=6" alt="ML">
    <div class="badge-row" style="justify-content: flex-start; margin-top: 10px;">
      <img src="https://img.shields.io/badge/Generative_AI-412991?style=for-the-badge&logo=openai&logoColor=white" alt="GenAI">
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
      <img src="https://img.shields.io/badge/RAG_Pipelines-7C3AED?style=for-the-badge&logo=googlegemini&logoColor=white" alt="RAG">
      <img src="https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" alt="Scikit-learn">
    </div>
  </div>

  <div class="stack-section">
    <h3>Frontend</h3>
    <img src="https://skillicons.dev/icons?i=react,vite,tailwind,redux,threejs&perline=6" alt="Frontend">
  </div>

  <div class="stack-section">
    <h3>Backend & Databases</h3>
    <img src="https://skillicons.dev/icons?i=nodejs,express,fastapi,postgres,mongodb,mysql&perline=6" alt="Backend">
  </div>

  <div class="stack-section">
    <h3>Tools & Deploy</h3>
    <img src="https://skillicons.dev/icons?i=git,github,vscode,vercel,netlify,bash&perline=6" alt="Tools">
  </div>

  <hr class="divider">

  <!-- FEATURED PROJECTS -->
  <h2>🚀 Featured Projects</h2>

  <div class="projects-grid">

    <div class="project">
      <h3>🧭 CareerCraft AI</h3>
      <span class="tag">Data-Driven Career Intelligence Hub</span>
      <p>ML-powered career platform combining scikit-learn predictions, market intelligence and personalized roadmaps.</p>
      <div class="chips"><span class="chip">React 19</span><span class="chip">Tailwind 4</span><span class="chip">FastAPI</span><span class="chip">Scikit-learn</span></div>
      <a class="repo-btn" href="https://github.com/harshlagwal/CareerCraft-AI">🐙 View Repo</a>
    </div>

    <div class="project">
      <h3>🌍 WanderLust.ai</h3>
      <span class="tag">AI-Powered Travel Planning Platform</span>
      <p>Full-stack travel planner with intelligent itinerary generation, trip management, auth and admin analytics.</p>
      <div class="chips"><span class="chip">React</span><span class="chip">TypeScript</span><span class="chip">Node.js</span><span class="chip">MongoDB</span></div>
      <a class="repo-btn" href="https://github.com/harshlagwal/WanderLust.ai">🐙 View Repo</a>
      <a class="repo-btn" href="https://github.com/harshlagwal/Wanderlust-backend" style="margin-left:8px;">⚙ Backend</a>
    </div>

    <div class="project">
      <h3>⚡ AlgoFlow</h3>
      <span class="tag">Visual Code Understanding — VS Code Tool</span>
      <p>Turns any selected code into animated, step-by-step flowcharts right inside VS Code. Built for students & debugging.</p>
      <div class="chips"><span class="chip">TypeScript</span><span class="chip">VS Code Extension</span></div>
      <a class="repo-btn" href="https://github.com/harshlagwal/AlgoFlow-">🐙 View Repo</a>
    </div>

    <div class="project">
      <h3>🏗️ AI DDR Report Generator</h3>
      <span class="tag">RAG Document Intelligence</span>
      <p>Merges Inspection & Thermal Reports into structured Detailed Diagnostic Reports using a RAG pipeline.</p>
      <div class="chips"><span class="chip">Python</span><span class="chip">LangChain</span><span class="chip">Streamlit</span><span class="chip">Groq</span></div>
      <a class="repo-btn" href="https://github.com/harshlagwal/Ai-ddr-report-generator">🐙 View Repo</a>
    </div>

    <div class="project">
      <h3>🎓 Master AI</h3>
      <span class="tag">7-Day Live AI + Career Masterclass Platform</span>
      <p>Interactive learning platform for a live AI masterclass — sessions, resources and career guidance.</p>
      <div class="chips"><span class="chip">React 18</span><span class="chip">TypeScript</span><span class="chip">Vite</span><span class="chip">Tailwind</span></div>
      <a class="repo-btn" href="https://github.com/harshlagwal/Master-Ai">🐙 View Repo</a>
    </div>

    <div class="project">
      <h3>🎮 CodeChaska</h3>
      <span class="tag">The Gamified Coding Universe</span>
      <p>A gamified coding experience that makes learning to code addictive — challenges, progress and fun.</p>
      <div class="chips"><span class="chip">React</span><span class="chip">TypeScript</span><span class="chip">Vite</span><span class="chip">Tailwind</span></div>
      <a class="repo-btn" href="https://github.com/harshlagwal/CodeChaska">🐙 View Repo</a>
    </div>

  </div>

  <h2 style="margin-top:36px;">🔭 More Work</h2>
  <div class="badge-row">
    <a href="https://github.com/harshlagwal/DevFlow-Master"><img src="https://img.shields.io/badge/DevFlow_Master-Code_to_Flowcharts-22D3EE?style=flat-square&logo=visualstudiocode&logoColor=white" alt="DevFlow Master"></a>
    <a href="https://github.com/harshlagwal/DidiVerse"><img src="https://img.shields.io/badge/DidiVerse-3D_Raksha_Bandhan_Experience-EC4899?style=flat-square&logo=threedotjs&logoColor=white" alt="DidiVerse"></a>
    <a href="https://github.com/harshlagwal/Safalta--Apki-Chatbot"><img src="https://img.shields.io/badge/Safalta_Apki-Career_Guidance_Chatbot-8B5CF6?style=flat-square&logo=openai&logoColor=white" alt="Safalta Apki"></a>
    <a href="https://github.com/harshlagwal/Object-Detection"><img src="https://img.shields.io/badge/Object_Detection-Computer_Vision-F7931E?style=flat-square&logo=opencv&logoColor=white" alt="Object Detection"></a>
    <a href="https://github.com/harshlagwal/Health-care-chatbot-assistant"><img src="https://img.shields.io/badge/Health_Care_Chatbot-AI_Assistant-10B981?style=flat-square&logo=healthchecks&logoColor=white" alt="Health Care Chatbot"></a>
    <a href="https://github.com/harshlagwal/Bhagwat-Geeta-Ai"><img src="https://img.shields.io/badge/Bhagwat_Geeta_AI-Spiritual_Guide-A16207?style=flat-square&logo=googlebooks&logoColor=white" alt="Bhagwat Geeta AI"></a>
  </div>

  <hr class="divider">

  <!-- STATS -->
  <h2>📊 GitHub Stats</h2>
  <div class="center">
    <div class="stats-grid">
      <img src="https://github-readme-stats.vercel.app/api?username=harshlagwal&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=radical&rank_icon=github" alt="GitHub stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harshlagwal&layout=compact&langs_count=8&hide_border=true&theme=radical" alt="Top languages">
    </div>
    <img src="https://streak-stats.demolab.com?user=harshlagwal&theme=radical&hide_border=true" style="width:65%; min-width: 300px;" alt="Streak stats">
    <div style="margin-top: 16px;">
      <img src="https://github-trophies.vercel.app/?username=harshlagwal&theme=radical&no-frame=true&no-bg=true&margin-w=8&column=7" style="width:100%;" alt="Trophies">
    </div>
  </div>

  <hr class="divider">

  <!-- ACTIVITY -->
  <h2>📈 Contribution Graph</h2>
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=harshlagwal&theme=react-dark&hide_border=true&area=true" style="width:100%; border: 1px solid var(--border); border-radius: 10px;" alt="Contribution activity">

  <div class="note">
    <strong>ℹ️ Note:</strong> Yeh ek single self-contained HTML page hai — sab sections ek sath.
    Images live internet se load hoti hain (pehli baar thoda time lag sakta hai).
    GitHub profile ke liye <code>README.md</code> ko <code>github.com/harshlagwal/harshlagwal</code> repo me paste karna hai — wahan sab icons automatically render hote hain.
  </div>

</div>

<div class="center" style="margin-top: 50px;">
  <p style="font-family: 'Fira Code', Consolas, monospace; color: var(--heading); font-size: 1.05em;">💬 Open to collaborations, internships & interesting AI problems</p>
  <p style="color: var(--pink); font-weight: 600; margin: 10px 0 22px;">"Build useful things. Learn deeply. Ship consistently."</p>
  <a href="mailto:harshlagwal123@gmail.com"><img src="https://img.shields.io/badge/Let's_Connect-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Let's Connect"></a>
</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:f472b6,50:8b5cf6,100:06b6d4&height=110&section=footer" style="width:100%; display:block;" alt="footer">

</body>
</html>
