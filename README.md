![b](https://github.com/user-attachments/assets/7526c5c4-fda3-4d1f-803a-0c4487f2b2b4)
<svg xmlns="http://www.w3.org/2000/svg" xmlns:dc="http://purl.org/dc/elements/1.1/" xmlns:cc="http://creativecommons.org/ns#" xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#" width="966" height="500" style="max-width:100%;height:auto;" aria-label="Animated neon glyph waterfall" role="img" focusable="true">
<metadata>
    <rdf:RDF>
      <cc:Work rdf:about="">
        <dc:title>Matrix Rain Glyph Cascade</dc:title>
        <dc:creator>Shane Macaulay (K2)</dc:creator>
        <dc:identifier>https://github.com/K2</dc:identifier>
        <dc:description>Animated matrix-style glyph rainfall generated via DeepSeek-OCR assets pipeline.</dc:description>
        <dc:rights>© 2025 Shane Macaulay (K2) — Noncommercial use only. Contact ktwo@ktwo.ca.</dc:rights>
        <dc:language>en</dc:language>
        <cc:license rdf:resource="https://creativecommons.org/licenses/by-nc/4.0/"/>
      </cc:Work>
      <cc:License rdf:about="https://creativecommons.org/licenses/by-nc/4.0/">
        <cc:permits rdf:resource="https://creativecommons.org/ns#Reproduction"/>
        <cc:permits rdf:resource="https://creativecommons.org/ns#Distribution"/>
        <cc:permits rdf:resource="https://creativecommons.org/ns#DerivativeWorks"/>
        <cc:requires rdf:resource="https://creativecommons.org/ns#Attribution"/>
        <cc:prohibits rdf:resource="https://creativecommons.org/ns#CommercialUse"/>
      </cc:License>
    </rdf:RDF>
  </metadata>
  <defs>
    <linearGradient id="gradGlow" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="500">
      <stop offset="0%" stop-color="#9AFF9A"/>
      <stop offset="60%" stop-color="#31FF6B"/>
      <stop offset="100%" stop-color="#00BF47"/>
    </linearGradient>
    <linearGradient id="gradBolt" gradientUnits="userSpaceOnUse" x1="0" y1="0" x2="0" y2="500">
      <stop offset="0%" stop-color="#FFB347"/>
      <stop offset="60%" stop-color="#FF6A00"/>
      <stop offset="100%" stop-color="#FF2400"/>
    </linearGradient>
    <filter id="softGlow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="2.2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <filter id="trailGlow" x="-40%" y="-40%" width="180%" height="220%">
      <feGaussianBlur in="SourceGraphic" stdDeviation="0 7" result="trail"/>
      <feColorMatrix in="trail" type="matrix" values="1 0 0 0 0
                                                        0 1 0 0 0
                                                        0 0 1 0 0
                                                        0 0 0 0.6 0" result="trailFade"/>
      <feMerge>
        <feMergeNode in="trailFade"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <radialGradient id="vignette" cx="50%" cy="50%" r="65%">
      <stop offset="0%" stop-color="rgba(0,0,0,0)"/>
      <stop offset="100%" stop-color="rgba(0,0,0,0.55)"/>
    </radialGradient>
    <radialGradient id="flashGlow" cx="50%" cy="50%" r="75%">
      <stop offset="0%" stop-color="#FFB347" stop-opacity="0.85"/>
      <stop offset="55%" stop-color="#FF5F1F" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#FF2400" stop-opacity="0"/>
    </radialGradient>
  </defs>
  <rect x="0" y="0" width="966" height="500" fill="#050507"/>
  <rect x="0" y="0" width="966" height="500" fill="url(#vignette)"/>
  <g id="matrixRain" opacity="0.95" font-family="system-ui, sans-serif" letter-spacing="2">
    <g transform="translate(0,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          A
          <animate attributeName="y" values="-240;560" dur="5.79s" begin="-1.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-0.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.78s" begin="-1.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-1.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-0.5s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="20">
          Σ
          <animate attributeName="y" values="-200;600" dur="6.58s" begin="-1.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-1.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.95s" begin="-1.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-0.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-0.76s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="21">
          7
          <animate attributeName="y" values="-160;640" dur="7.37s" begin="-1.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-0.54s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-1.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-1.47s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.31s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Ω
          <animate attributeName="y" values="-120;680" dur="7.25s" begin="-1.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.41s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-1.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-1.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.47s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="18">
          Ñ
          <animate attributeName="y" values="-80;720" dur="8.04s" begin="-1.68s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.38s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.78s" begin="-1.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-2.34s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.02s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          @
          <animate attributeName="y" values="-40;760" dur="6.39s" begin="-1.75s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-1.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-0.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.23s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          Z
          <animate attributeName="y" values="0;800" dur="6.27s" begin="-1.82s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.12s" begin="-1.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.8;21.5;23" dur="5.4s" begin="-2.81s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-2.74s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          É
          <animate attributeName="y" values="40;840" dur="7.06s" begin="-1.89s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-0.84s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.28s" begin="-1.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-0.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-0.94s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          ?
          <animate attributeName="y" values="80;880" dur="7.25s" begin="-1.96s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.46s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.78s" begin="-1.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-1.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-0.95s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          δ
          <animate attributeName="y" values="120;920" dur="8.04s" begin="-2.03s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.95s" begin="-1.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.2;16.2;17" dur="3.3s" begin="-1.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∞
          <animate attributeName="y" values="160;960" dur="6.39s" begin="-2.1s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.12s" begin="-1.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-1.75s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.76s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="200;1000" dur="6.27s" begin="-2.17s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.97s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.28s" begin="-1.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-1.39s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.92s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="240;1040" dur="7.06s" begin="-2.24s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.78s" begin="-1.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-2.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.47s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="280;1080" dur="7.86s" begin="-2.31s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.95s" begin="-1.95s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-1.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.68s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="320;1120" dur="7.73s" begin="-2.38s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-1.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.09s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="360;1160" dur="6.09s" begin="-2.45s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-2.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.39s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="400;1200" dur="6.27s" begin="-2.52s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.02s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="3.78s" begin="-2.07s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-1.66s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.4s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="440;1240" dur="7.06s" begin="-2.59s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-2.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-1.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="480;1280" dur="7.86s" begin="-2.66s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.12s" begin="-2.16s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.03s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.21s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="520;1320" dur="7.73s" begin="-2.73s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.53s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.28s" begin="-2.2s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-1.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="560;1360" dur="6.09s" begin="-2.8s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.78s" begin="-2.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-2.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.92s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="600;1400" dur="6.88s" begin="-2.87s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="3.95s" begin="-2.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.13s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(87.82,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-280" fill="url(#gradGlow)" font-size="18">
          ß
          <animate attributeName="y" values="-280;540" dur="7.39s" begin="-0.98s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-1.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5s" begin="-0.91s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-0.89s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-0.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="21">
          M
          <animate attributeName="y" values="-240;580" dur="8.36s" begin="-1.05s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-0.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-0.95s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-1.52s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.4s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="22">
          鶴
          <animate attributeName="y" values="-200;620" dur="8.21s" begin="-1.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.52s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-0.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21.5;22" dur="3.5s" begin="-1.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="19">
          λ
          <animate attributeName="y" values="-160;660" dur="9.17s" begin="-1.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.49s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.79s" begin="-1.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-2.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.11s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="18">
          Ü
          <animate attributeName="y" values="-120;700" dur="10.13s" begin="-1.26s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.08s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-0.93s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.32s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="20">
          鶴
          <animate attributeName="y" values="-80;740" dur="7.03s" begin="-1.33s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-1.12s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-2.87s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-2.82s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="23">
          Q
          <animate attributeName="y" values="-40;780" dur="7.99s" begin="-1.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-0.95s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.59s" begin="-1.16s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.9;20.9;23" dur="2.1s" begin="-0.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.03s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="0;820" dur="8.21s" begin="-1.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.57s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.79s" begin="-1.2s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-1.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="18">
          3
          <animate attributeName="y" values="40;860" dur="9.17s" begin="-1.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-1.17s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.29s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="17">
          η
          <animate attributeName="y" values="80;900" dur="10.13s" begin="-1.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.2s" begin="-1.29s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.8;15.8;17" dur="3.7s" begin="-1.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.85s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="20">
          ≈
          <animate attributeName="y" values="120;940" dur="7.03s" begin="-1.68s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.08s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-1.33s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-1.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="160;980" dur="7.99s" begin="-1.75s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.05s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.79s" begin="-1.37s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-2.68s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="200;1020" dur="8.95s" begin="-1.82s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5s" begin="-1.41s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.77s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="240;1060" dur="8.8s" begin="-1.89s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-1.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.15s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="280;1100" dur="9.76s" begin="-1.96s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.51s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-1.5s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-1.18s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="320;1140" dur="7.03s" begin="-2.03s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.13s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.79s" begin="-1.54s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-1.72s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="360;1180" dur="7.99s" begin="-2.1s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.58s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-1.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.74s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="400;1220" dur="8.95s" begin="-2.17s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.2s" begin="-1.62s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-2.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="440;1260" dur="8.8s" begin="-2.24s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.64s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.59s" begin="-1.66s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-1.72s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="480;1300" dur="9.76s" begin="-2.31s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.79s" begin="-1.71s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-2.96s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.01s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="520;1340" dur="7.76s" begin="-2.38s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5s" begin="-1.75s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-1.49s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.21s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="560;1380" dur="7.62s" begin="-2.45s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.2s" begin="-1.79s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.8;20.5;22" dur="5.4s" begin="-3.43s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.72s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(175.64,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="18">
          C
          <animate attributeName="y" values="-220;540" dur="7.16s" begin="-2.66s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-0.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-2.52s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-1.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.49s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="20">
          S
          <animate attributeName="y" values="-180;580" dur="7.02s" begin="-2.73s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.63s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.42s" begin="-2.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-1.22s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.64s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="22">
          %
          <animate attributeName="y" values="-140;620" dur="7.91s" begin="-2.8s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.61s" begin="-2.6s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-2.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="19">
          Ψ
          <animate attributeName="y" values="-100;660" dur="8.79s" begin="-2.87s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.79s" begin="-2.64s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-0.98s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.41s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="17">
          Í
          <animate attributeName="y" values="-60;700" dur="8.66s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-2.68s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.8;15.5;17" dur="5.4s" begin="-2.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-2.91s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="21">
          5
          <animate attributeName="y" values="-20;740" dur="6.82s" begin="-3.01s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.06s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.42s" begin="-2.73s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-0.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.12s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="23">
          T
          <animate attributeName="y" values="20;780" dur="7.02s" begin="-3.08s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.68s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.61s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24;22;23" dur="4s" begin="-1.49s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.12s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="19">
          χ
          <animate attributeName="y" values="60;820" dur="7.91s" begin="-3.15s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.79s" begin="-2.81s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-1.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="18">
          8
          <animate attributeName="y" values="100;860" dur="8.79s" begin="-3.22s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-1.86s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-1.94s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="17">
          κ
          <animate attributeName="y" values="140;900" dur="8.66s" begin="-3.29s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.19s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.42s" begin="-2.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16.5;17" dur="3.5s" begin="-1.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="20">
          ∈
          <animate attributeName="y" values="180;940" dur="6.82s" begin="-3.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.16s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.61s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-2.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="220;980" dur="7.7s" begin="-3.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.79s" begin="-2.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-1.26s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.85s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="260;1020" dur="7.56s" begin="-3.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-3.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="300;1060" dur="8.45s" begin="-3.57s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.62s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.42s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-1.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.57s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="340;1100" dur="8.66s" begin="-3.64s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.24s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.61s" begin="-3.1s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-1.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.57s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="380;1140" dur="6.82s" begin="-3.71s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.79s" begin="-3.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-1.51s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.83s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="420;1180" dur="7.7s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.14s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="460;1220" dur="7.56s" begin="-3.85s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.75s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.42s" begin="-3.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-1.78s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="500;1260" dur="8.45s" begin="-3.92s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.72s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.61s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-3.01s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.1s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="540;1300" dur="9.34s" begin="-3.99s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.79s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-1.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="580;1340" dur="6.47s" begin="-4.06s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-3.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.48s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.81s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="620;1380" dur="7.36s" begin="-4.13s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.18s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.42s" begin="-3.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-1.52s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.01s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(263.45,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-300" fill="url(#gradGlow)" font-size="18">
          D
          <animate attributeName="y" values="-300;540" dur="7.44s" begin="-0.94s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-1.74s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.29s" begin="-0.72s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-1.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-0.73s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-260" fill="url(#gradGlow)" font-size="21">
          L
          <animate attributeName="y" values="-260;580" dur="8.46s" begin="-1.01s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.71s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.51s" begin="-0.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-2.51s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.29s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="22">
          $
          <animate attributeName="y" values="-220;620" dur="9.47s" begin="-1.08s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.86s" begin="-0.81s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-1.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.49s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="19">
          β
          <animate attributeName="y" values="-180;660" dur="9.32s" begin="-1.15s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.08s" begin="-0.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-2.98s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="17">
          Ó
          <animate attributeName="y" values="-140;700" dur="10.34s" begin="-1.22s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.17s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.29s" begin="-0.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.9;14.9;17" dur="2.1s" begin="-1.01s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.21s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="21">
          1
          <animate attributeName="y" values="-100;740" dur="7.44s" begin="-1.29s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.51s" begin="-0.93s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-1.55s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.21s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="23">
          P
          <animate attributeName="y" values="-60;780" dur="8.46s" begin="-1.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.86s" begin="-0.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.2;22.2;23" dur="3.3s" begin="-1.28s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.47s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="19">
          Ξ
          <animate attributeName="y" values="-20;820" dur="9.47s" begin="-1.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.08s" begin="-1.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-1.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.02s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18">
          6
          <animate attributeName="y" values="20;860" dur="9.32s" begin="-1.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.29s" begin="-1.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-1.55s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="17">
          ϑ
          <animate attributeName="y" values="60;900" dur="10.34s" begin="-1.57s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.51s" begin="-1.1s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.6;15.7;17" dur="4.9s" begin="-2.79s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.74s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="20">
          ∮
          <animate attributeName="y" values="100;940" dur="8.22s" begin="-1.64s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.86s" begin="-1.14s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-1.32s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.94s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="140;980" dur="8.06s" begin="-1.71s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.08s" begin="-1.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-3.25s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="180;1020" dur="9.08s" begin="-1.78s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.73s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.29s" begin="-1.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.29s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="220;1060" dur="9.32s" begin="-1.85s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.35s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.51s" begin="-1.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-1.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.66s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="260;1100" dur="10.34s" begin="-1.92s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.86s" begin="-1.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-1.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.92s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="300;1140" dur="8.22s" begin="-1.99s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.08s" begin="-1.35s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.8;20.8;22" dur="3.7s" begin="-2.19s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.47s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="340;1180" dur="8.06s" begin="-2.06s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.86s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.29s" begin="-1.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-1.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.63s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="380;1220" dur="9.08s" begin="-2.13s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.83s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.51s" begin="-1.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.07s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="420;1260" dur="10.1s" begin="-2.2s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.86s" begin="-1.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-1.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.39s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="460;1300" dur="9.94s" begin="-2.27s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.08s" begin="-1.52s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-3.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.9s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="500;1340" dur="7.83s" begin="-2.34s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.29s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.29s" begin="-1.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.57s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.1s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="540;1380" dur="8.06s" begin="-2.41s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.91s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.51s" begin="-1.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-2.11s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.11s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(351.27,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          E
          <animate attributeName="y" values="-240;580" dur="5.94s" begin="-2.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-2.82s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.69s" begin="-2.33s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-2.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="21">
          V
          <animate attributeName="y" values="-200;620" dur="6.72s" begin="-2.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.85s" begin="-2.37s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-1.09s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.58s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="22">
          0
          <animate attributeName="y" values="-160;660" dur="6.6s" begin="-2.76s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.02s" begin="-2.42s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.8;20.5;22" dur="5.4s" begin="-3.03s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Γ
          <animate attributeName="y" values="-120;700" dur="7.37s" begin="-2.83s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.28s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.18s" begin="-2.46s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.29s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="17">
          Ú
          <animate attributeName="y" values="-80;740" dur="7.55s" begin="-2.9s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-1.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.69s" begin="-2.5s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16;17" dur="4s" begin="-1.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          2
          <animate attributeName="y" values="-40;780" dur="5.94s" begin="-2.97s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.85s" begin="-2.54s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-1.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          F
          <animate attributeName="y" values="0;820" dur="6.72s" begin="-3.04s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.54s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.02s" begin="-2.58s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.8;21.8;23" dur="3.7s" begin="-1.97s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.11s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          Ζ
          <animate attributeName="y" values="40;860" dur="6.6s" begin="-3.11s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.41s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.18s" begin="-2.63s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-1.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          4
          <animate attributeName="y" values="80;900" dur="7.37s" begin="-3.18s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.38s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.69s" begin="-2.67s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-2.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.82s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          θ
          <animate attributeName="y" values="120;940" dur="8.14s" begin="-3.25s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.85s" begin="-2.71s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.6;15.2;17" dur="2.4s" begin="-1.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.03s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∟
          <animate attributeName="y" values="160;980" dur="5.65s" begin="-3.32s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.02s" begin="-2.75s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-3.31s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="200;1020" dur="6.42s" begin="-3.39s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.84s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.18s" begin="-2.79s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-1.34s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.74s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="240;1060" dur="6.6s" begin="-3.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.46s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.69s" begin="-2.84s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21;22" dur="4s" begin="-1.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.75s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="280;1100" dur="7.37s" begin="-3.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.85s" begin="-2.88s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-1.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="320;1140" dur="8.14s" begin="-3.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.02s" begin="-2.92s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.25s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="360;1180" dur="5.65s" begin="-3.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.97s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.18s" begin="-2.96s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-1.89s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.72s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="400;1220" dur="6.42s" begin="-3.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="3.69s" begin="-3s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="440;1260" dur="7.19s" begin="-3.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.85s" begin="-3.05s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.66s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="480;1300" dur="7.07s" begin="-3.88s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.02s" begin="-3.09s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-3.59s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="520;1340" dur="7.85s" begin="-3.95s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.18s" begin="-3.13s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-1.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.19s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="560;1380" dur="5.65s" begin="-4.02s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.02s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.69s" begin="-3.17s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="600;1420" dur="6.42s" begin="-4.09s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="3.85s" begin="-3.21s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-1.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.45s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(439.09,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-280" fill="url(#gradGlow)" font-size="18">
          F
          <animate attributeName="y" values="-280;580" dur="8.83s" begin="-4.1s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-1.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.68s" begin="-3.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-1.15s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-1.67s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="21">
          X
          <animate attributeName="y" values="-240;620" dur="8.66s" begin="-4.17s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.92s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-3.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="22">
          !
          <animate attributeName="y" values="-200;660" dur="9.76s" begin="-4.24s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.39s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.22s" begin="-3.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.9;19.9;22" dur="2.1s" begin="-1.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="19">
          Φ
          <animate attributeName="y" values="-160;700" dur="10.01s" begin="-4.31s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.45s" begin="-3.87s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-1.66s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.39s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="17">
          Å
          <animate attributeName="y" values="-120;740" dur="11.1s" begin="-4.38s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.68s" begin="-3.91s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.2;16.2;17" dur="3.3s" begin="-1.39s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.64s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="21">
          %
          <animate attributeName="y" values="-80;780" dur="8.83s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.92s" begin="-3.95s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-2.02s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="23">
          N
          <animate attributeName="y" values="-40;820" dur="8.66s" begin="-4.52s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.52s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.22s" begin="-3.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24;22.5;23" dur="3.5s" begin="-1.66s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="19">
          Π
          <animate attributeName="y" values="0;860" dur="9.76s" begin="-4.59s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.49s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.45s" begin="-4.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-2.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-2.91s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="18">
          œ
          <animate attributeName="y" values="40;900" dur="10.85s" begin="-4.66s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.68s" begin="-4.08s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-1.43s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.12s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="17">
          μ
          <animate attributeName="y" values="80;940" dur="10.68s" begin="-4.73s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.92s" begin="-4.12s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.8;15.5;17" dur="5.4s" begin="-3.37s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="20">
          ∴
          <animate attributeName="y" values="120;980" dur="8.41s" begin="-4.8s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.95s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.22s" begin="-4.16s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-1.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.83s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="160;1020" dur="8.66s" begin="-4.87s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.57s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.45s" begin="-4.2s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-1.94s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="200;1060" dur="9.76s" begin="-4.94s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.68s" begin="-4.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-1.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="240;1100" dur="10.85s" begin="-5.01s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.92s" begin="-4.29s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-2.3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="280;1140" dur="10.68s" begin="-5.08s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.08s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.22s" begin="-4.33s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-1.94s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="320;1180" dur="8.41s" begin="-5.15s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.05s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.45s" begin="-4.37s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.18s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="360;1220" dur="9.5s" begin="-5.22s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.68s" begin="-4.41s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-1.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.57s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="400;1260" dur="9.34s" begin="-5.29s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.92s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.65s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.07s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="440;1300" dur="10.43s" begin="-5.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.51s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.22s" begin="-4.5s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.68s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.28s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="480;1340" dur="10.68s" begin="-5.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.13s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="5.45s" begin="-4.54s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-2.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.28s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="520;1380" dur="8.41s" begin="-5.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.68s" begin="-4.58s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.2;21.2;22" dur="3.3s" begin="-1.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="560;1420" dur="9.5s" begin="-5.57s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="5.92s" begin="-4.62s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-2.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.1s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(526.91,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          G
          <animate attributeName="y" values="-240;540" dur="6.06s" begin="-1.28s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-3.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="3.96s" begin="-0.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.14s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.26s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="21">
          Y
          <animate attributeName="y" values="-200;580" dur="6.89s" begin="-1.35s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.14s" begin="-0.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-1.18s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.47s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="22">
          @
          <animate attributeName="y" values="-160;620" dur="7.08s" begin="-1.42s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-0.93s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21;22" dur="4s" begin="-1.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Υ
          <animate attributeName="y" values="-120;660" dur="7.91s" begin="-1.49s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-2.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.49s" begin="-0.97s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-1.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.73s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="17">
          Í
          <animate attributeName="y" values="-80;700" dur="8.74s" begin="-1.56s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="3.96s" begin="-1.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.8;15.8;17" dur="3.7s" begin="-2.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.29s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          ρ
          <animate attributeName="y" values="-40;740" dur="6.06s" begin="-1.63s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.63s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.14s" begin="-1.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-1.72s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.44s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          Æ
          <animate attributeName="y" values="0;780" dur="6.89s" begin="-1.7s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.31s" begin="-1.1s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.6;21.7;23" dur="4.9s" begin="-2.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          W
          <animate attributeName="y" values="40;820" dur="7.72s" begin="-1.77s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.49s" begin="-1.14s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.48s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.21s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          ħ
          <animate attributeName="y" values="80;860" dur="7.59s" begin="-1.84s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-1.18s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.42s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          ξ
          <animate attributeName="y" values="120;900" dur="8.42s" begin="-1.91s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.06s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.14s" begin="-1.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.9;14.9;17" dur="2.1s" begin="-1.46s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.92s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∠
          <animate attributeName="y" values="160;940" dur="6.06s" begin="-1.98s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.68s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.31s" begin="-1.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-1.99s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.92s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="200;980" dur="6.89s" begin="-2.05s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-1.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-1.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="240;1020" dur="7.72s" begin="-2.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="3.96s" begin="-1.35s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-2.36s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.74s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="280;1060" dur="7.59s" begin="-2.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.14s" begin="-1.39s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="320;1100" dur="8.42s" begin="-2.26s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.16s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-1.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="360;1140" dur="6.7s" begin="-2.33s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.49s" begin="-1.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.76s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="400;1180" dur="6.57s" begin="-2.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="3.96s" begin="-1.52s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-3.7s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="440;1220" dur="7.4s" begin="-2.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.62s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.14s" begin="-1.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.9;19.9;22" dur="2.1s" begin="-1.74s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.37s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="480;1260" dur="7.59s" begin="-2.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.24s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.31s" begin="-1.6s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.37s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="520;1300" dur="8.42s" begin="-2.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.49s" begin="-1.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.63s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="560;1340" dur="6.7s" begin="-2.68s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-1.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-2.64s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="600;1380" dur="6.57s" begin="-2.75s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.75s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.14s" begin="-1.73s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-2.28s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.34s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(614.73,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-260" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="-260;580" dur="7.25s" begin="-2.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-1.61s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.9s" begin="-1.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-1.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-1.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="21">
          T
          <animate attributeName="y" values="-220;620" dur="7.47s" begin="-2.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.1s" begin="-1.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-1.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="22">
          8
          <animate attributeName="y" values="-180;660" dur="8.41s" begin="-2.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.5s" begin="-1.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.2;21.2;22" dur="3.3s" begin="-1.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.82s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="19">
          ϖ
          <animate attributeName="y" values="-140;700" dur="9.35s" begin="-2.57s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.87s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.7s" begin="-1.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.13s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="17">
          Ê
          <animate attributeName="y" values="-100;740" dur="9.21s" begin="-2.64s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.74s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.9s" begin="-2.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16.5;17" dur="3.5s" begin="-1.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.53s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="21">
          σ
          <animate attributeName="y" values="-60;780" dur="7.25s" begin="-2.71s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.71s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-2.07s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.01s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="23">
          Ğ
          <animate attributeName="y" values="-20;820" dur="8.19s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.5s" begin="-2.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.6;21.2;23" dur="2.4s" begin="-1.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.29s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="19">
          V
          <animate attributeName="y" values="20;860" dur="8.05s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.7s" begin="-2.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.48s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="18">
          ň
          <animate attributeName="y" values="60;900" dur="8.99s" begin="-2.92s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.17s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.9s" begin="-2.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-1.51s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.01s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="17">
          ς
          <animate attributeName="y" values="100;940" dur="9.21s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="5.1s" begin="-2.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16;17" dur="4s" begin="-2.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.01s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="20">
          ∵
          <animate attributeName="y" values="140;980" dur="7.25s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.5s" begin="-2.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-1.78s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="180;1020" dur="8.19s" begin="-3.13s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.7s" begin="-2.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.42s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.82s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="220;1060" dur="8.05s" begin="-3.2s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.9s" begin="-2.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.05s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="260;1100" dur="8.99s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.27s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.1s" begin="-2.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-3.29s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="300;1140" dur="9.93s" begin="-3.34s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.5s" begin="-2.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-1.82s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.74s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="340;1180" dur="6.89s" begin="-3.41s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.7s" begin="-2.49s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.75s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.25s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="380;1220" dur="7.83s" begin="-3.48s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.73s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.9s" begin="-2.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.79s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="420;1260" dur="8.05s" begin="-3.55s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.35s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-2.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.46s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="460;1300" dur="8.99s" begin="-3.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.5s" begin="-2.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.72s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="500;1340" dur="9.93s" begin="-3.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.7s" begin="-2.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.69s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="540;1380" dur="6.89s" begin="-3.76s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.86s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.9s" begin="-2.7s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-2.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.43s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="580;1420" dur="7.83s" begin="-3.83s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.83s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="5.1s" begin="-2.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-3.57s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.98s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(702.55,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="18">
          I
          <animate attributeName="y" values="-220;540" dur="5.92s" begin="-4.14s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="3.87s" begin="-3.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-1.82s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-1.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="21">
          P
          <animate attributeName="y" values="-180;580" dur="6.73s" begin="-4.21s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.04s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-1.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-1.91s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="22">
          6
          <animate attributeName="y" values="-140;620" dur="7.54s" begin="-4.28s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-1.98s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-3.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.8;20.8;22" dur="3.7s" begin="-2.19s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.46s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="19">
          ϱ
          <animate attributeName="y" values="-100;660" dur="7.42s" begin="-4.35s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.39s" begin="-3.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-1.82s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="17">
          Ë
          <animate attributeName="y" values="-60;700" dur="8.23s" begin="-4.42s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.82s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.87s" begin="-3.73s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.6;15.7;17" dur="4.9s" begin="-3.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="21">
          ϙ
          <animate attributeName="y" values="-20;740" dur="6.55s" begin="-4.49s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.04s" begin="-3.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-1.59s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="23">
          Ð
          <animate attributeName="y" values="20;780" dur="6.42s" begin="-4.56s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.21s" begin="-3.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.8;21.5;23" dur="5.4s" begin="-3.53s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="19">
          U
          <animate attributeName="y" values="60;820" dur="7.23s" begin="-4.63s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.28s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.39s" begin="-3.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="18">
          ŕ
          <animate attributeName="y" values="100;860" dur="7.42s" begin="-4.7s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-2.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.87s" begin="-3.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.1s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="17">
          Ϟ
          <animate attributeName="y" values="140;900" dur="8.23s" begin="-4.77s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.04s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.2;16.2;17" dur="3.3s" begin="-1.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="20">
          ∗
          <animate attributeName="y" values="180;940" dur="6.55s" begin="-4.84s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.54s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.21s" begin="-3.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-2.47s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.91s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="220;980" dur="6.42s" begin="-4.91s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.41s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.39s" begin="-4.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21.5;22" dur="3.5s" begin="-2.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.07s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="260;1020" dur="7.23s" begin="-4.98s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.38s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="3.87s" begin="-4.07s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-3.34s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="300;1060" dur="8.04s" begin="-5.05s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.04s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.83s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="340;1100" dur="7.92s" begin="-5.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-4.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.81s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.34s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="380;1140" dur="6.23s" begin="-5.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.84s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.39s" begin="-4.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-1.85s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="420;1180" dur="6.42s" begin="-5.26s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.46s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.87s" begin="-4.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.55s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="460;1220" dur="7.23s" begin="-5.33s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.04s" begin="-4.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="500;1260" dur="8.04s" begin="-5.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.21s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-2.75s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="540;1300" dur="7.92s" begin="-5.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.97s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.39s" begin="-4.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.52s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="580;1340" dur="6.23s" begin="-5.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.94s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.87s" begin="-4.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.07s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="620;1380" dur="7.05s" begin="-5.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.04s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-2.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.28s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(790.36,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-300" fill="url(#gradGlow)" font-size="18">
          ¿
          <animate attributeName="y" values="-300;580" dur="8.12s" begin="-3.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.49s" begin="-2.47s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-1.61s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-260" fill="url(#gradGlow)" font-size="21">
          N
          <animate attributeName="y" values="-260;620" dur="9.18s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.09s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.71s" begin="-2.51s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-2.25s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.55s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="22">
          5
          <animate attributeName="y" values="-220;660" dur="9.01s" begin="-3.26s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-2.96s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.04s" begin="-2.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21.5;22" dur="3.5s" begin="-1.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="19">
          ϗ
          <animate attributeName="y" values="-180;700" dur="10.07s" begin="-3.33s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-3.93s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.26s" begin="-2.6s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.26s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="17">
          Ę
          <animate attributeName="y" values="-140;740" dur="11.12s" begin="-3.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.49s" begin="-2.64s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.6;15.2;17" dur="2.4s" begin="-1.65s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.47s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="21">
          ϛ
          <animate attributeName="y" values="-100;780" dur="7.71s" begin="-3.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.71s" begin="-2.68s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-3.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-3.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="23">
          Ç
          <animate attributeName="y" values="-60;820" dur="8.77s" begin="-3.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.39s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.04s" begin="-2.72s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.9;20.9;23" dur="2.1s" begin="-1.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="19">
          R
          <animate attributeName="y" values="-20;860" dur="9.01s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.26s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.19s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18">
          ś
          <animate attributeName="y" values="20;900" dur="10.07s" begin="-3.68s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.49s" begin="-2.81s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-1.89s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.44s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="17">
          ϟ
          <animate attributeName="y" values="60;940" dur="11.12s" begin="-3.75s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.71s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.8;15.8;17" dur="3.7s" begin="-2.52s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="20">
          ∯
          <animate attributeName="y" values="100;980" dur="7.71s" begin="-3.82s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.52s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.04s" begin="-2.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-2.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="140;1020" dur="8.77s" begin="-3.89s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.49s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.26s" begin="-2.93s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-3.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="180;1060" dur="9.83s" begin="-3.96s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.49s" begin="-2.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-1.93s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.92s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="220;1100" dur="9.66s" begin="-4.03s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.71s" begin="-3.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.87s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="260;1140" dur="10.72s" begin="-4.1s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.95s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.04s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-1.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.63s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="300;1180" dur="7.71s" begin="-4.17s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.57s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.26s" begin="-3.1s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-2.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.64s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="340;1220" dur="8.77s" begin="-4.24s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.49s" begin="-3.14s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.17s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="380;1260" dur="9.83s" begin="-4.31s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.71s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="420;1300" dur="9.66s" begin="-4.38s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.08s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.04s" begin="-3.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-2.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="460;1340" dur="10.72s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.05s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="5.26s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-3.68s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="500;1380" dur="8.53s" begin="-4.52s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.49s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.37s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="540;1420" dur="8.36s" begin="-4.59s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="5.71s" begin="-3.35s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.14s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.87s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(878.18,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          K
          <animate attributeName="y" values="-240;540" dur="6.85s" begin="-2.7s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.05s" begin="-1.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-2.3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-2.64s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="21">
          C
          <animate attributeName="y" values="-200;580" dur="6.72s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.07s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-2.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-1.94s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="22">
          4
          <animate attributeName="y" values="-160;620" dur="7.57s" begin="-2.84s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.04s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.41s" begin="-2.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-3.17s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.35s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Ϥ
          <animate attributeName="y" values="-120;660" dur="8.42s" begin="-2.91s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.59s" begin="-2.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-1.7s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.56s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="17">
          Ě
          <animate attributeName="y" values="-80;700" dur="8.29s" begin="-2.98s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.05s" begin="-2.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.8;15.5;17" dur="5.4s" begin="-3.64s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.06s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          ϝ
          <animate attributeName="y" values="-40;740" dur="6.52s" begin="-3.05s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-2.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-1.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          Ō
          <animate attributeName="y" values="0;780" dur="6.72s" begin="-3.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.41s" begin="-2.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24;22;23" dur="4s" begin="-2.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.28s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          S
          <animate attributeName="y" values="40;820" dur="7.57s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-3.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.59s" begin="-2.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-1.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.53s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          ž
          <animate attributeName="y" values="80;860" dur="8.42s" begin="-3.26s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.05s" begin="-2.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-2.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          ϡ
          <animate attributeName="y" values="120;900" dur="8.29s" begin="-3.33s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.63s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-2.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16.5;17" dur="3.5s" begin="-2.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.24s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∼
          <animate attributeName="y" values="160;940" dur="6.52s" begin="-3.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.41s" begin="-2.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-3.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="200;980" dur="7.37s" begin="-3.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.59s" begin="-2.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-1.98s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.01s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="240;1020" dur="7.24s" begin="-3.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.05s" begin="-2.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-3.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="280;1060" dur="8.09s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.23s" begin="-2.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.96s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.72s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="320;1100" dur="8.29s" begin="-3.68s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.68s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.41s" begin="-2.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.49s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.72s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="360;1140" dur="6.52s" begin="-3.75s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.59s" begin="-2.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-2.22s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="400;1180" dur="7.37s" begin="-3.82s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.05s" begin="-2.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.8;20.8;22" dur="3.7s" begin="-2.86s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="440;1220" dur="7.24s" begin="-3.89s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.19s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.23s" begin="-2.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-2.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="480;1260" dur="8.09s" begin="-3.96s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.16s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.41s" begin="-2.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.25s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="520;1300" dur="8.94s" begin="-4.03s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.59s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.26s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="560;1340" dur="6.2s" begin="-4.1s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.05s" begin="-2.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-4.2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.96s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="600;1380" dur="7.05s" begin="-4.17s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.62s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.23s" begin="-2.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-2.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.17s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(966,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-280" fill="url(#gradGlow)" font-size="18">
          ψ
          <animate attributeName="y" values="-280;580" dur="7.16s" begin="-4.48s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.18s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.1s" begin="-3.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-1.99s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-1.88s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="21">
          E
          <animate attributeName="y" values="-240;620" dur="8.14s" begin="-4.55s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.15s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.3s" begin="-3.73s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.44s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="22">
          3
          <animate attributeName="y" values="-200;660" dur="9.12s" begin="-4.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.68s" begin="-3.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-1.76s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.65s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="19">
          Θ
          <animate attributeName="y" values="-160;700" dur="8.97s" begin="-4.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-4.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.89s" begin="-3.81s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.7s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.15s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="17">
          Á
          <animate attributeName="y" values="-120;740" dur="9.95s" begin="-4.76s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.61s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.1s" begin="-3.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.9;14.9;17" dur="2.1s" begin="-1.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="21">
          Δ
          <animate attributeName="y" values="-80;780" dur="7.16s" begin="-4.83s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.3s" begin="-3.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-2.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="23">
          Š
          <animate attributeName="y" values="-40;820" dur="8.14s" begin="-4.9s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.68s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.2;22.2;23" dur="3.3s" begin="-2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="19">
          T
          <animate attributeName="y" values="0;860" dur="9.12s" begin="-4.97s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.87s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.89s" begin="-3.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.63s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="40;900" dur="8.97s" begin="-5.04s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.74s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-4.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-2.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="17">
          β
          <animate attributeName="y" values="80;940" dur="9.95s" begin="-5.11s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.71s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.3s" begin="-4.07s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.6;15.7;17" dur="4.9s" begin="-3.51s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="20">
          ⊕
          <animate attributeName="y" values="120;980" dur="7.92s" begin="-5.18s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.68s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-2.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.09s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="160;1020" dur="7.77s" begin="-5.25s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.89s" begin="-4.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-3.98s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="200;1060" dur="8.75s" begin="-5.32s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.17s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.1s" begin="-4.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-2.01s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.81s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="240;1100" dur="8.97s" begin="-5.39s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.3s" begin="-4.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21;22" dur="4s" begin="-2.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.81s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="280;1140" dur="9.95s" begin="-5.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.68s" begin="-4.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-2.28s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.07s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="320;1180" dur="7.92s" begin="-5.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.89s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="360;1220" dur="7.77s" begin="-5.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="5.1s" begin="-4.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-2.55s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="400;1260" dur="8.75s" begin="-5.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.27s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.3s" begin="-4.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.79s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.34s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="440;1300" dur="9.73s" begin="-5.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.68s" begin="-4.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.32s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="480;1340" dur="9.58s" begin="-5.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.89s" begin="-4.49s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-4.25s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.05s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="520;1380" dur="7.54s" begin="-5.88s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.73s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.1s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-2.29s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.25s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="560;1420" dur="7.77s" begin="-5.95s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.35s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.3s" begin="-4.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.26s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(0,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          A
          <animate attributeName="y" values="-240;560" dur="7.19s" begin="-2.71s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.26s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.23s" begin="-2.14s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-3.28s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.53s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="20">
          Σ
          <animate attributeName="y" values="-200;600" dur="8.12s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.42s" begin="-2.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-1.81s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.73s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="21">
          7
          <animate attributeName="y" values="-160;640" dur="7.98s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-2.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-3.75s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.24s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Ω
          <animate attributeName="y" values="-120;680" dur="8.91s" begin="-2.92s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.72s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.8s" begin="-2.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-1.79s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="18">
          Ñ
          <animate attributeName="y" values="-80;720" dur="9.13s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.23s" begin="-2.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.32s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          @
          <animate attributeName="y" values="-40;760" dur="7.19s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.42s" begin="-2.35s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          Z
          <animate attributeName="y" values="0;800" dur="8.12s" begin="-3.13s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-2.98s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.61s" begin="-2.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.8;21.8;23" dur="3.7s" begin="-2.69s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.26s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          É
          <animate attributeName="y" values="40;840" dur="7.98s" begin="-3.2s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.85s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.8s" begin="-2.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          ?
          <animate attributeName="y" values="80;880" dur="8.91s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.82s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-2.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-3.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-3.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          δ
          <animate attributeName="y" values="120;920" dur="9.85s" begin="-3.34s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.42s" begin="-2.52s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.6;15.2;17" dur="2.4s" begin="-2.09s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.18s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∞
          <animate attributeName="y" values="160;960" dur="6.83s" begin="-3.41s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.61s" begin="-2.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-4.03s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="200;1000" dur="7.76s" begin="-3.48s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.28s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.8s" begin="-2.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-2.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="240;1040" dur="7.98s" begin="-3.55s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.23s" begin="-2.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.9s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="280;1080" dur="8.91s" begin="-3.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.42s" begin="-2.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-2.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="320;1120" dur="9.85s" begin="-3.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.54s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-2.73s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-2.97s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="360;1160" dur="6.83s" begin="-3.76s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.41s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.8s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.87s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="400;1200" dur="7.76s" begin="-3.83s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.38s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.23s" begin="-2.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="440;1240" dur="8.7s" begin="-3.9s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.42s" begin="-2.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-2.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.63s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="480;1280" dur="8.55s" begin="-3.97s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.61s" begin="-2.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.31s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.14s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="520;1320" dur="9.49s" begin="-4.04s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.84s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.8s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-2.35s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.34s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="560;1360" dur="6.83s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.46s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-2.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-2.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.35s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="600;1400" dur="7.76s" begin="-4.18s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.42s" begin="-3.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.2;21.2;22" dur="3.3s" begin="-2.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.6s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(90.01,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-280" fill="url(#gradGlow)" font-size="18">
          ß
          <animate attributeName="y" values="-280;540" dur="6.37s" begin="-3.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.3s" begin="-2.59s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-1.87s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-2.82s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="21">
          M
          <animate attributeName="y" values="-240;580" dur="6.25s" begin="-3.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-2.64s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-3.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="22">
          鶴
          <animate attributeName="y" values="-200;620" dur="7.03s" begin="-3.88s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.83s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-2.68s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.9;19.9;22" dur="2.1s" begin="-1.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.53s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="19">
          λ
          <animate attributeName="y" values="-160;660" dur="7.22s" begin="-3.95s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.12s" begin="-2.72s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.54s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="18">
          Ü
          <animate attributeName="y" values="-120;700" dur="8s" begin="-4.02s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-2.76s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-2.11s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="20">
          鶴
          <animate attributeName="y" values="-80;740" dur="6.37s" begin="-4.09s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.09s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-2.8s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-2.75s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.35s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="23">
          Q
          <animate attributeName="y" values="-40;780" dur="6.25s" begin="-4.16s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-3.96s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.95s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24;22.5;23" dur="3.5s" begin="-2.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="0;820" dur="7.03s" begin="-4.23s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-4.93s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-2.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.06s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="18">
          3
          <animate attributeName="y" values="40;860" dur="7.82s" begin="-4.3s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-2.93s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.15s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.27s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="17">
          η
          <animate attributeName="y" values="80;900" dur="7.7s" begin="-4.37s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.47s" begin="-2.97s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.8;15.5;17" dur="5.4s" begin="-4.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="20">
          ≈
          <animate attributeName="y" values="120;940" dur="6.06s" begin="-4.44s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.39s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-3.01s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-2.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="160;980" dur="6.25s" begin="-4.51s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-2.66s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.99s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="200;1020" dur="7.03s" begin="-4.58s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.3s" begin="-3.1s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.39s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.24s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="240;1060" dur="7.82s" begin="-4.65s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-3.14s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-3.02s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="280;1100" dur="7.7s" begin="-4.72s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.52s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.95s" begin="-3.18s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-2.66s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.96s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="320;1140" dur="6.06s" begin="-4.79s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.49s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.12s" begin="-3.22s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="360;1180" dur="6.85s" begin="-4.86s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.43s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.72s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="400;1220" dur="6.73s" begin="-4.93s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-4.37s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="440;1260" dur="7.52s" begin="-5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.95s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="3.95s" begin="-3.35s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.9;19.9;22" dur="2.1s" begin="-2.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.43s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="480;1300" dur="7.7s" begin="-5.07s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.57s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.12s" begin="-3.39s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.94s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.44s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="520;1340" dur="6.06s" begin="-5.14s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.3s" begin="-3.43s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="560;1380" dur="6.85s" begin="-5.21s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.47s" begin="-3.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-3.3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.25s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(186.61,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="18">
          C
          <animate attributeName="y" values="-220;540" dur="8.74s" begin="-3.42s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.5s" begin="-2.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-3.86s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="20">
          S
          <animate attributeName="y" values="-180;580" dur="9.94s" begin="-3.49s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.74s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-1.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="22">
          %
          <animate attributeName="y" values="-140;620" dur="10.21s" begin="-3.56s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.99s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21;22" dur="4s" begin="-2.43s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.63s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="19">
          Ψ
          <animate attributeName="y" values="-100;660" dur="11.41s" begin="-3.63s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="6.23s" begin="-3.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.17s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.88s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="17">
          Í
          <animate attributeName="y" values="-60;700" dur="12.6s" begin="-3.7s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.5s" begin="-3.07s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.8;15.8;17" dur="3.7s" begin="-2.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.44s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="21">
          5
          <animate attributeName="y" values="-20;740" dur="8.74s" begin="-3.77s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.07s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.74s" begin="-3.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-2.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="23">
          T
          <animate attributeName="y" values="20;780" dur="9.94s" begin="-3.84s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.04s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.99s" begin="-3.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.6;21.7;23" dur="4.9s" begin="-3.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.15s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="19">
          χ
          <animate attributeName="y" values="60;820" dur="11.13s" begin="-3.91s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="6.23s" begin="-3.2s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.36s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="18">
          8
          <animate attributeName="y" values="100;860" dur="10.95s" begin="-3.98s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.5s" begin="-3.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-4.14s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.86s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="17">
          κ
          <animate attributeName="y" values="140;900" dur="12.14s" begin="-4.05s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.74s" begin="-3.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.9;14.9;17" dur="2.1s" begin="-2.18s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.07s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="20">
          ∈
          <animate attributeName="y" values="180;940" dur="8.74s" begin="-4.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.99s" begin="-3.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-2.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.08s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="220;980" dur="9.94s" begin="-4.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="6.23s" begin="-3.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-2.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="260;1020" dur="11.13s" begin="-4.26s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.5s" begin="-3.41s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="300;1060" dur="10.95s" begin="-4.33s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.63s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.74s" begin="-3.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="340;1100" dur="12.14s" begin="-4.4s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.99s" begin="-3.49s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-3.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="380;1140" dur="9.66s" begin="-4.47s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="6.23s" begin="-3.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-2.49s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.81s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="420;1180" dur="9.48s" begin="-4.54s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.5s" begin="-3.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-4.42s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.31s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="460;1220" dur="10.67s" begin="-4.61s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.06s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.74s" begin="-3.62s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-2.46s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.52s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="500;1260" dur="10.95s" begin="-4.68s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.68s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.99s" begin="-3.66s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.99s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.52s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="540;1300" dur="12.14s" begin="-4.75s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="6.23s" begin="-3.7s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="580;1340" dur="9.66s" begin="-4.82s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.5s" begin="-3.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.36s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.34s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="620;1380" dur="9.48s" begin="-4.89s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.19s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.74s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.49s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(283.21,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-300" fill="url(#gradGlow)" font-size="18">
          D
          <animate attributeName="y" values="-300;540" dur="6.81s" begin="-4.25s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.05s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.76s" begin="-2.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-1.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-2.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-260" fill="url(#gradGlow)" font-size="21">
          L
          <animate attributeName="y" values="-260;580" dur="7.02s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.96s" begin="-2.81s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-2.48s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.72s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="22">
          $
          <animate attributeName="y" values="-220;620" dur="7.9s" begin="-4.39s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.37s" begin="-2.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.2;21.2;22" dur="3.3s" begin="-2.22s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-2.97s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="19">
          β
          <animate attributeName="y" values="-180;660" dur="8.79s" begin="-4.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.57s" begin="-2.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-2.85s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.53s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="17">
          Ó
          <animate attributeName="y" values="-140;700" dur="8.65s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.18s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.76s" begin="-2.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16.5;17" dur="3.5s" begin="-2.49s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.68s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="21">
          1
          <animate attributeName="y" values="-100;740" dur="6.81s" begin="-4.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.15s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.96s" begin="-2.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.24s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="23">
          P
          <animate attributeName="y" values="-60;780" dur="7.7s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.37s" begin="-3.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.6;21.2;23" dur="2.4s" begin="-2.26s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.45s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="19">
          Ξ
          <animate attributeName="y" values="-20;820" dur="7.56s" begin="-4.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-5.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.57s" begin="-3.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-4.95s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18">
          6
          <animate attributeName="y" values="20;860" dur="8.45s" begin="-4.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.76s" begin="-3.1s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-2.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="17">
          ϑ
          <animate attributeName="y" values="60;900" dur="8.65s" begin="-4.88s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.96s" begin="-3.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16;17" dur="4s" begin="-2.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="20">
          ∮
          <animate attributeName="y" values="100;940" dur="6.81s" begin="-4.95s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.37s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-2.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="140;980" dur="7.7s" begin="-5.02s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.87s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.57s" begin="-3.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-3.13s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="180;1020" dur="7.56s" begin="-5.09s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.74s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.76s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21.5;22" dur="3.5s" begin="-2.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.13s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="220;1060" dur="8.45s" begin="-5.16s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.71s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.96s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="260;1100" dur="9.33s" begin="-5.23s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.37s" begin="-3.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="300;1140" dur="6.47s" begin="-5.3s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.57s" begin="-3.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-4.47s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.4s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="340;1180" dur="7.36s" begin="-5.37s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.17s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.76s" begin="-3.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-2.51s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.61s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="380;1220" dur="7.56s" begin="-5.44s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.96s" begin="-3.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-3.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.61s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="420;1260" dur="8.45s" begin="-5.51s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.37s" begin="-3.52s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.78s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.87s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="460;1300" dur="9.33s" begin="-5.58s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.57s" begin="-3.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-3.41s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="500;1340" dur="6.47s" begin="-5.65s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.3s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.76s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-3.05s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.58s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="540;1380" dur="7.36s" begin="-5.72s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.27s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.96s" begin="-3.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-4.29s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.14s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(360.05,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          E
          <animate attributeName="y" values="-240;580" dur="7.12s" begin="-4.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-3.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.35s" begin="-3.42s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-2.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="21">
          V
          <animate attributeName="y" values="-200;620" dur="8.09s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.55s" begin="-3.46s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.06s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="22">
          0
          <animate attributeName="y" values="-160;660" dur="9.06s" begin="-4.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.42s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.74s" begin="-3.5s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.8;20.8;22" dur="3.7s" begin="-2.91s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Γ
          <animate attributeName="y" values="-120;700" dur="8.91s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.29s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.93s" begin="-3.55s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.54s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.77s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="17">
          Ú
          <animate attributeName="y" values="-80;740" dur="9.89s" begin="-4.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.26s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.35s" begin="-3.59s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.6;15.7;17" dur="4.9s" begin="-3.78s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          2
          <animate attributeName="y" values="-40;780" dur="7.87s" begin="-4.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.55s" begin="-3.63s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-2.31s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.53s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          F
          <animate attributeName="y" values="0;820" dur="7.72s" begin="-4.88s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.74s" begin="-3.67s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.8;21.5;23" dur="5.4s" begin="-4.25s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          Ζ
          <animate attributeName="y" values="40;860" dur="8.69s" begin="-4.95s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.72s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.93s" begin="-3.71s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-2.29s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.25s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          4
          <animate attributeName="y" values="80;900" dur="8.91s" begin="-5.02s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.35s" begin="-3.76s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-2.82s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.25s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          θ
          <animate attributeName="y" values="120;940" dur="9.89s" begin="-5.09s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.55s" begin="-3.8s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.2;16.2;17" dur="3.3s" begin="-2.55s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∟
          <animate attributeName="y" values="160;980" dur="7.87s" begin="-5.16s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.98s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.74s" begin="-3.84s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-3.19s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.06s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="200;1020" dur="7.72s" begin="-5.23s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.85s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.93s" begin="-3.88s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-2.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="240;1060" dur="8.69s" begin="-5.3s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.82s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.35s" begin="-3.92s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-4.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="280;1100" dur="9.66s" begin="-5.37s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.55s" begin="-3.97s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-2.59s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.98s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="320;1140" dur="9.51s" begin="-5.44s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.74s" begin="-4.01s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.53s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.49s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="360;1180" dur="7.49s" begin="-5.51s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.28s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.93s" begin="-4.05s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-2.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="400;1220" dur="7.72s" begin="-5.58s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.35s" begin="-4.09s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-3.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.7s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="440;1260" dur="8.69s" begin="-5.65s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.55s" begin="-4.13s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.96s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="480;1300" dur="9.66s" begin="-5.72s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.54s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.74s" begin="-4.18s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.47s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="520;1340" dur="9.51s" begin="-5.79s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.41s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.93s" begin="-4.22s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-3.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.67s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="560;1380" dur="7.49s" begin="-5.86s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.38s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.35s" begin="-4.26s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-4.34s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="600;1420" dur="8.46s" begin="-5.93s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.55s" begin="-4.3s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.43s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(454.46,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-280" fill="url(#gradGlow)" font-size="18">
          F
          <animate attributeName="y" values="-280;580" dur="6.64s" begin="-4.34s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-4.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.66s" begin="-3.79s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-2.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.15s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="21">
          X
          <animate attributeName="y" values="-240;620" dur="7.51s" begin="-4.41s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.53s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.85s" begin="-3.83s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-2.96s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.7s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="22">
          !
          <animate attributeName="y" values="-200;660" dur="7.37s" begin="-4.48s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.28s" begin="-3.87s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21.5;22" dur="3.5s" begin="-2.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.86s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="19">
          Φ
          <animate attributeName="y" values="-160;700" dur="8.24s" begin="-4.55s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.37s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.47s" begin="-3.91s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-3.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="17">
          Å
          <animate attributeName="y" values="-120;740" dur="9.1s" begin="-4.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-3.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.66s" begin="-3.96s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.6;15.2;17" dur="2.4s" begin="-2.37s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.62s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="21">
          %
          <animate attributeName="y" values="-80;780" dur="6.31s" begin="-4.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.85s" begin="-4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-4.3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.13s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="23">
          N
          <animate attributeName="y" values="-40;820" dur="7.18s" begin="-4.76s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.83s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-4.04s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.9;20.9;23" dur="2.1s" begin="-2.34s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="19">
          Π
          <animate attributeName="y" values="0;860" dur="7.37s" begin="-4.83s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.47s" begin="-4.08s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-2.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.34s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="18">
          œ
          <animate attributeName="y" values="40;900" dur="8.24s" begin="-4.9s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.66s" begin="-4.12s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-2.61s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="17">
          μ
          <animate attributeName="y" values="80;940" dur="9.1s" begin="-4.97s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.09s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.85s" begin="-4.17s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.8;15.8;17" dur="3.7s" begin="-3.25s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.15s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="20">
          ∴
          <animate attributeName="y" values="120;980" dur="6.31s" begin="-5.04s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.96s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.28s" begin="-4.21s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-2.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.31s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="160;1020" dur="7.18s" begin="-5.11s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.93s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.47s" begin="-4.25s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-4.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.86s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="200;1060" dur="8.04s" begin="-5.18s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.66s" begin="-4.29s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-2.65s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.07s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="240;1100" dur="7.91s" begin="-5.25s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.85s" begin="-4.33s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-4.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.58s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="280;1140" dur="8.77s" begin="-5.32s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.39s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.28s" begin="-4.38s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-2.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="320;1180" dur="6.31s" begin="-5.39s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.47s" begin="-4.42s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-3.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.79s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="360;1220" dur="7.18s" begin="-5.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.66s" begin="-4.46s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-2.89s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="400;1260" dur="8.04s" begin="-5.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.85s" begin="-4.5s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.8;20.8;22" dur="3.7s" begin="-3.52s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="440;1300" dur="7.91s" begin="-5.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.52s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.28s" begin="-4.54s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-3.16s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.76s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="480;1340" dur="8.77s" begin="-5.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.49s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.95;0.06" dur="4.47s" begin="-4.59s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-4.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.31s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="520;1380" dur="6.98s" begin="-5.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.66s" begin="-4.63s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.93s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.52s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="560;1420" dur="6.84s" begin="-5.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.87;0.06" dur="4.85s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-4.87s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.02s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(551.06,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          G
          <animate attributeName="y" values="-240;540" dur="8.84s" begin="-4.22s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-3.64s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.91s" begin="-2.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-3.02s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-3.79s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="21">
          Y
          <animate attributeName="y" values="-200;580" dur="8.67s" begin="-4.29s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.51s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.13s" begin="-2.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-2.65s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-2.95s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="22">
          @
          <animate attributeName="y" values="-160;620" dur="9.77s" begin="-4.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.48s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.35s" begin="-2.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-3.89s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.5s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Υ
          <animate attributeName="y" values="-120;660" dur="10.86s" begin="-4.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.57s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.42s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.71s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="17">
          Í
          <animate attributeName="y" values="-80;700" dur="10.7s" begin="-4.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.91s" begin="-2.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.8;15.5;17" dur="5.4s" begin="-4.36s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          ρ
          <animate attributeName="y" values="-40;740" dur="8.42s" begin="-4.57s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.13s" begin="-2.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-2.4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          Æ
          <animate attributeName="y" values="0;780" dur="8.67s" begin="-4.64s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.35s" begin="-2.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24;22;23" dur="4s" begin="-2.93s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.43s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          W
          <animate attributeName="y" values="40;820" dur="9.77s" begin="-4.71s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.57s" begin="-2.95s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.68s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          ħ
          <animate attributeName="y" values="80;860" dur="10.86s" begin="-4.78s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.91s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-3.3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.24s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          ξ
          <animate attributeName="y" values="120;900" dur="10.7s" begin="-4.85s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.07s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.13s" begin="-3.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16.5;17" dur="3.5s" begin="-2.94s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.4s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∠
          <animate attributeName="y" values="160;940" dur="8.42s" begin="-4.92s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.04s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.35s" begin="-3.07s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-4.17s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.95s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="200;980" dur="9.52s" begin="-4.99s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.57s" begin="-3.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.16s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="240;1020" dur="9.35s" begin="-5.06s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.91s" begin="-3.16s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.64s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.66s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="280;1060" dur="10.44s" begin="-5.13s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.13s" begin="-3.2s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-2.68s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.87s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="320;1100" dur="10.7s" begin="-5.2s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.35s" begin="-3.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21;22" dur="4s" begin="-3.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.88s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="360;1140" dur="8.42s" begin="-5.27s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.57s" begin="-3.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-2.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.13s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="400;1180" dur="9.52s" begin="-5.34s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="4.91s" begin="-3.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="440;1220" dur="9.35s" begin="-5.41s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.63s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.13s" begin="-3.37s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-3.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="480;1260" dur="10.44s" begin="-5.48s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.35s" begin="-3.41s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-4.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.4s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="520;1300" dur="11.54s" begin="-5.55s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.93;0.06" dur="5.57s" begin="-3.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.99s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.61s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="560;1340" dur="8s" begin="-5.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.91s" begin="-3.49s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-4.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.11s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="600;1380" dur="9.1s" begin="-5.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.06s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="5.13s" begin="-3.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-2.96s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.32s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(627.9,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-260" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="-260;580" dur="6.2s" begin="-3.24s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-4.62s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.31s" begin="-2.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-2.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="21">
          T
          <animate attributeName="y" values="-220;620" dur="7.05s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.59s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.49s" begin="-2.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-3.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.59s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="22">
          8
          <animate attributeName="y" values="-180;660" dur="7.9s" begin="-3.38s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-2.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-2.48s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.8s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="19">
          ϖ
          <animate attributeName="y" values="-140;700" dur="7.76s" begin="-3.45s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.14s" begin="-2.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.42s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="17">
          Ê
          <animate attributeName="y" values="-100;740" dur="8.61s" begin="-3.52s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.05s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.31s" begin="-2.49s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.9;14.9;17" dur="2.1s" begin="-2.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="21">
          σ
          <animate attributeName="y" values="-60;780" dur="6.2s" begin="-3.59s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-2.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-2.99s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.52s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="23">
          Ğ
          <animate attributeName="y" values="-20;820" dur="7.05s" begin="-3.66s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="3.96s" begin="-2.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.2;22.2;23" dur="3.3s" begin="-2.72s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.77s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="19">
          V
          <animate attributeName="y" values="20;860" dur="7.9s" begin="-3.73s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.31s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.14s" begin="-2.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.35s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="18">
          ň
          <animate attributeName="y" values="60;900" dur="7.76s" begin="-3.8s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.18s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-2.66s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17.5;18" dur="3.5s" begin="-2.99s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="17">
          ς
          <animate attributeName="y" values="100;940" dur="8.61s" begin="-3.87s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.15s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.49s" begin="-2.7s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.6;15.7;17" dur="4.9s" begin="-4.22s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="20">
          ∵
          <animate attributeName="y" values="140;980" dur="6.85s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="3.96s" begin="-2.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-2.76s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.25s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="180;1020" dur="6.72s" begin="-4.01s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.14s" begin="-2.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.8;20.5;22" dur="5.4s" begin="-4.7s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.75s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="220;1060" dur="7.57s" begin="-4.08s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.61s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.31s" begin="-2.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-2.73s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.96s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="260;1100" dur="7.76s" begin="-4.15s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.49s" begin="-2.87s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-3.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.96s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="300;1140" dur="8.61s" begin="-4.22s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="3.96s" begin="-2.91s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.2;17.2;18" dur="3.3s" begin="-3s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="340;1180" dur="6.85s" begin="-4.29s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.87s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.14s" begin="-2.95s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-3.63s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="380;1220" dur="6.72s" begin="-4.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.74s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.31s" begin="-2.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-3.27s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.93s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="420;1260" dur="7.57s" begin="-4.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.71s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-3.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-4.51s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.49s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="460;1300" dur="8.42s" begin="-4.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="3.96s" begin="-3.08s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.6;18.2;20" dur="2.4s" begin="-3.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="500;1340" dur="8.29s" begin="-4.57s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.14s" begin="-3.12s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.97s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="540;1380" dur="6.52s" begin="-4.64s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.17s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.31s" begin="-3.16s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-3.01s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.41s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="580;1420" dur="6.72s" begin="-4.71s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.79s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.89;0.06" dur="4.49s" begin="-3.2s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-3.55s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.41s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(711.33,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="18">
          I
          <animate attributeName="y" values="-220;540" dur="7.73s" begin="-6.72s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-5.7s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.49s" begin="-5.13s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-4s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-4.68s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="21">
          P
          <animate attributeName="y" values="-180;580" dur="8.74s" begin="-6.79s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.69s" begin="-5.17s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-2.53s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.89s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="22">
          6
          <animate attributeName="y" values="-140;620" dur="8.58s" begin="-6.86s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.54s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.89s" begin="-5.22s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.8;20.5;22" dur="5.4s" begin="-4.47s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.39s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="19">
          ϱ
          <animate attributeName="y" values="-100;660" dur="9.59s" begin="-6.93s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.16s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.09s" begin="-5.26s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-2.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="17">
          Ë
          <animate attributeName="y" values="-60;700" dur="9.82s" begin="-7s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.49s" begin="-5.3s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16;17" dur="4s" begin="-3.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="21">
          ϙ
          <animate attributeName="y" values="-20;740" dur="7.73s" begin="-7.07s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.69s" begin="-5.34s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-2.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.86s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="23">
          Ð
          <animate attributeName="y" values="20;780" dur="8.74s" begin="-7.14s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.42s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.89s" begin="-5.38s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.8;21.8;23" dur="3.7s" begin="-3.41s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="19">
          U
          <animate attributeName="y" values="60;820" dur="8.58s" begin="-7.21s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.29s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.09s" begin="-5.43s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-3.04s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.57s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="18">
          ŕ
          <animate attributeName="y" values="100;860" dur="9.59s" begin="-7.28s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.26s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-5.47s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-4.28s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.13s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="17">
          Ϟ
          <animate attributeName="y" values="140;900" dur="10.59s" begin="-7.35s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.69s" begin="-5.51s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.6;15.2;17" dur="2.4s" begin="-2.81s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.33s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="20">
          ∗
          <animate attributeName="y" values="180;940" dur="7.34s" begin="-7.42s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.89s" begin="-5.55s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-4.75s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="220;980" dur="8.35s" begin="-7.49s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.72s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="5.09s" begin="-5.59s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-2.78s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.05s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="260;1020" dur="8.58s" begin="-7.56s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.34s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.49s" begin="-5.64s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-3.32s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.05s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="300;1060" dur="9.59s" begin="-7.63s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.69s" begin="-5.68s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-3.05s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.31s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="340;1100" dur="10.59s" begin="-7.7s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.98s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.89s" begin="-5.72s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-3.69s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.86s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="380;1140" dur="7.34s" begin="-7.77s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.85s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="5.09s" begin="-5.76s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-3.32s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.02s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="420;1180" dur="8.35s" begin="-7.84s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.82s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="4.49s" begin="-5.8s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-4.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.58s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="460;1220" dur="9.35s" begin="-7.91s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.69s" begin="-5.85s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-3.09s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="500;1260" dur="9.2s" begin="-7.98s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.89s" begin="-5.89s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.8;18.5;20" dur="5.4s" begin="-5.03s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.29s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="540;1300" dur="10.21s" begin="-8.05s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.28s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.92;0.06" dur="5.09s" begin="-5.93s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.9;19.9;22" dur="2.1s" begin="-3.06s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.49s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="580" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="580;1340" dur="7.34s" begin="-8.12s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.9s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.49s" begin="-5.97s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-3.6s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.5s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="620" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="620;1380" dur="8.35s" begin="-8.19s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.85;0.06" dur="4.69s" begin="-6.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-3.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.76s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(788.17,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-300" fill="url(#gradGlow)" font-size="18">
          ¿
          <animate attributeName="y" values="-300;580" dur="7.16s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.61s" begin="-3.14s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.59s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-3.97s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-260" fill="url(#gradGlow)" font-size="21">
          N
          <animate attributeName="y" values="-260;620" dur="7.03s" begin="-4.39s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.8s" begin="-3.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.8;19.5;21" dur="5.4s" begin="-4.53s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-220" fill="url(#gradGlow)" font-size="22">
          5
          <animate attributeName="y" values="-220;660" dur="7.91s" begin="-4.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.27s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-3.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.9;19.9;22" dur="2.1s" begin="-2.56s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-180" fill="url(#gradGlow)" font-size="19">
          ϗ
          <animate attributeName="y" values="-180;700" dur="8.12s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-4.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.42s" begin="-3.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-3.09s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.69s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-140" fill="url(#gradGlow)" font-size="17">
          Ę
          <animate attributeName="y" values="-140;740" dur="9s" begin="-4.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.61s" begin="-3.31s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.2;16.2;17" dur="3.3s" begin="-2.83s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-3.95s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-100" fill="url(#gradGlow)" font-size="21">
          ϛ
          <animate attributeName="y" values="-100;780" dur="7.16s" begin="-4.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.8s" begin="-3.35s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.8;19.8;21" dur="3.7s" begin="-3.46s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.5s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-60" fill="url(#gradGlow)" font-size="23">
          Ç
          <animate attributeName="y" values="-60;820" dur="7.03s" begin="-4.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.23s" begin="-3.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24;22.5;23" dur="3.5s" begin="-3.1s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.66s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-20" fill="url(#gradGlow)" font-size="19">
          R
          <animate attributeName="y" values="-20;860" dur="7.91s" begin="-4.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.37s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.42s" begin="-3.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.6;17.7;19" dur="4.9s" begin="-4.33s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="20" fill="url(#gradGlow)" font-size="18">
          ś
          <animate attributeName="y" values="20;900" dur="8.8s" begin="-4.88s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-4.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-3.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.6;16.2;18" dur="2.4s" begin="-2.87s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.42s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="60" fill="url(#gradGlow)" font-size="17">
          ϟ
          <animate attributeName="y" values="60;940" dur="8.66s" begin="-4.95s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.8s" begin="-3.52s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18.8;15.5;17" dur="5.4s" begin="-4.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.93s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="100" fill="url(#gradGlow)" font-size="20">
          ∯
          <animate attributeName="y" values="100;980" dur="6.82s" begin="-5.02s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.83s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.23s" begin="-3.56s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.9;17.9;20" dur="2.1s" begin="-2.84s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.13s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="140" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="140;1020" dur="7.03s" begin="-5.09s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.45s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.42s" begin="-3.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-3.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.14s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="180" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="180;1060" dur="7.91s" begin="-5.16s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.22s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.61s" begin="-3.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-3.11s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.4s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="220" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="220;1100" dur="8.8s" begin="-5.23s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.09s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.8s" begin="-3.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.74s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.95s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="260" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="260;1140" dur="8.66s" begin="-5.3s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.96s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.23s" begin="-3.73s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-3.38s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.11s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="300" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="300;1180" dur="6.82s" begin="-5.37s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.93s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.42s" begin="-3.77s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.6;18.7;20" dur="4.9s" begin="-4.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.66s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="340" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="340;1220" dur="7.71s" begin="-5.44s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.55s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.61s" begin="-3.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;22.6;20.2;22" dur="2.4s" begin="-3.15s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.87s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="380" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="380;1260" dur="7.57s" begin="-5.51s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.8s" begin="-3.86s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-5.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.38s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="420" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="420;1300" dur="8.46s" begin="-5.58s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.39s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.23s" begin="-3.9s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.9;16.9;19" dur="2.1s" begin="-3.12s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.58s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="460" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="460;1340" dur="8.66s" begin="-5.65s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-6.01s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.96;0.06" dur="4.42s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19;17;18" dur="4s" begin="-3.65s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.59s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="500" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="500;1380" dur="6.82s" begin="-5.72s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.78s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.61s" begin="-3.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-3.39s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="540" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="540;1420" dur="7.71s" begin="-5.79s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.65s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.88;0.06" dur="4.8s" begin="-4.03s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-4.03s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.4s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(880.38,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="18">
          K
          <animate attributeName="y" values="-240;540" dur="8s" begin="-6.34s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-6.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.94s" begin="-4.24s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-4.58s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-5.57s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="21">
          C
          <animate attributeName="y" values="-200;580" dur="9.09s" begin="-6.41s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.38s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.16s" begin="-4.28s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-2.62s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.77s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="22">
          4
          <animate attributeName="y" values="-160;620" dur="9.34s" begin="-6.48s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.38s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21;22" dur="4s" begin="-3.15s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.78s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="19">
          Ϥ
          <animate attributeName="y" values="-120;660" dur="10.44s" begin="-6.55s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.6s" begin="-4.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-2.88s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="17">
          Ě
          <animate attributeName="y" values="-80;700" dur="11.53s" begin="-6.62s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.64s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.94s" begin="-4.41s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.8;15.8;17" dur="3.7s" begin="-3.52s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.59s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="21">
          ϝ
          <animate attributeName="y" values="-40;740" dur="8s" begin="-6.69s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.51s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.16s" begin="-4.45s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20.5;21" dur="3.5s" begin="-3.15s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.75s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="23">
          Ō
          <animate attributeName="y" values="0;780" dur="9.09s" begin="-6.76s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.48s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.38s" begin="-4.49s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;24.6;21.7;23" dur="4.9s" begin="-4.39s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.3s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="19">
          S
          <animate attributeName="y" values="40;820" dur="10.18s" begin="-6.83s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.6s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-2.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.51s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="18">
          ž
          <animate attributeName="y" values="80;860" dur="10.02s" begin="-6.9s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.32s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.94s" begin="-4.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-4.86s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.02s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="17">
          ϡ
          <animate attributeName="y" values="120;900" dur="11.11s" begin="-6.97s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.94s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.16s" begin="-4.62s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;17.9;14.9;17" dur="2.1s" begin="-2.9s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.22s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="20">
          ∼
          <animate attributeName="y" values="160;940" dur="8s" begin="-7.04s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.56s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.38s" begin="-4.66s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-3.43s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.23s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="200;980" dur="9.09s" begin="-7.11s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.33s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.6s" begin="-4.7s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-3.17s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.48s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="240;1020" dur="10.18s" begin="-7.18s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="4.94s" begin="-4.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-3.8s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.04s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="280;1060" dur="10.02s" begin="-7.25s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.07s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.16s" begin="-4.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23;21.5;22" dur="3.5s" begin="-3.44s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.2s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="320;1100" dur="11.11s" begin="-7.32s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-7.04s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.38s" begin="-4.83s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-4.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.75s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="360;1140" dur="8.84s" begin="-7.39s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.66s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.6s" begin="-4.87s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.6;17.2;19" dur="2.4s" begin="-3.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.96s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="400;1180" dur="8.67s" begin="-7.46s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="4.94s" begin="-4.91s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.8;16.5;18" dur="5.4s" begin="-5.14s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.46s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="440;1220" dur="9.76s" begin="-7.53s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.5s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="5.16s" begin="-4.95s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-3.18s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.67s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="480;1260" dur="10.02s" begin="-7.6s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-6.12s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.38s" begin="-4.99s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18;19" dur="4s" begin="-3.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.68s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="520;1300" dur="11.11s" begin="-7.67s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.89s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.9;0.06" dur="5.6s" begin="-5.04s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.2;20.2;21" dur="3.3s" begin="-3.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.93s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="560;1340" dur="8.84s" begin="-7.74s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.76s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.97;0.06" dur="4.94s" begin="-5.08s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;20.8;18.8;20" dur="3.7s" begin="-4.08s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.49s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="600" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="600;1380" dur="8.67s" begin="-7.81s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.63s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.83;0.06" dur="5.16s" begin="-5.12s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-3.71s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.64s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
    <g transform="translate(966,0)">
      <g filter="url(#trailGlow)">
        <text x="0" y="-280" fill="url(#gradGlow)" font-size="18">
          ψ
          <animate attributeName="y" values="-280;580" dur="7.01s" begin="-5.03s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-4.49s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.59s" begin="-3.94s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-2.67s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-3.86s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-240" fill="url(#gradGlow)" font-size="21">
          E
          <animate attributeName="y" values="-240;620" dur="7.22s" begin="-5.1s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.11s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.77s" begin="-3.98s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22;20;21" dur="4s" begin="-3.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-3.87s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-200" fill="url(#gradGlow)" font-size="22">
          3
          <animate attributeName="y" values="-200;660" dur="8.13s" begin="-5.17s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-5.88s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-4.02s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.2;21.2;22" dur="3.3s" begin="-2.94s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.12s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-160" fill="url(#gradGlow)" font-size="19">
          Θ
          <animate attributeName="y" values="-160;700" dur="9.05s" begin="-5.24s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-4.75s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.4s" begin="-4.06s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-3.57s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-4.68s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-120" fill="url(#gradGlow)" font-size="17">
          Á
          <animate attributeName="y" values="-120;740" dur="8.91s" begin="-5.31s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-5.62s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.59s" begin="-4.11s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16.5;17" dur="3.5s" begin="-3.21s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-3.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-80" fill="url(#gradGlow)" font-size="21">
          Δ
          <animate attributeName="y" values="-80;780" dur="7.01s" begin="-5.38s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-6.59s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.77s" begin="-4.15s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;22.6;19.7;21" dur="4.9s" begin="-4.45s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.39s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="-40" fill="url(#gradGlow)" font-size="23">
          Š
          <animate attributeName="y" values="-40;820" dur="7.92s" begin="-5.45s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.21s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.21s" begin="-4.19s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="23;23.6;21.2;23" dur="2.4s" begin="-2.98s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-4.6s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="0" fill="url(#gradGlow)" font-size="19">
          T
          <animate attributeName="y" values="0;860" dur="7.78s" begin="-5.52s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.43s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.4s" begin="-4.23s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-4.92s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.1s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="40" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="40;900" dur="8.7s" begin="-5.59s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.05s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-4.27s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.9;15.9;18" dur="2.1s" begin="-2.95s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.31s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="80" fill="url(#gradGlow)" font-size="17">
          β
          <animate attributeName="y" values="80;940" dur="8.91s" begin="-5.66s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-5.67s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.77s" begin="-4.32s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="17;18;16;17" dur="4s" begin="-3.48s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.32s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="120" fill="url(#gradGlow)" font-size="20">
          ⊕
          <animate attributeName="y" values="120;980" dur="7.01s" begin="-5.73s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-6.44s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.21s" begin="-4.36s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21.2;19.2;20" dur="3.3s" begin="-3.22s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-4.57s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="160" fill="url(#gradGlow)" font-size="18">
          ñ
          <animate attributeName="y" values="160;1020" dur="7.92s" begin="-5.8s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.31s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.4s" begin="-4.4s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;18.8;16.8;18" dur="3.7s" begin="-3.85s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.13s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="200" fill="url(#gradGlow)" font-size="19">
          #
          <animate attributeName="y" values="200;1060" dur="7.78s" begin="-5.87s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.18s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.59s" begin="-4.44s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20;18.5;19" dur="3.5s" begin="-3.49s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.28s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="240" fill="url(#gradGlow)" font-size="18">
          ξ
          <animate attributeName="y" values="240;1100" dur="8.7s" begin="-5.94s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-7.15s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.77s" begin="-4.48s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="18;19.6;16.7;18" dur="4.9s" begin="-4.72s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-5.84s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="280" fill="url(#gradGlow)" font-size="21">
          Þ
          <animate attributeName="y" values="280;1140" dur="9.61s" begin="-6.01s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.4;1;0.5;0.4" dur="1.7s" begin="-5.77s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.21s" begin="-4.53s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.6;19.2;21" dur="2.4s" begin="-3.26s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-14;0,3;0,-9;0,-14" dur="2.1s" begin="-5.05s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="320" fill="url(#gradGlow)" font-size="19">
          ¡
          <animate attributeName="y" values="320;1180" dur="6.66s" begin="-6.08s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.22;0.9;0.3;0.22" dur="5.6s" begin="-7.99s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.4s" begin="-4.57s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.8;17.5;19" dur="5.4s" begin="-5.2s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,5;0,-8;0,-6" dur="6.8s" begin="-6.55s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="360" fill="url(#gradGlow)" font-size="21">
          ψ
          <animate attributeName="y" values="360;1220" dur="7.57s" begin="-6.15s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.32;0.96;0.4;0.32" dur="1.4s" begin="-5.61s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.59s" begin="-4.61s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="21;21.9;18.9;21" dur="2.1s" begin="-3.23s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-18;0,8;0,-11;0,-18" dur="1.9s" begin="-4.76s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="400" fill="url(#gradGlow)" font-size="20">
          Ł
          <animate attributeName="y" values="400;1260" dur="7.78s" begin="-6.22s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.3;0.95;0.3" dur="2.6s" begin="-6.23s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.77s" begin="-4.65s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19;20" dur="4s" begin="-3.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-8;0,4;0,-5;0,-8" dur="3.4s" begin="-4.76s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="440" fill="url(#gradGlow)" font-size="19">
          ¿
          <animate attributeName="y" values="440;1300" dur="8.7s" begin="-6.29s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.25;0.88;0.28;0.25" dur="2.2s" begin="-7s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.21s" begin="-4.69s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;20.2;18.2;19" dur="3.3s" begin="-3.5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-6;0,2;0,-4;0,-6" dur="2.9s" begin="-5.02s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="480" fill="url(#gradGlow)" font-size="19">
          ß
          <animate attributeName="y" values="480;1340" dur="9.61s" begin="-6.36s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.2;0.92;0.2" dur="3.1s" begin="-5.87s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.94;0.06" dur="4.4s" begin="-4.74s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="19;19.8;17.8;19" dur="3.7s" begin="-4.13s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-10;0,5;0,-3;0,-10" dur="3.6s" begin="-5.58s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="520" fill="url(#gradGlow)" font-size="20">
          ø
          <animate attributeName="y" values="520;1380" dur="6.66s" begin="-6.43s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.34;0.9;0.34" dur="2.4s" begin="-6.74s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.98;0.06" dur="4.59s" begin="-4.78s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="20;21;19.5;20" dur="3.5s" begin="-3.77s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-7;0,3;0,-6;0,-7" dur="3s" begin="-4.73s" repeatCount="indefinite" additive="sum"/>
        </text>
        <text x="0" y="560" fill="url(#gradGlow)" font-size="22">
          Σ
          <animate attributeName="y" values="560;1420" dur="7.57s" begin="-6.5s" repeatCount="indefinite"/>
          <animate attributeName="fill-opacity" values="0.18;0.82;0.24;0.18" dur="4.8s" begin="-7.71s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.08;0.86;0.06" dur="4.77s" begin="-4.82s" repeatCount="indefinite"/>
          <animate attributeName="font-size" values="22;23.6;20.7;22" dur="4.9s" begin="-5s" repeatCount="indefinite"/>
          <animateTransform attributeName="transform" type="translate" values="0,-5;0,6;0,-7;0,-5" dur="6.3s" begin="-6.29s" repeatCount="indefinite" additive="sum"/>
        </text>
      </g>
    </g>
  </g>
  <g id="lightning" pointer-events="none">
    <rect x="0" y="0" width="966" height="500" fill="url(#flashGlow)" opacity="0">
      <animate attributeName="opacity" values="0;0;0.88;0" keyTimes="0;0.8;0.84;1" dur="12s" repeatCount="indefinite"/>
    </rect>
    <polyline points="483,-60 506.18,80 467.54,170 502.32,260 459.82,360 486.86,480 475.27,560" stroke="url(#gradBolt)" stroke-width="12" stroke-linecap="round" stroke-linejoin="round" fill="none" opacity="0" filter="url(#softGlow)">
      <animate attributeName="opacity" values="0;0;1;0" keyTimes="0;0.82;0.86;1" dur="12s" repeatCount="indefinite"/>
      <animate attributeName="stroke-width" values="12;16;12" dur="12s" begin="-0.4s" repeatCount="indefinite"/>
      <animate attributeName="stroke-dashoffset" values="0;-140;0" dur="0.9s" repeatCount="indefinite"/>
    </polyline>
  </g>
</svg>
