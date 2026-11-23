<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 820 600" width="100%" height="100%">
  <defs>
    <linearGradient id="bg-grad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0a080d"/>
      <stop offset="50%" stop-color="#050305"/>
      <stop offset="100%" stop-color="#0d070a"/>
    </linearGradient>
    <filter id="card-shadow" x="-5%" y="-5%" width="110%" height="115%">
      <feDropShadow dx="0" dy="18" stdDeviation="25" flood-color="#000000" flood-opacity="0.8"/>
      <feDropShadow dx="0" dy="0" stdDeviation="15" flood-color="#ff2432" flood-opacity="0.12"/>
    </filter>
  </defs>

  <style>
    .code-text {
      font-family: 'JetBrains Mono', 'Fira Code', 'Cascadia Code', 'SF Mono', Menlo, Monaco, Consolas, monospace;
      font-size: 15px;
      font-weight: 500;
      line-height: 25px;
      letter-spacing: -0.01em;
    }
    .kw { fill: #ff5565; font-weight: 700; }
    .def { fill: #ffffff; font-weight: 700; }
    .type { fill: #7aa2f7; }
    .prop { fill: #7dcfff; font-weight: 600; }
    .str { fill: #ffdf5d; font-weight: 500; }
    .punc { fill: #abb2bf; }
  </style>

  <!-- Window Container -->
  <rect x="10" y="10" width="800" height="580" rx="14" fill="url(#bg-grad)" stroke="rgba(255, 36, 50, 0.28)" stroke-width="1.5" filter="url(#card-shadow)"/>

  <!-- Window Top Bar -->
  <path d="M 10 24 A 14 14 0 0 1 24 10 L 796 10 A 14 14 0 0 1 810 24 L 810 50 L 10 50 Z" fill="#11090d"/>
  <line x1="10" y1="50" x2="810" y2="50" stroke="rgba(255, 255, 255, 0.08)" stroke-width="1"/>

  <!-- macOS Window Dots -->
  <circle cx="34" cy="30" r="6" fill="#ff5f56"/>
  <circle cx="54" cy="30" r="6" fill="#ffbd2e"/>
  <circle cx="74" cy="30" r="6" fill="#27c93f"/>

  <!-- Top Bar Title -->
  <text x="410" y="34" font-family="'JetBrains Mono', monospace" font-size="12" fill="#8c7d81" text-anchor="middle" font-weight="600" letter-spacing="0.05em">fahadMB.ts — Developer Object</text>

  <!-- Live Status Badge -->
  <rect x="680" y="21" width="112" height="18" rx="9" fill="rgba(34, 197, 94, 0.12)" stroke="rgba(34, 197, 94, 0.35)" stroke-width="1"/>
  <circle cx="692" cy="30" r="3.5" fill="#22c55e"/>
  <text x="702" y="33" font-family="'JetBrains Mono', monospace" font-size="9" fill="#4ade80" font-weight="700" letter-spacing="0.08em">AVAILABLE</text>

  <!-- Code Body -->
  <g transform="translate(36, 82)" class="code-text">
    <text y="0"><tspan class="kw">const </tspan><tspan class="def">fahadMB</tspan><tspan class="punc">: </tspan><tspan class="type">Developer </tspan><tspan class="punc">= {</tspan></text>
    <text y="26"><tspan class="prop">&nbsp;&nbsp;name</tspan><tspan class="punc">: </tspan><tspan class="str">"Fahad MB"</tspan><tspan class="punc">,</tspan></text>
    <text y="52"><tspan class="prop">&nbsp;&nbsp;role</tspan><tspan class="punc">: </tspan><tspan class="str">"Software Developer &amp; Product Builder"</tspan><tspan class="punc">,</tspan></text>
    <text y="78"><tspan class="prop">&nbsp;&nbsp;background</tspan><tspan class="punc">: </tspan><tspan class="str">"Biology ➔ Software Engineering"</tspan><tspan class="punc">,</tspan></text>
    <text y="104"><tspan class="prop">&nbsp;&nbsp;currentFocus</tspan><tspan class="punc">: </tspan><tspan class="str">"High-Performance React &amp; Full-Stack Architectures"</tspan><tspan class="punc">,</tspan></text>
    <text y="130"><tspan class="prop">&nbsp;&nbsp;philosophy</tspan><tspan class="punc">: [</tspan></text>
    <text y="156"><tspan class="str">&nbsp;&nbsp;&nbsp;&nbsp;"Clean, maintainable component systems"</tspan><tspan class="punc">,</tspan></text>
    <text y="182"><tspan class="str">&nbsp;&nbsp;&nbsp;&nbsp;"Sub-second web performance &amp; Core Web Vitals"</tspan><tspan class="punc">,</tspan></text>
    <text y="208"><tspan class="str">&nbsp;&nbsp;&nbsp;&nbsp;"Solving real-world problems with considered software"</tspan></text>
    <text y="234"><tspan class="punc">&nbsp;&nbsp;],</tspan></text>
    <text y="260"><tspan class="prop">&nbsp;&nbsp;stack</tspan><tspan class="punc">: {</tspan></text>
    <text y="286"><tspan class="prop">&nbsp;&nbsp;&nbsp;&nbsp;languages</tspan><tspan class="punc">: [</tspan><tspan class="str">"TypeScript"</tspan><tspan class="punc">, </tspan><tspan class="str">"JavaScript"</tspan><tspan class="punc">, </tspan><tspan class="str">"SQL"</tspan><tspan class="punc">, </tspan><tspan class="str">"HTML5/CSS3"</tspan><tspan class="punc">],</tspan></text>
    <text y="312"><tspan class="prop">&nbsp;&nbsp;&nbsp;&nbsp;frontend</tspan><tspan class="punc">: [</tspan><tspan class="str">"React 19"</tspan><tspan class="punc">, </tspan><tspan class="str">"Next.js"</tspan><tspan class="punc">, </tspan><tspan class="str">"Tailwind CSS"</tspan><tspan class="punc">, </tspan><tspan class="str">"Motion"</tspan><tspan class="punc">, </tspan><tspan class="str">"Vite"</tspan><tspan class="punc">],</tspan></text>
    <text y="338"><tspan class="prop">&nbsp;&nbsp;&nbsp;&nbsp;backend</tspan><tspan class="punc">: [</tspan><tspan class="str">"Node.js"</tspan><tspan class="punc">, </tspan><tspan class="str">"Express.js"</tspan><tspan class="punc">, </tspan><tspan class="str">"REST APIs"</tspan><tspan class="punc">, </tspan><tspan class="str">"WebSockets"</tspan><tspan class="punc">],</tspan></text>
    <text y="364"><tspan class="prop">&nbsp;&nbsp;&nbsp;&nbsp;databases</tspan><tspan class="punc">: [</tspan><tspan class="str">"PostgreSQL"</tspan><tspan class="punc">, </tspan><tspan class="str">"MongoDB"</tspan><tspan class="punc">, </tspan><tspan class="str">"Redis"</tspan><tspan class="punc">, </tspan><tspan class="str">"Supabase"</tspan><tspan class="punc">],</tspan></text>
    <text y="390"><tspan class="prop">&nbsp;&nbsp;&nbsp;&nbsp;tools</tspan><tspan class="punc">: [</tspan><tspan class="str">"Git &amp; GitHub"</tspan><tspan class="punc">, </tspan><tspan class="str">"Docker"</tspan><tspan class="punc">, </tspan><tspan class="str">"VS Code"</tspan><tspan class="punc">, </tspan><tspan class="str">"Figma"</tspan><tspan class="punc">]</tspan></text>
    <text y="416"><tspan class="punc">&nbsp;&nbsp;},</tspan></text>
    <text y="442"><tspan class="prop">&nbsp;&nbsp;status</tspan><tspan class="punc">: </tspan><tspan class="str">"Available for engineering collaborations &amp; opportunities"</tspan></text>
    <text y="468"><tspan class="punc">};</tspan></text>
  </g>
</svg>
