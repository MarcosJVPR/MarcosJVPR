<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="assets/banner-light.svg" />
  <img alt="Marcos — Frontend, 3D & Interactive" src="assets/banner-light.svg" />
</picture>

<h2 align="left">Hi. I'm Marcos. I build interactive interfaces with React, 3D worlds with Three.js and games in Unreal Engine.</h2>

<p>
Specialized in <b>interactive experiences</b> and <b>frontend performance</b>. Currently shipping two projects: a Spanish tourism data app in production and an asymmetric RTS in UE5 with faction systems. When I'm not coding, I'm exploring cybersecurity or on a film set.
</p>

<!-- Solarpunk animation -->
<svg width="100%" height="200" viewBox="0 0 400 200" xmlns="http://www.w3.org/2000/svg" style="margin: 24px 0;">
  <defs>
    <style>
      @keyframes grow {
        0% { transform: scaleY(0.8); opacity: 0.6; }
        50% { transform: scaleY(1.1); opacity: 1; }
        100% { transform: scaleY(0.9); opacity: 0.8; }
      }
      @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-8px); }
      }
      @keyframes spin {
        0% { transform: rotate(0deg); }
        100% { transform: rotate(360deg); }
      }
      .leaf { animation: grow 3s ease-in-out infinite; transform-origin: bottom; }
      .leaf1 { animation-delay: 0s; }
      .leaf2 { animation-delay: 0.6s; }
      .leaf3 { animation-delay: 1.2s; }
      .solar { animation: spin 12s linear infinite; transform-origin: center; }
      .vine { animation: float 2.5s ease-in-out infinite; }
      .vine2 { animation-delay: 0.4s; }
    </style>
  </defs>
  
  <!-- Background gradient -->
  <defs>
    <linearGradient id="skyGradient" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#e8f4f8;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f0fdf4;stop-opacity:1" />
    </linearGradient>
  </defs>
  <rect width="400" height="200" fill="url(#skyGradient)"/>
  
  <!-- Left plant -->
  <g transform="translate(60, 120)">
    <line x1="0" y1="0" x2="0" y2="-40" stroke="#7c9a3a" stroke-width="2"/>
    <ellipse cx="-8" cy="-20" rx="6" ry="12" fill="#9dc649" class="leaf leaf1" transform="rotate(-30)"/>
    <ellipse cx="8" cy="-25" rx="6" ry="12" fill="#a8d569" class="leaf leaf2" transform="rotate(30)"/>
    <ellipse cx="0" cy="-35" rx="7" ry="14" fill="#b8e986" class="leaf leaf3"/>
  </g>
  
  <!-- Center solar panel with vines -->
  <g transform="translate(200, 80)">
    <g class="solar">
      <rect x="-20" y="-20" width="40" height="40" fill="none" stroke="#f4b860" stroke-width="2" rx="4"/>
      <line x1="-15" y1="0" x2="15" y2="0" stroke="#f4b860" stroke-width="1.5"/>
      <line x1="0" y1="-15" x2="0" y2="15" stroke="#f4b860" stroke-width="1.5"/>
      <circle cx="0" cy="0" r="8" fill="#ffd700" opacity="0.3"/>
    </g>
    <!-- Vines around panel -->
    <path d="M -25 -15 Q -35 -25 -30 -35" stroke="#7c9a3a" stroke-width="2" fill="none" class="vine"/>
    <path d="M 25 -15 Q 35 -25 30 -35" stroke="#7c9a3a" stroke-width="2" fill="none" class="vine vine2"/>
    <circle cx="-30" cy="-35" r="4" fill="#9dc649"/>
    <circle cx="30" cy="-35" r="4" fill="#9dc649"/>
  </g>
  
  <!-- Right plant -->
  <g transform="translate(320, 125)">
    <line x1="0" y1="0" x2="0" y2="-50" stroke="#6d8f2e" stroke-width="2.5"/>
    <ellipse cx="-10" cy="-25" rx="7" ry="14" fill="#8fbc34" class="leaf leaf1" transform="rotate(-35)"/>
    <ellipse cx="10" cy="-30" rx="7" ry="14" fill="#9dc649" class="leaf leaf2" transform="rotate(35)"/>
    <ellipse cx="-6" cy="-40" rx="6" ry="12" fill="#a8d569" class="leaf leaf3" transform="rotate(-15)"/>
    <ellipse cx="6" cy="-43" rx="6" ry="12" fill="#b8e986" class="leaf leaf1" transform="rotate(15)"/>
  </g>
  
  <!-- Ground line -->
  <line x1="0" y1="170" x2="400" y2="170" stroke="#d4e5d4" stroke-width="1" opacity="0.5"/>
</svg>

<!-- Avatar -->
<img align="right" src="assets/avatar.png" width="140" alt="Marcos avatar" style="border-radius:50%; margin-left: 16px; margin-top: 8px;" />

---

### Building Now

**Travel to Spain** — React + Vite + Tailwind  
Production app visualizing real Spanish tourism data (Dataestur API) with serverless integration, dynamic routing and per-destination animations. Frontend polished; currently debugging Vercel deployment.  
→ [Live Demo](https://travel-to-spain.vercel.app/) | [Repository](https://github.com/MarcosJVPR/TravelToSpain)

**HadasOgros** — Unreal Engine 5 (Blueprints)  
Asymmetric 3D RTS: The Sylvan Court vs. The Iron-Crag Clans. Era progression, dynamic biomes, cosmetic minion variants per biome, LoL-style damage formula. Solo dev in Blueprints; architecture with Object Pooling and Master Material system.

**Interactive 3D Portfolio** — Three.js + React  
Interactive island with penguin. Playground for 3D experiments and visual storytelling.  
→ [Live](https://portfolio-rho-nine-97.vercel.app/)

---

### Tech Stack

**Frontend & Web**  
![React](https://img.shields.io/badge/React-00D1F7?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=threedotjs&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-38BDF8?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-000000?style=for-the-badge&logo=framer&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=reactrouter&logoColor=white)

**Backend & Data**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![SheetJS](https://img.shields.io/badge/SheetJS-4CAF50?style=for-the-badge&logoColor=white)

**Engines & Tools**  
![Unreal Engine 5](https://img.shields.io/badge/Unreal_Engine_5-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-F5792A?style=for-the-badge&logo=blender&logoColor=white)

**Deployment**  
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black)

---

### Connect

[Interactive 3D Portfolio](https://portfolio-rho-nine-97.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/marcosjvpr/) · [Email](mailto:perezmarcosjulio@gmail.com)

---

Acting · Cybersecurity (Security+ track) · Solarpunk & fairycore · Tabletop RPGs · Balcony gardening
