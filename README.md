# Power Platform & Copilot Studio Adoption Strategy – Quick Assessment

[Español](#español) · [English](#english)

![Power Platform & Copilot Studio Adoption Strategy – Quick Assessment](./assets/adoption-home.png)

---

## Breve descripción

Herramienta web bilingüe de autoevaluación que permite analizar la madurez de la estrategia de adopción de Power Platform y Copilot Studio. Evalúa estrategia, audiencias, capacitación, comunidad, acceso, gobernanza, activación de casos de uso, medición y generación de valor, y produce un diagnóstico ejecutivo con riesgos, prioridades y un plan orientativo de 90 días.

---

# Español

## Descripción

**Power Platform & Copilot Studio Adoption Strategy – Quick Assessment v1.0** es una aplicación web de una sola página diseñada para ayudar a una organización a evaluar si dispone de las capacidades necesarias para transformar Power Platform y Copilot Studio en comportamientos sostenibles, soluciones utilizadas de forma recurrente y resultados medibles.

La herramienta forma parte del **CoE Toolkit** desarrollado por **Nico Fernandez**.

## Características principales

- Español de Argentina (`es-AR`) e inglés de Estados Unidos (`en-US`).
- Interfaz responsive para desktop, tablet y dispositivos móviles.
- Perfil organizacional y selección del alcance tecnológico.
- 24 preguntas comunes distribuidas en seis dominios.
- Módulo condicional de Power Platform.
- Módulo condicional de Copilot Studio.
- Escala de madurez de 0 a 4.
- Puntuación global ponderada de 0 a 100.
- Estado de riesgo independiente: rojo, ámbar o verde.
- Resultados por dominio y por módulo tecnológico.
- Mapa de cobertura de las preguntas aplicables.
- Identificación automática de fortalezas, gaps y riesgos críticos.
- Hasta cinco acciones prioritarias.
- Plan orientativo de actuación para los siguientes 90 días.
- Reporte ejecutivo multipágina en PDF.
- Enlaces a LinkedIn, libros y herramientas relacionadas.
- Procesamiento local de las respuestas en el navegador.
- Sin backend, base de datos ni autenticación.

## Dominios evaluados

| Dominio | Peso |
|---|---:|
| Estrategia, objetivos y patrocinio | 20 % |
| Audiencias y recorridos de adopción | 15 % |
| Capacitación, comunidad y acompañamiento | 15 % |
| Acceso, gobernanza y confianza | 15 % |
| Activación y escalado de casos de uso | 15 % |
| Medición, valor y sostenibilidad | 20 % |

## Módulos condicionales

### Power Platform

Se activa cuando Power Apps, Power Automate, Power BI o Power Pages forman parte del alcance.

Evalúa:

- Segmentación y progresión de makers.
- Transición desde prototipos hasta soluciones productivas.
- Ownership, soporte y ciclo de vida.
- Uso recurrente y valor.
- Escalado, mejora o retirada de soluciones.

### Copilot Studio

Se activa cuando Copilot Studio forma parte del alcance actual o previsto.

Evalúa:

- Preparación de creadores y propietarios de agentes.
- Propósito, audiencia y límites.
- Fuentes de conocimiento, acciones y pruebas.
- Publicación y responsabilidades operativas.
- Comprensión de capacidades y limitaciones por los usuarios.
- Calidad, resolución, feedback y escalado.
- Mejora continua y uso responsable de IA.

## Escala de madurez

| Puntuación | Nivel | Interpretación |
|---:|---|---|
| 0 | Inexistente | La capacidad no existe o no fue considerada. |
| 1 | Inicial | Existen iniciativas aisladas o informales. |
| 2 | Definido | La capacidad está diseñada, pero se aplica parcialmente. |
| 3 | Gestionado | La capacidad se aplica de forma consistente y se revisa con evidencias. |
| 4 | Optimizado | La capacidad se mide, mejora continuamente y se conecta con resultados de negocio. |

## Niveles globales

| Resultado | Nivel |
|---:|---|
| 0–39 | Inicial |
| 40–59 | Emergente |
| 60–74 | Definido |
| 75–89 | Gestionado |
| 90–100 | Optimizado |

Las respuestas marcadas como **No aplicable** se excluyen del cálculo.

## Evaluación de riesgo

El estado de riesgo se calcula por separado de la puntuación global. Una puntuación general alta no compensa automáticamente una carencia crítica.

- **Rojo:** existe al menos una ausencia crítica o varias capacidades críticas en estado inicial.
- **Ámbar:** hay capacidades relevantes definidas, pero todavía no se aplican de forma consistente.
- **Verde:** las capacidades críticas presentan una cobertura adecuada.

## Reporte PDF

El assessment genera un informe ejecutivo A4 con:

- Portada y fecha de generación.
- Resultado global, madurez, riesgo y completitud.
- Contexto organizacional.
- Resultados por dominio y módulo.
- Fortalezas y gaps.
- Riesgos críticos.
- Acciones prioritarias.
- Plan de 90 días.
- Mapa de cobertura.
- Respuestas abiertas.
- Definición de la escala.
- Herramientas adicionales.
- Libros relacionados.
- Enlaces clicables.

El PDF se genera localmente mediante **jsPDF**.

## Privacidad

- Las respuestas se procesan localmente en el navegador.
- No se transmiten a ningún servidor.
- No se utiliza una base de datos.
- No se requiere iniciar sesión.
- La preferencia de idioma puede guardarse en `localStorage`.
- El PDF solo se genera y descarga cuando el usuario lo solicita.

## Uso local

1. Descargá o cloná el repositorio.
2. Abrí `index.html` en un navegador moderno.
3. Seleccioná el idioma.
4. Completá el perfil y las preguntas aplicables.
5. Revisá los resultados.
6. Descargá el reporte PDF.

No se requiere instalación, compilación ni servidor local.

## Publicación en GitHub Pages

1. Creá un repositorio en GitHub.
2. Copiá `index.html`, `README.md` y la carpeta `assets` en la raíz.
3. Realizá el commit y push.
4. Abrí **Settings > Pages**.
5. Seleccioná **Deploy from a branch**.
6. Elegí la rama principal y la carpeta `/root`.
7. Guardá la configuración.

## Estructura del proyecto

```text
.
├── index.html
├── README.md
└── assets
    └── adoption-home.png
```

## Herramientas adicionales del CoE Toolkit

- [Power Platform Tenant Inventory Explorer](https://nfernandezba.github.io/power-platform-tenant-inventory-explorer/)
- [Power Platform & Copilot Studio Environment Strategy – Quick Assessment](https://nfernandezba.github.io/Power-Platform-Copilot-Studio-Environment-Assessment/)
- [Copilot Studio Credits Monitor](https://nfernandezba.github.io/Copilot-Studio-Credits-Monitor/)

## Libros relacionados

### Español

- [Definiendo la estructura marco para el Centro de Excelencia de Power Platform](https://www.amazon.com/-/es/Definiendo-estructura-Centro-Excelencia-Platform/dp/B0FSDWQMHW/ref=tmm_pap_swatch_0)
- [Copilot Studio y el futuro del Centro de Excelencia de Power Platform](https://www.amazon.com/-/es/Nicol%C3%A1s-Andr%C3%A9s-Fern%C3%A1ndez/dp/B0GZGL3T1K/ref=tmm_pap_swatch_0)

### English

- [Defining the Framework Structure for the Power Platform Center of Excellence](https://www.amazon.com/-/es/Defining-Framework-Structure-Platform-Excellence/dp/B0GDDRCD2C/ref=tmm_pap_swatch_0)
- [Copilot Studio and the Future of the Power Platform Center of Excellence](https://www.amazon.com/-/es/Nicol%C3%A1s-Andr%C3%A9s-Fern%C3%A1ndez/dp/B0GZGNS19B/ref=tmm_pap_swatch_0)

## Autor

**Nico Fernandez**

[LinkedIn](https://www.linkedin.com/in/nfernandezba)

## Aviso

Esta herramienta es una autoevaluación orientativa. No constituye una certificación de Microsoft, una auditoría de cumplimiento, una evaluación de seguridad, una garantía de adopción ni un sustituto de una revisión profesional detallada.

---

# English

## Short description

A bilingual browser-based self-assessment that helps organizations evaluate the maturity of their Power Platform and Copilot Studio adoption strategy. It reviews strategy, audiences, enablement, community, access, governance, use-case activation, measurement, and value, and produces an executive diagnosis with risks, priorities, and an indicative 90-day action plan.

## Overview

**Power Platform & Copilot Studio Adoption Strategy – Quick Assessment v1.0** is a single-page web application designed to help organizations assess whether they have the capabilities required to turn Power Platform and Copilot Studio into sustainable behaviors, recurring use, and measurable outcomes.

The tool is part of the **CoE Toolkit** developed by **Nico Fernandez**.

## Key features

- Argentinian Spanish (`es-AR`) and United States English (`en-US`).
- Responsive interface for desktop, tablet, and mobile.
- Organization profile and technology scope.
- 24 common questions across six domains.
- Conditional Power Platform module.
- Conditional Copilot Studio module.
- Maturity scale from 0 to 4.
- Weighted overall score from 0 to 100.
- Independent red, amber, or green risk status.
- Domain and technology-module results.
- Coverage map for applicable questions.
- Automatic identification of strengths, gaps, and critical risks.
- Up to five priority actions.
- Indicative 90-day action plan.
- Multi-page executive PDF report.
- LinkedIn, book, and related-tool links.
- Client-side response processing.
- No backend, database, or authentication.

## Assessment domains

| Domain | Weight |
|---|---:|
| Strategy, objectives, and sponsorship | 20% |
| Audiences and adoption journeys | 15% |
| Enablement, community, and support | 15% |
| Access, governance, and trust | 15% |
| Use-case activation and scaling | 15% |
| Measurement, value, and sustainability | 20% |

## Conditional modules

### Power Platform

Enabled when Power Apps, Power Automate, Power BI, or Power Pages is in scope.

It evaluates maker progression, prototype-to-production transition, ownership, support, lifecycle, recurring use, value, scaling, improvement, and retirement.

### Copilot Studio

Enabled when Copilot Studio is in the current or planned scope.

It evaluates agent-maker and owner preparation, purpose, audience, boundaries, knowledge, actions, testing, publishing, operations, user trust, quality, resolution, feedback, escalation, and responsible AI improvement.

## Privacy

- Answers are processed locally in the browser.
- No answers are transmitted to a server.
- No database is used.
- No sign-in is required.
- The PDF is generated locally and downloaded only when requested.

## Local use

1. Download or clone the repository.
2. Open `index.html` in a modern browser.
3. Select a language.
4. Complete the profile and applicable questions.
5. Review the results.
6. Download the PDF report.

## Deploying with GitHub Pages

1. Create a GitHub repository.
2. Copy `index.html`, `README.md`, and the `assets` folder to the repository root.
3. Commit and push the files.
4. Open **Settings > Pages**.
5. Select **Deploy from a branch**.
6. Choose the main branch and `/root`.
7. Save the configuration.

## Author

**Nico Fernandez**

[LinkedIn](https://www.linkedin.com/in/nfernandezba)

## Disclaimer

This tool is an indicative self-assessment. It is not a Microsoft certification, compliance audit, security assessment, adoption guarantee, or substitute for a detailed professional review.
