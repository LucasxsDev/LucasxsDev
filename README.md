<svg xmlns="http://www.w3.org/2000/svg" width="900" height="280" viewBox="0 0 900 280">
  <defs>
    <pattern id="grid" width="30" height="30" patternUnits="userSpaceOnUse">
      <path d="M 30 0 L 0 0 0 30" fill="none" stroke="#ffffff" stroke-opacity="0.04" stroke-width="1"/>
    </pattern>
    <clipPath id="reveal">
      <rect x="40" y="105" width="0" height="90">
        <animate attributeName="width" from="0" to="480" dur="1.4s" begin="0.5s" fill="freeze"/>
      </rect>
    </clipPath>
  </defs>

  <rect width="900" height="280" rx="14" fill="#000000"/>
  <rect width="900" height="280" rx="14" fill="url(#grid)"/>
  <rect x="0.5" y="0.5" width="899" height="279" rx="14" fill="none" stroke="#ffffff" stroke-opacity="0.18"/>

  <circle cx="34" cy="30" r="6" fill="#444444"/>
  <circle cx="54" cy="30" r="6" fill="#777777"/>
  <circle cx="74" cy="30" r="6" fill="#aaaaaa"/>
  <text x="450" y="35" text-anchor="middle" fill="#666666" font-size="13" font-family="Consolas, Menlo, 'Liberation Mono', monospace">lucas@github: ~</text>
  <line x1="0" y1="54" x2="900" y2="54" stroke="#ffffff" stroke-opacity="0.1"/>

  <text x="40" y="100" fill="#888888" font-size="18" font-family="Consolas, Menlo, 'Liberation Mono', monospace">$ whoami</text>

  <g clip-path="url(#reveal)">
    <text x="40" y="170" fill="#ffffff" font-size="64" font-weight="bold" textLength="470" lengthAdjust="spacingAndGlyphs" font-family="Consolas, Menlo, 'Liberation Mono', monospace">Lucas Eduardo</text>
  </g>

  <rect x="522" y="122" width="14" height="52" fill="#ffffff" opacity="0">
    <animate attributeName="opacity" values="1;0;1" dur="1s" begin="2s" repeatCount="indefinite"/>
  </rect>

  <text x="40" y="214" fill="#bbbbbb" font-size="20" opacity="0" font-family="Consolas, Menlo, 'Liberation Mono', monospace">
    estudante de programação | análise de dados
    <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="1.9s" fill="freeze"/>
  </text>

  <text x="40" y="250" fill="#666666" font-size="14" opacity="0" font-family="Consolas, Menlo, 'Liberation Mono', monospace">
    python · linux · git · postgresql · power bi · fastapi
    <animate attributeName="opacity" from="0" to="1" dur="0.6s" begin="2.3s" fill="freeze"/>
  </text>
</svg>
