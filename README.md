<div align="center">

<!-- ANIMATED BOOT HEADER -->
<svg width="700" height="200" viewBox="0 0 700 200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="cg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00fff0"/>
      <stop offset="50%" stop-color="#00c9b1"/>
      <stop offset="100%" stop-color="#0077ff"/>
    </linearGradient>
    <linearGradient id="cg2" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#0077ff"/>
      <stop offset="100%" stop-color="#00fff0"/>
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="softglow">
      <feGaussianBlur stdDeviation="1.5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- bg -->
  <rect width="700" height="200" rx="10" fill="#050505"/>

  <!-- animated scan line -->
  <rect x="0" y="0" width="700" height="3" fill="url(#cg)" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" repeatCount="indefinite"/>
  </rect>

  <!-- corner brackets -->
  <polyline points="12,12 12,30 30,30" fill="none" stroke="#00fff0" stroke-width="1.5" opacity="0.6"/>
  <polyline points="688,12 688,30 670,30" fill="none" stroke="#00fff0" stroke-width="1.5" opacity="0.6"/>
  <polyline points="12,188 12,170 30,170" fill="none" stroke="#00fff0" stroke-width="1.5" opacity="0.6"/>
  <polyline points="688,188 688,170 670,170" fill="none" stroke="#00fff0" stroke-width="1.5" opacity="0.6"/>

  <!-- blinking cursor top left -->
  <rect x="18" y="15" width="6" height="10" fill="#00fff0">
    <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
  </rect>

  <!-- boot text lines with fade-in -->
  <text x="350" y="38" font-family="monospace" font-size="10" fill="#1d9e75" text-anchor="middle" opacity="0">
    // chandru0x.init() — loading profile...
    <animate attributeName="opacity" values="0;1" dur="0.5s" begin="0.2s" fill="freeze"/>
  </text>

  <!-- ASCII art name -->
  <text x="350" y="72" font-family="monospace" font-size="10" fill="#00fff0" text-anchor="middle" filter="url(#softglow)" opacity="0">
    ██████╗██╗  ██╗ █████╗ ███╗  ██╗██████╗ ██████╗ ██╗   ██╗
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.6s" fill="freeze"/>
  </text>
  <text x="350" y="84" font-family="monospace" font-size="10" fill="#00fff0" text-anchor="middle" filter="url(#softglow)" opacity="0">
    ██╔════╝██║  ██║██╔══██╗████╗ ██║██╔══██╗██╔══██╗██║   ██║
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.7s" fill="freeze"/>
  </text>
  <text x="350" y="96" font-family="monospace" font-size="10" fill="#00c9b1" text-anchor="middle" filter="url(#softglow)" opacity="0">
    ██║     ███████║███████║██╔██╗██║██║  ██║██████╔╝██║   ██║
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.8s" fill="freeze"/>
  </text>
  <text x="350" y="108" font-family="monospace" font-size="10" fill="#0099cc" text-anchor="middle" filter="url(#softglow)" opacity="0">
    ██║     ██╔══██║██╔══██║██║╚████║██║  ██║██╔══██╗██║   ██║
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="0.9s" fill="freeze"/>
  </text>
  <text x="350" y="120" font-family="monospace" font-size="10" fill="#0077ff" text-anchor="middle" filter="url(#softglow)" opacity="0">
    ╚██████╗██║  ██║██║  ██║██║ ╚███║██████╔╝██║  ██║╚██████╔╝
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.0s" fill="freeze"/>
  </text>
  <text x="350" y="132" font-family="monospace" font-size="10" fill="#0055cc" text-anchor="middle" filter="url(#softglow)" opacity="0">
    ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝╚═╝  ╚══╝╚═════╝ ╚═╝  ╚═╝ ╚═════╝
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.1s" fill="freeze"/>
  </text>

  <!-- subtitle with typewriter feel -->
  <text x="350" y="155" font-family="monospace" font-size="12" fill="#555" text-anchor="middle" opacity="0">
    backend engineer  ·  ai tooling  ·  local-first systems
    <animate attributeName="opacity" values="0;1" dur="0.5s" begin="1.4s" fill="freeze"/>
  </text>

  <!-- location pill -->
  <rect x="270" y="165" width="160" height="20" rx="10" fill="#0a2a1a" opacity="0">
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.7s" fill="freeze"/>
  </rect>
  <text x="350" y="179" font-family="monospace" font-size="10" fill="#1d9e75" text-anchor="middle" opacity="0">
    ⬡  Chennai, India  ·  GMT+5:30
    <animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.7s" fill="freeze"/>
  </text>

  <!-- bottom scan line -->
  <rect x="0" y="197" width="700" height="3" fill="url(#cg2)" opacity="0.9">
    <animate attributeName="opacity" values="0.9;0.4;0.9" dur="3s" begin="0.5s" repeatCount="indefinite"/>
  </rect>
</svg>

<br/>

[![LinkedIn](https://img.shields.io/badge/◈_LinkedIn-chandru--v-0a66c2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/chandru-v)
[![Andro](https://img.shields.io/badge/◈_Project-Andro_CLI-00c9b1?style=for-the-badge&logo=github&logoColor=white)](https://github.com/chandru0x/Andro)
[![Open to Work](https://img.shields.io/badge/⚡_Available-Backend_+_AI_Infra-1d9e75?style=for-the-badge)](mailto:)

</div>

---

<!-- SECTION: WHOAMI -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ whoami</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ SYSTEM:INFO ]</text>
</svg>

```
  ┌──────────────────────────────────────────────────────────────────┐
  │  Chan · Backend Engineer · 2 yrs production systems              │
  │  Java · Spring Boot · Kafka · Redis · PostgreSQL                 │
  │                                                                  │
  │  Day job  →  PropTechRadar AI (Dubai real estate analytics)      │
  │  Side     →  Andro — local-first AI developer CLI                │
  │                                                                  │
  │  I care about systems that work correctly under real conditions.  │
  │  Not just in demos.                                              │
  └──────────────────────────────────────────────────────────────────┘
```

---

<!-- SECTION: EXPERIENCE -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="2.3s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ cat experience.log</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ WORK:HISTORY ]</text>
</svg>

```
  ╔══════════════════════════════════════════════════════════════════╗
  ║  Softtwig Technology Solutions                                   ║
  ║  Backend Software Engineer                        2023 – present ║
  ╠══════════════════════════════════════════════════════════════════╣
  ║  Product  →  PropTechRadar AI · Dubai real estate platform       ║
  ║  Stack    →  Java · Spring Boot · Kafka · Redis · PostgreSQL     ║
  ║  Domain   →  Event-driven systems · analytics pipelines          ║
  ╚══════════════════════════════════════════════════════════════════╝
```

---

<!-- SECTION: PROJECTS -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.8s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ ls -la ~/projects</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ BUILD:LOG ]</text>
</svg>

### &nbsp;⬡ &nbsp;[Andro](https://github.com/chandru0x/Andro) &nbsp;—&nbsp; local-first AI developer CLI

[![Stars](https://img.shields.io/github/stars/chandru0x/Andro?style=flat-square&color=00fff0&labelColor=0a0a0a&logo=github)](https://github.com/chandru0x/Andro/stargazers)
[![Commits](https://img.shields.io/github/commit-activity/m/chandru0x/Andro?style=flat-square&color=1d9e75&labelColor=0a0a0a&label=commits%2Fmo)](https://github.com/chandru0x/Andro/commits)
[![Java](https://img.shields.io/badge/Java-99.6%25-ED8B00?style=flat-square&logo=openjdk&logoColor=white&labelColor=0a0a0a)](https://github.com/chandru0x/Andro)
[![Status](https://img.shields.io/badge/status-active-1d9e75?style=flat-square&labelColor=0a0a0a)](https://github.com/chandru0x/Andro)

```bash
$ andro index --embed --recreate .
  ✓ 26 files · 135 chunks · 135 embedded · 11.2s    # was 311s — 96% faster after batching

$ andro search --hybrid "jwt authentication filter"
  JwtAuthenticationFilter.java   3.42   src/main/java/.../security/
  JwtService.java                2.91   src/main/java/.../service/
  SecurityConfig.java            1.83   src/main/java/.../config/

$ andro impact AnomalyKafkaListener --grouped
  → 14 symbols affected · 3 kafka consumers · 4 integration tests

$ andro plan "add idempotency to consumeAnomaly"
  ✓ repository grounded · 0 hallucinated files · plan saved
```

> *codebases are graphs, not documents*

---

<!-- SECTION: STACK -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="2.6s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ cat stack.json</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ TECH:STACK ]</text>
</svg>

<br/>

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Kafka-231F20?style=flat-square&logo=apachekafka&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Lucene](https://img.shields.io/badge/Lucene-BM25+KNN-00c9b1?style=flat-square)
![Groq](https://img.shields.io/badge/Groq-LLM-f55036?style=flat-square)
![OpenRouter](https://img.shields.io/badge/OpenRouter-Embeddings-7c3aed?style=flat-square)

---

<!-- SECTION: STATS -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="2.1s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ git log --stat --all</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ GIT:STATS ]</text>
</svg>

<div align="center">
<br/>

<img height="155" src="https://github-readme-stats.vercel.app/api?username=chandru0x&show_icons=true&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=00fff0&icon_color=00c9b1&text_color=888888&count_private=true&include_all_commits=true&ring_color=00fff0" />
&nbsp;
<img height="155" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chandru0x&layout=compact&theme=dark&hide_border=true&bg_color=0a0a0a&title_color=00fff0&text_color=888888&langs_count=6" />

<br/><br/>

<img width="520" src="https://github-readme-streak-stats.herokuapp.com?user=chandru0x&theme=dark&hide_border=true&background=0a0a0a&ring=00fff0&fire=00c9b1&currStreakLabel=00fff0&sideLabels=666666&dates=444444&stroke=1d9e75" />

<br/><br/>

<img width="700" src="https://github-readme-activity-graph.vercel.app/graph?username=chandru0x&bg_color=0a0a0a&color=00fff0&line=00c9b1&point=ffffff&area=true&area_color=00fff0&hide_border=true" />

</div>

---

<!-- SECTION: LESSONS -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="1.6s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ grep -r "lessons" ./brain --include="*.log"</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ HARD:TRUTHS ]</text>
</svg>

```diff
+ retrieval quality matters more than model size
+ hybrid search doesn't fix bad ranking — it amplifies it
+ a 4000-line file is a terrible embedding unit
+ developer tools live or die by latency, not accuracy
+ codebases are graphs — change one node, the ripple is the real problem
- AI tools earn trust by sounding confident
+ AI tools earn trust by exposing uncertainty
```

---

<!-- SECTION: INTERESTS -->
<svg width="700" height="36" viewBox="0 0 700 36" xmlns="http://www.w3.org/2000/svg">
  <rect width="700" height="36" rx="4" fill="#0d0d0d"/>
  <rect x="0" y="0" width="3" height="36" fill="#00fff0">
    <animate attributeName="opacity" values="1;0.3;1" dur="3s" repeatCount="indefinite"/>
  </rect>
  <text x="16" y="23" font-family="monospace" font-size="13" fill="#00fff0">▸ cat /etc/interests</text>
  <text x="685" y="23" font-family="monospace" font-size="9" fill="#222" text-anchor="end">[ HUMAN:DATA ]</text>
</svg>

```
  Ghost in the Shell  ·  Akira  ·  cyberpunk aesthetics
  Minecraft infra rabbit holes  ·  building in public on LinkedIn
```

---

<!-- ANIMATED FOOTER -->
<div align="center">

<svg width="600" height="52" viewBox="0 0 600 52" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="fg" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00fff0" stop-opacity="0"/>
      <stop offset="30%" stop-color="#00fff0" stop-opacity="0.8"/>
      <stop offset="70%" stop-color="#00c9b1" stop-opacity="0.8"/>
      <stop offset="100%" stop-color="#0077ff" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="600" height="52" rx="6" fill="#080808"/>
  <rect x="0" y="0" width="600" height="1" fill="url(#fg)">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2.5s" repeatCount="indefinite"/>
  </rect>
  <text x="300" y="22" font-family="monospace" font-size="11" fill="#00fff0" text-anchor="middle">
    ⚡  open to backend + AI infrastructure roles
  </text>
  <text x="300" y="40" font-family="monospace" font-size="10" fill="#1d9e75" text-anchor="middle">
    Chennai, India  ·  remote-friendly  ·  chandru0x@github
  </text>
  <rect x="0" y="51" width="600" height="1" fill="url(#fg)">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2.5s" begin="1.25s" repeatCount="indefinite"/>
  </rect>
</svg>

</div>
