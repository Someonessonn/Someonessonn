<img width="736" height="736" alt="dottore widget 𝜗𝜚 ࣪ ࣭ 𓏲" src="https://github.com/user-attachments/assets/96aaba71-0573-4168-a893-d72701257fec" />
<svg xmlns="http://w3.org" viewBox="0 0 600 120" width="100%" height="100%">
  <style>
    .text-base {
      font-family: 'Courier New', Courier, monospace;
      font-weight: bold;
      fill: #5CB0C0; /* Dottore Teal */
    }

    /* Controls which line shows up */
    .line-1 { animation: showLine1 8s infinite; }
    .line-2 { animation: showLine2 8s infinite; }
    .cursor { animation: blink 0.8s infinite; fill: #5CB0C0; }

    @keyframes showLine1 {
      0%, 45% { opacity: 1; }
      50%, 100% { opacity: 0; }
    }

    @keyframes showLine2 {
      0%, 45% { opacity: 0; }
      50%, 95% { opacity: 1; }
      100% { opacity: 0; }
    }

    @keyframes blink {
      0%, 49% { opacity: 1; }
      50%, 100% { opacity: 0; }
    }
  </style>

  <!-- Dark Mode Borderless Background -->
  <rect width="100%" height="100%" fill="#152238" rx="6"/>

  <!-- First Sentence Layer -->
  <g class="line-1">
    <text x="50" y="65" class="text-base" font-size="24">So+don't+keep+the+devil+waiting</text>
    <!-- Blinking Cursor at the end of line 1 -->
    <rect x="495" y="47" width="12" height="22" class="cursor" />
  </g>

  <!-- Second Sentence Layer -->
  <g class="line-2">
    <text x="50" y="65" class="text-base" font-size="24">friend..</text>
    <!-- Blinking Cursor at the end of line 2 -->
    <rect x="165" y="47" width="12" height="22" class="cursor" />
  </g>
</svg>
