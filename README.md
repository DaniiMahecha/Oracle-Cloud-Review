<div align="center">

# ☁️ OCI Explorer
### *De "No sé nada" a Experto en Oracle Cloud*

[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)](https://www.chartjs.org/)
[![Oracle Cloud](https://img.shields.io/badge/Oracle_Cloud-F80000?style=for-the-badge&logo=oracle&logoColor=white)](https://www.oracle.com/cloud/)

**Una Single Page Application interactiva para explorar el ecosistema de Oracle Cloud Infrastructure (OCI) de forma visual e intuitiva.**

[🚀 Ver Demo](#) · [📖 Documentación](#categorías-cubiertas) · [🐛 Reportar Bug](issues)

---

<img src="https://img.shields.io/badge/Servicios_Documentados-40+-red?style=flat-square" />
<img src="https://img.shields.io/badge/Categorías-6-blue?style=flat-square" />
<img src="https://img.shields.io/badge/Idioma-Español-green?style=flat-square" />

</div>

---

## 🎯 ¿Qué es esto?

**OCI Explorer** es una guía técnica interactiva que transforma la documentación densa de Oracle Cloud en **tarjetas visuales con analogías del mundo real**. Pensado para estudiantes, profesionales que migran a OCI, o cualquiera que necesite entender el ecosistema de Oracle Cloud sin perderse en jerga técnica.

> *"¿Qué es un VCN? ¿Para qué sirve Exadata? ¿Cuándo uso Object Storage vs Block Storage?"* — Todas esas preguntas, respondidas con lenguaje claro.

---

## ✨ Features

| Feature | Descripción |
|---|---|
| 📊 **Dashboard Visual** | Gráfico de dona interactivo con la distribución de servicios por categoría |
| 🗂️ **Navegación por Pilares** | Sidebar organizado en los 6 pilares fundamentales de OCI |
| 🃏 **Tarjetas Interactivas** | Cada servicio explicado con analogías simples y sin tecnicismos innecesarios |
| 📱 **Responsive** | Funciona en móvil, tablet y desktop |
| ⚡ **Sin dependencias externas** | Todo corre directamente en el navegador (CDN), sin build process |

---

## 🏗️ Categorías Cubiertas

```
☁️ OCI Explorer
├── 💻 Compute & OS
│   ├── Bare Metal, VMs, HPC, GPUs
│   ├── Containers, Kubernetes (OKE), Service Mesh, Registry
│   └── Autonomous Linux, OS Management, Marketplace
│
├── 🗂️ Storage (Almacenamiento)
│   └── NVMe, Block, File, Object, Archive Storage & Data Transfer
│
├── 🌐 Networking (Redes)
│   └── VCN, Load Balancer, FastConnect, VPN, Service Gateway, Cluster Networking
│
├── 🗄️ Bases de Datos
│   ├── Oracle DB: ATP, ADW, DBCS, JSON DB, Exadata Cloud, Exadata C@C
│   └── Open Source: MySQL, PostgreSQL, Redis, OpenSearch, NoSQL, Kafka (Streaming)
│
├── 📈 Analytics
│   └── Analytics Cloud (OAC), Fusion Analytics
│
└── 🛡️ Gobernanza, Seguridad & Dev
    ├── IAM, Compartments, Cost Advisor
    ├── Cloud Guard, Vault/KMS, Data Safe, WAF & DDoS
    ├── Monitoring & Logging
    └── APEX (Low Code), IaC (Terraform/Ansible)
```

---

## 🚀 Inicio Rápido

No requiere instalación. Solo abre el archivo en tu navegador:

```bash
# Clona el repositorio
git clone https://github.com/tu-usuario/oci-explorer.git

# Abre el archivo directamente
cd oci-explorer
open OracleCloudReview.html   # macOS
start OracleCloudReview.html  # Windows
xdg-open OracleCloudReview.html  # Linux
```

> ✅ Compatible con Chrome, Firefox, Safari y Edge modernos.

---

## 🛠️ Stack Técnico

- **HTML5** — Estructura semántica, Single Page Application vanilla
- **Tailwind CSS** (CDN) — Estilos utilitarios y diseño responsive
- **Chart.js** (CDN) — Visualización del gráfico de dona del ecosistema OCI
- **JavaScript Vanilla** — Navegación dinámica, renderizado de tarjetas y estado

---

## 📐 Arquitectura de la App

La SPA usa un paradigma de **"Dashboard Explorer"** con tres vistas:

```
┌─────────────────────────────────────────────────┐
│  Sidebar Nav          │   Main Content           │
│  ─────────────────    │   ─────────────────────  │
│  📊 Visión General   │   [ Vista Overview ]      │
│  ─────────────────    │   Gráfico de dona +       │
│  💻 Compute          │   3 pilares principales   │
│  🗂️ Storage          │                           │
│  🌐 Networking       │   [ Vista Categoría ]     │
│  🗄️ Databases        │   Subheader del pilar +   │
│  📈 Analytics        │   Grid de tarjetas        │
│  🛡️ Security & Dev   │   por subcategoría        │
└─────────────────────────────────────────────────┘
```

---

## 🤝 Contribuciones

¿Falta un servicio de OCI? ¿Tienes una mejor analogía para explicar algo? ¡Los PRs son bienvenidos!

1. Haz fork del repo
2. Agrega o edita servicios en el objeto `ociData` dentro del `<script>`
3. Cada servicio sigue el formato:
   ```javascript
   { name: 'Nombre del Servicio', desc: 'Explicación clara y directa...' }
   ```
4. Abre un Pull Request

---

## 📄 Licencia

Este proyecto está bajo la licencia **MIT**. Úsalo, modifícalo y compártelo libremente.

---

<div align="center">

Hecho con ☕ y mucha documentación de Oracle

*Si te fue útil, dale una ⭐ al repo*

</div>
