# Pool-Tower
<p align="center">
  <svg width="600" height="120" viewBox="0 0 600 120" xmlns="http://www.w3.org/2000/svg">
    
    <defs>
      <!-- 金色漸層 -->
      <linearGradient id="gold" x1="0%" y1="0%" x2="100%">
        <stop offset="0%" stop-color="#FFD700"/>
        <stop offset="50%" stop-color="#FFF8DC"/>
        <stop offset="100%" stop-color="#FFC107"/>
      </linearGradient>

      <!-- 發光效果 -->
      <filter id="glow">
        <feGaussianBlur stdDeviation="3.5" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- 文字 -->
    <text x="50%" y="55%" text-anchor="middle"
          font-size="48"
          font-family="Orbitron, sans-serif"
          fill="url(#gold)"
          filter="url(#glow)">
      ✨ Pool Tower ✨
    </text>

  </svg>
</p>
