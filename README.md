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

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=pranavvishwakarma&theme=tokyonight&no-bg=true&no-frame=true&column=-1" alt="trophies"/>
</p>

## Contribution Streak
<p align="center">
  <img src="https://streak-stats.demolab.com?user=pranavvishwakarma&theme=tokyonight-duo&hide_border=true&date_format=j%20M%5B%20Y%5D" alt="streak"/>
</p>

## Activity Graph
<p align="center">
  <img src="https://metrics.lecoq.io/pranavvishwakarma?template=classic&isocalendar=1&isocalendar.duration=full-year&base=header&config.timezone=Asia/Kolkata" alt="isometric contribution calendar"/>
</p>
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

## CV + One‑Click Apply
<p align="center">
  <a href="https://raw.githubusercontent.com/pranavvishwakarma/pranavvishwakarma/main/CV_Pranav_Vishwakarma.pdf" style="display:inline-block;padding:12px 18px;border-radius:14px;background:linear-gradient(135deg,#0b0f17,#131a29);box-shadow:0 0 14px #7df9ff33;margin:6px;text-decoration:none;color:#d6e7ff;">⬇️ Download CV (PDF)</a>
  <a href="https://raw.githubusercontent.com/pranavvishwakarma/pranavvishwakarma/main/CV_Pranav_Vishwakarma.pdf" target="_blank" style="display:inline-block;padding:12px 18px;border-radius:14px;background:linear-gradient(135deg,#0b0f17,#14202f);box-shadow:0 0 14px #00f5ff33;margin:6px;text-decoration:none;color:#d6e7ff;">👁️ View CV</a>
  <a href="https://mail.google.com/mail/?view=cm&fs=1&su=Application%3A%20Software%20Engineer%20%2F%20Backend%20Developer%20%2F%20Application%20Development&body=Resume%3A%20https%3A%2F%2Fraw.githubusercontent.com%2Fpranavvishwakarma%2Fpranavvishwakarma%2Fmain%2FCV_Pranav_Vishwakarma.pdf%0D%0A%0D%0ADear%20Hiring%20Team%2C%0D%0A%0D%0AI%20hope%20you%20are%20doing%20well.%20My%20name%20is%20Pranav%20Vishwakarma%2C%20and%20I%20am%20writing%20to%20express%20my%20interest%20in%20Software%20Engineer%20%2F%20Backend%20Developer%20%2F%20Application%20Development%20roles%20at%20your%20organization.%0D%0A%0D%0AKey%20Highlights%0D%0A%E2%80%A2%20Python%2C%20PHP%2C%20C%2B%2B%2C%20SQL%0D%0A%E2%80%A2%20Laravel%2C%20Node.js%2C%20React%2C%20REST%20APIs%2C%20MySQL%2C%20MongoDB%0D%0A%E2%80%A2%20TravelCRM%2C%20Live%20Streaming%2C%20Multi-currency%2C%20Automation%2C%20AI%0D%0A%0D%0AThank%20you%2C%0D%0APranav%20Vishwakarma%0D%0AEmail%3A%20pranav213234%40gmail.com%0D%0APhone%3A%20%2B91%209302204834" target="_blank" style="display:inline-block;padding:12px 18px;border-radius:14px;background:linear-gradient(135deg,#0b0f17,#1a2434);box-shadow:0 0 14px #8a2be233;margin:6px;text-decoration:none;color:#d6e7ff;">🟦 Compose in Gmail</a>
  <a href="mailto:?subject=Application%3A%20Software%20Engineer%20%2F%20Backend%20Developer%20%2F%20Application%20Development&body=Resume%3A%20https%3A%2F%2Fraw.githubusercontent.com%2Fpranavvishwakarma%2Fpranavvishwakarma%2Fmain%2FCV_Pranav_Vishwakarma.pdf%0D%0A%0D%0ADear%20Hiring%20Team%2C%0D%0A%0D%0AI%20hope%20you%20are%20doing%20well.%20My%20name%20is%20Pranav%20Vishwakarma%2C%20and%20I%20am%20writing%20to%20express%20my%20interest%20in%20Software%20Engineer%20%2F%20Backend%20Developer%20%2F%20Application%20Development%20roles%20at%20your%20organization.%0D%0A%0D%0AI%20hold%20a%20B.Tech%20in%20Computer%20Science%20and%20have%20hands-on%20experience%20in%20building%20scalable%20applications%2C%20backend%20systems%2C%20REST%20APIs%2C%20and%20AI-powered%20solutions.%20With%20professional%20experience%20at%20Oyelabs%20(Associate%20PHP%20Developer)%20and%20India%20Websoft%20(Software%20Engineer%20Intern)%2C%20I%20have%20contributed%20to%2010%2B%20real-world%20projects%2C%20including%20CRM%20systems%2C%20e-commerce%20platforms%2C%20automation%20tools%2C%20live%20streaming%20modules%2C%20and%20AI-integrated%20applications.%0D%0A%0D%0AKey%20Highlights%0D%0A%E2%80%A2%20Strong%20in%20Python%2C%20PHP%2C%20C%2B%2B%2C%20SQL%2C%20and%20object-oriented%20programming%0D%0A%E2%80%A2%20Experience%20with%20Laravel%2C%20Node.js%2C%20React%2C%20REST%20APIs%2C%20MySQL%2C%20MongoDB%0D%0A%E2%80%A2%20Built%20complete%20systems%20like%20TravelCRM%2C%20live%20streaming%20modules%2C%20multi-currency%20engines%2C%20PDF%20reports%2C%20automation%20workflows%2C%20and%20AI-based%20solutions%0D%0A%E2%80%A2%20Skilled%20in%20debugging%2C%20performance%20optimization%2C%20architecture%20design%2C%20and%20Agile%20teamwork%0D%0A%E2%80%A2%20Certified%20in%20LLM%20Development%20(DeepLearning.AI)%2C%20Google%20Cloud%20LLM%2C%20and%20AI%2FML%20%26%20Blockchain%20(BITS%20Pilani)%0D%0A%0D%0AI%20am%20confident%20that%20my%20technical%20skills%2C%20problem-solving%20ability%2C%20and%20experience%20working%20on%20production-grade%20systems%20make%20me%20a%20strong%20fit%20for%20your%20team.%20I%20would%20appreciate%20the%20opportunity%20to%20contribute%20to%20your%20organization%20and%20discuss%20how%20I%20can%20add%20value.%0D%0A%0D%0APlease%20find%20my%20resume%20attached%20for%20your%20review.%0D%0A%0D%0APortfolio%0D%0AGitHub%3A%20https%3A%2F%2Fgithub.com%2Fpranavvishwakarma%0D%0ALinkedIn%3A%20https%3A%2F%2Fwww.linkedin.com%2Fin%2Fpranavvishwakarmaa%0D%0A%0D%0AThank%20you%20for%20your%20time%20and%20consideration.%20I%20look%20forward%20to%20hearing%20from%20you.%0D%0A%0D%0AWarm%20regards%2C%0D%0APranav%20Vishwakarma%0D%0AEmail%3A%20pranav213234%40gmail.com%0D%0APhone%3A%20%2B91%209302204834" style="display:inline-block;padding:12px 18px;border-radius:14px;background:linear-gradient(135deg,#0b0f17,#1b2336);box-shadow:0 0 14px #ff00e633;margin:6px;text-decoration:none;color:#d6e7ff;">✉️ Open Email with Message</a>
</p>

<p align="center">
  <svg width="260" height="70" viewBox="0 0 260 70" xmlns="http://www.w3.org/2000/svg">
    <path d="M10 50 C 60 10, 120 90, 190 20 S 250 60, 250 50" stroke="#7df9ff" stroke-width="2" fill="none">
      <animate attributeName="stroke" values="#7df9ff;#ff00e6;#8a2be2;#7df9ff" dur="6s" repeatCount="indefinite"/>
    </path>
    <text x="130" y="38" text-anchor="middle" fill="#b0f3ff" font-family="'Great Vibes', cursive" font-size="20">— Pranav</text>
  </svg>
</p>

