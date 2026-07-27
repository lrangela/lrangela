# Luis Eduardo Rangel Araujo 👋

### Frontend Architect | Angular Tech Lead | Enterprise Applications

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/luis-e-rangel-a-69691324/)
[![GitHub GovPortal Live](https://img.shields.io/badge/GovPortal-Live_Demo-007ACC?style=for-the-badge&logo=angular)](https://lrangela.github.io/govportal)
[![TechGear Live](https://img.shields.io/badge/TechGear-Live_Demo-10B981?style=for-the-badge&logo=angular)](https://lrangela.github.io/techgear-inventory-pro)

---

## 📊 Engineering Activity & Stack Metrics

<p align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=lrangela&layout=compact&theme=dark" height="165" alt="Top Languages - Luis Rangel" />
  <img src="https://github-readme-stats-fast.vercel.app/api?username=lrangela&show_icons=true&theme=dark" height="165" alt="GitHub Stats - Luis Rangel" />
</p>

---

## 👤 Professional Summary
Ingeniero de Software y Arquitecto de Frontend especializado en el diseño, desarrollo y gobernanza de plataformas web empresariales de alta escalabilidad. Con amplia experiencia en sectores de alta exigencia contractual y regulatoria (como GovTech y HealthTech), me enfoco en estructurar arquitecturas desacopladas mediante el patrón de Microfrontends y monorreferenciales Nx. Mi propósito principal es mitigar el acoplamiento técnico con el backend mediante capas anti-corrupción (ACL) y establecer sistemas de reactividad eficientes (Angular Signals/Zoneless) para maximizar la performance y el time-to-market de equipos autónomos de ingeniería.

---

## 💻 Engineering Focus

### Frontend Architecture:
- **Angular 14-21**: Dominio avanzado de APIs modernas, Standalone Components, directivas funcionales e inyección de dependencias.
- **Angular Signals**: Reactividad declarativa, control fino de cambios e interoperabilidad RxJS (`linkedSignal`, `rxResource`).
- **Nx Monorepos**: Delimitación de fronteras de código, gobernanza de dependencias y modularización enterprise (`apps/` vs `libs/`).
- **Microfrontend Architecture**: Orquestación dinámica y descentralizada de módulos remotos.
- **Native Federation**: Integración de federación de módulos nativa sobre estándar ESM, eliminando ataduras de Webpack.

### Engineering Practices:
- **Clean Architecture**: Aislamiento estricto de reglas de negocio frente a librerías y contratos de red externos.
- **Domain Driven Design (DDD)**: Subdivisión táctica y estratégica de contextos acotados a nivel de código.
- **Architecture Decision Records (ADRs)**: Documentación de decisiones arquitectónicas basadas en trade-offs concretos.
- **Code Review**: Liderazgo técnico en la auditoría de calidad de código y cumplimiento de convenciones.
- **Performance Optimization**: Control de bundle size, carga diferida (lazy loading), hidratación inteligente y SSR.

### DevOps & Microservices:
- **GitHub Actions / GitLab CI/CD**: Automatización de pipelines orientados a módulos afectados para optimizar costes de CI.
- **Docker**: Containerización multi-stage de aplicaciones frontend, NestJS BFFs e imágenes Nginx optimizadas.
- **Nginx**: Configuración avanzada de servidores web como proxies inversos, cache-control y routing de SPAs.

### Security:
- **OWASP Principles**: Mitigación de inyecciones XSS, control de secuestro de click y cabeceras CSP.
- **JWT & SSO**: Flujos seguros de autenticación federada y propagación de tokens en arquitecturas distribuidas.

---

## 🚀 Featured Enterprise Architectures

### 🏛️ [GovPortal](https://github.com/lrangela/govportal) | [Live Demo](https://lrangela.github.io/govportal)
*Plataforma GovTech de Microfrontends empresariales construida bajo Native Federation y orquestada en un monorepo Nx.*
- **Enfoque**: Coexistencia de plataformas legadas y modernas, despliegue independiente por verticales y límites de importaciones estrictos en el monorepo.
- **Tecnologías**: Angular 21, Native Federation, Nx Workspace, Playwright, Vitest.

### 📈 [CryptoFin Architect](https://github.com/lrangela/cryptofin-architect)
*Dashboard financiero de analíticas cripto y trading de baja latencia con arquitectura BFF sobre Nitro.*
- **Enfoque**: Aislamiento de tokens de APIs externas mediante patrón BFF, Server-Side Rendering (SSR) con AnalogJS y carga perezosa con `@defer`.
- **Tecnologías**: Angular 21, AnalogJS, Nitro Engine, Signals, TailwindCSS.

### 📦 [TechGear Inventory Pro](https://github.com/lrangela/techgear-inventory-pro)
*Monorepo de comercio B2B e inventario integrado con separación rígida de aplicaciones de cara al público y administración.*
- **Enfoque**: Reutilización de lógica de negocio compartida en libs, validación de esquemas en runtime con Zod y aseguramiento del tipado estricto.
- **Tecnologías**: Angular 21, Nx Monorepo, Zod, Signals, Vitest, Playwright.

### 🚀 [Portal UI Base](https://github.com/lrangela/portal-ui-base) | [Live Demo](https://lrangela.github.io/portal-ui-base)
*Sistema de componentes corporativos Storybook y template base de alta velocidad para portales de contenido.*
- **Enfoque**: Arquitectura de islas con hidratación inteligente sobre Astro y Vue 3 para maximizar Core Web Vitals.
- **Tecnologías**: Astro, Vue 3, TailwindCSS, Storybook.

