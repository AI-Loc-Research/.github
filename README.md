
<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:080808,45:1A1A1A,75:2B2B2B,100:101010&height=190&section=header&text=AI%20Research&fontSize=46&fontColor=FFFFFF&fontAlignY=36&desc=LOSS%20OF%20CONTROL&descSize=18&descColor=BDBDBD&descAlignY=57" alt="AI Research — Loss of Control" />

**Understanding AI risk. Preserving human control.**

![AI Safety](https://img.shields.io/badge/FOCUS-AI_SAFETY-CFCFCF?style=for-the-badge&labelColor=111111)
![Loss of Control](https://img.shields.io/badge/RESEARCH-LOSS_OF_CONTROL-8D8D8D?style=for-the-badge&labelColor=111111)
![Open Research](https://img.shields.io/badge/STATUS-OPEN_RESEARCH-FFFFFF?style=for-the-badge&labelColor=111111)

[Explore research](https://github.com/YOUR_ORG?tab=repositories) · [Get in touch](mailto:YOUR_EMAIL)

</div>

---

## 🎯 Our Mission

We investigate how **human control over increasingly capable AI systems could fail**—and develop evidence, evaluations, and safeguards to reduce that risk.

## 🔬 Research Directions

<div align="center">
  <img src="../assets/research-directions.svg" width="100%" alt="Animated visualization of our research directions: Failure Modes, Evaluations, and Safeguards" />
</div>

<br />

| Direction | Core question |
| :-- | :-- |
| **Failure Modes** | How could advanced AI undermine meaningful human control? |
| **Evaluations** | What tests reveal dangerous capabilities and oversight failures? |
| **Safeguards** | How can monitoring, intervention, and shutdown become more reliable? |

## 🧭 Principles

> **Evidence over hype.**  
> We make assumptions explicit, communicate uncertainty clearly, and share research responsibly.

## 🤝 Collaborate

We welcome researchers, engineers, and critical thinkers working on:

`AI evaluations` · `control methods` · `alignment` · `interpretability` · `governance` · `safety tooling`

[**Start a conversation →**](mailto:YOUR_EMAIL)

---

<div align="center">
  <sub>Better evidence. Stronger safeguards. Meaningful control.</sub>
</div>

---

<div align="center">
  <sub>Better evidence. Stronger safeguards. Meaningful control.</sub>
</div>


<svg width="1200" height="270" viewBox="0 0 1200 270" fill="none" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="background" x1="0" y1="0" x2="1200" y2="270" gradientUnits="userSpaceOnUse">
      <stop stop-color="#0A0A0A"/>
      <stop offset="0.5" stop-color="#1B1B1B"/>
      <stop offset="1" stop-color="#101010"/>
    </linearGradient>

    <linearGradient id="line" x1="160" y1="135" x2="1040" y2="135" gradientUnits="userSpaceOnUse">
      <stop stop-color="#777777" stop-opacity="0.15"/>
      <stop offset="0.5" stop-color="#FFFFFF"/>
      <stop offset="1" stop-color="#777777" stop-opacity="0.15"/>
    </linearGradient>

    <filter id="glow" x="-80%" y="-80%" width="260%" height="260%">
      <feGaussianBlur stdDeviation="7" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>

    <style>
      .card { fill: #151515; stroke: #3A3A3A; stroke-width: 1; }
      .title { fill: #F5F5F5; font-family: Arial, Helvetica, sans-serif; font-size: 19px; font-weight: 700; }
      .body { fill: #969696; font-family: Arial, Helvetica, sans-serif; font-size: 13px; }
      .icon { stroke: #F1F1F1; stroke-width: 2; stroke-linecap: round; stroke-linejoin: round; fill: none; }
      .node { fill: #F1F1F1; }
      .connector { stroke: url(#line); stroke-width: 1.5; stroke-dasharray: 5 8; }
    </style>
  </defs>

  <!-- Background -->
  <rect width="1200" height="270" rx="18" fill="url(#background)"/>
  <rect x="1" y="1" width="1198" height="268" rx="17" stroke="#303030"/>

  <!-- Connecting line -->
  <path class="connector" d="M310 135H445M755 135H890">
    <animate attributeName="stroke-dashoffset" values="0;-26" dur="2s" repeatCount="indefinite"/>
  </path>

  <!-- Card 1: Failure Modes -->
  <g>
    <rect class="card" x="55" y="45" width="255" height="180" rx="14"/>
    <circle cx="182.5" cy="91" r="25" fill="#212121" stroke="#4A4A4A"/>
    
    <!-- Warning / failure icon -->
    <path class="icon" d="M182.5 77L196 102H169L182.5 77Z"/>
    <path class="icon" d="M182.5 86V93"/>
    <circle class="node" cx="182.5" cy="97.5" r="1.5"/>

    <text class="title" x="182.5" y="145" text-anchor="middle">Failure Modes</text>
    <text class="body" x="182.5" y="170" text-anchor="middle">How can control fail?</text>
    <text class="body" x="182.5" y="190" text-anchor="middle">Map risks before they scale.</text>

    <circle cx="182.5" cy="91" r="31" stroke="#FFFFFF" stroke-opacity="0.18" stroke-width="1">
      <animate attributeName="r" values="31;40;31" dur="2.6s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.45;0;0.45" dur="2.6s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- Central animated signal -->
  <g filter="url(#glow)">
    <circle cx="600" cy="135" r="7" fill="#FFFFFF">
      <animate attributeName="r" values="6;9;6" dur="1.8s" repeatCount="indefinite"/>
    </circle>
  </g>
  <circle cx="600" cy="135" r="20" stroke="#FFFFFF" stroke-opacity="0.3">
    <animate attributeName="r" values="16;34;16" dur="1.8s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.55;0;0.55" dur="1.8s" repeatCount="indefinite"/>
  </circle>

  <!-- Card 2: Evaluations -->
  <g>
    <rect class="card" x="472" y="45" width="255" height="180" rx="14"/>
    <circle cx="599.5" cy="91" r="25" fill="#212121" stroke="#4A4A4A"/>

    <!-- Evaluation / scan icon -->
    <rect class="icon" x="588" y="79" width="23" height="23" rx="3"/>
    <path class="icon" d="M592 91L597 96L607 85"/>

    <text class="title" x="599.5" y="145" text-anchor="middle">Evaluations</text>
    <text class="body" x="599.5" y="170" text-anchor="middle">What signals reveal risk?</text>
    <text class="body" x="599.5" y="190" text-anchor="middle">Measure capability and oversight.</text>

    <path d="M580 91H619" stroke="#FFFFFF" stroke-opacity="0.45" stroke-width="1">
      <animate attributeName="x1" values="580;619;580" dur="2s" repeatCount="indefinite"/>
      <animate attributeName="x2" values="580;619;580" dur="2s" repeatCount="indefinite"/>
    </path>
  </g>

  <!-- Card 3: Safeguards -->
  <g>
    <rect class="card" x="890" y="45" width="255" height="180" rx="14"/>
    <circle cx="1017.5" cy="91" r="25" fill="#212121" stroke="#4A4A4A"/>

    <!-- Shield icon -->
    <path class="icon" d="M1017.5 76L1029 81V90C1029 98 1024 104 1017.5 107C1011 104 1006 98 1006 90V81L1017.5 76Z"/>
    <path class="icon" d="M1012 91L1016 95L1023 87"/>

    <text class="title" x="1017.5" y="145" text-anchor="middle">Safeguards</text>
    <text class="body" x="1017.5" y="170" text-anchor="middle">How do we retain control?</text>
    <text class="body" x="1017.5" y="190" text-anchor="middle">Build reliable interventions.</text>

    <circle cx="1017.5" cy="91" r="31" stroke="#FFFFFF" stroke-opacity="0.15" stroke-width="1">
      <animate attributeName="r" values="31;37;31" dur="2.2s" repeatCount="indefinite"/>
      <animate attributeName="opacity" values="0.4;0.05;0.4" dur="2.2s" repeatCount="indefinite"/>
    </circle>
  </g>
</svg>
