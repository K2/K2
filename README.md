![matrix-demo](https://github.com/user-attachments/assets/69ae8d13-5e2c-4b60-86ac-da59406d1d74)
<svg xmlns="http://www.w3.org/2000/svg" width="966" height="500" viewBox="0 0 966 500" style="width:100%;height:auto;" aria-label="Animated neon glyph waterfall" role="img" focusable="true">
  <style>
#matrixRain text {
  will-change: transform, opacity;
  transform-box: fill-box;
  transform-origin: center;
}
</style>
  <defs>
    <linearGradient id="gradGlow" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="500">
      <stop offset="0%" stop-color="#9AFF9A" />
      <stop offset="60%" stop-color="#31FF6B" />
      <stop offset="100%" stop-color="#00BF47" />
    </linearGradient>
    <linearGradient id="gradBolt" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="500">
      <stop offset="0%" stop-color="#FFB347" />
      <stop offset="60%" stop-color="#FF6A00" />
      <stop offset="100%" stop-color="#FF2400" />
    </linearGradient>
    <filter id="softGlow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="2.2" result="blur" />
      <feMerge>
        <feMergeNode in="blur" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <filter id="trailGlow" x="-40%" y="-40%" width="180%" height="220%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="0 7" result="trail" />
      <feColorMatrix in="trail" type="matrix" values="1 0 0 0 0&#10;0 1 0 0 0&#10;0 0 1 0 0&#10;0 0 0 0.6 0" result="trailFade" />
      <feMerge>
        <feMergeNode in="trailFade" />
        <feMergeNode in="SourceGraphic" />
      </feMerge>
    </filter>
    <radialGradient id="vignette" cx="50%" cy="50%" r="65%">
      <stop offset="0%" stop-color="rgba(0,0,0,0)" />
      <stop offset="100%" stop-color="rgba(0,0,0,0.55)" />
    </radialGradient>
    <radialGradient id="flashGlow" cx="50%" cy="50%" r="75%">
      <stop offset="0%" stop-color="#FFB347" stop-opacity="0.85" />
      <stop offset="55%" stop-color="#FF5F1F" stop-opacity="0.45" />
      <stop offset="100%" stop-color="#FF2400" stop-opacity="0" />
    </radialGradient>
  </defs>
  <rect x="0" y="0" width="966" height="500" fill="#050507" />
  <rect x="0" y="0" width="966" height="500" fill="url(#vignette)" />
  <g id="matrixRain" opacity="0.95" font-family="system-ui, sans-serif" letter-spacing="2">
    <g transform="translate(0,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">A<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="5.79s" begin="-1.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-0.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.78s" begin="-1.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-0.5s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.58s" begin="-1.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-1.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.95s" begin="-1.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-0.76s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">7<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.37s" begin="-1.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-0.54s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-1.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.31s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Ω<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.25s" begin="-1.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.41s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-1.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.47s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">Ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.04s" begin="-1.68s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.38s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.78s" begin="-1.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.02s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">@<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.39s" begin="-1.75s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-1.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.23s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">Z<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.27s" begin="-1.82s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.12s" begin="-1.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-2.74s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">É<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.06s" begin="-1.89s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-0.84s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.28s" begin="-1.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-0.94s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">?<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.25s" begin="-1.96s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.46s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.78s" begin="-1.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-0.95s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">δ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.04s" begin="-2.03s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.95s" begin="-1.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∞<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.39s" begin="-2.1s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.12s" begin="-1.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.76s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">K2<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.27s" begin="-2.17s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.97s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.28s" begin="-1.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.92s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∑AI<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.06s" begin="-2.24s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.94s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.78s" begin="-1.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.47s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">ß<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.86s" begin="-2.31s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.95s" begin="-1.95s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.68s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">ø<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.73s" begin="-2.38s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-1.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.09s" begin="-2.45s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-2.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.39s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.27s" begin="-2.52s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.02s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.78s" begin="-2.07s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.4s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">#<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.06s" begin="-2.59s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-2.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.86s" begin="-2.66s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.12s" begin="-2.16s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.21s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Þ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.73s" begin="-2.73s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.53s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.28s" begin="-2.2s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¡<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.09s" begin="-2.8s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.78s" begin="-2.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.92s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ψ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.88s" begin="-2.87s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.95s" begin="-2.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.13s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(87.82,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.39s" begin="-0.98s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-1.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5s" begin="-0.91s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-0.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">M<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.36s" begin="-1.05s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-0.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-0.95s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.4s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">鶴<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.21s" begin="-1.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.52s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-0.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">λ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="9.17s" begin="-1.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.49s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.79s" begin="-1.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.11s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">Ü<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="10.13s" begin="-1.26s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.08s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.32s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">鶴<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.03s" begin="-1.33s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-1.12s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-2.82s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-300)">Q<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.99s" begin="-1.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-0.95s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.59s" begin="-1.16s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.03s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.21s" begin="-1.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.57s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.79s" begin="-1.2s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">3<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="9.17s" begin="-1.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.29s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">η<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="10.13s" begin="-1.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.2s" begin="-1.29s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.85s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">≈<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.03s" begin="-1.68s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.08s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-1.33s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.99s" begin="-1.75s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.05s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.79s" begin="-1.37s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">#<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.95s" begin="-1.82s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5s" begin="-1.41s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.77s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ξ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.8s" begin="-1.89s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-1.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Þ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="9.76s" begin="-1.96s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.51s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-1.5s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¡<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.03s" begin="-2.03s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.13s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.79s" begin="-1.54s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">ψ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.99s" begin="-2.1s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.58s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.74s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">Ł<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.95s" begin="-2.17s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-1.62s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¿<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8.8s" begin="-2.24s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.64s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.59s" begin="-1.66s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">K<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="9.76s" begin="-2.31s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.61s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.79s" begin="-1.71s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.01s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">κ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.76s" begin="-2.38s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.75s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.21s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.62s" begin="-2.45s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.2s" begin="-1.79s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.72s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(175.64,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">C<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.16s" begin="-2.66s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-0.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-2.52s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.49s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">S<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.02s" begin="-2.73s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.63s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.42s" begin="-2.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.64s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">%<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.91s" begin="-2.8s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.61s" begin="-2.6s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">Ψ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.79s" begin="-2.87s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.79s" begin="-2.64s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.41s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">Í<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.66s" begin="-2.94s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-2.68s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-2.91s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">5<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.82s" begin="-3.01s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.06s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.42s" begin="-2.73s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.12s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-240)">T<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.02s" begin="-3.08s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.68s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.61s" begin="-2.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.12s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">χ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.91s" begin="-3.15s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.79s" begin="-2.81s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">8<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.79s" begin="-3.22s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-2.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.94s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">κ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.66s" begin="-3.29s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.19s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.42s" begin="-2.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">∈<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.82s" begin="-3.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.16s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.61s" begin="-2.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">Þ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.7s" begin="-3.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.79s" begin="-2.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.85s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¡<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.56s" begin="-3.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-3.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">ψ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.45s" begin="-3.57s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.62s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.42s" begin="-3.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.57s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">Ł<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.66s" begin="-3.64s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.24s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.61s" begin="-3.1s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.57s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¿<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.82s" begin="-3.71s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.79s" begin="-3.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.83s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">K<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.7s" begin="-3.78s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-3.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">κ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.56s" begin="-3.85s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.75s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.42s" begin="-3.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.45s" begin="-3.92s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.72s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.61s" begin="-3.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.1s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">2<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.34s" begin="-3.99s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.79s" begin="-3.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">0<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.47s" begin="-4.06s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-3.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.81s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">Ω<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.36s" begin="-4.13s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.18s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.42s" begin="-3.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.01s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(263.45,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">D<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.44s" begin="-0.94s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.74s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.29s" begin="-0.72s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.73s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">L<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.46s" begin="-1.01s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.71s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.51s" begin="-0.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.29s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">$<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.47s" begin="-1.08s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.86s" begin="-0.81s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.49s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">β<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.32s" begin="-1.15s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.08s" begin="-0.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">Ó<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="10.34s" begin="-1.22s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.17s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.29s" begin="-0.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.21s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">1<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.44s" begin="-1.29s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.51s" begin="-0.93s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.21s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-320)">P<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.46s" begin="-1.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.86s" begin="-0.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.47s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">Ξ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.47s" begin="-1.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.08s" begin="-1.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.02s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">6<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.32s" begin="-1.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.3s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.29s" begin="-1.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">ϑ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="10.34s" begin="-1.57s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.27s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.51s" begin="-1.1s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.74s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">∮<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.22s" begin="-1.64s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.86s" begin="-1.14s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.94s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">Ł<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.06s" begin="-1.71s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.08s" begin="-1.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">¿<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.08s" begin="-1.78s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.73s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.29s" begin="-1.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">K<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.32s" begin="-1.85s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.35s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.51s" begin="-1.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.66s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">κ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="10.34s" begin="-1.92s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.86s" begin="-1.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.92s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.22s" begin="-1.99s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.08s" begin="-1.35s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.47s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">2<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.06s" begin="-2.06s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.86s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.29s" begin="-1.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.63s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">0<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.08s" begin="-2.13s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.83s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.51s" begin="-1.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ω<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="10.1s" begin="-2.2s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.86s" begin="-1.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.39s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">ß<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.94s" begin="-2.27s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.08s" begin="-1.52s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.9s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">ø<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.83s" begin="-2.34s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.29s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.29s" begin="-1.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.1s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Σ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.06s" begin="-2.41s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.91s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.51s" begin="-1.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.11s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(351.27,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">E<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="5.94s" begin="-2.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.82s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.69s" begin="-2.33s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">V<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.72s" begin="-2.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.85s" begin="-2.37s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.58s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">0<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.6s" begin="-2.76s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.02s" begin="-2.42s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Γ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.37s" begin="-2.83s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.28s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.18s" begin="-2.46s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.29s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">Ú<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.55s" begin="-2.9s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.69s" begin="-2.5s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">2<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="5.94s" begin="-2.97s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.85s" begin="-2.54s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">F<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.72s" begin="-3.04s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.54s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.02s" begin="-2.58s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.11s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Ζ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.6s" begin="-3.11s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.41s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.18s" begin="-2.63s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">4<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.37s" begin="-3.18s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.38s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.69s" begin="-2.67s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.82s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">θ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.14s" begin="-3.25s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.85s" begin="-2.71s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.03s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∟<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="5.65s" begin="-3.32s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.02s" begin="-2.75s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">κ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.42s" begin="-3.39s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.84s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.18s" begin="-2.79s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.74s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.6s" begin="-3.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.46s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.69s" begin="-2.84s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.75s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">2<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.37s" begin="-3.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.85s" begin="-2.88s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">0<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.14s" begin="-3.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.02s" begin="-2.92s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ω<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="5.65s" begin="-3.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.97s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.18s" begin="-2.96s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.72s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">ß<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.42s" begin="-3.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.94s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.69s" begin="-3s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">ø<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.19s" begin="-3.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.85s" begin="-3.05s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.07s" begin="-3.88s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.02s" begin="-3.09s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.85s" begin="-3.95s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.18s" begin="-3.13s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.19s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">#<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="5.65s" begin="-4.02s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.02s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.69s" begin="-3.17s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="6.42s" begin="-4.09s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.85s" begin="-3.21s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.45s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(439.09,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">F<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.83s" begin="-4.1s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.68s" begin="-3.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.67s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">X<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.66s" begin="-4.17s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.92s" begin="-3.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">!<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.76s" begin="-4.24s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.39s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.22s" begin="-3.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">Φ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.01s" begin="-4.31s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.45s" begin="-3.87s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.39s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">Å<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="11.1s" begin="-4.38s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.68s" begin="-3.91s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.64s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">%<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.83s" begin="-4.45s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.92s" begin="-3.95s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-300)">N<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.66s" begin="-4.52s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.52s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.22s" begin="-3.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">Π<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.76s" begin="-4.59s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.49s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.45s" begin="-4.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.91s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">œ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.85s" begin="-4.66s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.68s" begin="-4.08s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.12s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">μ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.68s" begin="-4.73s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.92s" begin="-4.12s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">∴<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.41s" begin="-4.8s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.95s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.22s" begin="-4.16s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.83s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">2<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.66s" begin="-4.87s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.57s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.45s" begin="-4.2s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">0<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.76s" begin="-4.94s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.68s" begin="-4.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Ω<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.85s" begin="-5.01s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.92s" begin="-4.29s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">K2<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.68s" begin="-5.08s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.08s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.22s" begin="-4.33s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.41s" begin="-5.15s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.05s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.45s" begin="-4.37s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">ø<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.5s" begin="-5.22s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.68s" begin="-4.41s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.57s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Σ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.34s" begin="-5.29s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.92s" begin="-4.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.07s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.43s" begin="-5.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.51s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.22s" begin="-4.5s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.28s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">#<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="10.68s" begin="-5.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.13s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.45s" begin="-4.54s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.28s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ξ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.41s" begin="-5.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.68s" begin="-4.58s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Þ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.5s" begin="-5.57s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.92s" begin="-4.62s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.1s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(526.91,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">G<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.06s" begin="-1.28s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="3.96s" begin="-0.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.26s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Y<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.89s" begin="-1.35s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.14s" begin="-0.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.47s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">@<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.08s" begin="-1.42s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-0.93s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Υ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.91s" begin="-1.49s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.49s" begin="-0.97s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.73s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">Í<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.74s" begin="-1.56s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="3.96s" begin="-1.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.29s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ρ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.06s" begin="-1.63s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.63s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.14s" begin="-1.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.44s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">Æ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.89s" begin="-1.7s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.31s" begin="-1.1s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">W<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.72s" begin="-1.77s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.49s" begin="-1.14s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.21s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ħ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.59s" begin="-1.84s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-1.18s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-1.91s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.06s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.14s" begin="-1.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.92s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∠<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.06s" begin="-1.98s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.68s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.31s" begin="-1.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.92s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">ø<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.89s" begin="-2.05s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-1.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.72s" begin="-2.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="3.96s" begin="-1.35s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.74s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.59s" begin="-2.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.19s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.14s" begin="-1.39s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">#<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-2.26s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.16s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-1.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.7s" begin="-2.33s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.49s" begin="-1.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Þ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.57s" begin="-2.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="3.96s" begin="-1.52s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¡<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.4s" begin="-2.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.62s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.14s" begin="-1.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.37s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ψ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.59s" begin="-2.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.24s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.31s" begin="-1.6s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.37s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">Ł<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-2.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.49s" begin="-1.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.63s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¿<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.7s" begin="-2.68s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-1.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.57s" begin="-2.75s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.75s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.14s" begin="-1.73s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.34s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(614.73,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-280)">ñ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.25s" begin="-2.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.61s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.9s" begin="-1.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">T<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.47s" begin="-2.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.1s" begin="-1.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-280)">8<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.41s" begin="-2.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.5s" begin="-1.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.82s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">ϖ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="9.35s" begin="-2.57s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.87s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.7s" begin="-1.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-280)">Ê<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="9.21s" begin="-2.64s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.74s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.9s" begin="-2.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.53s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">σ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.25s" begin="-2.71s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.71s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-2.07s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-280)">Ğ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.19s" begin="-2.78s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.5s" begin="-2.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.29s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">V<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.05s" begin="-2.85s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.7s" begin="-2.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-280)">ň<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.99s" begin="-2.92s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.17s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.9s" begin="-2.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.01s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-280)">ς<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="9.21s" begin="-2.99s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="5.1s" begin="-2.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.01s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-280)">∵<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.25s" begin="-3.06s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.5s" begin="-2.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="22" transform="translate(0,-280)">Σ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.19s" begin="-3.13s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.7s" begin="-2.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.82s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="18" transform="translate(0,-280)">ñ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.05s" begin="-3.2s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.3s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.9s" begin="-2.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">#<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.99s" begin="-3.27s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.27s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.1s" begin="-2.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="18" transform="translate(0,-280)">ξ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="9.93s" begin="-3.34s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.5s" begin="-2.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.74s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">Þ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.89s" begin="-3.41s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.7s" begin="-2.49s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.25s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">¡<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.83s" begin="-3.48s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.73s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.9s" begin="-2.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">ψ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.05s" begin="-3.55s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.35s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-2.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.46s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="20" transform="translate(0,-280)">Ł<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.99s" begin="-3.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.5s" begin="-2.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.72s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">¿<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="9.93s" begin="-3.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.7s" begin="-2.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">K<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.89s" begin="-3.76s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.86s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.9s" begin="-2.7s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.43s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="20" transform="translate(0,-280)">κ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.83s" begin="-3.83s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.83s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="5.1s" begin="-2.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.98s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(702.55,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">I<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="5.92s" begin="-4.14s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="3.87s" begin="-3.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">P<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.73s" begin="-4.21s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.04s" begin="-3.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.91s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">6<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.54s" begin="-4.28s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.98s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-3.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.46s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">ϱ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.42s" begin="-4.35s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.85s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.39s" begin="-3.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">Ë<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.23s" begin="-4.42s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.82s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.87s" begin="-3.73s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">ϙ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.55s" begin="-4.49s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.04s" begin="-3.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-240)">Ð<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.42s" begin="-4.56s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.21s" begin="-3.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">U<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.23s" begin="-4.63s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.28s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.39s" begin="-3.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">ŕ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.42s" begin="-4.7s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.87s" begin="-3.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.1s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.23s" begin="-4.77s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.04s" begin="-3.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">∗<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.55s" begin="-4.84s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.54s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.21s" begin="-3.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.91s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¡<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.42s" begin="-4.91s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.41s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.39s" begin="-4.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.07s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">ψ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.23s" begin="-4.98s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.38s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="3.87s" begin="-4.07s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">Ł<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.04s" begin="-5.05s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.04s" begin="-4.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.83s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¿<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.92s" begin="-5.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-4.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.34s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">K<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.23s" begin="-5.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.84s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.39s" begin="-4.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">κ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.42s" begin="-5.26s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.46s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.87s" begin="-4.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.55s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.23s" begin="-5.33s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.04s" begin="-4.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">2<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.04s" begin="-5.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.21s" begin="-4.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">0<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.92s" begin="-5.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.97s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.39s" begin="-4.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.52s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">Ω<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="6.23s" begin="-5.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.94s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.87s" begin="-4.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.07s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">ß<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.05s" begin="-5.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.04s" begin="-4.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.28s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(790.36,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">¿<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.12s" begin="-3.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.49s" begin="-2.47s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">N<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.18s" begin="-3.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.09s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.71s" begin="-2.51s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.55s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">5<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.01s" begin="-3.26s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.96s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.04s" begin="-2.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">ϗ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="10.07s" begin="-3.33s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.93s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.26s" begin="-2.6s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.26s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">Ę<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="11.12s" begin="-3.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.49s" begin="-2.64s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.47s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">ϛ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.71s" begin="-3.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.71s" begin="-2.68s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-320)">Ç<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.77s" begin="-3.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.39s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.04s" begin="-2.72s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">R<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.01s" begin="-3.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.26s" begin="-2.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.19s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">ś<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="10.07s" begin="-3.68s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.49s" begin="-2.81s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.44s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">ϟ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="11.12s" begin="-3.75s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.71s" begin="-2.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">∯<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.71s" begin="-3.82s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.52s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.04s" begin="-2.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">¿<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.77s" begin="-3.89s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.49s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.26s" begin="-2.93s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">K<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.83s" begin="-3.96s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.49s" begin="-2.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.92s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">κ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.66s" begin="-4.03s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.71s" begin="-3.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="10.72s" begin="-4.1s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.95s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.04s" begin="-3.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.63s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">2<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.71s" begin="-4.17s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.57s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.26s" begin="-3.1s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.64s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">0<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.77s" begin="-4.24s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.49s" begin="-3.14s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ω<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.83s" begin="-4.31s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.71s" begin="-3.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">ß<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9.66s" begin="-4.38s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.08s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.04s" begin="-3.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">ø<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="10.72s" begin="-4.45s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.05s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.26s" begin="-3.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Σ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.53s" begin="-4.52s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.49s" begin="-3.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.37s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">ñ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.36s" begin="-4.59s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.71s" begin="-3.35s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.87s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(878.18,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.85s" begin="-2.7s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.05s" begin="-1.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.64s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">C<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.72s" begin="-2.77s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.07s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-2.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">4<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.57s" begin="-2.84s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.04s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.41s" begin="-2.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.35s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Ϥ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-2.91s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.59s" begin="-2.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.56s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">Ě<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.29s" begin="-2.98s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.05s" begin="-2.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.06s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ϝ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.52s" begin="-3.05s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-2.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">Ō<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.72s" begin="-3.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.41s" begin="-2.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.28s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">S<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.57s" begin="-3.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.59s" begin="-2.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.53s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ž<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-3.26s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.05s" begin="-2.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">ϡ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.29s" begin="-3.33s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.63s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-2.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.24s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∼<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.52s" begin="-3.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.41s" begin="-2.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.37s" begin="-3.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.59s" begin="-2.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.01s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">κ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.24s" begin="-3.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.05s" begin="-2.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.09s" begin="-3.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.06s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-2.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.72s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">2<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.29s" begin="-3.68s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.68s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.41s" begin="-2.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.72s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">0<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.52s" begin="-3.75s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.59s" begin="-2.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ω<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.37s" begin="-3.82s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.05s" begin="-2.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">K2<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.24s" begin="-3.89s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.19s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-2.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">ß<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.09s" begin="-3.96s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.16s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.41s" begin="-2.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.25s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">ø<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.94s" begin="-4.03s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.59s" begin="-2.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="6.2s" begin="-4.1s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.05s" begin="-2.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.96s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="7.05s" begin="-4.17s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.62s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-2.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.17s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(966,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ψ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.16s" begin="-4.48s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.18s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.1s" begin="-3.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.88s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">E<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.14s" begin="-4.55s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.15s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.3s" begin="-3.73s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.44s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">3<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.12s" begin="-4.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.68s" begin="-3.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.65s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">Θ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.97s" begin="-4.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.89s" begin="-3.81s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.15s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">Á<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.95s" begin="-4.76s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.61s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.1s" begin="-3.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Δ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.16s" begin="-4.83s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.3s" begin="-3.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-300)">Š<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.14s" begin="-4.9s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.68s" begin="-3.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">T<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.12s" begin="-4.97s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.87s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.89s" begin="-3.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.97s" begin="-5.04s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.74s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-4.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">β<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.95s" begin="-5.11s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.71s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.3s" begin="-4.07s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">⊕<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.92s" begin="-5.18s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.68s" begin="-4.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.09s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">2<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.77s" begin="-5.25s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.89s" begin="-4.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">0<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.75s" begin="-5.32s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.17s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.1s" begin="-4.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.81s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Ω<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.97s" begin="-5.39s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.3s" begin="-4.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.81s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">∑AI<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.95s" begin="-5.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.68s" begin="-4.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.07s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.92s" begin="-5.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.89s" begin="-4.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">ø<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.77s" begin="-5.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.3s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.1s" begin="-4.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Σ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.75s" begin="-5.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.27s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.3s" begin="-4.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.34s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.73s" begin="-5.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.68s" begin="-4.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">#<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.58s" begin="-5.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.89s" begin="-4.49s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.05s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ξ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.54s" begin="-5.88s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.73s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-4.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.25s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Þ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.77s" begin="-5.95s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.35s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.3s" begin="-4.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.26s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(0,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">A<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.19s" begin="-2.71s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.26s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.23s" begin="-2.14s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.53s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.12s" begin="-2.78s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.42s" begin="-2.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.73s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">7<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.98s" begin="-2.85s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-2.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.24s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Ω<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.91s" begin="-2.92s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.72s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.8s" begin="-2.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">Ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="9.13s" begin="-2.99s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.23s" begin="-2.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">@<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.19s" begin="-3.06s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.42s" begin="-2.35s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">Z<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.12s" begin="-3.13s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.98s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.61s" begin="-2.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.26s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">É<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.98s" begin="-3.2s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.85s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.8s" begin="-2.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">?<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.91s" begin="-3.27s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.82s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-2.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">δ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="9.85s" begin="-3.34s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.42s" begin="-2.52s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.18s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∞<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.83s" begin="-3.41s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.61s" begin="-2.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.76s" begin="-3.48s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.28s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.8s" begin="-2.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.98s" begin="-3.55s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.23s" begin="-2.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.9s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">#<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.91s" begin="-3.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.42s" begin="-2.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="9.85s" begin="-3.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.54s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-2.73s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Þ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.83s" begin="-3.76s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.41s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.8s" begin="-2.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.87s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¡<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.76s" begin="-3.83s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.38s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.23s" begin="-2.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ψ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.7s" begin="-3.9s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.42s" begin="-2.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.63s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">Ł<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="8.55s" begin="-3.97s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.61s" begin="-2.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.14s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¿<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="9.49s" begin="-4.04s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.84s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.8s" begin="-2.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.34s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="6.83s" begin="-4.11s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.46s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-2.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.35s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">κ<animateTransform attributeName="transform" type="translate" values="0,-260;0,540" dur="7.76s" begin="-4.18s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.42s" begin="-3.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.6s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(90.01,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.37s" begin="-3.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.3s" begin="-2.59s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.82s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">M<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.25s" begin="-3.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-2.64s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">鶴<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.03s" begin="-3.88s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.83s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-2.68s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.53s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">λ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.22s" begin="-3.95s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.12s" begin="-2.72s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.54s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">Ü<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="8s" begin="-4.02s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-2.76s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">鶴<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.37s" begin="-4.09s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.09s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-2.8s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.35s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-300)">Q<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.25s" begin="-4.16s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.96s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.95s" begin="-2.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.03s" begin="-4.23s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.93s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-2.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.06s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">3<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.82s" begin="-4.3s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-2.93s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.27s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">η<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.7s" begin="-4.37s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.47s" begin="-2.97s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">≈<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.06s" begin="-4.44s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.39s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-3.01s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ξ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.25s" begin="-4.51s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-3.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.99s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Þ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.03s" begin="-4.58s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.3s" begin="-3.1s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.24s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¡<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.82s" begin="-4.65s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-3.14s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">ψ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.7s" begin="-4.72s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.52s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-3.18s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.96s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">Ł<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.06s" begin="-4.79s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.49s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.12s" begin="-3.22s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¿<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.85s" begin="-4.86s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-3.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.72s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">K<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.73s" begin="-4.93s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-3.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">κ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.52s" begin="-5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.95s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.95s" begin="-3.35s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.43s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="7.7s" begin="-5.07s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.57s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-3.39s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.44s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">2<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.06s" begin="-5.14s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-3.43s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">0<animateTransform attributeName="transform" type="translate" values="0,-300;0,520" dur="6.85s" begin="-5.21s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.47s" begin="-3.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.25s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(186.61,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">C<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.74s" begin="-3.42s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.5s" begin="-2.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">S<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.94s" begin="-3.49s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.94s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.74s" begin="-2.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">%<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.21s" begin="-3.56s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.99s" begin="-2.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.63s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">Ψ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="11.41s" begin="-3.63s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="6.23s" begin="-3.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.88s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">Í<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="12.6s" begin="-3.7s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.5s" begin="-3.07s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.44s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">5<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.74s" begin="-3.77s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.07s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.74s" begin="-3.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-240)">T<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.94s" begin="-3.84s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.04s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.99s" begin="-3.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.15s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">χ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="11.13s" begin="-3.91s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="6.23s" begin="-3.2s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.36s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">8<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.95s" begin="-3.98s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.5s" begin="-3.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.86s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">κ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="12.14s" begin="-4.05s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.74s" begin="-3.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.07s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">∈<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.74s" begin="-4.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.99s" begin="-3.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.08s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">ξ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.94s" begin="-4.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="6.23s" begin="-3.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">Þ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="11.13s" begin="-4.26s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.5s" begin="-3.41s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¡<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.95s" begin="-4.33s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.63s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.74s" begin="-3.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">ψ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="12.14s" begin="-4.4s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.99s" begin="-3.49s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">Ł<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.66s" begin="-4.47s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="6.23s" begin="-3.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.81s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¿<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.48s" begin="-4.54s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.5s" begin="-3.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.31s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">K<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.67s" begin="-4.61s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.06s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.74s" begin="-3.62s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.52s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">κ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.95s" begin="-4.68s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.68s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.99s" begin="-3.66s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.52s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="12.14s" begin="-4.75s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="6.23s" begin="-3.7s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">2<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.66s" begin="-4.82s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.5s" begin="-3.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.34s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">0<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.48s" begin="-4.89s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.19s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.74s" begin="-3.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.49s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(283.21,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">D<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="6.81s" begin="-4.25s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.05s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.76s" begin="-2.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">L<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.02s" begin="-4.32s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.96s" begin="-2.81s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.72s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">$<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.9s" begin="-4.39s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.37s" begin="-2.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.97s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">β<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.79s" begin="-4.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.31s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.57s" begin="-2.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.53s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">Ó<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.65s" begin="-4.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.18s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.76s" begin="-2.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.68s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">1<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="6.81s" begin="-4.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.15s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.96s" begin="-2.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.24s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-320)">P<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.7s" begin="-4.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.37s" begin="-3.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.45s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">Ξ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.56s" begin="-4.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.57s" begin="-3.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.95s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">6<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.45s" begin="-4.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.61s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.76s" begin="-3.1s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">ϑ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.65s" begin="-4.88s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.96s" begin="-3.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">∮<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="6.81s" begin="-4.95s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.37s" begin="-3.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">ψ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.7s" begin="-5.02s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.87s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.57s" begin="-3.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">Ł<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.56s" begin="-5.09s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.74s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.76s" begin="-3.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.13s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">¿<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.45s" begin="-5.16s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.71s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.96s" begin="-3.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">K<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.33s" begin="-5.23s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.37s" begin="-3.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">κ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="6.47s" begin="-5.3s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.57s" begin="-3.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.4s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.36s" begin="-5.37s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.17s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.76s" begin="-3.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.61s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">2<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.56s" begin="-5.44s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.96s" begin="-3.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.61s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">0<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="8.45s" begin="-5.51s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.37s" begin="-3.52s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.87s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ω<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="9.33s" begin="-5.58s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.57s" begin="-3.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">K2<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="6.47s" begin="-5.65s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.3s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.76s" begin="-3.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.58s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">ß<animateTransform attributeName="transform" type="translate" values="0,-320;0,520" dur="7.36s" begin="-5.72s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.27s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.96s" begin="-3.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.14s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(360.05,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">E<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.12s" begin="-4.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.35s" begin="-3.42s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">V<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.09s" begin="-4.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.55s" begin="-3.46s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.06s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">0<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.06s" begin="-4.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.42s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.74s" begin="-3.5s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Γ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.91s" begin="-4.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.29s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.93s" begin="-3.55s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.77s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">Ú<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.89s" begin="-4.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.26s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.35s" begin="-3.59s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">2<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.87s" begin="-4.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.55s" begin="-3.63s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.53s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">F<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.72s" begin="-4.88s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.74s" begin="-3.67s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Ζ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.69s" begin="-4.95s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.72s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.93s" begin="-3.71s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.25s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">4<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.91s" begin="-5.02s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.35s" begin="-3.76s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.25s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">θ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.89s" begin="-5.09s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.55s" begin="-3.8s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∟<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.87s" begin="-5.16s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.98s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.74s" begin="-3.84s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.06s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">2<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.72s" begin="-5.23s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.85s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.93s" begin="-3.88s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">0<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.69s" begin="-5.3s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.82s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.35s" begin="-3.92s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ω<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.66s" begin="-5.37s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.55s" begin="-3.97s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.98s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">ß<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.51s" begin="-5.44s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.74s" begin="-4.01s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.49s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">ø<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.49s" begin="-5.51s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.28s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.93s" begin="-4.05s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.72s" begin="-5.58s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.35s" begin="-4.09s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.7s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.69s" begin="-5.65s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.55s" begin="-4.13s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.96s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">#<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.66s" begin="-5.72s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.54s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.74s" begin="-4.18s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="9.51s" begin="-5.79s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.41s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.93s" begin="-4.22s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.67s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Þ<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="7.49s" begin="-5.86s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.38s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.35s" begin="-4.26s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¡<animateTransform attributeName="transform" type="translate" values="0,-260;0,560" dur="8.46s" begin="-5.93s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.55s" begin="-4.3s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.43s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(454.46,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">F<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.64s" begin="-4.34s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.66s" begin="-3.79s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.15s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">X<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.51s" begin="-4.41s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.53s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.85s" begin="-3.83s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.7s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">!<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.37s" begin="-4.48s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.28s" begin="-3.87s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.86s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">Φ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.24s" begin="-4.55s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.37s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.47s" begin="-3.91s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">Å<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.1s" begin="-4.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.66s" begin="-3.96s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.62s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">%<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.31s" begin="-4.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.85s" begin="-4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.13s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-300)">N<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.18s" begin="-4.76s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.83s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-4.04s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">Π<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.37s" begin="-4.83s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.47s" begin="-4.08s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.34s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">œ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.24s" begin="-4.9s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.66s" begin="-4.12s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">μ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.1s" begin="-4.97s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.09s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.85s" begin="-4.17s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.15s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">∴<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.31s" begin="-5.04s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.96s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.28s" begin="-4.21s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.31s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">ß<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.18s" begin="-5.11s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.93s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-4.25s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.86s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">ø<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.04s" begin="-5.18s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.66s" begin="-4.29s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.07s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Σ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.91s" begin="-5.25s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.85s" begin="-4.33s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.58s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.77s" begin="-5.32s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.39s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.28s" begin="-4.38s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">#<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.31s" begin="-5.39s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.47s" begin="-4.42s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.79s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ξ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.18s" begin="-5.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.66s" begin="-4.46s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Þ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.04s" begin="-5.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.85s" begin="-4.5s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¡<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.91s" begin="-5.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.52s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-4.54s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.76s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">ψ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.77s" begin="-5.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.49s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.47s" begin="-4.59s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.31s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">Ł<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.98s" begin="-5.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.66s" begin="-4.63s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.52s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¿<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.84s" begin="-5.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.85s" begin="-4.67s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.02s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(551.06,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">G<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.84s" begin="-4.22s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.64s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.91s" begin="-2.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.79s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Y<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.67s" begin="-4.29s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.51s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.13s" begin="-2.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.95s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">@<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.77s" begin="-4.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.48s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.35s" begin="-2.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.5s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Υ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.86s" begin="-4.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.57s" begin="-2.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.71s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">Í<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.7s" begin="-4.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.91s" begin="-2.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ρ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-4.57s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.94s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.13s" begin="-2.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">Æ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.67s" begin="-4.64s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.35s" begin="-2.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.43s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">W<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.77s" begin="-4.71s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.57s" begin="-2.95s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.68s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ħ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.86s" begin="-4.78s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.91s" begin="-2.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.24s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.7s" begin="-4.85s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.07s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.13s" begin="-3.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.4s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∠<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-4.92s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.04s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.35s" begin="-3.07s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.95s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.52s" begin="-4.99s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.57s" begin="-3.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.16s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">#<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.35s" begin="-5.06s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.91s" begin="-3.16s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.66s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ξ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.44s" begin="-5.13s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.13s" begin="-3.2s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.87s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">Þ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.7s" begin="-5.2s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.35s" begin="-3.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.88s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¡<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.42s" begin="-5.27s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.57s" begin="-3.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.13s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ψ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.52s" begin="-5.34s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.91s" begin="-3.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">Ł<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.35s" begin="-5.41s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.63s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.13s" begin="-3.37s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">¿<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.44s" begin="-5.48s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.35s" begin="-3.41s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.4s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="11.54s" begin="-5.55s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.57s" begin="-3.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.61s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">κ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8s" begin="-5.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.91s" begin="-3.49s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.11s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.1s" begin="-5.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.06s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.13s" begin="-3.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.32s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(627.9,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-280)">ñ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.2s" begin="-3.24s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.62s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.31s" begin="-2.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">T<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.05s" begin="-3.31s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.59s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.49s" begin="-2.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.59s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-280)">8<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.9s" begin="-3.38s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-2.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.8s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">ϖ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.76s" begin="-3.45s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.14s" begin="-2.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-280)">Ê<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.61s" begin="-3.52s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.05s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.31s" begin="-2.49s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">σ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.2s" begin="-3.59s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-2.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.52s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-280)">Ğ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.05s" begin="-3.66s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="3.96s" begin="-2.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.77s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">V<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.9s" begin="-3.73s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.31s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.14s" begin="-2.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-280)">ň<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.76s" begin="-3.8s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.18s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-2.66s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-280)">ς<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.61s" begin="-3.87s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.15s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.49s" begin="-2.7s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-280)">∵<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.85s" begin="-3.94s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.96s" begin="-2.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.25s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">Þ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.72s" begin="-4.01s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.14s" begin="-2.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.75s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">¡<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.57s" begin="-4.08s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.61s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.31s" begin="-2.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.96s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">ψ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.76s" begin="-4.15s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.49s" begin="-2.87s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.96s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20" transform="translate(0,-280)">Ł<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.61s" begin="-4.22s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-2.91s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19" transform="translate(0,-280)">¿<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.85s" begin="-4.29s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.87s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.14s" begin="-2.95s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">K<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.72s" begin="-4.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.74s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.31s" begin="-2.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.93s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="20" transform="translate(0,-280)">κ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="7.57s" begin="-4.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.71s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-3.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.49s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="22" transform="translate(0,-280)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.42s" begin="-4.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="3.96s" begin="-3.08s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">2<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="8.29s" begin="-4.57s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.14s" begin="-3.12s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-280)">0<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.52s" begin="-4.64s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.17s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-3.16s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.41s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="22" transform="translate(0,-280)">Ω<animateTransform attributeName="transform" type="translate" values="0,-280;0,560" dur="6.72s" begin="-4.71s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.79s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.49s" begin="-3.2s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.41s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(711.33,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">I<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.73s" begin="-6.72s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.7s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.49s" begin="-5.13s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.68s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">P<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.74s" begin="-6.79s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.69s" begin="-5.17s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.89s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">6<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.58s" begin="-6.86s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.54s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.89s" begin="-5.22s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.39s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">ϱ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.59s" begin="-6.93s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.16s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.09s" begin="-5.26s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">Ë<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.82s" begin="-7s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.49s" begin="-5.3s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">ϙ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.73s" begin="-7.07s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.69s" begin="-5.34s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.86s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-240)">Ð<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.74s" begin="-7.14s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.42s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.89s" begin="-5.38s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">U<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.58s" begin="-7.21s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.29s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.09s" begin="-5.43s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.57s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">ŕ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.59s" begin="-7.28s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.26s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-5.47s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.13s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-240)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.59s" begin="-7.35s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.69s" begin="-5.51s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.33s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">∗<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.34s" begin="-7.42s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.89s" begin="-5.55s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="18" transform="translate(0,-240)">ξ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.35s" begin="-7.49s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.72s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.09s" begin="-5.59s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.05s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">Þ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.58s" begin="-7.56s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.34s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.49s" begin="-5.64s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.05s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¡<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.59s" begin="-7.63s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.69s" begin="-5.68s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.31s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">ψ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.59s" begin="-7.7s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.98s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.89s" begin="-5.72s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.86s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">Ł<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.34s" begin="-7.77s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.85s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.09s" begin="-5.76s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.02s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="19" transform="translate(0,-240)">¿<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.35s" begin="-7.84s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.82s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.49s" begin="-5.8s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.58s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">K<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.35s" begin="-7.91s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.69s" begin="-5.85s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="20" transform="translate(0,-240)">κ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="9.2s" begin="-7.98s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.89s" begin="-5.89s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.29s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="22" transform="translate(0,-240)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="10.21s" begin="-8.05s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.28s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.09s" begin="-5.93s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.49s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">2<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="7.34s" begin="-8.12s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.9s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-5.97s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.5s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-240)">0<animateTransform attributeName="transform" type="translate" values="0,-240;0,520" dur="8.35s" begin="-8.19s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.69s" begin="-6.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.76s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(788.17,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">¿<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.16s" begin="-4.32s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.61s" begin="-3.14s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.97s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">N<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.03s" begin="-4.39s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.8s" begin="-3.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">5<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.91s" begin="-4.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.27s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-3.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">ϗ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.12s" begin="-4.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.42s" begin="-3.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.69s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">Ę<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="9s" begin="-4.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.61s" begin="-3.31s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.95s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">ϛ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.16s" begin="-4.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.53s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.8s" begin="-3.35s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.5s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-320)">Ç<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.03s" begin="-4.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.4s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.23s" begin="-3.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.66s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">R<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.91s" begin="-4.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.37s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.42s" begin="-3.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-320)">ś<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.8s" begin="-4.88s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-3.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.42s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-320)">ϟ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.66s" begin="-4.95s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.8s" begin="-3.52s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.93s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">∯<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="6.82s" begin="-5.02s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.83s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.23s" begin="-3.56s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.13s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">ψ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.03s" begin="-5.09s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.45s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.42s" begin="-3.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.14s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">Ł<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.91s" begin="-5.16s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.22s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.61s" begin="-3.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.4s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">¿<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.8s" begin="-5.23s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.09s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.8s" begin="-3.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.95s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">K<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.66s" begin="-5.3s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.96s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-3.73s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.11s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">κ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="6.82s" begin="-5.37s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.93s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.42s" begin="-3.77s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.66s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.71s" begin="-5.44s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.55s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.61s" begin="-3.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.87s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">2<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.57s" begin="-5.51s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.8s" begin="-3.86s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.38s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="21" transform="translate(0,-320)">0<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.46s" begin="-5.58s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.39s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.23s" begin="-3.9s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.58s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="22" transform="translate(0,-320)">Ω<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="8.66s" begin="-5.65s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-6.01s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.42s" begin="-3.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.59s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="20" transform="translate(0,-320)">ktwo<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="6.82s" begin="-5.72s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.78s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-3.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="19" transform="translate(0,-320)">ß<animateTransform attributeName="transform" type="translate" values="0,-320;0,560" dur="7.71s" begin="-5.79s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.65s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.8s" begin="-4.03s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.4s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(880.38,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8s" begin="-6.34s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.94s" begin="-4.24s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.57s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">C<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.09s" begin="-6.41s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.38s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.16s" begin="-4.28s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.77s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">4<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.34s" begin="-6.48s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.38s" begin="-4.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.78s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">Ϥ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.44s" begin="-6.55s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.6s" begin="-4.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">Ě<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="11.53s" begin="-6.62s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.64s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.94s" begin="-4.41s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.59s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">ϝ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8s" begin="-6.69s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.51s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.16s" begin="-4.45s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.75s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-260)">Ō<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.09s" begin="-6.76s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.48s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.38s" begin="-4.49s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.3s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">S<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.18s" begin="-6.83s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.1s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.6s" begin="-4.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.51s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ž<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.02s" begin="-6.9s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.32s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.94s" begin="-4.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.02s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-260)">ϡ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="11.11s" begin="-6.97s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.94s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.16s" begin="-4.62s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.22s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∼<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8s" begin="-7.04s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.56s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.38s" begin="-4.66s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.23s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">K<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.09s" begin="-7.11s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.33s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.6s" begin="-4.7s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.48s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">κ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.18s" begin="-7.18s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.2s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.94s" begin="-4.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.04s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ϟ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.02s" begin="-7.25s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.07s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.16s" begin="-4.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.2s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">2<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="11.11s" begin="-7.32s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-7.04s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.38s" begin="-4.83s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.75s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21" transform="translate(0,-260)">0<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.84s" begin="-7.39s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.66s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.6s" begin="-4.87s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.96s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Ω<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.67s" begin="-7.46s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.94s" begin="-4.91s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.46s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">∑AI<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="9.76s" begin="-7.53s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.5s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.16s" begin="-4.95s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.67s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="19" transform="translate(0,-260)">ß<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="10.02s" begin="-7.6s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-6.12s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.38s" begin="-4.99s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.68s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="20" transform="translate(0,-260)">ø<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="11.11s" begin="-7.67s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.89s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.6s" begin="-5.04s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.93s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="22" transform="translate(0,-260)">Σ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.84s" begin="-7.74s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.76s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.94s" begin="-5.08s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.49s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="18" transform="translate(0,-260)">ñ<animateTransform attributeName="transform" type="translate" values="0,-260;0,520" dur="8.67s" begin="-7.81s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.63s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.16s" begin="-5.12s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.64s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
    <g transform="translate(966,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ψ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.01s" begin="-5.03s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.49s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.59s" begin="-3.94s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.86s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">E<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.22s" begin="-5.1s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.11s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.77s" begin="-3.98s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.87s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">3<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.13s" begin="-5.17s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.88s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-4.02s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.12s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">Θ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.05s" begin="-5.24s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.75s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.4s" begin="-4.06s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.68s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">Á<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.91s" begin="-5.31s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.62s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.59s" begin="-4.11s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Δ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.01s" begin="-5.38s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.59s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.77s" begin="-4.15s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.39s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="23" transform="translate(0,-300)">Š<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.92s" begin="-5.45s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.21s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.21s" begin="-4.19s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.6s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">T<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.78s" begin="-5.52s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.43s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.4s" begin="-4.23s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.1s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.7s" begin="-5.59s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.05s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-4.27s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.31s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="17" transform="translate(0,-300)">β<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.91s" begin="-5.66s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.67s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.77s" begin="-4.32s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.32s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">⊕<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.01s" begin="-5.73s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.44s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.21s" begin="-4.36s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.57s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">ø<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.92s" begin="-5.8s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.31s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.4s" begin="-4.4s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.13s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="22" transform="translate(0,-300)">Σ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.78s" begin="-5.87s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.18s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.59s" begin="-4.44s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.28s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ñ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.7s" begin="-5.94s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-7.15s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.77s" begin="-4.48s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.84s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">#<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.61s" begin="-6.01s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.77s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-4.53s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-5.05s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="18" transform="translate(0,-300)">ξ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.66s" begin="-6.08s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.99s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.4s" begin="-4.57s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.55s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="660" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">Þ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.57s" begin="-6.15s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.61s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.59s" begin="-4.61s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.76s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="700" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¡<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.78s" begin="-6.22s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-6.23s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.77s" begin="-4.65s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.76s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="740" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">ψ<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="8.7s" begin="-6.29s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-7s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.21s" begin="-4.69s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-5.02s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="780" fill="url(#gradGlow)" font-size="20" transform="translate(0,-300)">Ł<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="9.61s" begin="-6.36s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.87s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.4s" begin="-4.74s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.58s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="820" fill="url(#gradGlow)" font-size="19" transform="translate(0,-300)">¿<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="6.66s" begin="-6.43s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.74s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-4.78s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.73s" repeatCount="indefinite" additive="sum" />
        </text>
        <text x="0" y="860" fill="url(#gradGlow)" font-size="21" transform="translate(0,-300)">K<animateTransform attributeName="transform" type="translate" values="0,-300;0,560" dur="7.57s" begin="-6.5s" repeatCount="indefinite" />
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-7.71s" repeatCount="indefinite" />
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.77s" begin="-4.82s" repeatCount="indefinite" />
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-6.29s" repeatCount="indefinite" additive="sum" />
        </text>
      </g>
    </g>
  </g>
</svg>
