<p align="center">
  <svg width="100%" height="180" viewBox="0 0 900 180" xmlns="http://www.w3.org/2000/svg">

    <!-- Background gradient -->
    <defs>
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#1E90FF"/>
        <stop offset="100%" stop-color="#6A5ACD"/>
      </linearGradient>

      <!-- Glow animation -->
      <filter id="glow">
        <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
        <feMerge>
          <feMergeNode in="coloredBlur"/>
          <feMergeNode in="SourceGraphic"/>
        </feMerge>
      </filter>
    </defs>

    <!-- Animated line background -->
    <rect width="100%" height="180" fill="url(#grad)">
      <animate attributeName="opacity" from="0.85" to="1" dur="3s" repeatCount="indefinite"/>
    </rect>

    <!-- Data Science Icon (nodes + pulses) -->
    <g transform="translate(150, 90)">
      <circle cx="0" cy="0" r="8" fill="white" filter="url(#glow)">
        <animate attributeName="r" values="8;12;8" dur="2s" repeatCount="indefinite"/>
      </circle>
      <circle cx="60" cy="-35" r="6" fill="#E0E0FF">
        <animate attributeName="r" values="6;9;6" dur="2.2s" repeatCount="indefinite"/>
      </circle>
      <circle cx="60" cy="35" r="6" fill="#E0E0FF">
        <animate attributeName="r" values="6;9;6" dur="2.4s" repeatCount="indefinite"/>
      </circle>
      <circle cx="120" cy="0" r="8" fill="white" filter="url(#glow)">
        <animate attributeName="r" values="8;11;8" dur="2.6s" repeatCount="indefinite"/>
      </circle>

      <!-- Connecting lines -->
      <line x1="0" y1="0" x2="60" y2="-35" stroke="white" stroke-width="2" opacity="0.8"/>
      <line x1="0" y1="0" x2="60" y2="35" stroke="white" stroke-width="2" opacity="0.8"/>
      <line x1="60" y1="-35" x2="120" y2="0" stroke="white" stroke-width="2" opacity="0.8"/>
      <line x1="60" y1="35" x2="120" y2="0" stroke="white" stroke-width="2" opacity="0.8"/>
    </g>

    <!-- Text: Your Name -->
    <text x="450" y="100" text-anchor="middle" font-size="48" fill="white" font-weight="bold" filter="url(#glow)">
      Vagner Vargas
      <animate attributeName="letter-spacing" values="1;4;1" dur="3s" repeatCount="indefinite"/>
    </text>

    <!-- Subtitle -->
    <text x="450" y="135" text-anchor="middle" font-size="22" fill="#F0F0FF">
      Ciência de Dados • Nutrição • Tecnologia
      <animate attributeName="opacity" values="1;0.6;1" dur="3s" repeatCount="indefinite"/>
    </text>

  </svg>
</p>
# 👋 Olá — eu sou Vagner Vargas

### 🎓 Sobre mim
27 anos • Estudante de Ciências de Dados e Nutrição  
Em transição profissional, combinando ciência de dados, tecnologia e saúde para desenvolver soluções baseadas em evidências.

---

### 📌 Áreas de Interesse
- Ciência de Dados  
- Nutrição  
- Análise de Dados  
- Tecnologia  
- Estudos e Pesquisa

---

### 🧰 Habilidades
**Linguagens e Ferramentas**  
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-0D1117?style=for-the-badge&logo=postgresql&logoColor=white)

**Nutrição**  
![Nutrição](https://img.shields.io/badge/Nutrição-Cálculos%20Nutricionais%20%7C%20Planejamento-4caf50?style=for-the-badge)

---

### 🎯 Objetivo
Documentar projetos, estudos e experimentos nas áreas de dados e saúde digital — registrando aprendizado e construindo um portfólio técnico e científico.

---

### 🗂 O que você encontrará aqui
- Notebooks e scripts em Python e SQL aplicados a dados de saúde  
- Projetos de análise e visualização (Power BI / Python)  
- Anotações e materiais de estudo em Nutrição e métodos de pesquisa

---

### 🔒 Estilo do perfil
Tom sério e profissional — foco em clareza, organização e documentação reprodutível.

---

> 📫 **Contatos & projetos completos:** Em breve adicionarei links para LinkedIn, portfólio e repositórios destacados.

---
