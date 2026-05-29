<p align="center">
  <svg width="100%" height="200" viewBox="0 0 800 200" xmlns="http://www.w3.org/2000/svg" style="max-width: 800px;">
    <style>
      @keyframes borderPulse {
        0%, 100% { stroke: #0044aa; stroke-opacity: 0.4; }
        50% { stroke: #0088ff; stroke-opacity: 0.8; }
      }
      @keyframes titleGlow {
        0%, 100% { filter: drop-shadow(0 0 4px #0088ff) drop-shadow(0 0 8px #0055cc); }
        50% { filter: drop-shadow(0 0 8px #0088ff) drop-shadow(0 0 16px #0055cc) drop-shadow(0 0 32px #003388); }
      }
      @keyframes scanMove {
        0% { transform: translateY(0); }
        100% { transform: translateY(6px); }
      }
      @keyframes blink {
        0%, 100% { opacity: 1; }
        50% { opacity: 0; }
      }
      @keyframes fadeSlide {
        0% { opacity: 0; transform: translateY(12px); }
        100% { opacity: 1; transform: translateY(0); }
      }
      .anim-border { animation: borderPulse 3s ease-in-out infinite; }
      .anim-title { animation: titleGlow 3s ease-in-out infinite; transform-origin: center; }
      .anim-scan { animation: scanMove 0.08s linear infinite; }
      .anim-blink { animation: blink 0.7s step-end infinite; }
      .anim-fade-1 { animation: fadeSlide 0.5s ease-out 0.3s both; }
      .anim-fade-2 { animation: fadeSlide 0.5s ease-out 0.6s both; }
      .anim-fade-3 { animation: fadeSlide 0.5s ease-out 0.9s both; }
    </style>

    <rect width="800" height="200" rx="10" fill="#0a0e1a"/>
    <rect x="2" y="2" width="796" height="196" rx="8" fill="none" stroke-width="3" class="anim-border"/>

    <g opacity="0.08">
      <line x1="0" y1="30" x2="800" y2="30" stroke="#0088ff" stroke-width="0.5"/>
      <line x1="0" y1="60" x2="800" y2="60" stroke="#0088ff" stroke-width="0.5"/>
      <line x1="0" y1="90" x2="800" y2="90" stroke="#0088ff" stroke-width="0.5"/>
      <line x1="0" y1="120" x2="800" y2="120" stroke="#0088ff" stroke-width="0.5"/>
      <line x1="0" y1="150" x2="800" y2="150" stroke="#0088ff" stroke-width="0.5"/>
      <line x1="0" y1="180" x2="800" y2="180" stroke="#0088ff" stroke-width="0.5"/>
    </g>

    <rect x="0" y="0" width="800" height="26" fill="#001a33" rx="10"/>
    <rect x="0" y="18" width="800" height="8" fill="#001a33"/>
    <circle cx="770" cy="13" r="4" fill="#ff5555"/>
    <circle cx="782" cy="13" r="4" fill="#ffaa00"/>
    <circle cx="794" cy="13" r="4" fill="#00cc44"/>

    <text x="400" y="80" text-anchor="middle" font-family="'Courier New',monospace" font-size="36" font-weight="bold" fill="#0088ff" class="anim-title">JHONATAN MELCHOR</text>
    <text x="400" y="118" text-anchor="middle" font-family="monospace" font-size="15" fill="#4a8aff" class="anim-fade-1">&gt; Full Stack Web Developer</text>
    <text x="400" y="145" text-anchor="middle" font-family="monospace" font-size="11" fill="#2a5aaa" class="anim-fade-2">PHP &bull; Laravel &bull; Vue.js &bull; React &bull; Python &bull; Docker</text>

    <text x="45" y="175" font-family="monospace" font-size="10" fill="#1a4a6a" class="anim-fade-3">C:\&gt; ./profile.exe —status=active</text>
    <rect x="340" y="168" width="7" height="2" fill="#0088ff" class="anim-blink"/>

    <g class="anim-scan" opacity="0.04">
      <rect width="800" height="1" fill="white" y="0"/><rect width="800" height="1" fill="white" y="2"/>
      <rect width="800" height="1" fill="white" y="4"/><rect width="800" height="1" fill="white" y="6"/>
      <rect width="800" height="1" fill="white" y="8"/><rect width="800" height="1" fill="white" y="10"/>
      <rect width="800" height="1" fill="white" y="12"/><rect width="800" height="1" fill="white" y="14"/>
    </g>
  </svg>
</p>
<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Press+Start+2P&size=18&duration=2000&pause=800&color=0088FF&center=true&vCenter=true&repeat=false&width=300&height=50&lines=NEW+GAME" alt="New Game" />
</p>

<p align="center">
  <svg width="100%" height="280" viewBox="0 0 800 280" xmlns="http://www.w3.org/2000/svg" style="max-width: 800px;">
    <style>
      @keyframes pulseBorder {
        0%, 100% { stroke: #004488; }
        50% { stroke: #0088ff; }
      }
      @keyframes glowHP {
        0%, 100% { filter: drop-shadow(0 0 2px #00cc66); }
        50% { filter: drop-shadow(0 0 8px #00cc66) drop-shadow(0 0 16px #009944); }
      }
      @keyframes glowMP {
        0%, 100% { filter: drop-shadow(0 0 2px #0088ff); }
        50% { filter: drop-shadow(0 0 8px #0088ff) drop-shadow(0 0 16px #0055cc); }
      }
      @keyframes glowEXP {
        0%, 100% { filter: drop-shadow(0 0 2px #ffaa00); }
        50% { filter: drop-shadow(0 0 8px #ffaa00) drop-shadow(0 0 16px #cc8800); }
      }
      @keyframes scanMove {
        0% { transform: translateY(0); }
        100% { transform: translateY(6px); }
      }
      @keyframes fadeInUp {
        0% { opacity: 0; transform: translateY(10px); }
        100% { opacity: 1; transform: translateY(0); }
      }
      .stat-border { animation: pulseBorder 3s ease-in-out infinite; }
      .stat-hp { animation: glowHP 2s ease-in-out infinite; }
      .stat-mp { animation: glowMP 2s ease-in-out infinite; }
      .stat-exp { animation: glowEXP 2s ease-in-out infinite; }
      .stat-scan { animation: scanMove 0.08s linear infinite; }
      .stat-row-1 { animation: fadeInUp 0.4s ease-out 0.2s both; }
      .stat-row-2 { animation: fadeInUp 0.4s ease-out 0.4s both; }
      .stat-row-3 { animation: fadeInUp 0.4s ease-out 0.6s both; }
      .stat-row-4 { animation: fadeInUp 0.4s ease-out 0.8s both; }
      .stat-row-5 { animation: fadeInUp 0.4s ease-out 1.0s both; }
      .stat-row-6 { animation: fadeInUp 0.4s ease-out 1.2s both; }
      .stat-row-7 { animation: fadeInUp 0.4s ease-out 1.4s both; }
      .bar-track { fill: #0d1a2d; }
    </style>

    <defs>
      <linearGradient id="hpGrad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#009944"/>
        <stop offset="100%" stop-color="#00dd66"/>
      </linearGradient>
      <linearGradient id="mpGrad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#0044cc"/>
        <stop offset="100%" stop-color="#0088ff"/>
      </linearGradient>
      <linearGradient id="expGrad" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#cc8800"/>
        <stop offset="100%" stop-color="#ffcc00"/>
      </linearGradient>
      <filter id="glow">
        <feGaussianBlur stdDeviation="2" result="blur"/>
        <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
      </filter>
    </defs>

    <rect width="800" height="280" rx="8" fill="#0a0e1a"/>
    <rect x="2" y="2" width="796" height="276" rx="6" fill="none" stroke-width="2" class="stat-border"/>

    <rect x="0" y="0" width="800" height="30" fill="#001a33" rx="8"/>
    <rect x="0" y="22" width="800" height="8" fill="#001a33"/>
    <text x="20" y="20" font-family="monospace" font-size="11" fill="#4a6a9a">PLAYER STATS — HUD v2.4</text>

    <g class="stat-row-1">
      <text x="30" y="65" font-family="monospace" font-size="12" fill="#4a8aff">NAME</text>
      <text x="180" y="65" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Jhonatan Melchor Chimal</text>
    </g>

    <g class="stat-row-2">
      <text x="30" y="90" font-family="monospace" font-size="12" fill="#4a8aff">CLASS</text>
      <text x="180" y="90" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Full Stack Web Developer</text>
      <text x="460" y="90" font-family="monospace" font-size="12" fill="#4a8aff">RANK</text>
      <text x="530" y="90" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Junior</text>
    </g>

    <g class="stat-row-3">
      <text x="30" y="115" font-family="monospace" font-size="12" fill="#4a8aff">SECTOR</text>
      <text x="180" y="115" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Cosautlan de Carvajal, Veracruz, MX</text>
    </g>

    <g class="stat-row-4">
      <text x="30" y="145" font-family="monospace" font-size="12" fill="#4a8aff">GUILD</text>
      <text x="180" y="145" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Welldex Logistic</text>
      <text x="460" y="145" font-family="monospace" font-size="12" fill="#4a8aff">QUESTS</text>
      <text x="530" y="145" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Aug 2025 — Jan 2026</text>
    </g>

    <g class="stat-row-5">
      <text x="30" y="170" font-family="monospace" font-size="12" fill="#4a8aff">ACADEMY</text>
      <text x="180" y="170" font-family="monospace" font-size="12" font-weight="bold" fill="#c9d1d9">Univ. Interserrana del Estado de Puebla</text>
      <text x="640" y="170" font-family="monospace" font-size="12" fill="#4a8aff">2022-2025</text>
    </g>

    <g class="stat-row-6">
      <text x="30" y="202" font-family="monospace" font-size="12" fill="#4a8aff">HP</text>
      <rect x="180" y="188" width="360" height="16" rx="3" class="bar-track"/>
      <rect x="180" y="188" height="16" rx="3" fill="url(#hpGrad)" filter="url(#glow)" class="stat-hp">
        <animate attributeName="width" from="0" to="300" dur="1.5s" begin="0.5s" fill="freeze"/>
      </rect>
      <text x="555" y="200" font-family="monospace" font-size="11" fill="#00dd66" class="stat-hp">96/100</text>
    </g>

    <g class="stat-row-7">
      <text x="30" y="232" font-family="monospace" font-size="12" fill="#4a8aff">MP</text>
      <rect x="180" y="218" width="360" height="16" rx="3" class="bar-track"/>
      <rect x="180" y="218" height="16" rx="3" fill="url(#mpGrad)" filter="url(#glow)" class="stat-mp">
        <animate attributeName="width" from="0" to="225" dur="1.5s" begin="0.8s" fill="freeze"/>
      </rect>
      <text x="555" y="230" font-family="monospace" font-size="11" fill="#0088ff" class="stat-mp">72/100</text>
    </g>

    <g class="stat-row-7">
      <text x="30" y="262" font-family="monospace" font-size="12" fill="#4a8aff">EXP</text>
      <rect x="180" y="248" width="360" height="16" rx="3" class="bar-track"/>
      <rect x="180" y="248" height="16" rx="3" fill="url(#expGrad)" filter="url(#glow)" class="stat-exp">
        <animate attributeName="width" from="0" to="285" dur="1.5s" begin="1.1s" fill="freeze"/>
      </rect>
      <text x="555" y="260" font-family="monospace" font-size="11" fill="#ffcc00" class="stat-exp">95/100</text>
    </g>

    <g class="stat-scan" opacity="0.03">
      <rect width="800" height="1" fill="white" y="0"/><rect width="800" height="1" fill="white" y="2"/>
      <rect width="800" height="1" fill="white" y="4"/><rect width="800" height="1" fill="white" y="6"/>
      <rect width="800" height="1" fill="white" y="8"/><rect width="800" height="1" fill="white" y="10"/>
    </g>
  </svg>
</p>

### ⚔️ Equipment

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&amp;logo=php&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&amp;logo=javascript&amp;logoColor=black" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&amp;logo=python&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&amp;logo=mysql&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&amp;logo=html5&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&amp;logo=css3&amp;logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&amp;logo=laravel&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&amp;logo=vue.js&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&amp;logo=react&amp;logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&amp;logo=fastapi&amp;logoColor=white" />
  <br />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&amp;logo=git&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&amp;logo=docker&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&amp;logo=firebase&amp;logoColor=black" />
  <img src="https://img.shields.io/badge/BigQuery-4285F4?style=for-the-badge&amp;logo=google-cloud&amp;logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&amp;logo=postman&amp;logoColor=white" />
</p>

### 🏆 Achievements

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=jhona-dev&amp;theme=onedark&amp;no-frame=true&amp;no-bg=true&amp;margin-w=8&amp;row=1&amp;column=6" />
</p>

### 📊 Quest Log

<p align="center">
  <img height="160em" src="https://github-readme-stats.vercel.app/api?username=jhona-dev&amp;show_icons=true&amp;theme=transparent&amp;hide_border=true&amp;title_color=0088ff&amp;text_color=c9d1d9&amp;icon_color=0088ff&amp;bg_color=0a0e1a&amp;include_all_commits=true" />
  <img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=jhona-dev&amp;layout=compact&amp;theme=transparent&amp;hide_border=true&amp;title_color=0088ff&amp;text_color=c9d1d9&amp;bg_color=0a0e1a" />
  <br />
  <img src="https://streak-stats.demolab.com?user=jhona-dev&amp;theme=transparent&amp;hide_border=true&amp;ring=0088ff&amp;fire=0088ff&amp;currStreakLabel=0088ff" />
</p>

### 💬 Quest Available

<p align="center">
  <i>Interested in teaming up? Send a message!</i>
  <br /><br />
  <a href="https://www.linkedin.com/in/jhona-dev"><img src="https://img.shields.io/badge/LinkedIn-0a66c2?style=for-the-badge&amp;logo=linkedin&amp;logoColor=white" /></a>
  <a href="mailto:jhonatanchimal164@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&amp;logo=gmail&amp;logoColor=white" /></a>
  <a href="https://github.com/jhona-dev"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" /></a>
</p>

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=jhona-dev&amp;color=0088ff&amp;style=flat-square&amp;label=VISITORS" />
  <img src="https://img.shields.io/github/followers/jhona-dev?label=Followers&amp;style=social" />
</p>

<p align="center">
  <sub>⚡ Currently looking for junior developer opportunities ⚡</sub>
</p>
