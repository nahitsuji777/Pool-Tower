# Pool-Tower
<p align="center">
  <svg width="600" height="120" xmlns="http://www.w3.org/2000/svg">

    <defs>
      <linearGradient id="goldAnim" x1="0%" y1="0%" x2="100%">
        <stop offset="0%" stop-color="#FFD700">
          <animate attributeName="offset" values="0;1;0" dur="3s" repeatCount="indefinite"/>
        </stop>
        <stop offset="50%" stop-color="#FFF8DC"/>
        <stop offset="100%" stop-color="#FFC107"/>
      </linearGradient>

      <filter id="glow">
        <feGaussianBlur stdDeviation="4" result="blur"/>
        <feMerge>
          <feMergeNode in="blur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <text x="50%" y="60%" text-anchor="middle"
          font-size="50"
          font-family="Orbitron, sans-serif"
          fill="url(#goldAnim)"
          filter="url(#glow)">
      ⚡ Pool Tower ⚡
    </text>

  </svg>
</p>
</p>
