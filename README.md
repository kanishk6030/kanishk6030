<svg viewBox="0 0 700 270" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="termBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#131a24"/>
    </linearGradient>
  </defs>

  <rect width="700" height="270" rx="10" fill="url(#termBg)" stroke="#233047" stroke-width="1.5"/>

  <!-- title bar -->
  <rect width="700" height="34" rx="10" fill="#161b22"/>
  <rect y="24" width="700" height="10" fill="#161b22"/>
  <circle cx="22" cy="17" r="6" fill="#ff5f56"/>
  <circle cx="42" cy="17" r="6" fill="#ffbd2e"/>
  <circle cx="62" cy="17" r="6" fill="#27c93f"/>
  <text x="350" y="22" text-anchor="middle" fill="#8b96a8" font-family="Consolas, monospace" font-size="12">kanishk@agent-lab: ~/queryPilot</text>

  <g font-family="Consolas, 'Fira Code', monospace" font-size="14">
    <text x="24" y="66" fill="#38B2AC">
      $ <tspan fill="#e6edf3">python run_agent.py --query "optimize retrieval latency"</tspan>
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.02;0.06;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>

    <text x="24" y="94" fill="#7ee787">
      &gt; loading vector store ... <tspan fill="#e6edf3">done (312ms)</tspan>
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.12;0.16;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>

    <text x="24" y="122" fill="#7ee787">
      &gt; hybrid retrieval: <tspan fill="#e6edf3">BM25 + dense, k=12</tspan>
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.22;0.26;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>

    <text x="24" y="150" fill="#7ee787">
      &gt; reranking chunks ... <tspan fill="#e6edf3">9 kept</tspan>
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.32;0.36;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>

    <text x="24" y="178" fill="#7ee787">
      &gt; grounding check (LLM-as-judge) ... <tspan fill="#e6edf3">passed ✅</tspan>
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.44;0.48;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>

    <text x="24" y="206" fill="#f0883e">
      &gt; tracing run logged to <tspan fill="#e6edf3">LangSmith</tspan>
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.56;0.6;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>

    <text x="24" y="238" fill="#38B2AC" font-weight="700">
      ✔ response ready — building the next agent...
      <animate attributeName="opacity" values="0;0;1;1;1;0" keyTimes="0;0.68;0.72;0.85;0.95;1" dur="10s" repeatCount="indefinite"/>
    </text>
  </g>

  <!-- blinking cursor -->
  <rect x="24" y="246" width="9" height="14" fill="#38B2AC">
    <animate attributeName="opacity" values="1;1;0;0" dur="1s" repeatCount="indefinite"/>
  </rect>
</svg>
