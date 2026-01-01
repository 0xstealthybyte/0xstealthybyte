<p align="center">
  <svg width="800" height="300" viewBox="0 0 800 300" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .node { fill: #1a1a1a; stroke: #39FF14; stroke-width: 2; }
      .signal { stroke: #39FF14; stroke-width: 2; stroke-dasharray: 10, 50; animation: flow 2s linear infinite; }
      .pulse { animation: pulse-node 1.5s ease-in-out infinite; transform-origin: center; }
      
      @keyframes flow {
        from { stroke-dashoffset: 60; }
        to { stroke-dashoffset: 0; }
      }
      
      @keyframes pulse-node {
        0%, 100% { r: 4; fill: #1a1a1a; filter: drop-shadow(0 0 2px #39FF14); }
        50% { r: 6; fill: #39FF14; filter: drop-shadow(0 0 8px #39FF14); }
      }
    </style>

    <path d="M100 150 L300 100" class="signal" />
    <path d="M100 150 L300 200" class="signal" />
    <path d="M300 100 L500 150" class="signal" />
    <path d="M300 200 L500 150" class="signal" />
    <path d="M500 150 L700 150" class="signal" />

    <circle cx="100" cy="150" r="5" class="node pulse" style="animation-delay: 0s;" />
    <circle cx="300" cy="100" r="5" class="node pulse" style="animation-delay: 0.5s;" />
    <circle cx="300" cy="200" r="5" class="node pulse" style="animation-delay: 0.8s;" />
    <circle cx="500" cy="150" r="5" class="node pulse" style="animation-delay: 1.2s;" />
    <circle cx="700" cy="150" r="5" class="node pulse" style="animation-delay: 1.8s;" />

    <text x="400" y="280" text-anchor="middle" fill="#39FF14" font-family="monospace" font-size="14">
      NEURAL_LOGIC_ENGINE_ACTIVE: CREATIVITY_STIMULATED
    </text>
  </svg>
</p>
