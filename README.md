<!--
  ============================================================
  EMMY PENCIL | GitHub Profile
  Digital Headquarters of a Robotics Founder
  Design Language: Apple × SpaceX × Anduril × Neuralink
  ============================================================
-->

<!-- ============================================================ -->
<!-- CINEMATIC SVG HERO – All animations inline                    -->
<!-- ============================================================ -->
<p align="center">
  <svg width="100%" height="400" viewBox="0 0 1200 400" xmlns="http://www.w3.org/2000/svg" style="max-width:1200px;">
    <defs>
      <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#000000;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#0A1128;stop-opacity:1" />
      </linearGradient>
      <linearGradient id="gridGrad" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#00B4D8;stop-opacity:0.1" />
        <stop offset="100%" style="stop-color:#00B4D8;stop-opacity:0.3" />
      </linearGradient>
      <radialGradient id="pulseGrad" cx="50%" cy="50%" r="50%">
        <stop offset="0%" style="stop-color:#00B4D8;stop-opacity:0.5" />
        <stop offset="100%" style="stop-color:#00B4D8;stop-opacity:0" />
      </radialGradient>
      <linearGradient id="trailGrad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00B4D8;stop-opacity:0" />
        <stop offset="50%" style="stop-color:#00B4D8;stop-opacity:0.8" />
        <stop offset="100%" style="stop-color:#00FF88;stop-opacity:1" />
      </linearGradient>
      <radialGradient id="jetGlow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" style="stop-color:#FFFFFF;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#00B4D8;stop-opacity:0.5" />
        <stop offset="100%" style="stop-color:#00B4D8;stop-opacity:0" />
      </radialGradient>
    </defs>

    <!-- Background -->
    <rect width="1200" height="400" fill="url(#bgGrad)" />

    <!-- Animated Grid -->
    <g opacity="0.15">
      <line x1="0" y1="80" x2="1200" y2="80" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="0" y1="160" x2="1200" y2="160" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="0" y1="240" x2="1200" y2="240" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="0" y1="320" x2="1200" y2="320" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="200" y1="0" x2="200" y2="400" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="400" y1="0" x2="400" y2="400" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="600" y1="0" x2="600" y2="400" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="800" y1="0" x2="800" y2="400" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="1000" y1="0" x2="1000" y2="400" stroke="#00B4D8" stroke-width="0.5" />
      <animate attributeName="opacity" values="0.1;0.2;0.1" dur="4s" repeatCount="indefinite" />
    </g>

    <!-- Radar Sweep -->
    <circle cx="150" cy="200" r="80" fill="none" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <circle cx="150" cy="200" r="60" fill="none" stroke="#00B4D8" stroke-width="1" opacity="0.2" />
    <circle cx="150" cy="200" r="40" fill="none" stroke="#00B4D8" stroke-width="1" opacity="0.1" />
    <line x1="150" y1="200" x2="230" y2="120" stroke="#00FF88" stroke-width="2" opacity="0.6">
      <animateTransform attributeName="transform" type="rotate" from="0 150 200" to="360 150 200" dur="4s" repeatCount="indefinite" />
    </line>

    <!-- Neural Network -->
    <g opacity="0.3">
      <circle cx="950" cy="120" r="4" fill="#00B4D8" />
      <circle cx="1000" cy="150" r="4" fill="#00B4D8" />
      <circle cx="900" cy="170" r="4" fill="#00B4D8" />
      <circle cx="970" cy="200" r="4" fill="#00B4D8" />
      <circle cx="930" cy="230" r="4" fill="#00B4D8" />
      <circle cx="1010" cy="260" r="4" fill="#00B4D8" />
      <line x1="950" y1="120" x2="1000" y2="150" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="950" y1="120" x2="900" y2="170" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="1000" y1="150" x2="970" y2="200" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="900" y1="170" x2="930" y2="230" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="970" y1="200" x2="1010" y2="260" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="930" y1="230" x2="1010" y2="260" stroke="#00B4D8" stroke-width="0.5" />
    </g>

    <!-- Flying Drones -->
    <g>
      <text x="750" y="100" font-size="24" fill="#00B4D8" opacity="0.8">✦</text>
      <animateTransform attributeName="transform" type="translate" values="0,0;40,-30;80,0;40,30;0,0" dur="8s" repeatCount="indefinite" />
    </g>
    <g>
      <text x="800" y="130" font-size="18" fill="#00B4D8" opacity="0.6">✦</text>
      <animateTransform attributeName="transform" type="translate" values="0,0;-30,20;-60,0;-30,-20;0,0" dur="10s" repeatCount="indefinite" />
    </g>

    <!-- Satellite Orbit -->
    <g>
      <ellipse cx="1100" cy="300" rx="80" ry="25" fill="none" stroke="#00B4D8" stroke-width="1" opacity="0.2" />
      <circle cx="1100" cy="300" r="4" fill="#00FF88">
        <animateMotion dur="12s" repeatCount="indefinite" path="M1100,275 A80,25 0 1,1 1100,325 A80,25 0 1,1 1100,275" />
      </circle>
    </g>

    <!-- AI Pulse -->
    <circle cx="600" cy="200" r="150" fill="url(#pulseGrad)" opacity="0.08">
      <animate attributeName="r" values="120;250;120" dur="5s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.12;0.03;0.12" dur="5s" repeatCount="indefinite" />
    </circle>

    <!-- Fighter Jet Trail -->
    <path d="M 50 300 Q 200 280, 400 320 T 700 290 T 1000 310 T 1150 300" fill="none" stroke="url(#trailGrad)" stroke-width="6" opacity="0.5">
      <animate attributeName="stroke-dashoffset" from="0" to="2000" dur="6s" repeatCount="indefinite" />
    </path>
    <path d="M 50 300 Q 200 280, 400 320 T 700 290 T 1000 310 T 1150 300" fill="none" stroke="#00B4D8" stroke-width="18" opacity="0.1">
      <animate attributeName="stroke-dashoffset" from="0" to="2000" dur="6s" repeatCount="indefinite" />
    </path>

    <!-- Fighter Jet -->
    <g>
      <animateMotion dur="6s" repeatCount="indefinite" path="M 50 300 Q 200 280, 400 320 T 700 290 T 1000 310 T 1150 300" />
      <circle cx="0" cy="0" r="12" fill="url(#jetGlow)" />
      <polygon points="0,-6 20,0 0,6" fill="#90E0EF" />
      <polygon points="-4,-10 -12,-6 -4,-3" fill="#00B4D8" />
      <polygon points="-4,10 -12,6 -4,3" fill="#00B4D8" />
      <polygon points="-6,-3 -15,0 -6,3" fill="#00FF88" opacity="0.8">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="0.3s" repeatCount="indefinite" />
      </polygon>
    </g>

    <!-- Hero Title -->
    <text x="600" y="190" font-family="'Orbitron',sans-serif" font-size="64" fill="#FFFFFF" text-anchor="middle" stroke="#00B4D8" stroke-width="1" letter-spacing="4" font-weight="700">
      EMMY PENCIL
      <animate attributeName="opacity" values="0;1;1;0" dur="10s" repeatCount="indefinite" />
    </text>
    <text x="600" y="240" font-family="'Nevada',sans-serif" font-size="20" fill="#90E0EF" text-anchor="middle" letter-spacing="6">
      BUILDING THE FUTURE
      <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite" />
    </text>

    <!-- Scan Line -->
    <rect x="0" y="0" width="1200" height="2" fill="#00B4D8" opacity="0.2">
      <animate attributeName="y" values="0;400;0" dur="8s" repeatCount="indefinite" />
    </rect>

    <!-- Status -->
    <text x="600" y="370" font-family="'Nevada',sans-serif" font-size="12" fill="#00B4D8" text-anchor="middle" opacity="0.5">
      <animate attributeName="opacity" values="0.2;0.6;0.2" dur="2s" repeatCount="indefinite" />
      ▼ SYSTEM ONLINE — SECURITY CLEARANCE: LEVEL OMEGA ▼
    </text>
  </svg>
</p>

<!-- ============================================================ -->
<!-- TYPING HEADER                                                -->
<!-- ============================================================ -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&weight=700&size=28&duration=3000&pause=1000&color=00B4D8&center=true&vCenter=true&width=800&height=60&lines=Robotics+Engineer+%E2%80%A2+AI+Researcher;Rocket+Scientist+%E2%80%A2+Founder+%26+CEO;Building+Autonomous+Intelligence;For+Earth+and+Beyond" alt="Typing Animation" />
</p>

<!-- ============================================================ -->
<!-- BADGES                                                       -->
<!-- ============================================================ -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=EmmyPencilAI&label=SECURITY+CLEARANCE&color=00B4D8&style=flat-square" />
  &nbsp;&nbsp;
  <img src="https://img.shields.io/github/followers/EmmyPencilAI?label=ASSETS&style=flat-square&color=00B4D8" />
  &nbsp;&nbsp;
  <img src="https://img.shields.io/github/stars/EmmyPencilAI?label=STARS&style=flat-square&color=00B4D8" />
  &nbsp;&nbsp;
  <img src="https://img.shields.io/badge/STATUS-OPERATIONAL-00FF88?style=flat-square" />
</p>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: ECOSYSTEM                                          -->
<!-- ============================================================ -->
<p align="center">
  <svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="250" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="300" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">ECOSYSTEM</text>
    <line x1="350" y1="20" x2="600" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <circle cx="300" cy="20" r="3" fill="#00B4D8">
      <animate attributeName="r" values="2;4;2" dur="2s" repeatCount="indefinite" />
    </circle>
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- COMPANY ECOSYSTEM MAP                                       -->
<!-- ============================================================ -->
<p align="center">
  <svg width="900" height="400" viewBox="0 0 900 400" xmlns="http://www.w3.org/2000/svg" style="max-width:900px;">
    <defs>
      <radialGradient id="centerGlow" cx="50%" cy="50%" r="50%">
        <stop offset="0%" style="stop-color:#00B4D8;stop-opacity:0.6" />
        <stop offset="100%" style="stop-color:#00B4D8;stop-opacity:0" />
      </radialGradient>
    </defs>

    <rect width="900" height="400" fill="#0A1128" rx="20" />

    <!-- Center Glow -->
    <circle cx="450" cy="200" r="100" fill="url(#centerGlow)" />

    <!-- Connection Lines -->
    <g opacity="0.3">
      <line x1="450" y1="200" x2="150" y2="100" stroke="#00B4D8" stroke-width="1.5" stroke-dasharray="6,4" />
      <line x1="450" y1="200" x2="150" y2="300" stroke="#00B4D8" stroke-width="1.5" stroke-dasharray="6,4" />
      <line x1="450" y1="200" x2="750" y2="100" stroke="#00B4D8" stroke-width="1.5" stroke-dasharray="6,4" />
      <line x1="450" y1="200" x2="750" y2="300" stroke="#00B4D8" stroke-width="1.5" stroke-dasharray="6,4" />
      <line x1="450" y1="200" x2="450" y2="340" stroke="#00B4D8" stroke-width="1.5" stroke-dasharray="6,4" />
    </g>

    <!-- Orbit Rings -->
    <ellipse cx="450" cy="200" rx="160" ry="50" fill="none" stroke="#00B4D8" stroke-width="0.5" opacity="0.15">
      <animateTransform attributeName="transform" type="rotate" from="0 450 200" to="360 450 200" dur="20s" repeatCount="indefinite" />
    </ellipse>
    <ellipse cx="450" cy="200" rx="190" ry="40" fill="none" stroke="#00B4D8" stroke-width="0.5" opacity="0.1">
      <animateTransform attributeName="transform" type="rotate" from="360 450 200" to="0 450 200" dur="25s" repeatCount="indefinite" />
    </ellipse>

    <!-- Center Node -->
    <circle cx="450" cy="200" r="55" fill="#000000" stroke="#00B4D8" stroke-width="2.5" />
    <text x="450" y="190" font-family="'Orbitron',sans-serif" font-size="18" fill="#00B4D8" text-anchor="middle" font-weight="bold">EMMY</text>
    <text x="450" y="215" font-family="'Orbitron',sans-serif" font-size="18" fill="#00B4D8" text-anchor="middle" font-weight="bold">PENCIL</text>

    <!-- Node: QuantumAgent -->
    <circle cx="150" cy="100" r="40" fill="#000000" stroke="#00B4D8" stroke-width="1.5" />
    <text x="150" y="98" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">QuantumAgent</text>
    <text x="150" y="115" font-family="'Nevada',sans-serif" font-size="8" fill="#00B4D8" text-anchor="middle">AI Agents</text>

    <!-- Node: Gugu Robotics -->
    <circle cx="150" cy="300" r="40" fill="#000000" stroke="#00B4D8" stroke-width="1.5" />
    <text x="150" y="295" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Gugu</text>
    <text x="150" y="312" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Robotics</text>

    <!-- Node: Nexus Mars -->
    <circle cx="750" cy="100" r="40" fill="#000000" stroke="#00B4D8" stroke-width="1.5" />
    <text x="750" y="95" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Nexus</text>
    <text x="750" y="112" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Mars</text>

    <!-- Node: Thalexa AI -->
    <circle cx="750" cy="300" r="40" fill="#000000" stroke="#00B4D8" stroke-width="1.5" />
    <text x="750" y="295" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Thalexa</text>
    <text x="750" y="312" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">AI</text>

    <!-- Node: Wealth Tailor -->
    <circle cx="450" cy="340" r="40" fill="#000000" stroke="#00B4D8" stroke-width="1.5" />
    <text x="450" y="335" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Wealth</text>
    <text x="450" y="352" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle">Tailor</text>

    <!-- Status Indicators -->
    <circle cx="110" cy="80" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite" />
    </circle>
    <circle cx="110" cy="280" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite" />
    </circle>
    <circle cx="710" cy="80" r="4" fill="#FFD700">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite" />
    </circle>
    <circle cx="710" cy="280" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite" />
    </circle>
    <circle cx="450" cy="320" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2s" repeatCount="indefinite" />
    </circle>
  </svg>
</p>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: ABOUT                                              -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="190" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="250" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">MISSION</text>
    <line x1="310" y1="20" x2="500" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- ABOUT ME – Product Launch Style                             -->
<!-- ============================================================ -->
<table align="center" width="95%" border="0" cellpadding="30" style="border-collapse:collapse;">
  <tr>
    <td width="35%" align="center" valign="middle">
      <svg width="280" height="350" viewBox="0 0 280 350" xmlns="http://www.w3.org/2000/svg">
        <rect width="280" height="350" fill="#0A1128" rx="20" stroke="#00B4D8" stroke-width="1" />
        <!-- Robot Portrait -->
        <circle cx="140" cy="120" r="70" fill="#000000" stroke="#00B4D8" stroke-width="2" />
        <circle cx="140" cy="120" r="60" fill="none" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
        <!-- Eyes -->
        <circle cx="115" cy="110" r="12" fill="#00B4D8">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite" />
        </circle>
        <circle cx="165" cy="110" r="12" fill="#00B4D8">
          <animate attributeName="opacity" values="0.5;1;0.5" dur="3s" repeatCount="indefinite" />
        </circle>
        <circle cx="115" cy="110" r="6" fill="#FFFFFF" />
        <circle cx="165" cy="110" r="6" fill="#FFFFFF" />
        <!-- Scanner Line -->
        <line x1="80" y1="140" x2="200" y2="140" stroke="#00FF88" stroke-width="1" opacity="0.5">
          <animate attributeName="x1" values="80;200;80" dur="4s" repeatCount="indefinite" />
          <animate attributeName="x2" values="200;80;200" dur="4s" repeatCount="indefinite" />
        </line>
        <!-- Tech Elements -->
        <text x="140" y="240" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle">EMMY PENCIL</text>
        <text x="140" y="265" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Robotics · AI · Aerospace</text>
        <rect x="40" y="285" width="200" height="2" fill="#00B4D8" opacity="0.3" />
        <text x="140" y="310" font-family="'Nevada',sans-serif" font-size="9" fill="#00B4D8" text-anchor="middle">SECURITY CLEARANCE: OMEGA</text>
        <text x="140" y="330" font-family="'Nevada',sans-serif" font-size="9" fill="#00FF88" text-anchor="middle">● ACTIVE</text>
      </svg>
    </td>
    <td width="65%" valign="top">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">BUILDING AUTONOMOUS INTELLIGENCE</h3>
      <p style="font-family:'Nevada',sans-serif; font-size:1.1rem; color:#FFFFFF; line-height:1.8;">
        I'm <strong style="color:#00B4D8;">Emmy Pencil</strong> — a robotics engineer, AI researcher, rocket scientist, and founder of multiple deep-tech ventures. My work spans autonomous agents, defense-grade robotics, aerospace systems, and next‑generation energy solutions.
      </p>
      <p style="font-family:'Nevada',sans-serif; font-size:1.1rem; color:#FFFFFF; line-height:1.8;">
        I believe in technology that serves humanity — not just products, but platforms that redefine what's possible. From <strong style="color:#00B4D8;">QuantumAgent</strong> to <strong style="color:#00B4D8;">Nexus Mars</strong>, every project is a step toward a future where intelligence is embedded in everything.
      </p>
      <br />
      <h4 style="color:#90E0EF; font-family:'Orbitron',sans-serif;">CORE VALUES</h4>
      <table border="0" cellpadding="5" style="width:100%;">
        <tr>
          <td style="color:#00B4D8;">✦ <strong style="color:#FFFFFF;">Autonomy</strong></td>
          <td style="color:#90E0EF;">Systems that think independently</td>
        </tr>
        <tr>
          <td style="color:#00B4D8;">✦ <strong style="color:#FFFFFF;">Precision</strong></td>
          <td style="color:#90E0EF;">Engineering with zero tolerance</td>
        </tr>
        <tr>
          <td style="color:#00B4D8;">✦ <strong style="color:#FFFFFF;">Future</strong></td>
          <td style="color:#90E0EF;">Building what doesn't exist yet</td>
        </tr>
        <tr>
          <td style="color:#00B4D8;">✦ <strong style="color:#FFFFFF;">Impact</strong></td>
          <td style="color:#90E0EF;">Technology that outlives its creator</td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: FOCUS                                              -->
<!-- ============================================================ -->
<p align="center">
  <svg width="600" height="40" viewBox="0 0 600 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="220" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="300" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">CURRENT FOCUS</text>
    <line x1="380" y1="20" x2="600" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- FOCUS PILLARS                                               -->
<!-- ============================================================ -->
<p align="center">
  <svg width="1000" height="140" viewBox="0 0 1000 140" xmlns="http://www.w3.org/2000/svg" style="max-width:1000px;">
    <rect width="1000" height="140" fill="#0A1128" rx="16" />

    <!-- Pillar 1: AI Agents -->
    <rect x="20" y="15" width="180" height="110" fill="#000000" stroke="#00B4D8" stroke-width="1" rx="10" />
    <text x="110" y="45" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle">AI AGENTS</text>
    <text x="110" y="70" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Autonomous</text>
    <text x="110" y="90" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Decision Systems</text>
    <circle cx="110" cy="107" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="1.5s" repeatCount="indefinite" />
    </circle>

    <!-- Pillar 2: Robotics -->
    <rect x="210" y="15" width="180" height="110" fill="#000000" stroke="#00B4D8" stroke-width="1" rx="10" />
    <text x="300" y="45" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle">ROBOTICS</text>
    <text x="300" y="70" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Industrial &</text>
    <text x="300" y="90" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Defense Systems</text>
    <circle cx="300" cy="107" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="1.8s" repeatCount="indefinite" />
    </circle>

    <!-- Pillar 3: Defense -->
    <rect x="400" y="15" width="180" height="110" fill="#000000" stroke="#00B4D8" stroke-width="1" rx="10" />
    <text x="490" y="45" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle">DEFENSE</text>
    <text x="490" y="70" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">National Security</text>
    <text x="490" y="90" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Infrastructure</text>
    <circle cx="490" cy="107" r="4" fill="#FFD700">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2.1s" repeatCount="indefinite" />
    </circle>

    <!-- Pillar 4: Aerospace -->
    <rect x="590" y="15" width="180" height="110" fill="#000000" stroke="#00B4D8" stroke-width="1" rx="10" />
    <text x="680" y="45" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle">AEROSPACE</text>
    <text x="680" y="70" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Planetary</text>
    <text x="680" y="90" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Exploration</text>
    <circle cx="680" cy="107" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="1.6s" repeatCount="indefinite" />
    </circle>

    <!-- Pillar 5: Open Source -->
    <rect x="780" y="15" width="200" height="110" fill="#000000" stroke="#00B4D8" stroke-width="1" rx="10" />
    <text x="880" y="45" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle">OPEN SOURCE</text>
    <text x="880" y="70" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Collaborative</text>
    <text x="880" y="90" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle">Innovation</text>
    <circle cx="880" cy="107" r="4" fill="#00FF88">
      <animate attributeName="opacity" values="0.3;1;0.3" dur="2.2s" repeatCount="indefinite" />
    </circle>
  </svg>
</p>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: PROJECTS                                           -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="180" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="250" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">PROJECTS</text>
    <line x1="320" y1="20" x2="500" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- FEATURED PROJECTS                                           -->
<!-- ============================================================ -->
<table align="center" width="95%" border="0" cellpadding="20" style="border-collapse:collapse;">
  <tr>
    <td width="33%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:25px;">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">QuantumAgent</h3>
      <p style="color:#90E0EF; font-family:'Nevada',sans-serif;">Autonomous AI agents for enterprise & defense</p>
      <p><strong style="color:#00B4D8;">Status:</strong> <span style="color:#00FF88;">● Active</span></p>
      <p><strong style="color:#00B4D8;">Tech:</strong> Python, TensorFlow, ROS2, Rust</p>
      <p><strong style="color:#00B4D8;">Impact:</strong> Real‑time decision systems</p>
      <br />
      <a href="https://quantumagent.one"><img src="https://img.shields.io/badge/▶_DEPLOY-00B4D8?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
    <td width="33%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:25px;">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">Gugu Robotics</h3>
      <p style="color:#90E0EF; font-family:'Nevada',sans-serif;">Autonomous robotics for industrial & defense</p>
      <p><strong style="color:#00B4D8;">Status:</strong> <span style="color:#00FF88;">● Active</span></p>
      <p><strong style="color:#00B4D8;">Tech:</strong> C++, ROS2, OpenCV, Arduino</p>
      <p><strong style="color:#00B4D8;">Impact:</strong> Manufacturing & logistics</p>
      <br />
      <a href="https://gugurobotics.com"><img src="https://img.shields.io/badge/▶_DEPLOY-00B4D8?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
    <td width="33%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:25px;">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">Nexus Mars</h3>
      <p style="color:#90E0EF; font-family:'Nevada',sans-serif;">Aerospace & planetary exploration systems</p>
      <p><strong style="color:#00B4D8;">Status:</strong> <span style="color:#FFD700;">● R&D</span></p>
      <p><strong style="color:#00B4D8;">Tech:</strong> C++, ROS2, PX4, Aerospace</p>
      <p><strong style="color:#00B4D8;">Impact:</strong> Mars colonization infrastructure</p>
      <br />
      <a href="#"><img src="https://img.shields.io/badge/▶_DEPLOY-00B4D8?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
  </tr>
  <tr>
    <td width="33%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:25px;">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">Thalexa AI</h3>
      <p style="color:#90E0EF; font-family:'Nevada',sans-serif;">Next‑gen AI infrastructure & agents</p>
      <p><strong style="color:#00B4D8;">Status:</strong> <span style="color:#00FF88;">● Active</span></p>
      <p><strong style="color:#00B4D8;">Tech:</strong> PyTorch, TypeScript, Next.js, Docker</p>
      <p><strong style="color:#00B4D8;">Impact:</strong> Scalable AI for enterprise</p>
      <br />
      <a href="#"><img src="https://img.shields.io/badge/▶_DEPLOY-00B4D8?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
    <td width="33%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:25px;">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">Wealth Tailor</h3>
      <p style="color:#90E0EF; font-family:'Nevada',sans-serif;">AI‑driven financial intelligence</p>
      <p><strong style="color:#00B4D8;">Status:</strong> <span style="color:#00FF88;">● Active</span></p>
      <p><strong style="color:#00B4D8;">Tech:</strong> Python, Rust, Cloud, Cybersecurity</p>
      <p><strong style="color:#00B4D8;">Impact:</strong> Decentralized wealth management</p>
      <br />
      <a href="#"><img src="https://img.shields.io/badge/▶_DEPLOY-00B4D8?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
    <td width="33%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:25px;">
      <h3 style="color:#00B4D8; font-family:'Orbitron',sans-serif;">Black Halo</h3>
      <p style="color:#90E0EF; font-family:'Nevada',sans-serif;">Cybersecurity & defense AI platform</p>
      <p><strong style="color:#00B4D8;">Status:</strong> <span style="color:#00FF88;">● Active</span></p>
      <p><strong style="color:#00B4D8;">Tech:</strong> Python, Rust, Cloud, Cybersecurity</p>
      <p><strong style="color:#00B4D8;">Impact:</strong> National security & infrastructure</p>
      <br />
      <a href="#"><img src="https://img.shields.io/badge/▶_DEPLOY-00B4D8?style=for-the-badge&logo=vercel&logoColor=white" /></a>
    </td>
  </tr>
</table>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: TECH STACK                                         -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="180" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="250" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">TECH STACK</text>
    <line x1="320" y1="20" x2="500" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- TECH STACK – Skill Icons + Categories                       -->
<!-- ============================================================ -->
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,rust,ts,nextjs,react,threejs,docker,linux,tensorflow,pytorch,opencv,arduino,ros,git,github,vercel" />
</p>

<br />

<table align="center" width="80%" border="0" cellpadding="8">
  <tr>
    <td align="center"><strong style="color:#00B4D8;">Languages</strong><br /><span style="color:#90E0EF;">Python · C++ · Rust · TypeScript</span></td>
    <td align="center"><strong style="color:#00B4D8;">AI & ML</strong><br /><span style="color:#90E0EF;">TensorFlow · PyTorch · OpenCV</span></td>
    <td align="center"><strong style="color:#00B4D8;">Cloud</strong><br /><span style="color:#90E0EF;">Docker · Linux · Cloud</span></td>
  </tr>
  <tr>
    <td align="center"><strong style="color:#00B4D8;">Robotics</strong><br /><span style="color:#90E0EF;">ROS2 · Arduino · Embedded</span></td>
    <td align="center"><strong style="color:#00B4D8;">Frameworks</strong><br /><span style="color:#90E0EF;">Next.js · React · Three.js</span></td>
    <td align="center"><strong style="color:#00B4D8;">DevOps</strong><br /><span style="color:#90E0EF;">Git · Vercel · CI/CD</span></td>
  </tr>
</table>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: ANALYTICS                                         -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="170" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="250" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">ANALYTICS</text>
    <line x1="330" y1="20" x2="500" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- GITHUB STATS – Futuristic Panels                            -->
<!-- ============================================================ -->
<table align="center" width="95%" border="0" cellpadding="20" style="border-collapse:collapse;">
  <tr>
    <td width="50%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:20px;">
      <img src="https://github-readme-stats.vercel.app/api?username=EmmyPencilAI&show_icons=true&count_private=true&hide_border=true&bg_color=0A1128&title_color=00B4D8&text_color=FFFFFF&icon_color=00B4D8" alt="GitHub Stats" width="100%" />
    </td>
    <td width="50%" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:20px;">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EmmyPencilAI&layout=compact&hide_border=true&bg_color=0A1128&title_color=00B4D8&text_color=FFFFFF" alt="Top Languages" width="100%" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:20px;">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=EmmyPencilAI&hide_border=true&background=0A1128&stroke=00B4D8&ring=00B4D8&fire=00B4D8&currStreakLabel=00B4D8&sideLabels=FFFFFF&dates=FFFFFF" alt="GitHub Streak" width="100%" />
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center" style="background:linear-gradient(145deg,#0A1128,#000000); border:1px solid #00B4D8; border-radius:20px; padding:20px;">
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=EmmyPencilAI&bg_color=0A1128&color=FFFFFF&line=00B4D8&point=90E0EF&area=true&hide_border=true" alt="Activity Graph" width="100%" />
    </td>
  </tr>
</table>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: ACHIEVEMENTS                                       -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="160" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="250" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">ACHIEVEMENTS</text>
    <line x1="340" y1="20" x2="500" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- TROPHIES                                                     -->
<!-- ============================================================ -->
<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=EmmyPencilAI&theme=darkhub&no-frame=true&row=2&column=4" alt="GitHub Trophies" width="85%" />
</p>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: PHILOSOPHY                                         -->
<!-- ============================================================ -->
<p align="center">
  <svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="130" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="200" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">PHILOSOPHY</text>
    <line x1="270" y1="20" x2="400" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- QUOTE                                                       -->
<!-- ============================================================ -->
<blockquote align="center" style="border:none; padding:40px; background:linear-gradient(145deg,#0A1128,#000000); border-radius:20px; border-left:8px solid #00B4D8; max-width:800px; margin:0 auto;">
  <p style="font-family:'Orbitron',sans-serif; font-size:2.2rem; color:#FFFFFF; letter-spacing:2px; line-height:1.4;">
    "We don't chase the future.<br />We engineer it."
  </p>
  <p style="font-family:'Nevada',sans-serif; font-size:1.2rem; color:#90E0EF;">
    — Emmy Pencil
  </p>
</blockquote>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: TIMELINE                                           -->
<!-- ============================================================ -->
<p align="center">
  <svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="130" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="200" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">TIMELINE</text>
    <line x1="270" y1="20" x2="400" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- TIMELINE – Vertical Journey                                 -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="600" viewBox="0 0 500 600" xmlns="http://www.w3.org/2000/svg" style="max-width:500px;">
    <rect width="500" height="600" fill="#0A1128" rx="16" />

    <!-- Central Line -->
    <line x1="250" y1="40" x2="250" y2="560" stroke="#00B4D8" stroke-width="2" opacity="0.3" />

    <!-- Node 1 -->
    <circle cx="250" cy="60" r="14" fill="#00B4D8" />
    <text x="250" y="65" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">1</text>
    <text x="330" y="65" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8">FOUNDER</text>
    <text x="330" y="85" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2018 — Built first startup</text>

    <!-- Node 2 -->
    <circle cx="250" cy="140" r="14" fill="#00B4D8" />
    <text x="250" y="145" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">2</text>
    <text x="330" y="145" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8">ENGINEER</text>
    <text x="330" y="165" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2020 — Full‑stack & robotics</text>

    <!-- Node 3 -->
    <circle cx="250" cy="220" r="14" fill="#00B4D8" />
    <text x="250" y="225" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">3</text>
    <text x="330" y="225" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8">RESEARCH</text>
    <text x="330" y="245" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2021 — AI & autonomous systems</text>

    <!-- Node 4 -->
    <circle cx="250" cy="300" r="14" fill="#00B4D8" />
    <text x="250" y="305" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">4</text>
    <text x="330" y="305" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8">ROBOTICS</text>
    <text x="330" y="325" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2022 — Industrial robotics</text>

    <!-- Node 5 -->
    <circle cx="250" cy="380" r="14" fill="#00B4D8" />
    <text x="250" y="385" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">5</text>
    <text x="330" y="385" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8">DEFENSE</text>
    <text x="330" y="405" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2023 — Security systems</text>

    <!-- Node 6 -->
    <circle cx="250" cy="460" r="14" fill="#00B4D8" />
    <text x="250" y="465" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">6</text>
    <text x="330" y="465" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8">AEROSPACE</text>
    <text x="330" y="485" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2024 — Mars exploration</text>

    <!-- Node 7 -->
    <circle cx="250" cy="540" r="14" fill="#FFD700" />
    <text x="250" y="545" text-anchor="middle" font-size="10" fill="#0A1128" font-family="'Orbitron',sans-serif" font-weight="bold">7</text>
    <text x="330" y="545" font-family="'Orbitron',sans-serif" font-size="14" fill="#FFD700">FUTURE</text>
    <text x="330" y="565" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF">2026+ — Beyond Earth</text>

    <!-- Glowing Pulse on Future -->
    <circle cx="250" cy="540" r="25" fill="#FFD700" opacity="0.1">
      <animate attributeName="r" values="20;35;20" dur="2s" repeatCount="indefinite" />
      <animate attributeName="opacity" values="0.2;0.05;0.2" dur="2s" repeatCount="indefinite" />
    </circle>
  </svg>
</p>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: CONTRIBUTIONS                                      -->
<!-- ============================================================ -->
<p align="center">
  <svg width="500" height="40" viewBox="0 0 500 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="140" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="250" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">CONTRIBUTIONS</text>
    <line x1="360" y1="20" x2="500" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- FIGHTER JET TRAIL – Animated SVG                            -->
<!-- ============================================================ -->
<p align="center">
  <svg width="1000" height="200" viewBox="0 0 1000 200" xmlns="http://www.w3.org/2000/svg" style="max-width:1000px;">
    <defs>
      <linearGradient id="trailGrad2" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" style="stop-color:#00B4D8;stop-opacity:0" />
        <stop offset="30%" style="stop-color:#00B4D8;stop-opacity:0.6" />
        <stop offset="100%" style="stop-color:#00FF88;stop-opacity:1" />
      </linearGradient>
      <radialGradient id="jetGlow2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" style="stop-color:#FFFFFF;stop-opacity:1" />
        <stop offset="50%" style="stop-color:#00B4D8;stop-opacity:0.5" />
        <stop offset="100%" style="stop-color:#00B4D8;stop-opacity:0" />
      </radialGradient>
    </defs>

    <rect width="1000" height="200" fill="#0A1128" rx="12" />

    <!-- Contribution Grid Background -->
    <g opacity="0.08">
      <rect x="20" y="20" width="28" height="28" fill="#00B4D8" rx="4" />
      <rect x="58" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.5" />
      <rect x="96" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.8" />
      <rect x="134" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.3" />
      <rect x="172" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.9" />
      <rect x="210" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.4" />
      <rect x="248" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.7" />
      <rect x="286" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.2" />
      <rect x="324" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.6" />
      <rect x="362" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.9" />
      <rect x="400" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.3" />
      <rect x="438" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.7" />
      <rect x="476" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.5" />
      <rect x="514" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.8" />
      <rect x="552" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.4" />
      <rect x="590" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.9" />
      <rect x="628" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.2" />
      <rect x="666" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.6" />
      <rect x="704" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.3" />
      <rect x="742" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.8" />
      <rect x="780" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.5" />
      <rect x="818" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.7" />
      <rect x="856" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.9" />
      <rect x="894" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.4" />
      <rect x="932" y="20" width="28" height="28" fill="#00B4D8" rx="4" opacity="0.6" />
    </g>

    <!-- Jet Trail -->
    <path d="M 30 100 Q 180 80, 350 120 T 550 90 T 750 110 T 970 100" fill="none" stroke="url(#trailGrad2)" stroke-width="6" opacity="0.5">
      <animate attributeName="stroke-dashoffset" from="0" to="2000" dur="5s" repeatCount="indefinite" />
    </path>
    <path d="M 30 100 Q 180 80, 350 120 T 550 90 T 750 110 T 970 100" fill="none" stroke="#00B4D8" stroke-width="16" opacity="0.1">
      <animate attributeName="stroke-dashoffset" from="0" to="2000" dur="5s" repeatCount="indefinite" />
    </path>

    <!-- Fighter Jet -->
    <g>
      <animateMotion dur="5s" repeatCount="indefinite" path="M 30 100 Q 180 80, 350 120 T 550 90 T 750 110 T 970 100" />
      <circle cx="0" cy="0" r="12" fill="url(#jetGlow2)" />
      <polygon points="0,-6 20,0 0,6" fill="#90E0EF" />
      <polygon points="-4,-10 -12,-6 -4,-3" fill="#00B4D8" />
      <polygon points="-4,10 -12,6 -4,3" fill="#00B4D8" />
      <polygon points="-6,-3 -15,0 -6,3" fill="#00FF88" opacity="0.8">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="0.2s" repeatCount="indefinite" />
      </polygon>
    </g>

    <text x="500" y="175" font-family="'Nevada',sans-serif" font-size="11" fill="#90E0EF" text-anchor="middle" opacity="0.4">
      ▲ FIGHTER JET TRAIL — CONTRIBUTION TRACKING ACTIVE ▲
    </text>
  </svg>
</p>

<br />

<!-- GitHub Actions Instructions -->
<details>
  <summary style="color:#00B4D8; font-family:'Orbitron',sans-serif;">
    <strong>▼ DEPLOY JET TRAIL GENERATOR</strong>
  </summary>
  <br />
  <pre style="background:#0A1128; color:#00B4D8; padding:20px; border-radius:12px; border:1px solid #00B4D8; overflow-x:auto;">
name: Generate Jet Trail
on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:
jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: Platane/snk@v3
        with:
          github_user_name: EmmyPencilAI
          outputs: |
            dist/jet-trail.svg
      - uses: actions/upload-artifact@v3
        with:
          name: jet-trail
          path: dist
  </pre>
</details>

<br /><br />

<!-- ============================================================ -->
<!-- DIVIDER: CONNECT                                            -->
<!-- ============================================================ -->
<p align="center">
  <svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
    <line x1="0" y1="20" x2="140" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
    <text x="200" y="30" font-family="'Orbitron',sans-serif" font-size="16" fill="#00B4D8" text-anchor="middle" letter-spacing="6">CONNECT</text>
    <line x1="260" y1="20" x2="400" y2="20" stroke="#00B4D8" stroke-width="1" opacity="0.3" />
  </svg>
</p>

<br />

<!-- ============================================================ -->
<!-- SOCIAL LINKS – Glowing Buttons                              -->
<!-- ============================================================ -->
<p align="center">
  <a href="https://github.com/EmmyPencilAI"><img src="https://img.shields.io/badge/GITHUB-0A1128?style=for-the-badge&logo=github&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="https://emmypencil.one"><img src="https://img.shields.io/badge/WEBSITE-0A1128?style=for-the-badge&logo=vercel&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="https://vercel.com/emmypencilais-projects"><img src="https://img.shields.io/badge/VERCEL-0A1128?style=for-the-badge&logo=vercel&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="#"><img src="https://img.shields.io/badge/LINKEDIN-0A1128?style=for-the-badge&logo=linkedin&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
</p>
<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/X-0A1128?style=for-the-badge&logo=x&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="#"><img src="https://img.shields.io/badge/YOUTUBE-0A1128?style=for-the-badge&logo=youtube&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="#"><img src="https://img.shields.io/badge/INSTAGRAM-0A1128?style=for-the-badge&logo=instagram&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="#"><img src="https://img.shields.io/badge/TIKTOK-0A1128?style=for-the-badge&logo=tiktok&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
  &nbsp;
  <a href="mailto:hello@emmypencil.one"><img src="https://img.shields.io/badge/EMAIL-0A1128?style=for-the-badge&logo=gmail&logoColor=00B4D8&labelColor=0A1128&color=00B4D8" /></a>
</p>

<br /><br />

<!-- ============================================================ -->
<!-- FOOTER – Mars Horizon + Blueprint Grid                      -->
<!-- ============================================================ -->
<p align="center">
  <svg width="100%" height="180" viewBox="0 0 1200 180" xmlns="http://www.w3.org/2000/svg" style="max-width:1200px;">
    <defs>
      <linearGradient id="marsGrad" x1="0%" y1="0%" x2="0%" y2="100%">
        <stop offset="0%" style="stop-color:#000000;stop-opacity:0" />
        <stop offset="70%" style="stop-color:#8B0000;stop-opacity:0.3" />
        <stop offset="100%" style="stop-color:#FF4500;stop-opacity:0.5" />
      </linearGradient>
    </defs>

    <!-- Sky -->
    <rect width="1200" height="180" fill="#0A1128" />

    <!-- Stars -->
    <g fill="#FFFFFF" opacity="0.2">
      <circle cx="50" cy="25" r="1.5" />
      <circle cx="150" cy="50" r="1" />
      <circle cx="250" cy="20" r="1.5" />
      <circle cx="350" cy="70" r="1" />
      <circle cx="450" cy="35" r="1.5" />
      <circle cx="550" cy="15" r="1" />
      <circle cx="650" cy="45" r="1.5" />
      <circle cx="750" cy="60" r="1" />
      <circle cx="850" cy="20" r="1.5" />
      <circle cx="950" cy="50" r="1" />
      <circle cx="1050" cy="30" r="1.5" />
      <circle cx="1150" cy="55" r="1" />
    </g>

    <!-- Mars Surface -->
    <ellipse cx="600" cy="180" rx="700" ry="90" fill="url(#marsGrad)" />

    <!-- Mars Features -->
    <ellipse cx="300" cy="175" rx="80" ry="25" fill="#8B0000" opacity="0.15" />
    <ellipse cx="500" cy="170" rx="60" ry="20" fill="#8B0000" opacity="0.1" />
    <ellipse cx="700" cy="178" rx="100" ry="30" fill="#8B0000" opacity="0.15" />
    <ellipse cx="900" cy="172" rx="70" ry="22" fill="#8B0000" opacity="0.1" />

    <!-- Rover Tracks -->
    <path d="M 200 165 Q 250 160, 300 168 T 400 162 T 500 170" fill="none" stroke="#FF4500" stroke-width="1" opacity="0.2" stroke-dasharray="4,4" />
    <path d="M 600 158 Q 650 165, 700 155 T 800 162 T 900 152" fill="none" stroke="#FF4500" stroke-width="1" opacity="0.2" stroke-dasharray="4,4" />

    <!-- Blueprint Grid -->
    <g opacity="0.04">
      <line x1="0" y1="36" x2="1200" y2="36" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="0" y1="72" x2="1200" y2="72" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="0" y1="108" x2="1200" y2="108" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="0" y1="144" x2="1200" y2="144" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="200" y1="0" x2="200" y2="180" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="400" y1="0" x2="400" y2="180" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="600" y1="0" x2="600" y2="180" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="800" y1="0" x2="800" y2="180" stroke="#00B4D8" stroke-width="0.5" />
      <line x1="1000" y1="0" x2="1000" y2="180" stroke="#00B4D8" stroke-width="0.5" />
    </g>

    <!-- Footer Text -->
    <text x="600" y="115" font-family="'Orbitron',sans-serif" font-size="14" fill="#00B4D8" text-anchor="middle" letter-spacing="4" opacity="0.6">
      © 2026 EMMY PENCIL
    </text>
    <text x="600" y="142" font-family="'Nevada',sans-serif" font-size="10" fill="#90E0EF" text-anchor="middle" letter-spacing="6" opacity="0.4">
      BUILDING THE FUTURE • AUTONOMOUS INTELLIGENCE
    </text>

    <!-- Status Pulse -->
    <circle cx="600" cy="160" r="3" fill="#00FF88" opacity="0.5">
      <animate attributeName="opacity" values="0.2;1;0.2" dur="2s" repeatCount="indefinite" />
    </circle>
  </svg>
</p>
