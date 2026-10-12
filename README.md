<div align="center">

<a href="https://juandgaitan.com/"><img src="assets/header.svg" width="100%" alt="Juan David Gaitán, arquitecto de software y cofundador de HYVENTO. Sitio web: juandgaitan.com"/></a>

<h1>Juan David Gaitán</h1>

<p>Arquitecto de software · Cofundador de HYVENTO · Pereira, Colombia<br/>Software architect · Co-founder of HYVENTO · Pereira, Colombia</p>

<a href="https://juandgaitan.com/"><img src="https://img.shields.io/badge/juandgaitan.com-0b6b64?style=for-the-badge&labelColor=0b141f&label=web" alt="Sitio web de Juan David Gaitán: juandgaitan.com"/></a>&nbsp;<a href="https://www.linkedin.com/in/juandavidgaitand/"><img src="https://img.shields.io/badge/in%2Fjuandavidgaitand-0b6b64?style=for-the-badge&labelColor=0b141f&label=LinkedIn" alt="LinkedIn de Juan David Gaitán"/></a>

<br/>

<a href="#español"><img src="https://img.shields.io/badge/ES-Espa%C3%B1ol-0b6b64?style=flat-square&labelColor=0b141f" alt="Leer en español"/></a> &nbsp;·&nbsp; <a href="#english"><img src="https://img.shields.io/badge/EN-English-0b6b64?style=flat-square&labelColor=0b141f" alt="Read in English"/></a>

</div>

<h2 id="español">Español</h2>

### Sobre mí

Soy Juan David Gaitán, arquitecto de software en Pereira, Colombia.

**Cofundador de HYVENTO.** Dirijo [HYVENTO](https://juandgaitan.com/), un estudio de desarrollo de software para LLCs de EE. UU. y proyectos B2B en Colombia.

**Del frontend a la infraestructura.** Cubro el sistema completo y tomo las decisiones de arquitectura: monolito o microservicios, serverless o servidor dedicado, llamadas síncronas o mensajería.

**Respondo por lo que diseño.** Diseño sistemas de software y respondo por ellos en producción.

**Primer lugar en TINKU Hackathon 2026.** Con mi equipo construimos Solara para Techos Rentables en 18 horas: monitoreo unificado de más de 200 proyectos solares en un solo dashboard. Fui el desarrollador backend.

**Asesorías de arquitectura.** Asesoro equipos de desarrollo. Una muestra: tres APIs con microservicios, una base de datos por API y mensajería asíncrona con RabbitMQ.

**Código público.** Mi GitHub reúne proyectos propios como StatLab, KallIt y utilidades de estadística y firma digital.

<h3 align="center"><samp>$ ls tech-stack/</samp></h3>

<p align="center"><samp>architecture/</samp></p>
<p align="center"><sub>Microservicios · Event-driven · Serverless · Mensajería asíncrona · APIs RESTful</sub></p>

<p align="center"><samp>cloud/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=gcp,firebase,azure,kubernetes,docker,linux,cloudflare&theme=dark" alt="Google Cloud Platform, Firebase, Azure, Kubernetes, Docker, Linux, Cloudflare"/>
</p>
<p align="center"><sub>También: Cloud Functions</sub></p>

<p align="center"><samp>backend/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,python,php,java,wordpress,rabbitmq&theme=dark" alt="Node.js, Python, PHP, Java, WordPress, RabbitMQ"/>
</p>

<p align="center"><samp>data/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,supabase,mongodb&theme=dark" alt="PostgreSQL, Supabase, MongoDB"/>
</p>
<p align="center"><sub>También: Firestore · Búsqueda vectorial · SQL</sub></p>

<p align="center"><samp>ai-automation/</samp></p>
<p align="center">
  <img src="https://img.shields.io/badge/n8n-0b6b64?style=flat-square&labelColor=0b141f&logo=n8n&logoColor=white" alt="n8n"/>
  <img src="https://img.shields.io/badge/Integración%20de%20LLMs-0b6b64?style=flat-square&labelColor=0b141f" alt="Integración de LLMs"/>
  <img src="https://img.shields.io/badge/Vertex%20AI-0b6b64?style=flat-square&labelColor=0b141f" alt="Vertex AI"/>
  <img src="https://img.shields.io/badge/OCR-0b6b64?style=flat-square&labelColor=0b141f" alt="OCR"/>
  <img src="https://img.shields.io/badge/Google%20Apps%20Script-0b6b64?style=flat-square&labelColor=0b141f&logo=googleappsscript&logoColor=white" alt="Google Apps Script"/>
  <img src="https://img.shields.io/badge/Prompt%20engineering-0b6b64?style=flat-square&labelColor=0b141f" alt="Prompt engineering"/>
</p>

<p align="center"><samp>frontend/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,angular,ts,tailwind&theme=dark" alt="Next.js, React, Angular, TypeScript, Tailwind CSS"/>
</p>
<p align="center"><sub>También: React Native</sub></p>

### Proyectos destacados

Sistemas en los que trabajé, con mi parte en cada uno.

| Proyecto | Qué es y mi parte | Enlaces |
|---|---|---|
| **Zephr** | SaaS que reúne en un solo buscador la información de varias autoridades de aviación. La base de directivas de aeronavegabilidad cubre seis autoridades (FAA, EASA, TC, ANAC Brasil, ANAC Argentina y DGAC Chile) y la comparte con Aeromate.<br/>**Mi parte:** actualizamos y optimizamos la base de datos y construimos la conexión con la API de la FAA. Las consultas quedaron 90% más rápidas.<br/><sub>Next.js · Python · Supabase · FAA API</sub> | [adscrapper.hyvento.co](https://adscrapper.hyvento.co/) |
| **Aeromate**<br/><sub>En proceso</sub> | Pipeline serverless que identifica, organiza y procesa documentos aeronáuticos. Usa la misma base de directivas de Zephr. Es serverless porque los documentos llegan en ráfagas y un servidor encendido todo el día pagaría por tiempo ocioso.<br/>**Mi parte:** validación de fidelidad por OCR con métodos de fallback. Un trabajo de semanas queda en menos de un día.<br/><sub>GCP · Firebase Functions · Eventarc · Cloud Tasks · Vertex AI · PostgreSQL</sub> | [aeromate.hyvento.co](https://aeromate.hyvento.co/) |
| **Ingenio Obra** | Plataforma de gestión de obra para constructoras que construimos para Ingenio Advice. Resolvimos el cuello de botella en la gestión de contratación y liquidación en obra, automatizamos las encuestas de salud y el Análisis de Trabajo Seguro (ATS), y automatizamos la bitácora diaria: SST y residentes envían texto, audio e imágenes por Telegram y el sistema genera los reportes.<br/>**Mi parte:** ingeniero de software principal. Desarrollé todos los módulos menos el de Encuestas de salud, que desarrolló otra persona.<br/><sub>WordPress · PHP · n8n · Telegram · IA</sub> | [dashboard.ingenioia.com](https://dashboard.ingenioia.com) |
| **Moradia** | Agente inmobiliario que recibe lo que el cliente pide en lenguaje natural y le muestra los inmuebles que mejor encajan.<br/>**Mi parte:** el agente y su funcionamiento dentro de un plugin en PHP. El diseño es de otro equipo.<br/><sub>WordPress · PHP · Agente IA</sub> | [moradia.ai](https://www.moradia.ai/) |
| **Fultr**<br/><sub>En proceso</sub> | Software de nodos logísticos para los centros comerciales de la línea Arauco.<br/>**Mi parte:** validar la arquitectura del sistema y llevarlo a una versión lista para producción. El diseño y la lógica de negocio son de otro equipo.<br/><sub>Next.js · PostgreSQL · Prisma · Cloudflare R2</sub> | [fultr.co](https://fultr.co/) |
| **Solara para Techos Rentables**<br/><sub>1er lugar · TINKU Hackathon 2026</sub> | Monitoreo unificado de más de 200 proyectos solares en un solo dashboard, construido en 18 horas. Cloud Functions hace el polling a las APIs de los fabricantes y corre el motor de reglas. Detecta fallas en menos de 5 minutos, genera informes de cliente automáticos y elimina más de 130 horas al mes de trabajo manual.<br/>**Mi parte:** desarrollador backend. Construí el backend que sostiene la app web y consume las APIs de los fabricantes internacionales.<br/><sub>Next.js · Cloud Functions · Firestore · Deye · Huawei · Growatt</sub> | [Código](https://github.com/The-Tribu/tinku_team_ojala_hubiera_pasado_a_la_utp)<br/>[techosrentables.com](https://techosrentables.com)<br/>[Demo](https://solariapp.vercel.app/) |
| **SIGBA**<br/><sub>En proceso</sub> | Sistema de información para bancos de alimentos. El Banco de Alimentos de Pereira, que opera la Fundación Cáritas de la Diócesis de Pereira, participa como cliente del piloto.<br/>**Mi parte, con mi equipo:** diseño y carga del directorio de instituciones, portal para el responsable de cada institución, registro nominal de beneficiarios con una sola membresía activa, alertas de duplicidad y caracterización derivada.<br/><sub>NestJS · React · PWA</sub> | Sin sitio público |
| **Asesoría de arquitectura: tres APIs y un dashboard** | Asesoría para un equipo de más de cinco personas que construía tres APIs: gestión, caracterización y estadística. Microservicios con una base de datos por API, porque dos de ellas necesitaban escalar y desplegarse por separado. La API de estadística consume a las otras dos por mensajería asíncrona con RabbitMQ. He hecho otras asesorías de este tipo; esta es una muestra.<br/><sub>Azure · Kubernetes · RabbitMQ · Microservicios</sub> | Sin sitio público |

### Open source

Proyectos con código público en GitHub.

| Proyecto | Descripción | Stack | Código |
|---|---|---|---|
| **StatLab**<br/><sub>En proceso</sub> | Calculadora de estadística descriptiva que corre en el navegador. Pegas o importas datos, un asistente te guía en español y StatLab calcula, explica y grafica. Ningún dato sale del dispositivo. | TypeScript | [estadistica-diego](https://github.com/JuanGaitanD/estadistica-diego) |
| **KallIt** | Llamadas grupales estilo Discord con WebRTC en mesh: audio y pantalla compartida peer-to-peer, sin servidor de medios. Supabase maneja auth, presencia y chat en tiempo real. | React · Supabase · WebRTC | [Comunicaciones-web-app](https://github.com/JuanGaitanD/Comunicaciones-web-app) |
| **Visión Electoral**<br/><sub>Colaborador</sub> | Encuestas de campo para contexto electoral. App Android offline-first que sincroniza al recuperar señal, API en Express con MongoDB y dashboard en Angular con estadísticas por rol. Repositorio de un tercero en el que participé. | Kotlin · Angular · Node.js · MongoDB | [vision-electoral](https://github.com/MiloAgudelo/vision-electoral) |
| **Calculadora de estadística inferencial** | Distribuciones de probabilidad, tamaño de muestra, intervalos de confianza y pruebas de hipótesis con Z, t y χ². | JavaScript | [calculadora-estadistica-inferencial](https://github.com/JuanGaitanD/calculadora-estadistica-inferencial) |
| **Generador de contratos con firma** | Login con Google, formulario guiado, firma en canvas y generación del contrato en PDF con webhooks de Google Apps Script. | Angular · Firebase | [GeneradorContratosConFirma](https://github.com/JuanGaitanD/GeneradorContratosConFirma) |
| **Firma digital** | Dibuja tu firma y descárgala en PNG o SVG, sin registro. | Angular | [obtener_firma_digital](https://github.com/JuanGaitanD/obtener_firma_digital) |
| **NASA Exoplanet Challenge** | Modelo de machine learning que evalúa candidatos a exoplaneta. | Python | [challenge-nasa-exoplanet](https://github.com/JuanGaitanD/challenge-nasa-exoplanet) |

### Contacto

Escríbeme para asesorías de arquitectura o propuestas de desarrollo.

<div align="center">

<a href="https://juandgaitan.com/"><img src="https://img.shields.io/badge/juandgaitan.com-0b6b64?style=for-the-badge&labelColor=0b141f&label=web" alt="Sitio web de Juan David Gaitán: juandgaitan.com"/></a>&nbsp;<a href="https://www.linkedin.com/in/juandavidgaitand/"><img src="https://img.shields.io/badge/in%2Fjuandavidgaitand-0b6b64?style=for-the-badge&labelColor=0b141f&label=LinkedIn" alt="LinkedIn de Juan David Gaitán"/></a>&nbsp;<a href="mailto:juandavidgaitandiaz@gmail.com"><img src="https://img.shields.io/badge/juandavidgaitandiaz%40gmail.com-0b6b64?style=for-the-badge&labelColor=0b141f&label=correo" alt="Correo de Juan David Gaitán"/></a>

</div>

<br/>

<div align="center"><a href="#english">Read this profile in English ↓</a></div>

---

<h2 id="english">English</h2>

### About me

I'm Juan David Gaitán, a software architect based in Pereira, Colombia.

**Co-founder of HYVENTO.** I run [HYVENTO](https://juandgaitan.com/), a software development studio for US LLCs and B2B projects in Colombia.

**From the frontend to the infrastructure.** I cover the whole system and make the architecture calls: monolith or microservices, serverless or a dedicated server, synchronous calls or messaging.

**I answer for what I design.** I design software systems and answer for them in production.

**1st place at TINKU Hackathon 2026.** With my team we built Solara for Techos Rentables in 18 hours: unified monitoring of more than 200 solar projects in one dashboard. I was the backend developer.

**Architecture consulting.** I advise development teams. One example: three APIs with microservices, one database per API and asynchronous messaging with RabbitMQ.

**Public code.** My GitHub holds personal projects such as StatLab, KallIt and statistics and digital signature tools.

<h3 align="center"><samp>$ ls tech-stack/</samp></h3>

<p align="center"><samp>architecture/</samp></p>
<p align="center"><sub>Microservices · Event-driven · Serverless · Asynchronous messaging · RESTful APIs</sub></p>

<p align="center"><samp>cloud/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=gcp,firebase,azure,kubernetes,docker,linux,cloudflare&theme=dark" alt="Google Cloud Platform, Firebase, Azure, Kubernetes, Docker, Linux, Cloudflare"/>
</p>
<p align="center"><sub>Also: Cloud Functions</sub></p>

<p align="center"><samp>backend/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,python,php,java,wordpress,rabbitmq&theme=dark" alt="Node.js, Python, PHP, Java, WordPress, RabbitMQ"/>
</p>

<p align="center"><samp>data/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,supabase,mongodb&theme=dark" alt="PostgreSQL, Supabase, MongoDB"/>
</p>
<p align="center"><sub>Also: Firestore · Vector search · SQL</sub></p>

<p align="center"><samp>ai-automation/</samp></p>
<p align="center">
  <img src="https://img.shields.io/badge/n8n-0b6b64?style=flat-square&labelColor=0b141f&logo=n8n&logoColor=white" alt="n8n"/>
  <img src="https://img.shields.io/badge/LLM%20integration-0b6b64?style=flat-square&labelColor=0b141f" alt="LLM integration"/>
  <img src="https://img.shields.io/badge/Vertex%20AI-0b6b64?style=flat-square&labelColor=0b141f" alt="Vertex AI"/>
  <img src="https://img.shields.io/badge/OCR-0b6b64?style=flat-square&labelColor=0b141f" alt="OCR"/>
  <img src="https://img.shields.io/badge/Google%20Apps%20Script-0b6b64?style=flat-square&labelColor=0b141f&logo=googleappsscript&logoColor=white" alt="Google Apps Script"/>
  <img src="https://img.shields.io/badge/Prompt%20engineering-0b6b64?style=flat-square&labelColor=0b141f" alt="Prompt engineering"/>
</p>

<p align="center"><samp>frontend/</samp></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nextjs,react,angular,ts,tailwind&theme=dark" alt="Next.js, React, Angular, TypeScript, Tailwind CSS"/>
</p>
<p align="center"><sub>Also: React Native</sub></p>

### Featured projects

Systems I worked on, with my role in each one.

| Project | What it is and my role | Links |
|---|---|---|
| **Zephr** | SaaS that brings data from several aviation authorities into a single search. The airworthiness directives database covers six authorities (FAA, EASA, TC, ANAC Brazil, ANAC Argentina and DGAC Chile) and is shared with Aeromate.<br/>**My role:** we updated and optimized the database and built the integration with the FAA API. Queries are 90% faster.<br/><sub>Next.js · Python · Supabase · FAA API</sub> | [adscrapper.hyvento.co](https://adscrapper.hyvento.co/) |
| **Aeromate**<br/><sub>In progress</sub> | Serverless pipeline that identifies, organizes and processes aviation documents. It uses the same directives database as Zephr. It is serverless because documents arrive in bursts and a server running all day would pay for idle time.<br/>**My role:** OCR fidelity validation with fallback methods. Weeks of work done in under a day.<br/><sub>GCP · Firebase Functions · Eventarc · Cloud Tasks · Vertex AI · PostgreSQL</sub> | [aeromate.hyvento.co](https://aeromate.hyvento.co/) |
| **Ingenio Obra** | Construction site management platform for builders that we built for Ingenio Advice. We removed the bottleneck in on-site hiring and payroll settlement, automated health surveys and the Job Safety Analysis (JSA), and automated the daily site log: safety staff and site managers send text, audio and images over Telegram and the system generates the reports.<br/>**My role:** lead software engineer. I built every module except Health Surveys, which another person built.<br/><sub>WordPress · PHP · n8n · Telegram · AI</sub> | [dashboard.ingenioia.com](https://dashboard.ingenioia.com) |
| **Moradia** | Real estate agent that takes what the client asks for in natural language and shows the listings that fit best.<br/>**My role:** the agent and how it runs inside a PHP plugin. Another team did the design.<br/><sub>WordPress · PHP · AI agent</sub> | [moradia.ai](https://www.moradia.ai/) |
| **Fultr**<br/><sub>In progress</sub> | Logistics node software for the Arauco line of shopping centers.<br/>**My role:** validate the system architecture and take it to a production-ready version. Another team owns the design and the business logic.<br/><sub>Next.js · PostgreSQL · Prisma · Cloudflare R2</sub> | [fultr.co](https://fultr.co/) |
| **Solara for Techos Rentables**<br/><sub>1st place · TINKU Hackathon 2026</sub> | Unified monitoring of more than 200 solar projects in one dashboard, built in 18 hours. Cloud Functions polls the manufacturer APIs and runs the rules engine. It detects faults in under 5 minutes, generates automated client reports and removes more than 130 hours a month of manual work.<br/>**My role:** backend developer. I built the backend behind the web app, which consumes the APIs of international manufacturers.<br/><sub>Next.js · Cloud Functions · Firestore · Deye · Huawei · Growatt</sub> | [Code](https://github.com/The-Tribu/tinku_team_ojala_hubiera_pasado_a_la_utp)<br/>[techosrentables.com](https://techosrentables.com)<br/>[Demo](https://solariapp.vercel.app/) |
| **SIGBA**<br/><sub>In progress</sub> | Information system for food banks. The Pereira Food Bank, run by the Cáritas Foundation of the Diocese of Pereira, takes part as the pilot client.<br/>**My role, with my team:** design and loading of the institutions directory, portal for the person in charge of each institution, named beneficiary registry with a single active membership, duplicate alerts and derived characterization.<br/><sub>NestJS · React · PWA</sub> | No public site |
| **Architecture consulting: three APIs and a dashboard** | Consulting for a team of more than five people building three APIs: management, characterization and statistics. Microservices with one database per API, because two of them needed to scale and deploy on their own. The statistics API consumes the other two through asynchronous messaging with RabbitMQ. I have done other consulting work of this kind; this is one example.<br/><sub>Azure · Kubernetes · RabbitMQ · Microservices</sub> | No public site |

### Open source

Projects with public code on GitHub.

| Project | Description | Stack | Code |
|---|---|---|---|
| **StatLab**<br/><sub>In progress</sub> | Descriptive statistics calculator that runs in the browser. You paste or import data, a wizard guides you in Spanish and StatLab calculates, explains and plots. No data leaves the device. | TypeScript | [estadistica-diego](https://github.com/JuanGaitanD/estadistica-diego) |
| **KallIt** | Discord-style group calls with mesh WebRTC: peer-to-peer audio and screen sharing, no media server. Supabase handles auth, presence and real-time chat. | React · Supabase · WebRTC | [Comunicaciones-web-app](https://github.com/JuanGaitanD/Comunicaciones-web-app) |
| **Visión Electoral**<br/><sub>Contributor</sub> | Field surveys for an electoral context. Offline-first Android app that syncs when signal returns, Express API with MongoDB and an Angular dashboard with statistics by role. A third party's repository where I took part. | Kotlin · Angular · Node.js · MongoDB | [vision-electoral](https://github.com/MiloAgudelo/vision-electoral) |
| **Inferential statistics calculator** | Probability distributions, sample size, confidence intervals and hypothesis tests with Z, t and χ². | JavaScript | [calculadora-estadistica-inferencial](https://github.com/JuanGaitanD/calculadora-estadistica-inferencial) |
| **Contract generator with signature** | Google login, guided form, canvas signature and PDF contract generation with Google Apps Script webhooks. | Angular · Firebase | [GeneradorContratosConFirma](https://github.com/JuanGaitanD/GeneradorContratosConFirma) |
| **Digital signature** | Draw your signature and download it as PNG or SVG, no sign-up. | Angular | [obtener_firma_digital](https://github.com/JuanGaitanD/obtener_firma_digital) |
| **NASA Exoplanet Challenge** | Machine learning model that scores exoplanet candidates. | Python | [challenge-nasa-exoplanet](https://github.com/JuanGaitanD/challenge-nasa-exoplanet) |

### Contact

Write to me for architecture consulting or development proposals.

<div align="center">

<a href="https://juandgaitan.com/"><img src="https://img.shields.io/badge/juandgaitan.com-0b6b64?style=for-the-badge&labelColor=0b141f&label=web" alt="Website of Juan David Gaitán: juandgaitan.com"/></a>&nbsp;<a href="https://www.linkedin.com/in/juandavidgaitand/"><img src="https://img.shields.io/badge/in%2Fjuandavidgaitand-0b6b64?style=for-the-badge&labelColor=0b141f&label=LinkedIn" alt="LinkedIn of Juan David Gaitán"/></a>&nbsp;<a href="mailto:juandavidgaitandiaz@gmail.com"><img src="https://img.shields.io/badge/juandavidgaitandiaz%40gmail.com-0b6b64?style=for-the-badge&labelColor=0b141f&label=email" alt="Email of Juan David Gaitán"/></a>

</div>

<br/>

<div align="center"><a href="#español">Leer este perfil en español ↑</a></div>
