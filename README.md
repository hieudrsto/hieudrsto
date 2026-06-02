<!-- BANNER CHIP LAYOUT (EDA STYLED) -->
<p align="center">
  <svg width="100%" height="180" viewBox="0 0 800 180" fill="none" xmlns="http://www.w3.org/2000/svg" style="background: #0B132B; border-radius: 10px; border: 1px solid #00FFCC;">
    <!-- Grid Cao Cấp Phong Cách EDA -->
    <defs>
      <pattern id="eda-grid" width="20" height="20" patternUnits="userSpaceOnUse">
        <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#1C2541" stroke-width="1"/>
      </pattern>
      <!-- Hiệu ứng Glow cho Chữ -->
      <filter id="glow" x="-20%" y="-20%" width="140%" height="140%">
        <feGaussianBlur stdDeviation="4" result="blur" />
        <feComposite in="SourceGraphic" in2="blur" operator="over" />
      </filter>
    </defs>
    <rect width="100%" height="100%" fill="url(#eda-grid)" />
    
    <!-- Mô Phỏng Đường Dây IC (Routing Track) -->
    <path d="M -10 30 L 150 30 L 180 60 L 400 60" stroke="#00FFCC" stroke-width="1.5" opacity="0.4" stroke-dasharray="5,5" />
    <path d="M 810 150 L 650 150 L 620 120 L 500 120" stroke="#48CAE4" stroke-width="1.5" opacity="0.4" />
    <path d="M 200 180 L 200 130 L 230 100 L 350 100" stroke="#3A0CA3" stroke-width="2" opacity="0.3" />
    
    <!-- Các Khối Chip Layout (Standard Cells) -->
    <rect x="40" y="70" width="80" height="50" rx="4" fill="#1C2541" stroke="#00FFCC" stroke-width="1.5" opacity="0.8" />
    <line x1="45" y1="85" x2="115" y2="85" stroke="#00FFCC" stroke-width="1" opacity="0.5" />
    <line x1="45" y1="100" x2="95" y2="100" stroke="#00FFCC" stroke-width="1" opacity="0.5" />
    
    <rect x="680" y="40" width="70" height="60" rx="4" fill="#1C2541" stroke="#48CAE4" stroke-width="1.5" opacity="0.8" />
    
    <!-- Điểm Kết Nối (Vias) -->
    <circle cx="150" cy="30" r="3" fill="#00FFCC" />
    <circle cx="180" cy="60" r="3" fill="#00FFCC" />
    <circle cx="650" cy="150" r="3" fill="#48CAE4" />
    <circle cx="620" cy="120" r="3" fill="#48CAE4" />

    <!-- Chữ Tiêu Đề -->
    <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle" fill="#00FFCC" font-family="monospace" font-size="28" font-weight="bold" filter="url(#glow)">
      HIẾU | HARDWARE ENGINEER
    </text>
    <text x="50%" y="70%" dominant-baseline="middle" text-anchor="middle" fill="#48CAE4" font-family="monospace" font-size="14" letter-spacing="2">
      [ RTL Design & Physical Design ]
    </text>
  </svg>
</p>

---

## 👨‍💻 About me

* 👋 Hi, I'm Hieu
* 🌱 I'm currently learning **Verilog** and **Physical Design** 

---

### 🛠️ Tech Stack
<p>
  <img src="https://img.shields.io/badge/Language-Verilog_//_SystemVerilog-005A9C?style=flat-square&logo=cpu&logoColor=white" alt="Verilog">
  <img src="https://img.shields.io/badge/Domain-Physical_Design-00FFCC?style=flat-square&logo=microarchitecture&logoColor=black" alt="Physical Design">
  <img src="https://img.shields.io/badge/Hobby-Ethical_Hacking-red?style=flat-square&logo=linux&logoColor=white" alt="Hacking">
</p>
