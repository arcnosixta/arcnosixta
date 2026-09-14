<div align="center">

<!-- =========== BANNER: scanline + glitch title =========== -->
<svg viewBox="0 0 900 150" xmlns="http://www.w3.org/2000/svg" width="100%">
  <rect width="900" height="150" fill="#050505"/>
  <line x1="0" y1="0" x2="900" y2="0" stroke="#ffffff" stroke-width="2">
    <animate attributeName="y1" values="0;150" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="0;150" dur="5s" repeatCount="indefinite"/>
  </line>
  <line x1="0" y1="150" x2="900" y2="150" stroke="#ffffff" stroke-width="1" opacity="0.3">
    <animate attributeName="y1" values="150;0" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="150;0" dur="5s" repeatCount="indefinite"/>
  </line>
  <text x="450" y="80" text-anchor="middle" font-family="monospace" font-size="54" fill="#000000" opacity="0.9">
    a r c n o s i x t a
    <animate attributeName="x" values="450;453;447;450" dur="1.1s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="80" text-anchor="middle" font-family="monospace" font-size="54" fill="#ffffff" opacity="0.95">
    a r c n o s i x t a
    <animate attributeName="opacity" values="1;0.35;1" dur="2.8s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="126" text-anchor="middle" font-family="monospace" font-size="15" fill="#808080">
    [ KNIGHT OF THE NIGHT CODE ]
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </text>
</svg>

<!-- =========== SWORDS: crossing blades with clash spark =========== -->
<svg viewBox="0 0 900 110" xmlns="http://www.w3.org/2000/svg" width="100%">
  <filter id="swordGlow" x="-50%" y="-50%" width="200%" height="200%">
    <feGaussianBlur stdDeviation="3" result="b"/>
    <feMerge>
      <feMergeNode in="b"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>
  <g transform="translate(450 55)">
    <animateTransform attributeName="transform" type="rotate" values="-30;30;-30" dur="2.4s" repeatCount="indefinite" id="leftSwing"/>
    <g filter="url(#swordGlow)">
      <rect x="-4" y="-80" width="8" height="64" fill="#e0e0e0"/>
      <rect x="0" y="-80" width="3" height="64" fill="#ffffff"/>
      <rect x="-14" y="-16" width="28" height="6" fill="#444444"/>
      <rect x="-3" y="-10" width="6" height="14" fill="#222222"/>
      <rect x="-5" y="4" width="10" height="5" fill="#ffffff"/>
    </g>
  </g>
  <g transform="translate(450 55) scale(-1 1)">
    <animateTransform attributeName="transform" type="rotate" values="-30;30;-30" dur="2.4s" repeatCount="indefinite"/>
    <g filter="url(#swordGlow)">
      <rect x="-4" y="-80" width="8" height="64" fill="#e0e0e0"/>
      <rect x="0" y="-80" width="3" height="64" fill="#ffffff"/>
      <rect x="-14" y="-16" width="28" height="6" fill="#444444"/>
      <rect x="-3" y="-10" width="6" height="14" fill="#222222"/>
      <rect x="-5" y="4" width="10" height="5" fill="#ffffff"/>
    </g>
  </g>
  <circle cx="450" cy="55" r="6" fill="#ffffff" opacity="0">
    <animate attributeName="opacity" values="0;0;1;0;0" dur="2.4s" repeatCount="indefinite" keyTimes="0;0.45;0.5;0.55;1"/>
  </circle>
</svg>

<!-- =========== LOADING PROGRESS BAR =========== -->
<svg viewBox="0 0 900 40" xmlns="http://www.w3.org/2000/svg" width="100%">
  <text x="450" y="20" text-anchor="middle" font-family="monospace" font-size="13" fill="#666666" opacity="0.8">
    LOADING KNIGHT DATA
  </text>
  <rect x="250" y="26" width="400" height="8" fill="#111111" stroke="#333333"/>
  <rect x="250" y="26" width="0" height="8" fill="#ffffff">
    <animate attributeName="width" values="0;400" dur="2s" repeatCount="indefinite"/>
  </rect>
  <text x="650" y="35" font-family="monospace" font-size="12" fill="#ffffff" opacity="0">
    READY
    <animate attributeName="opacity" values="0;0;1;1;0" dur="2s" repeatCount="indefinite" keyTimes="0;0.75;0.85;0.95;1"/>
  </text>
</svg>

<br/>
<code>whoami: arcnosixta &middot; class: KNIGHT &middot; guild: SOLO DEVELOPER &middot; location: THE DARK</code>
<br/>

---

## [ COMBAT CORE ]

<!-- =========== STRIKE BARS: animated skill meters =========== -->
<svg viewBox="0 0 900 350" xmlns="http://www.w3.org/2000/svg" width="100%">
  <rect width="900" height="350" fill="none"/>
  <text x="40" y="22" font-family="monospace" font-size="12" fill="#555555">STRIKE METERS / EACH BAR THROWS AT ITS OWN RHYTHM</text>

  <!-- 1 CODE SWORD -->
  <text x="40" y="58" font-family="monospace" font-size="16" fill="#ffffff">CODE SWORD</text>
  <text x="40" y="74" font-family="monospace" font-size="10" fill="#555555">FRONTEND STRIKE</text>
  <rect x="40" y="82" width="620" height="12" fill="#0a0a0a" stroke="#333333"/>
  <rect x="40" y="82" width="40" height="12" fill="#777777">
    <animate attributeName="width" values="40;620;120;620;40" dur="7s" repeatCount="indefinite"/>
  </rect>
  <rect x="40" y="82" width="8" height="12" fill="#ffffff" opacity="0.85">
    <animate attributeName="x" values="40;652;40" dur="1.4s" repeatCount="indefinite"/>
  </rect>
  <text x="700" y="94" font-family="monospace" font-size="13" fill="#aaaaaa">A+</text>

  <!-- 2 BACKEND ARMOR -->
  <text x="40" y="118" font-family="monospace" font-size="16" fill="#ffffff">BACKEND ARMOR</text>
  <text x="40" y="134" font-family="monospace" font-size="10" fill="#555555">API DEFENSE RATING</text>
  <rect x="40" y="142" width="620" height="12" fill="#0a0a0a" stroke="#333333"/>
  <rect x="40" y="142" width="0" height="12" fill="#777777">
    <animate attributeName="width" values="0;320;620;80;0" dur="6s" repeatCount="indefinite"/>
  </rect>
  <rect x="40" y="142" width="8" height="12" fill="#ffffff" opacity="0.85">
    <animate attributeName="x" values="40;652;40" dur="1.7s" repeatCount="indefinite"/>
  </rect>
  <text x="700" y="154" font-family="monospace" font-size="13" fill="#aaaaaa">S</text>

  <!-- 3 DATABASE MANA -->
  <text x="40" y="178" font-family="monospace" font-size="16" fill="#ffffff">DATABASE MANA</text>
  <text x="40" y="194" font-family="monospace" font-size="10" fill="#555555">QUERY CASTING SPEED</text>
  <rect x="40" y="202" width="620" height="12" fill="#0a0a0a" stroke="#333333"/>
  <rect x="40" y="202" width="0" height="12" fill="#777777">
    <animate attributeName="width" values="0;620;240;620;0" dur="8s" repeatCount="indefinite"/>
  </rect>
  <rect x="40" y="202" width="8" height="12" fill="#ffffff" opacity="0.85">
    <animate attributeName="x" values="40;652;40" dur="1.1s" repeatCount="indefinite"/>
  </rect>
  <text x="700" y="214" font-family="monospace" font-size="13" fill="#aaaaaa">S</text>

  <!-- 4 DEVOPS LANCE -->
  <text x="40" y="238" font-family="monospace" font-size="16" fill="#ffffff">DEVOPS LANCE</text>
  <text x="40" y="254" font-family="monospace" font-size="10" fill="#555555">PIPELINE THRUST</text>
  <rect x="40" y="262" width="620" height="12" fill="#0a0a0a" stroke="#333333"/>
  <rect x="40" y="262" width="120" height="12" fill="#777777">
    <animate attributeName="width" values="120;620;60;620;120" dur="6.5s" repeatCount="indefinite"/>
  </rect>
  <rect x="40" y="262" width="8" height="12" fill="#ffffff" opacity="0.85">
    <animate attributeName="x" values="40;652;40" dur="1.9s" repeatCount="indefinite"/>
  </rect>
  <text x="700" y="274" font-family="monospace" font-size="13" fill="#aaaaaa">A</text>

  <!-- 5 SECURITY AURA -->
  <text x="40" y="298" font-family="monospace" font-size="16" fill="#ffffff">SECURITY AURA</text>
  <text x="40" y="314" font-family="monospace" font-size="10" fill="#555555">THREAT DETECTION FIELD</text>
  <rect x="40" y="322" width="620" height="12" fill="#0a0a0a" stroke="#333333"/>
  <rect x="40" y="322" width="0" height="12" fill="#ffffff" opacity="0.7">
    <animate attributeName="width" values="0;620;0;620;0" dur="3s" repeatCount="indefinite"/>
  </rect>
  <rect x="40" y="322" width="8" height="12" fill="#ffffff">
    <animate attributeName="x" values="40;652;40" dur="0.9s" repeatCount="indefinite"/>
  </rect>
  <text x="700" y="334" font-family="monospace" font-size="13" fill="#aaaaaa">SS</text>
</svg>

---

## [ VERSUS ]

<!-- =========== VERSUS: HP bars deplete and recover =========== -->
<svg viewBox="0 0 900 160" xmlns="http://www.w3.org/2000/svg" width="100%">
  <rect width="900" height="160" fill="none"/>

  <text x="230" y="36" text-anchor="middle" font-family="monospace" font-size="18" fill="#ffffff">KNIGHT</text>
  <rect x="50" y="48" width="360" height="16" fill="#0a0a0a" stroke="#333333"/>
  <rect x="50" y="48" width="360" height="16" fill="#dddddd">
    <animate attributeName="width" values="360;90;170;360" dur="6s" repeatCount="indefinite" keyTimes="0;0.35;0.6;1"/>
  </rect>

  <text x="670" y="36" text-anchor="middle" font-family="monospace" font-size="18" fill="#ffffff">BUGS</text>
  <rect x="490" y="48" width="360" height="16" fill="#0a0a0a" stroke="#333333"/>
  <rect x="490" y="48" width="360" height="16" fill="#dddddd">
    <animate attributeName="width" values="360;300;60;360" dur="7s" repeatCount="indefinite" keyTimes="0;0.3;0.6;1"/>
  </rect>

  <text x="450" y="66" text-anchor="middle" font-family="monospace" font-size="34" fill="#ffffff">
    VS
    <animate attributeName="opacity" values="1;0.1;1" dur="0.6s" repeatCount="indefinite"/>
  </text>

  <text x="450" y="128" text-anchor="middle" font-family="monospace" font-size="14" fill="#aaaaaa" opacity="0">
    ROUND 1 ... FIGHT!
    <animate attributeName="opacity" values="0;0;1;1;0;0;1;0" dur="7s" repeatCount="indefinite" keyTimes="0;0.1;0.2;0.4;0.55;0.65;0.75;1"/>
  </text>
</svg>

---

## [ STRIKE / COMBO ]

<!-- =========== COMBO METER + STRIKE FLASH =========== -->
<svg viewBox="0 0 900 130" xmlns="http://www.w3.org/2000/svg" width="100%">
  <text x="450" y="60" text-anchor="middle" font-family="monospace" font-size="38" fill="#ffffff">
    STRIKE!
    <animate attributeName="opacity" values="1;0;1;0;1;0;0.3;1" dur="1.2s" repeatCount="indefinite"/>
  </text>
  <rect x="150" y="84" width="600" height="18" fill="#0a0a0a" stroke="#333333"/>
  <rect x="150" y="84" width="0" height="18" fill="#ffffff">
    <animate attributeName="width" values="0;600;0" dur="1.6s" repeatCount="indefinite" keyTimes="0;0.5;1"/>
  </rect>
  <rect x="750" y="84" width="8" height="18" fill="#ffffff" opacity="0">
    <animate attributeName="opacity" values="0;1;0" dur="1.6s" repeatCount="indefinite" keyTimes="0;0.5;1"/>
  </rect>
  <text x="820" y="99" font-family="monospace" font-size="14" fill="#ffffff">
    HIT!!
    <animate attributeName="opacity" values="0;1;0" dur="1.6s" repeatCount="indefinite" keyTimes="0;0.5;1"/>
  </text>
</svg>

---

## [ ARSENAL ]

<img src="https://skillicons.dev/icons?i=flutter,dart,firebase,androidstudio,vscode,git,github,js,html,css&theme=dark&perline=5" />

<img src="https://img.shields.io/badge/Flutter-000000?style=flat-square&logo=flutter&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Dart-000000?style=flat-square&logo=dart&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Firebase-000000?style=flat-square&logo=firebase&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/TypeScript-000000?style=flat-square&logo=typescript&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/React-000000?style=flat-square&logo=react&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Node.js-000000?style=flat-square&logo=nodedotjs&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Python-000000?style=flat-square&logo=python&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Linux-000000?style=flat-square&logo=linux&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Docker-000000?style=flat-square&logo=docker&logoColor=white&labelColor=222222"/>
<img src="https://img.shields.io/badge/Git-000000?style=flat-square&logo=git&logoColor=white&labelColor=222222"/>

---

## [ BATTLE STATS ]

<img src="https://github-readme-stats.vercel.app/api?username=arcnosixta&show_icons=true&theme=github_dark&hide_border=true&bg_color=050505&title_color=ffffff&icon_color=ffffff&text_color=888888&border_color=222222" height="180"/>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=arcnosixta&hide_border=true&background=050505&stroke=ffffff&fire=ffffff&ring=cccccc&currStreakNum=aaaaaa&sideNums=666666&sideLabels=ffffff" height="180"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arcnosixta&layout=compact&theme=github_dark&hide_border=true&bg_color=050505&title_color=ffffff&text_color=888888&border_color=222222" height="150"/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=arcnosixta&theme=github-dark&hide_border=true&area=true&color=ffffff&line=999999&point=ffffff&bg_color=050505" />

<img src="https://github-profile-trophy.vercel.app/?username=arcnosixta&theme=dark&no-frame=true&column=7&margin-w=10&margin-h=10&title_color=ffffff" />

---

## [ CAMPAIGNS ]

| Campaign | Target | Status |
|---|---|---|
| Project Alpha | Full-Stack App | <img src="https://img.shields.io/badge/IN_PROGRESS-000000?style=flat&labelColor=222222"/> |
| Project Beta | API &amp; Backend | <img src="https://img.shields.io/badge/IN_PROGRESS-000000?style=flat&labelColor=222222"/> |
| Open Source | War on Bugs | <img src="https://img.shields.io/badge/ETERNAL-000000?style=flat&labelColor=222222"/> |

---

## [ ALLIES ]

<a href="https://t.me/arcnosixta"><img src="https://img.shields.io/badge/TELEGRAM-000000?style=for-the-badge&logo=telegram&logoColor=white&labelColor=111111"/></a>
<a href="mailto:arcnosixta@gmail.com"><img src="https://img.shields.io/badge/EMAIL-000000?style=for-the-badge&logo=gmail&logoColor=white&labelColor=111111"/></a>
<a href="https://github.com/arcnosixta"><img src="https://img.shields.io/badge/GITHUB-000000?style=for-the-badge&logo=github&logoColor=white&labelColor=111111"/></a>

<img src="https://komarev.com/ghpvc/?username=arcnosixta&label=KNIGHT+VIEWS&color=000000&style=for-the-badge&labelColor=111111"/>

<!-- =========== FOOTER =========== -->
<svg viewBox="0 0 900 90" xmlns="http://www.w3.org/2000/svg" width="100%">
  <rect width="900" height="90" fill="#050505"/>
  <text x="450" y="40" text-anchor="middle" font-family="monospace" font-size="16" fill="#ffffff">
    Forged in darkness. Sharpened by every battle.
    <animate attributeName="opacity" values="1;0.4;1" dur="2.5s" repeatCount="indefinite"/>
  </text>
  <text x="450" y="66" text-anchor="middle" font-family="monospace" font-size="12" fill="#666666">
    [ KNIGHT STATUS: LEGENDARY ]  [ NO DEATH BATTLE ]  [ STRIKE METER: FULL ]
  </text>
  <line x1="0" y1="86" x2="900" y2="86" stroke="#ffffff" stroke-width="1" opacity="0.4">
    <animate attributeName="opacity" values="0.1;0.6;0.1" dur="1s" repeatCount="indefinite"/>
  </line>
</svg>

</div>