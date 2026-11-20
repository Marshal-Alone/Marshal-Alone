<div align="center">

  <!-- ==================== SKEUOMORPHIC HERO CONSOLE ==================== -->
  <svg width="100%" max-width="840" height="260" viewBox="0 0 840 260" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Skeuomorphic Metal & Bevel Gradients -->
      <linearGradient id="chassisGrad" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#2a2e39"/>
        <stop offset="50%" stop-color="#1b1e25"/>
        <stop offset="100%" stop-color="#12141a"/>
      </linearGradient>
      
      <linearGradient id="innerScreen" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#090b10"/>
        <stop offset="100%" stop-color="#131722"/>
      </linearGradient>
      
      <linearGradient id="metallicBevel" x1="0" y1="0" x2="1" y2="1">
        <stop offset="0%" stop-color="#555d6e"/>
        <stop offset="50%" stop-color="#2c323f"/>
        <stop offset="100%" stop-color="#101319"/>
      </linearGradient>
      
      <linearGradient id="goldPlate" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#d4af37"/>
        <stop offset="50%" stop-color="#fff2a1"/>
        <stop offset="100%" stop-color="#aa820a"/>
      </linearGradient>

      <!-- Drop Shadows & Extrusions -->
      <filter id="consoleShadow" x="-10" y="-10" width="860" height="280" filterUnits="userSpaceOnUse">
        <feDropShadow dx="0" dy="16" stdDeviation="14" flood-color="#000000" flood-opacity="0.8"/>
        <feDropShadow dx="0" dy="3" stdDeviation="3" flood-color="#ffffff" flood-opacity="0.12"/>
      </filter>
      
      <filter id="insetBevel">
        <feComponentTransfer in="SourceAlpha">
          <feFuncA type="linear" slope="0.7"/>
        </feComponentTransfer>
      </filter>

      <!-- LED Glow -->
      <filter id="ledGlow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="4" result="blur" />
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Outer Tactile Console Chassis -->
    <rect x="15" y="15" width="810" height="230" rx="18" fill="url(#chassisGrad)" stroke="url(#metallicBevel)" stroke-width="3" filter="url(#consoleShadow)"/>
    
    <!-- Screws on Corners (Skeuomorphic Detail) -->
    <circle cx="35" cy="35" r="5" fill="#1b1e25" stroke="#485163" stroke-width="1.5"/>
    <line x1="32" y1="35" x2="38" y2="35" stroke="#68758e" stroke-width="1.2"/>
    
    <circle cx="805" cy="35" r="5" fill="#1b1e25" stroke="#485163" stroke-width="1.5"/>
    <line x1="802" y1="35" x2="808" y2="35" stroke="#68758e" stroke-width="1.2"/>

    <circle cx="35" cy="225" r="5" fill="#1b1e25" stroke="#485163" stroke-width="1.5"/>
    <line x1="33" y1="223" x2="37" y2="227" stroke="#68758e" stroke-width="1.2"/>

    <circle cx="805" cy="225" r="5" fill="#1b1e25" stroke="#485163" stroke-width="1.5"/>
    <line x1="803" y1="223" x2="807" y2="227" stroke="#68758e" stroke-width="1.2"/>

    <!-- Inset Display Screen with Glass Bevel -->
    <rect x="55" y="38" width="730" height="182" rx="12" fill="url(#innerScreen)" stroke="#0b0d13" stroke-width="3"/>
    <rect x="56" y="39" width="728" height="1" fill="#444c5e" opacity="0.4"/>

    <!-- Status LEDs -->
    <circle cx="85" cy="62" r="5" fill="#00ff66" filter="url(#ledGlow)"/>
    <circle cx="85" cy="62" r="2.5" fill="#ffffff"/>
    <text x="98" y="66" fill="#00ff66" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="12" font-weight="700" letter-spacing="1.5">LIVE // OPEN TO WORK</text>

    <circle cx="740" cy="62" r="4" fill="#3b82f6" filter="url(#ledGlow)"/>
    <text x="645" y="66" fill="#8b9bb4" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="11" font-weight="600" letter-spacing="1">FRESHER ENG</text>

    <!-- Name & Badge -->
    <text x="85" y="120" fill="#ffffff" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="34" font-weight="900" letter-spacing="0.5">MARSHAL ALONE</text>
    <text x="85" y="152" fill="url(#goldPlate)" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="16" font-weight="700" letter-spacing="2">JAVA DEVELOPER • WEB &amp; FULL-STACK ENGINEER</text>

    <!-- Subtitle Spec -->
    <text x="85" y="185" fill="#8f9cae" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="13">
      [Core Java / Spring Boot REST APIs] • [Node.js / Express] • [HTML5 &amp; CSS3] • [SQL / Mongo]
    </text>

    <!-- Screen Glass Scanlines / Skeuomorphic Sheen -->
    <path d="M57 40 L450 40 L320 218 L57 218 Z" fill="white" opacity="0.015"/>
  </svg>

  <br/>

  <!-- ==================== TACTILE 3D SKEUOMORPHIC PUSH BUTTONS ==================== -->
  <a href="https://linkedin.com/in/marshal-alone">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" height="36" style="margin: 4px; box-shadow: 0 6px 0 #004182, 0 10px 15px rgba(0,0,0,0.4); border-radius: 6px;" />
  </a>
  &nbsp;
  <a href="mailto:marshal3869@gmail.com">
    <img src="https://img.shields.io/badge/Email-Direct_Ping-EA4335?style=for-the-badge&logo=gmail&logoColor=white" height="36" style="margin: 4px; box-shadow: 0 6px 0 #a82418, 0 10px 15px rgba(0,0,0,0.4); border-radius: 6px;" />
  </a>
  &nbsp;
  <a href="https://marshal-alone.github.io/Small-Projects/">
    <img src="https://img.shields.io/badge/Live_Arcade-Try_Apps-238636?style=for-the-badge&logo=githubpages&logoColor=white" height="36" style="margin: 4px; box-shadow: 0 6px 0 #14532d, 0 10px 15px rgba(0,0,0,0.4); border-radius: 6px;" />
  </a>

</div>

---

### 🎛️ Physical Hardware & Skill Console

<div align="center">
  <svg width="100%" max-width="840" height="230" viewBox="0 0 840 230" fill="none" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <!-- Tactile Card Inset -->
      <linearGradient id="cardPlate" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#222630"/>
        <stop offset="100%" stop-color="#171922"/>
      </linearGradient>

      <!-- Key Switch Gradient -->
      <linearGradient id="switchTop" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#363c4a"/>
        <stop offset="100%" stop-color="#232732"/>
      </linearGradient>

      <filter id="raisedKey" x="-10%" y="-10%" width="120%" height="130%">
        <feDropShadow dx="0" dy="4" stdDeviation="2" flood-color="#000000" flood-opacity="0.7"/>
        <feDropShadow dx="0" dy="1" stdDeviation="0" flood-color="#ffffff" flood-opacity="0.15"/>
      </filter>
    </defs>

    <!-- Main Deck Plate -->
    <rect x="10" y="10" width="820" height="210" rx="14" fill="url(#cardPlate)" stroke="#384050" stroke-width="2"/>
    
    <!-- 4 Tactile Channel Columns -->
    
    <!-- CHANNEL 1: JAVA & BACKEND -->
    <rect x="30" y="30" width="180" height="170" rx="10" fill="#12141c" stroke="#252a36" stroke-width="2"/>
    <rect x="42" y="42" width="156" height="30" rx="6" fill="#e76f51" filter="url(#raisedKey)"/>
    <text x="120" y="62" fill="#ffffff" font-family="sans-serif" font-size="12" font-weight="900" text-anchor="middle" letter-spacing="1">JAVA ENGINE</text>
    <text x="45" y="100" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Core Java (OOP)</text>
    <text x="45" y="125" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Spring Boot APIs</text>
    <text x="45" y="150" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Collections / DSA</text>
    <text x="45" y="175" fill="#818cf8" font-family="monospace" font-size="11">Maven • REST CRUD</text>

    <!-- CHANNEL 2: JAVASCRIPT & NODE -->
    <rect x="225" y="30" width="180" height="170" rx="10" fill="#12141c" stroke="#252a36" stroke-width="2"/>
    <rect x="237" y="42" width="156" height="30" rx="6" fill="#2a9d8f" filter="url(#raisedKey)"/>
    <text x="315" y="62" fill="#ffffff" font-family="sans-serif" font-size="12" font-weight="900" text-anchor="middle" letter-spacing="1">NODE &amp; RUNTIME</text>
    <text x="240" y="100" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Node.js Architecture</text>
    <text x="240" y="125" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Express.js Routes</text>
    <text x="240" y="150" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Asynchronous JS</text>
    <text x="240" y="175" fill="#34d399" font-family="monospace" font-size="11">WebSockets • APIs</text>

    <!-- CHANNEL 3: WEB & UI FOUNDRY -->
    <rect x="420" y="30" width="180" height="170" rx="10" fill="#12141c" stroke="#252a36" stroke-width="2"/>
    <rect x="432" y="42" width="156" height="30" rx="6" fill="#457b9d" filter="url(#raisedKey)"/>
    <text x="510" y="62" fill="#ffffff" font-family="sans-serif" font-size="12" font-weight="900" text-anchor="middle" letter-spacing="1">WEB &amp; FRONTEND</text>
    <text x="435" y="100" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Semantic HTML5</text>
    <text x="435" y="125" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● CSS3 Grid / Flex</text>
    <text x="435" y="150" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● DOM Events &amp; UI</text>
    <text x="435" y="175" fill="#38bdf8" font-family="monospace" font-size="11">Responsive Layouts</text>

    <!-- CHANNEL 4: DATA & TOOLING -->
    <rect x="615" y="30" width="180" height="170" rx="10" fill="#12141c" stroke="#252a36" stroke-width="2"/>
    <rect x="627" y="42" width="156" height="30" rx="6" fill="#3d405b" filter="url(#raisedKey)"/>
    <text x="705" y="62" fill="#ffffff" font-family="sans-serif" font-size="12" font-weight="900" text-anchor="middle" letter-spacing="1">DATA &amp; TOOLING</text>
    <text x="630" y="100" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● MySQL Relational</text>
    <text x="630" y="125" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● MongoDB NoSQL</text>
    <text x="630" y="150" fill="#f8fafc" font-family="monospace" font-size="12" font-weight="600">● Git / GitHub</text>
    <text x="630" y="175" fill="#fbbf24" font-family="monospace" font-size="11">Postman • VS Code</text>
  </svg>
</div>

---

### 🕹️ Built Projects Vault (100% Original Source)

<!-- Project 1: Farm-Connnect -->
<table>
  <tr>
    <td width="70" align="center" style="background: linear-gradient(180deg, #2b313d 0%, #171a22 100%); border-radius: 10px; border: 2px solid #4a5468; box-shadow: inset 0 1px 0 rgba(255,255,255,0.2), 0 6px 12px rgba(0,0,0,0.6);">
      <h2 style="margin:0;">🌾</h2>
    </td>
    <td>
      <h4><a href="https://github.com/Marshal-Alone/Farm-Connnect">Farm-Connnect</a> <code>[Major Full-Stack Platform]</code></h4>
      <p>Comprehensive agricultural marketplace and advisory ecosystem connecting farmers with equipment rentals and advisory services.</p>
      <b>Tech Stack:</b> <code>Node.js</code> <code>Full-Stack</code> <code>MongoDB</code> <code>Responsive UI</code>
    </td>
  </tr>
</table>

<!-- Project 2: PG-SPLIT -->
<table>
  <tr>
    <td width="70" align="center" style="background: linear-gradient(180deg, #2b313d 0%, #171a22 100%); border-radius: 10px; border: 2px solid #4a5468; box-shadow: inset 0 1px 0 rgba(255,255,255,0.2), 0 6px 12px rgba(0,0,0,0.6);">
      <h2 style="margin:0;">☕</h2>
    </td>
    <td>
      <h4><a href="https://github.com/Marshal-Alone/PG-SPLIT">PG-SPLIT</a> <code>[Spring Boot + Telegram Automation]</code></h4>
      <p>Automated room expense ledger with a live Telegram bot interface and web dashboard to calculate, log, and settle rent and utility balances.</p>
      <b>Tech Stack:</b> <code>Java</code> <code>Spring Boot</code> <code>Maven</code> <code>Telegram Bot API</code> <code>HTML/CSS</code>
    </td>
  </tr>
</table>

<!-- Project 3: Advance-Java -->
<table>
  <tr>
    <td width="70" align="center" style="background: linear-gradient(180deg, #2b313d 0%, #171a22 100%); border-radius: 10px; border: 2px solid #4a5468; box-shadow: inset 0 1px 0 rgba(255,255,255,0.2), 0 6px 12px rgba(0,0,0,0.6);">
      <h2 style="margin:0;">⚡</h2>
    </td>
    <td>
      <h4><a href="https://github.com/Marshal-Alone/Advance-Java">Advance-Java &amp; REST APIs</a> <code>[Backend Architecture]</code></h4>
      <p>Modular Spring Boot RESTful services demonstrating layered architecture (Controller, Service, Repository), exception handling, and full Postman validation suites.</p>
      <b>Tech Stack:</b> <code>Java</code> <code>Spring Boot</code> <code>Maven</code> <code>Postman</code>
    </td>
  </tr>
</table>

<!-- Project 4: Collaboard -->
<table>
  <tr>
    <td width="70" align="center" style="background: linear-gradient(180deg, #2b313d 0%, #171a22 100%); border-radius: 10px; border: 2px solid #4a5468; box-shadow: inset 0 1px 0 rgba(255,255,255,0.2), 0 6px 12px rgba(0,0,0,0.6);">
      <h2 style="margin:0;">🎨</h2>
    </td>
    <td>
      <h4><a href="https://github.com/Marshal-Alone/Collaboard-Mini-Project">Collaboard</a> <code>[Real-Time Collaborative Canvas]</code></h4>
      <p>Multi-client digital whiteboard enabling simultaneous real-time sketching, shape rendering, and instant state synchronization.</p>
      <b>Tech Stack:</b> <code>JavaScript</code> <code>HTML5 Canvas</code> <code>CSS3</code> <code>Node.js WebSockets</code>
    </td>
  </tr>
</table>

<!-- Project 5: Small-Projects Live Arcade -->
<table>
  <tr>
    <td width="70" align="center" style="background: linear-gradient(180deg, #2b313d 0%, #171a22 100%); border-radius: 10px; border: 2px solid #4a5468; box-shadow: inset 0 1px 0 rgba(255,255,255,0.2), 0 6px 12px rgba(0,0,0,0.6);">
      <h2 style="margin:0;">🕹️</h2>
    </td>
    <td>
      <h4><a href="https://marshal-alone.github.io/Small-Projects/">Interactive Web Playground</a> <code>[Live on GitHub Pages]</code></h4>
      <p>Live arcade of interactive applications testing DOM reactivity, async/await data consumption, and responsive CSS styling.</p>
      <b>Live Apps:</b> Currency Converter (Live Exchange API) • Weather Forecast • Space Adventurer • Simon Says • Tic Tac Toe
    </td>
  </tr>
</table>

---

### 📊 Real-Time Diagnostic Dashboard

<div align="center">
  <table border="0" style="background: transparent;">
    <tr>
      <td style="border: none;">
        <img src="https://github-readme-stats.vercel.app/api?username=Marshal-Alone&show_icons=true&theme=tokyonight&hide_border=false&border_color=3b4252&bg_color=181c24" alt="GitHub Stats" />
      </td>
      <td style="border: none;">
        <img src="https://github-readme-streak-stats.herokuapp.com/?user=Marshal-Alone&theme=tokyonight&hide_border=false&border_color=3b4252&background=181c24" alt="GitHub Streak" />
      </td>
    </tr>
  </table>
</div>

---

<div align="center">
  <svg width="100%" max-width="840" height="90" viewBox="0 0 840 90" fill="none" xmlns="http://www.w3.org/2000/svg">
    <rect x="15" y="10" width="810" height="70" rx="12" fill="#151821" stroke="#2d3342" stroke-width="2"/>
    <text x="420" y="42" fill="#e2e8f0" font-family="-apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif" font-size="14" font-weight="700" text-anchor="middle" letter-spacing="1">LET'S BUILD SOMETHING RELIABLE TOGETHER</text>
    <text x="420" y="62" fill="#00ff66" font-family="monospace" font-size="12" text-anchor="middle">Ready to contribute to your engineering team as a Fresher Developer</text>
  </svg>
</div>
