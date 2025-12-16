<div align="center">

<!-- HEADER SVG WITH FRIEREN INSPIRED DESIGN -->
<svg width="100%" height="300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Gradiente principal -->
    <linearGradient id="headerGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1e1b4b;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#4c1d95;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#5b21b6;stop-opacity:1" />
    </linearGradient>
    
    <!-- Gradiente de acentos dorados -->
    <linearGradient id="goldenAccent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#fbbf24;stop-opacity:0.3" />
      <stop offset="50%" style="stop-color:#f59e0b;stop-opacity:0.5" />
      <stop offset="100%" style="stop-color:#fbbf24;stop-opacity:0.3" />
    </linearGradient>
    
    <!-- Patrón de estrellas mágicas -->
    <pattern id="magicStars" x="0" y="0" width="100" height="100" patternUnits="userSpaceOnUse">
      <circle cx="10" cy="10" r="1.5" fill="#e0d4f7" opacity="0.3">
        <animate attributeName="opacity" values="0.3;0.8;0.3" dur="3s" repeatCount="indefinite"/>
      </circle>
      <circle cx="45" cy="30" r="1" fill="#c8b6e2" opacity="0.4">
        <animate attributeName="opacity" values="0.4;0.9;0.4" dur="4s" repeatCount="indefinite"/>
      </circle>
      <circle cx="70" cy="15" r="1.2" fill="#fbbf24" opacity="0.3">
        <animate attributeName="opacity" values="0.3;0.7;0.3" dur="5s" repeatCount="indefinite"/>
      </circle>
      <circle cx="30" cy="60" r="0.8" fill="#e0d4f7" opacity="0.5">
        <animate attributeName="opacity" values="0.5;1;0.5" dur="3.5s" repeatCount="indefinite"/>
      </circle>
      <circle cx="85" cy="75" r="1.3" fill="#c8b6e2" opacity="0.3">
        <animate attributeName="opacity" values="0.3;0.8;0.3" dur="4.5s" repeatCount="indefinite"/>
      </circle>
    </pattern>
    
    <!-- Filtro de brillo -->
    <filter id="glow">
      <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Fondo base -->
  <rect width="100%" height="300" fill="url(#headerGradient)"/>
  
  <!-- Patrón de estrellas mágicas -->
  <rect width="100%" height="300" fill="url(#magicStars)"/>
  
  <!-- Líneas decorativas superiores -->
  <line x1="0" y1="30" x2="100%" y2="30" stroke="url(#goldenAccent)" stroke-width="2" opacity="0.6"/>
  <line x1="0" y1="35" x2="100%" y2="35" stroke="#e0d4f7" stroke-width="1" opacity="0.3"/>
  
  <!-- Líneas decorativas inferiores -->
  <line x1="0" y1="265" x2="100%" y2="265" stroke="#e0d4f7" stroke-width="1" opacity="0.3"/>
  <line x1="0" y1="270" x2="100%" y2="270" stroke="url(#goldenAccent)" stroke-width="2" opacity="0.6"/>
  
  <!-- Detalles ornamentales laterales -->
  <circle cx="50" cy="150" r="80" fill="none" stroke="#9b7ebd" stroke-width="1" opacity="0.1"/>
  <circle cx="50" cy="150" r="100" fill="none" stroke="#c8b6e2" stroke-width="0.5" opacity="0.1"/>
  
  <!-- Texto principal con sombra -->
  <text x="50%" y="130" font-family="'Segoe UI', Arial, sans-serif" font-size="72" font-weight="bold" fill="#1e1b4b" text-anchor="middle" opacity="0.3">
    KODEPE DEV
  </text>
  <text x="50%" y="128" font-family="'Segoe UI', Arial, sans-serif" font-size="72" font-weight="bold" fill="#ffffff" text-anchor="middle" filter="url(#glow)">
    KODEPE DEV
  </text>
  
  <!-- Subtítulo -->
  <text x="50%" y="175" font-family="'Segoe UI', Arial, sans-serif" font-size="24" fill="#e0d4f7" text-anchor="middle">
    Full Stack Developer | Laravel Specialist
  </text>
  
  <!-- Detalles mágicos (símbolos de magia) -->
  <polygon points="100,50 105,65 120,65 110,75 115,90 100,80 85,90 90,75 80,65 95,65" fill="#fbbf24" opacity="0.4">
    <animateTransform attributeName="transform" type="rotate" from="0 100 70" to="360 100 70" dur="20s" repeatCount="indefinite"/>
  </polygon>
</svg>

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=28&duration=3000&pause=1000&color=C8B6E2&center=true&vCenter=true&multiline=false&width=600&height=60&lines=Full+Stack+Developer+%F0%9F%9A%80;Laravel+Specialist+%E2%9A%A1;Building+Amazing+Systems+%F0%9F%92%BB" alt="Typing SVG" />
</a>

<!-- SOCIAL BADGES -->
<p>
  <a href="https://linkedin.com/in/tu-perfil">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:tu-email@ejemplo.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://twitter.com/tu-usuario">
    <img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter"/>
  </a>
  <a href="https://tu-portafolio.com">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/>
  </a>
</p>

<!-- PROFILE VIEWS COUNTER -->
<img src="https://komarev.com/ghpvc/?username=KodepeDev&label=Profile%20Views&color=9b7ebd&style=flat" alt="Profile Views" />

</div>

---

## 👨‍💻 Sobre Mí

```javascript
const kodepe = {
  empresa: "DAJHORSA SAC",
  rol: "Full Stack Developer",
  ubicacion: "Perú 🇵🇪",
  especialidades: [
    "Sistemas de Facturación Electrónica",
    "Sistemas de Cobranza Automatizada", 
    "Desarrollo de Sitios Web",
    "Integraciones con SUNAT"
  ],
  filosofia: "💡 Pasión por el Desarrollo",
  enfoque: "Transformando ideas en soluciones digitales escalables",
  codigo: "Clean, Documented, Scalable"
};
```

<div align="center">
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700">
</div>

---

<!-- TECH STACK SVG BANNER -->
<div align="center">
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="techGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#312e81;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#4c1d95;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#5b21b6;stop-opacity:1" />
    </linearGradient>
    
    <pattern id="techPattern" x="0" y="0" width="50" height="50" patternUnits="userSpaceOnUse">
      <rect x="0" y="0" width="1" height="1" fill="#e0d4f7" opacity="0.1"/>
      <rect x="25" y="25" width="1" height="1" fill="#fbbf24" opacity="0.1"/>
    </pattern>
    
    <linearGradient id="techAccent" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#c8b6e2;stop-opacity:0.3" />
      <stop offset="50%" style="stop-color:#e0d4f7;stop-opacity:0.6" />
      <stop offset="100%" style="stop-color:#c8b6e2;stop-opacity:0.3" />
    </linearGradient>
  </defs>
  
  <rect width="100%" height="200" fill="url(#techGradient)"/>
  <rect width="100%" height="200" fill="url(#techPattern)"/>
  
  <!-- Decoración superior -->
  <path d="M 0,20 Q 25,10 50,20 T 100,20 T 150,20 T 200,20 T 250,20 T 300,20 T 350,20 T 400,20 T 450,20 T 500,20 T 550,20 T 600,20 T 650,20 T 700,20 T 750,20 T 800,20 T 850,20 T 900,20 T 950,20 T 1000,20 T 1050,20 T 1100,20 T 1150,20 T 1200,20 T 1250,20 T 1300,20 T 1350,20 T 1400,20 T 1450,20 T 1500,20" 
        stroke="url(#techAccent)" stroke-width="2" fill="none" opacity="0.5"/>
  
  <!-- Iconos decorativos -->
  <circle cx="100" cy="100" r="30" fill="none" stroke="#fbbf24" stroke-width="2" opacity="0.2"/>
  <rect x="85" y="85" width="30" height="30" fill="none" stroke="#e0d4f7" stroke-width="2" opacity="0.2" transform="rotate(45 100 100)"/>
  
  <!-- Título -->
  <text x="50%" y="105" font-family="'Segoe UI', Arial, sans-serif" font-size="48" font-weight="bold" fill="#312e81" text-anchor="middle" opacity="0.3">
    🛠️ TECH STACK
  </text>
  <text x="50%" y="103" font-family="'Segoe UI', Arial, sans-serif" font-size="48" font-weight="bold" fill="#ffffff" text-anchor="middle">
    🛠️ TECH STACK
  </text>
  
  <!-- Subtítulo -->
  <text x="50%" y="140" font-family="'Segoe UI', Arial, sans-serif" font-size="20" fill="#c8b6e2" text-anchor="middle">
    Tecnologías y Herramientas
  </text>
  
  <!-- Decoración inferior -->
  <path d="M 0,180 Q 25,190 50,180 T 100,180 T 150,180 T 200,180 T 250,180 T 300,180 T 350,180 T 400,180 T 450,180 T 500,180 T 550,180 T 600,180 T 650,180 T 700,180 T 750,180 T 800,180 T 850,180 T 900,180 T 950,180 T 1000,180 T 1050,180 T 1100,180 T 1150,180 T 1200,180 T 1250,180 T 1300,180 T 1350,180 T 1400,180 T 1450,180 T 1500,180" 
        stroke="url(#techAccent)" stroke-width="2" fill="none" opacity="0.5"/>
</svg>
</div>

### 💻 Backend
<p align="center">
  <img src="https://skillicons.dev/icons?i=php,laravel,nodejs" alt="Backend Skills"/>
  <img src="https://img.shields.io/badge/Livewire-4E56A6?style=for-the-badge&logo=livewire&logoColor=white" alt="Livewire"/>
</p>

### 🎨 Frontend
<p align="center">
  <img src="https://skillicons.dev/icons?i=vue,js,html,css,bootstrap,astro" alt="Frontend Skills"/>
  <img src="https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white" alt="Chart.js"/>
</p>

### 🗄️ Database
<p align="center">
  <img src="https://skillicons.dev/icons?i=mysql,postgres" alt="Database Skills"/>
</p>

### 🔧 Tools & DevOps
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,docker,postman" alt="Tools"/>
  <img src="https://img.shields.io/badge/Composer-885630?style=for-the-badge&logo=composer&logoColor=white" alt="Composer"/>
  <img src="https://img.shields.io/badge/NPM-CB3837?style=for-the-badge&logo=npm&logoColor=white" alt="NPM"/>
</p>

---

<!-- PROJECTS SVG BANNER -->
<div align="center">
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="projectsGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#1e293b;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#3730a3;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#4c1d95;stop-opacity:1" />
    </linearGradient>
    
    <radialGradient id="projectsRadial">
      <stop offset="0%" style="stop-color:#fbbf24;stop-opacity:0.2" />
      <stop offset="100%" style="stop-color:#1e293b;stop-opacity:0" />
    </radialGradient>
    
    <pattern id="projectsDots" x="0" y="0" width="30" height="30" patternUnits="userSpaceOnUse">
      <circle cx="15" cy="15" r="1" fill="#e0d4f7" opacity="0.2">
        <animate attributeName="r" values="1;2;1" dur="4s" repeatCount="indefinite"/>
      </circle>
    </pattern>
  </defs>
  
  <rect width="100%" height="200" fill="url(#projectsGradient)"/>
  <rect width="100%" height="200" fill="url(#projectsDots)"/>
  <circle cx="50%" cy="100" r="150" fill="url(#projectsRadial)"/>
  
  <!-- Hexágonos decorativos -->
  <polygon points="150,60 165,70 165,90 150,100 135,90 135,70" fill="none" stroke="#fbbf24" stroke-width="2" opacity="0.3"/>
  <polygon points="150,60 165,70 165,90 150,100 135,90 135,70" fill="none" stroke="#e0d4f7" stroke-width="1" opacity="0.2" transform="scale(1.3) translate(-30, -10)"/>
  
  <!-- Título con efecto -->
  <text x="50%" y="105" font-family="'Segoe UI', Arial, sans-serif" font-size="48" font-weight="bold" fill="#1e293b" text-anchor="middle" opacity="0.4">
    🚀 PROYECTOS
  </text>
  <text x="50%" y="103" font-family="'Segoe UI', Arial, sans-serif" font-size="48" font-weight="bold" fill="#ffffff" text-anchor="middle">
    🚀 PROYECTOS
  </text>
  
  <!-- Subtítulo -->
  <text x="50%" y="140" font-family="'Segoe UI', Arial, sans-serif" font-size="20" fill="#c8b6e2" text-anchor="middle">
    Desarrollos Destacados
  </text>
  
  <!-- Línea decorativa animada -->
  <line x1="30%" y1="160" x2="70%" y2="160" stroke="#fbbf24" stroke-width="3" opacity="0.6">
    <animate attributeName="x1" values="30%;35%;30%" dur="3s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="70%;65%;70%" dur="3s" repeatCount="indefinite"/>
  </line>
</svg>
</div>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">💰 Sistema de Cobranza</h3>
      <br/>
      <a href="https://github.com/tu-usuario/sistema-cobranza">
        <img src="https://user-images.githubusercontent.com/74038190/212284087-bbe7e430-757e-4901-90bf-4cd2ce3e1852.gif" width="100%" alt="Cobranza"/>
      </a>
      <br/><br/>
      <p align="center">
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
        <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
        <img src="https://img.shields.io/badge/Livewire-4E56A6?style=for-the-badge&logo=livewire&logoColor=white"/>
      </p>
      <p><strong>Sistema automatizado de gestión de cobranzas</strong> - Lecturas de medidores, cálculo de consumo, generación automática de facturas y reportes con Chart.js para centros comerciales.</p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📄 Sistema de Facturación SUNAT</h3>
      <br/>
      <a href="https://github.com/tu-usuario/sistema-facturacion">
        <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width="100%" alt="Facturación"/>
      </a>
      <br/><br/>
      <p align="center">
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white"/>
        <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white"/>
        <img src="https://img.shields.io/badge/API-009688?style=for-the-badge&logo=fastapi&logoColor=white"/>
      </p>
      <p><strong>Plataforma integral de facturación electrónica</strong> - Integración completa con SUNAT, generación de comprobantes electrónicos, consulta de RUC, dashboard SIRE y gestión de documentos tributarios.</p>
    </td>
  </tr>
</table>

---

<!-- STATS SVG BANNER -->
<div align="center">
<svg width="100%" height="200" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="statsGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#0f172a;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#1e293b;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#334155;stop-opacity:1" />
    </linearGradient>
    
    <pattern id="statsGrid" x="0" y="0" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 0 0 L 0 40 M 0 0 L 40 0" stroke="#e0d4f7" stroke-width="0.5" opacity="0.1"/>
    </pattern>
    
    <linearGradient id="statsLine" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#c8b6e2;stop-opacity:0" />
      <stop offset="50%" style="stop-color:#fbbf24;stop-opacity:0.8" />
      <stop offset="100%" style="stop-color:#c8b6e2;stop-opacity:0" />
    </linearGradient>
  </defs>
  
  <rect width="100%" height="200" fill="url(#statsGradient)"/>
  <rect width="100%" height="200" fill="url(#statsGrid)"/>
  
  <!-- Elementos gráficos de estadísticas -->
  <polyline points="100,150 150,120 200,140 250,100 300,130" 
            fill="none" stroke="#fbbf24" stroke-width="2" opacity="0.3"/>
  <polyline points="800,150 850,130 900,145 950,110 1000,125" 
            fill="none" stroke="#c8b6e2" stroke-width="2" opacity="0.3"/>
  
  <!-- Círculos animados -->
  <circle cx="200" cy="140" r="4" fill="#fbbf24" opacity="0.6">
    <animate attributeName="r" values="4;6;4" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="900" cy="145" r="4" fill="#c8b6e2" opacity="0.6">
    <animate attributeName="r" values="4;6;4" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Título -->
  <text x="50%" y="95" font-family="'Segoe UI', Arial, sans-serif" font-size="48" font-weight="bold" fill="#0f172a" text-anchor="middle" opacity="0.5">
    📊 ESTADÍSTICAS
  </text>
  <text x="50%" y="93" font-family="'Segoe UI', Arial, sans-serif" font-size="48" font-weight="bold" fill="#ffffff" text-anchor="middle">
    📊 ESTADÍSTICAS
  </text>
  
  <!-- Subtítulo -->
  <text x="50%" y="130" font-family="'Segoe UI', Arial, sans-serif" font-size="20" fill="#c8b6e2" text-anchor="middle">
    GitHub Activity & Contributions
  </text>
  
  <!-- Línea brillante inferior -->
  <line x1="0" y1="180" x2="100%" y2="180" stroke="url(#statsLine)" stroke-width="3"/>
</svg>
</div>

<div align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=KodepeDev&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats"/>
  <img width="49%" src="https://streak-stats.demolab.com/?user=KodepeDev&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</div>

<div align="center">
  <img width="60%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=KodepeDev&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages"/>
</div>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=KodepeDev&theme=tokyo-night&hide_border=true&area=true" alt="Contribution Graph"/>
</div>

---

## 🏆 GitHub Trophies

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=KodepeDev&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7" alt="GitHub Trophies"/>
</div>

---

## 💼 Experiencia Profesional

<div align="center">

| 🏢 Empresa | 👨‍💻 Rol | 📅 Período | 🎯 Logros |
|:---:|:---:|:---:|:---|
| **DAJHORSA SAC** | Full Stack Developer | Actualidad | • Desarrollo de sistemas internos<br>• Gestión de 200+ empresas clientes<br>• Procesamiento de 180K+ documentos/mes<br>• Integración completa con SUNAT |

</div>

---

## 📈 Actividad de Desarrollo

<div align="center">
  
<!--START_SECTION:waka-->
<!--END_SECTION:waka-->

</div>

---

## 🎯 Filosofía de Desarrollo

<div align="center">

```diff
+ Código Limpio y Documentado
+ Arquitectura Escalable
+ Mejores Prácticas de Laravel
! Pasión por el Desarrollo
# Soluciones que Transforman Negocios
```

<img src="https://user-images.githubusercontent.com/74038190/212284158-e840e285-664b-44d7-b79b-e264b5e54825.gif" width="400">

</div>

---

## 🤝 Conectemos

<div align="center">

### 💬 Siempre abierto a:
✅ Colaborar en proyectos innovadores  
✅ Discutir sobre Laravel y arquitectura de software  
✅ Compartir conocimientos sobre sistemas fiscales en Perú  
✅ Nuevas oportunidades y desafíos  

---

<!-- FOOTER SVG -->
<svg width="100%" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGradient" x1="0%" y1="100%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#5b21b6;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#4c1d95;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#1e1b4b;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <rect width="100%" height="120" fill="url(#footerGradient)"/>
  
  <!-- Onda decorativa -->
  <path d="M 0,60 Q 150,20 300,60 T 600,60 T 900,60 T 1200,60 T 1500,60 L 1500,120 L 0,120 Z" 
        fill="#1e1b4b" opacity="0.3"/>
  
  <!-- Estrellas brillantes finales -->
  <circle cx="20%" cy="40" r="2" fill="#fbbf24" opacity="0.7">
    <animate attributeName="opacity" values="0.7;1;0.7" dur="2s" repeatCount="indefinite"/>
  </circle>
  <circle cx="50%" cy="30" r="2.5" fill="#e0d4f7" opacity="0.8">
    <animate attributeName="opacity" values="0.8;1;0.8" dur="3s" repeatCount="indefinite"/>
  </circle>
  <circle cx="80%" cy="45" r="2" fill="#c8b6e2" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2.5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Texto del footer -->
  <text x="50%" y="80" font-family="'Segoe UI', Arial, sans-serif" font-size="18" fill="#ffffff" text-anchor="middle">
    ⭐️ Si te gusta mi trabajo, considera darle una estrella a mis repositorios ⭐️
  </text>
</svg>

</div>
