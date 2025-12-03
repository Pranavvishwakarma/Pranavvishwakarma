<div align="center">
  <svg width="100%" height="420" viewBox="0 0 1200 420" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="cyber" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#00f5ff"/>
        <stop offset="50%" stop-color="#8a2be2"/>
        <stop offset="100%" stop-color="#ff00e6"/>
      </linearGradient>
      <linearGradient id="faceT" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#7df9ff"/>
        <stop offset="100%" stop-color="#b0f3ff"/>
      </linearGradient>
      <linearGradient id="faceL" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#8a2be2"/>
        <stop offset="100%" stop-color="#3a1c71"/>
      </linearGradient>
      <linearGradient id="faceR" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#ff00e6"/>
        <stop offset="100%" stop-color="#4b006e"/>
      </linearGradient>
      <filter id="glow3d">
        <feGaussianBlur stdDeviation="4" result="b"/>
        <feMerge>
          <feMergeNode in="b"/><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>
    <rect x="0" y="0" width="1200" height="420" fill="#0b0f17"/>
    <g opacity="0.35">
      <line x1="0" y1="300" x2="1200" y2="300" stroke="#1a2340"/>
      <line x1="0" y1="330" x2="1200" y2="330" stroke="#1a2340"/>
      <line x1="0" y1="360" x2="1200" y2="360" stroke="#1a2340"/>
      <line x1="0" y1="390" x2="1200" y2="390" stroke="#1a2340"/>
    </g>
    <g filter="url(#glow3d)">
      <g transform="translate(280,170)">
        <polygon points="0,-42 42,-21 0,0 -42,-21" fill="url(#faceT)" />
        <polygon points="-42,-21 0,0 0,64 -42,43" fill="url(#faceL)" />
        <polygon points="42,-21 0,0 0,64 42,43" fill="url(#faceR)" />
        <animateTransform attributeName="transform" type="rotate" values="0;7;-7;0" dur="8s" repeatCount="indefinite" additive="sum"/>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-8;0,0;0,8;0,0" dur="6.5s" repeatCount="indefinite" additive="sum"/>
      </g>
      <g transform="translate(560,150)">
        <polygon points="0,-38 38,-19 0,0 -38,-19" fill="url(#faceT)" />
        <polygon points="-38,-19 0,0 0,58 -38,38" fill="url(#faceL)" />
        <polygon points="38,-19 0,0 0,58 38,38" fill="url(#faceR)" />
        <animateTransform attributeName="transform" type="rotate" values="0;-5;5;0" dur="7s" repeatCount="indefinite" additive="sum"/>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,6;0,0;-3,-3;0,0" dur="5.5s" repeatCount="indefinite" additive="sum"/>
      </g>
      <g transform="translate(840,180)">
        <polygon points="0,-34 34,-17 0,0 -34,-17" fill="url(#faceT)" />
        <polygon points="-34,-17 0,0 0,52 -34,34" fill="url(#faceL)" />
        <polygon points="34,-17 0,0 0,52 34,34" fill="url(#faceR)" />
        <animateTransform attributeName="transform" type="rotate" values="0;4;-4;0" dur="9s" repeatCount="indefinite" additive="sum"/>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,-5;0,0" dur="5s" repeatCount="indefinite" additive="sum"/>
      </g>
      <g transform="translate(1040,140)">
        <polygon points="0,-30 30,-15 0,0 -30,-15" fill="url(#faceT)" />
        <polygon points="-30,-15 0,0 0,46 -30,30" fill="url(#faceL)" />
        <polygon points="30,-15 0,0 0,46 30,30" fill="url(#faceR)" />
        <animateTransform attributeName="transform" type="rotate" values="0;3;-3;0" dur="8.5s" repeatCount="indefinite" additive="sum"/>
        <animateTransform attributeName="transform" type="translate" values="0,0;0,4;0,0" dur="5.2s" repeatCount="indefinite" additive="sum"/>
      </g>
    </g>
    <g>
      <circle cx="600" cy="220" r="120" stroke="url(#cyber)" stroke-width="2" fill="none" stroke-dasharray="12 8">
        <animate attributeName="stroke-dashoffset" values="0;300;0" dur="10s" repeatCount="indefinite"/>
      </circle>
    </g>
    <g>
      <text x="600" y="90" text-anchor="middle" fill="url(#cyber)" font-family="'Orbitron', sans-serif" font-size="44" letter-spacing="7">PRANAV VISHWAKARMA</text>
      <text x="600" y="125" text-anchor="middle" fill="#b0f3ff" font-family="'Montserrat', sans-serif" font-size="18">Software Engineer • Full Stack Developer • AI & ML Enthusiast</text>
    </g>
    <g font-family="'Montserrat', sans-serif" font-size="14" letter-spacing="2" fill="#b0f3ff">
      <text x="180" y="360" fill="#7df9ff">PYTHON</text>
      <text x="360" y="340" fill="#8a2be2">LARAVEL</text>
      <text x="540" y="360" fill="#ff00e6">NODEJS</text>
      <text x="720" y="340" fill="#7df9ff">REACT</text>
      <text x="900" y="360" fill="#8a2be2">MYSQL</text>
      <text x="1020" y="335" fill="#ff00e6">MONGODB</text>
      <text x="80" y="335" fill="#8a2be2">AWS</text>
      <animate attributeName="opacity" values="0.85;1;0.85" dur="6s" repeatCount="indefinite"/>
    </g>
    <path d="M0 310 C 240 280, 480 350, 720 300 S 960 280, 1200 330" stroke="url(#cyber)" stroke-width="2" fill="none">
      <animate attributeName="d" dur="7s" repeatCount="indefinite" values="M0 310 C 240 280, 480 350, 720 300 S 960 280, 1200 330; M0 310 C 260 300, 500 330, 740 280 S 980 300, 1200 320; M0 310 C 240 280, 480 350, 720 300 S 960 280, 1200 330"/>
    </path>
  </svg>

  <img src="https://readme-typing-svg.demolab.com?font=Orbitron&size=24&duration=2500&pause=900&color=7DF9FF&center=true&vCenter=true&width=1000&lines=3D+Neon+Grid+%E2%80%A2+Skills+in+motion;Clean+APIs+%E2%80%A2+Premium+UX" alt="typing"/>
</div>

# Software Engineer | Full Stack Developer | AI & ML Enthusiast

Confident builder crafting premium, production-grade systems with clean architectures, fast APIs, and intelligent experiences.

## About
- Shipping backend-first products with robust auth, caching, observability, and CI/CD
- Passion for AI-assisted workflows, automation, and data reliability
- Pragmatic problem-solver focused on performance, DX, and maintainability

## Tech Stack
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,php,laravel,nodejs,express,react,js,html,css,bootstrap,jquery,mysql,mongodb,aws,git,github,gitlab,postman,figma&perline=9"/>
</p>

## GitHub Pulse
<table>
  <tr>
    <td>
      <img src="https://github-readme-stats.vercel.app/api?username=pranavvishwakarma&show_icons=true&hide_border=true&theme=tokyonight&rank_icon=percent" alt="stats"/>
    </td>
    <td>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pranavvishwakarma&layout=compact&hide_border=true&theme=tokyonight" alt="top langs"/>
    </td>
  </tr>
</table>

## Contribution Streak
<p align="center">
  <img src="https://streak-stats.demolab.com?user=pranavvishwakarma&theme=tokyonight-duo&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="streak"/>
</p>

## Activity Graph
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=pranavvishwakarma&theme=tokyo-night&hide_border=true" alt="activity graph"/>
</p>

## Featured Projects
<p>
  <a href="https://github.com/pranavvishwakarma?tab=repositories&q=attendance" style="display:inline-block;padding:14px 18px;border-radius:16px;background:linear-gradient(135deg,#0b0f17,#131a29);box-shadow:0 0 16px #7df9ff33;margin:8px;text-decoration:none;color:#d6e7ff;">
    <b>Face Recognition Attendance</b><br/>Python • OpenCV • MySQL
  </a>
  <a href="https://github.com/pranavvishwakarma?tab=repositories&q=tomato" style="display:inline-block;padding:14px 18px;border-radius:16px;background:linear-gradient(135deg,#0b0f17,#1b2336);box-shadow:0 0 16px #ff00e633;margin:8px;text-decoration:none;color:#d6e7ff;">
    <b>Tomato Leaf Disease</b><br/>CNN • Model Serving
  </a>
  <a href="https://github.com/pranavvishwakarma?tab=repositories&q=crm" style="display:inline-block;padding:14px 18px;border-radius:16px;background:linear-gradient(135deg,#0b0f17,#172135);box-shadow:0 0 16px #8a2be233;margin:8px;text-decoration:none;color:#d6e7ff;">
    <b>TravelCRM</b><br/>Laravel • Multi-currency
  </a>
  <a href="https://github.com/pranavvishwakarma?tab=repositories&q=homelyhub" style="display:inline-block;padding:14px 18px;border-radius:16px;background:linear-gradient(135deg,#0b0f17,#14202f);box-shadow:0 0 16px #00f5ff33;margin:8px;text-decoration:none;color:#d6e7ff;">
    <b>HomelyHub</b><br/>MERN • Booking Platform
  </a>
</p>

## Contact
<p align="center">
  <a href="https://github.com/pranavvishwakarma"><img src="https://skillicons.dev/icons?i=github"/></a>
  <a href="https://www.linkedin.com/in/pranavvishwakarma"><img src="https://skillicons.dev/icons?i=linkedin"/></a>
  <a href="mailto:pranav213234@gmail.com"><img src="https://skillicons.dev/icons?i=gmail"/></a>
</p>

<p align="center">
  <svg width="260" height="70" viewBox="0 0 260 70" xmlns="http://www.w3.org/2000/svg">
    <path d="M10 50 C 60 10, 120 90, 190 20 S 250 60, 250 50" stroke="#7df9ff" stroke-width="2" fill="none">
      <animate attributeName="stroke" values="#7df9ff;#ff00e6;#8a2be2;#7df9ff" dur="6s" repeatCount="indefinite"/>
    </path>
    <text x="130" y="38" text-anchor="middle" fill="#b0f3ff" font-family="'Great Vibes', cursive" font-size="20">— Pranav</text>
  </svg>
</p>

