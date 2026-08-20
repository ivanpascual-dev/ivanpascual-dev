# Iván Pascual
**Full Stack Developer & AI Engineer**

Construyo productos AI-first en producción: sistemas multi-agente, automatizaciones y plataformas completas desde cero.

> Si algo se puede automatizar, hay que automatizarlo.

Vengo del desarrollo full stack y del soporte IT (retail, aeronáutico, logística con AS400/RPG), y desde marzo de 2026 estoy centrado a tiempo completo en la IA: mantengo en producción **Albivi** (gestión financiera personal con agentes), **Asignatura Pendiente** (plataforma con pagos y backoffice conversacional) y **ANDAV** (tienda online con asistente 24/7, proyecto de cliente), mientras curso el Máster en Desarrollo de IA.

🌐 **[ivanpascualrodriguez.com](https://ivanpascualrodriguez.com)** · proyectos, stack y cómo trabajo, todo en un sitio.

---

## 🔧 Stack principal

```
IA & Agentes      Claude · OpenAI · Gemini · Multi-Agent Systems · Tool Use · Prompt Engineering
Backend           Python · FastAPI · SQLAlchemy · Alembic · Node.js · TypeScript
Frontend          Astro · React · TypeScript · TailwindCSS · HTML5 · CSS
Datos & Infra     PostgreSQL (Neon) · Drizzle ORM · Stripe · REST APIs · Docker · GitHub Actions (CI/CD) · Git · Vercel · Cloudflare Workers
Dev con IA        Claude Code · Antigravity
Aprendiendo       Next.js · LangChain · n8n
También           Java · Spring Boot · Angular · PHP · WordPress
```


---

## 🚀 Proyectos activos

### [Albivi](https://github.com/ivanpascual-dev/albivi-showcase) · Plataforma de finanzas personales con agentes de IA

Plataforma completa de finanzas personales: banco (CaixaBank/ING/Revolut), bolsa (DeGiro),
crypto (KuCoin + Ledger), préstamos con tabla de amortización y patrimonio neto histórico.
Dos agentes de IA: uno conversacional con **tool-use real** (9 herramientas que consultan la BD
en tiempo real) y uno autónomo mensual que analiza la actividad y da recomendaciones que mejora
con mi feedback. Proveedor seleccionable: Claude o Gemini. Tests automatizados y CI/CD.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4B896?logo=anthropic&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white)
![IA](https://img.shields.io/badge/IA%20%2F%20Function%20Calling-8B5CF6?logoColor=white)
![Finanzas Personales](https://img.shields.io/badge/Finanzas%20Personales-10B981?logoColor=white)
![Showcase](https://img.shields.io/badge/Showcase-6B7280?logoColor=white)


### [La Asignatura Pendiente](https://github.com/ivanpascual-dev/asignatura-pendiente-showcase) · [🌐 Web](https://asignaturapendiente.es)

Plataforma web AI-first en producción para una psicóloga: tienda con **Stripe**, contenido
protegido (vídeo/audio/PDF), comunidad privada tipo red social (**PWA** con notificaciones push)
y **dos agentes de IA con tool-use real**: uno público de ventas y soporte (Gemini) y un backoffice
donde se gestiona todo el negocio conversando (Claude, 29 herramientas). Auth propia con JWT + Google OAuth.

![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?logo=drizzle&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4B896?logo=anthropic&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white)
![PWA](https://img.shields.io/badge/PWA-5A0FC8?logo=pwa&logoColor=white)
![IA](https://img.shields.io/badge/IA%20%2F%20Multi--Agente-8B5CF6?logoColor=white)
![Bienestar Mental](https://img.shields.io/badge/Bienestar%20Mental-F7235B?logoColor=white)
![Showcase](https://img.shields.io/badge/Showcase-6B7280?logoColor=white)


### [ANDAV](https://github.com/ivanpascual-dev/andav-showcase) · [🌐 Web](https://andav.es)

Proyecto de cliente entregado de principio a fin: web, tienda online y asistente 24/7 para una
marca de materiales y suministros de reforma. Catálogo de 30 productos y **1.461 variantes**
(color, medida, acabado), precio calculado **siempre en servidor** (por unidad, por m² con
mínimos de venta), **Stripe Checkout** con webhook verificado por firma y confirmación por email.
Asistente conversacional con **6 tools de solo lectura** sobre datos reales del negocio, scope
acotado con batería propia de pruebas de inyección, escalado por WhatsApp y conmutación automática
Gemini → Claude si el modelo principal no responde. 18 ADR documentadas y purga de datos por RGPD.

![Astro](https://img.shields.io/badge/Astro-FF5D01?logo=astro&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwindcss&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/Cloudflare%20Workers-F38020?logo=cloudflare&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F74F?logo=drizzle&logoColor=black)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?logo=stripe&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D4B896?logo=anthropic&logoColor=black)
![Resend](https://img.shields.io/badge/Resend-000000?logo=resend&logoColor=white)
![IA](https://img.shields.io/badge/IA%20%2F%20Tool%20Use-8B5CF6?logoColor=white)
![Ecommerce](https://img.shields.io/badge/Ecommerce-F97316?logoColor=white)
![Showcase](https://img.shields.io/badge/Showcase-6B7280?logoColor=white)


### [Chronorium](https://github.com/ivanpascual-dev/chronorium) · Motor open source de informes periódicos con IA

**Código público (MIT), no un showcase.** Motor genérico que convierte cualquier tema que sigas en un
informe periódico con opinión: el tema, las fuentes, el tono y la estructura viven en una **receta**
(YAML + Markdown que editas), nunca en el código. Sin servidor ni panel: corre en **GitHub Actions** y
el propio repositorio hace de base de datos. 5 tipos de fuente, 3 canales de entrega (email, Telegram,
webhook) y 3 proveedores de modelo intercambiables con cadena de respaldo. Reescritura completa del
original a partir de **5 fallos medidos en 49 días** de ejecución desatendida: los enlaces que devuelve
el modelo se validan **en código**, no se le piden en el prompt; el estado de salud viaja dentro del
informe; y la CI falla si la documentación deja de coincidir con el código. 44 ficheros de test y 22 ADR.

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js%2024-5FA04E?logo=nodedotjs&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=githubactions&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?logo=openai&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?logo=zod&logoColor=white)
![Biome](https://img.shields.io/badge/Biome-60A5FA?logo=biome&logoColor=white)
![Agentes IA](https://img.shields.io/badge/Agentes%20de%20IA-8B5CF6?logoColor=white)
![MIT](https://img.shields.io/badge/Licencia-MIT-22C55E?logoColor=white)
![Código público](https://img.shields.io/badge/C%C3%B3digo%20p%C3%BAblico-16A34A?logoColor=white)


### Otros proyectos

- **Fitness Harness**: sistema multi-agente (Claude API) con orquestador + subagentes
  especializados (entrenador, nutricionista, sueño, revisor) para seguimiento de salud y
  rendimiento. En desarrollo.
- **Sistema de arneses personales con IA**: framework propio de orquestación multi-agente
  basado en markdown (sin código que compilar), aplicado a la gestión de mi búsqueda de empleo y
  a mi sistema de salud. Proyecto interno, sin repo público.

---

## 📫 Contacto

- 🌐 [ivanpascualrodriguez.com](https://ivanpascualrodriguez.com)
- 💼 [LinkedIn](https://linkedin.com/in/iprodriguez)
- 📧 [ivanpascual988@gmail.com](mailto:ivanpascual988@gmail.com)
- 📍 Madrid, España

---

*Disponibilidad inmediata. Buscando un equipo donde seguir creciendo como desarrollador de IA.*
