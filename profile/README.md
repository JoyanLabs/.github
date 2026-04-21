# Joyan | Ecosistema de Innovación 🌐

**Visión:** Ser el socio tecnológico integral para empresas en crecimiento, transformando desafíos complejos en soluciones unificadas a través de un ecosistema de innovación sinérgico.


---

## 🚀 Acerca de esta Organización

Esta organización de GitHub es el centro de ejecución técnica de **Joyan EXP**, el motor de integración y software a medida de nuestro ecosistema. Aquí gestionamos el código, la infraestructura y los activos de ingeniería que nos permiten construir y conectar el software que nuestros clientes necesitan para operar sin fricciones.

Nuestro objetivo es implementar una infraestructura de procesos y tecnología cohesiva. Cada repositorio es un activo diseñado para escalar nuestras operaciones, garantizar la calidad y habilitar la sinergia entre nuestras divisiones.

---

## 🏗️ Arquitectura y Nomenclatura de Repositorios

Para mantener la claridad, la escalabilidad y facilitar la automatización, todos los repositorios siguen una estricta convención de nomenclatura. Esto nos permite entender el propósito de cada proyecto de un vistazo y automatizar nuestros flujos de trabajo.

La estructura estándar es:
```
tipo-division-descriptor
```

-   **`tipo`**: Define el propósito del repositorio (qué es).
-   **`division`**: Define el propietario (quién lo lidera).
-   **`descriptor`**: Define el contenido (qué hace). Se utiliza kebab-case (guiones).

### 📋 Definiciones de Tipos y Divisiones

| Tipo | Descripción |
| :--- | :--- |
| `template` | Plantillas de inicio para nuevos proyectos. |
| `client` | Proyecto específico para un cliente (facturable). |
| `project` | Proyecto de I+D, producto interno o piloto (no facturable). |
| `internal` | Herramientas internas, servicios de soporte, configuraciones. |
| `demo` | Demostraciones de productos o servicios (para uso interno o público). |
| `public` | Proyectos públicos: landings, open source, etc. |

| División | Descripción |
| :--- | :--- |
| `exp` | Experience: Integración, ERPs, CRMs, software a medida. |
| `iot` | IoT: Proyectos de hardware y conectividad. |
| `sec` | Security: Servicios y auditorías de seguridad. |
| `mkt` | Marketing: Proyectos de cara al público, landings, etc. |
| `labs` | R&D: Investigación y desarrollo de nuevos productos/pilotos. |
| `ops` | Operations: Herramientas transversales, CI/CD, infraestructura interna. |

### 🏷️ Tabla de Nomenclatura y Etiquetado

| Tipo de Repositorio | Formato del Nombre | Ejemplo | Etiquetas/Topics Recomendadas |
| :--- | :--- | :--- | :--- |
| 📦 **Plantilla** | `template-division-servicio` | `template-exp-odoo-v19` | `template`, `odoo`, `exp` |
| 🤝 **Cliente** | `client-division-cliente-servicio` | `client-exp-acme-odoo` | `client-project`, `acme`, `odoo` |
| 🔬 **Proyecto (I+D)** | `project-division-nombre` | `project-labs-tars_backend` | `project`, `labs`, `tars`, `backend` |
| 🛠️ **Herramienta Interna** | `internal-division-herramienta` | `internal-ops-n8n_workflows` | `internal-tool`, `ops`, `n8n` |
| 🎬 **Demostración** | `demo-division-servicio` | `demo-exp-twenty-crm` | `demo`, `twenty`, `exp` |
| 🌍 **Público** | `public-division-proyecto` | `public-mkt-amanto_landing` | `public`, `mkt`, `landing` |

> [!IMPORTANT]
> El uso de **Etiquetas (Topics)** en cada repositorio no es opcional. Es fundamental para filtrar y organizar nuestros activos, permitiendo una gestión visual y programática del ecosistema.

---

## 🧩 Estrategia de Ecosistema

Si bien gran parte de la actividad aquí proviene de **Joyan EXP**, es crucial entender que cada solución desplegada está diseñada para ser parte de un todo más grande.

-   Un ERP **Odoo** (desplegado por Joyan EXP) puede ser asegurado por **Joyan Sec**.
-   Un panel de control a medida (Joyan EXP) puede visualizar datos de sensores instalados por **Joyan IoT**.
-   Un proyecto piloto de **Joyan Labs** (como TARS) puede convertirse en un producto comercializado por **Joyan MKT**.

Esta capacidad para gestionar el ciclo de vida tecnológico completo de un cliente es nuestra **ventaja competitiva** y el principio rector de todo lo que construimos.

---

## 📫 Contacto

Si tienes preguntas sobre nuestra metodología o cómo nuestro ecosistema puede ayudarte a crecer, no dudes en ponerte en contacto.

---

## 📋 Apéndice: Migración de Repositorios Actuales

Basado en la nueva nomenclatura, se sugiere renombrar los repositorios existentes que no cumplan el estándar para mantener la consistencia:

| Nombre Actual | Nombre Sugerido | Justificación |
| :--- | :--- | :--- |
| `joyan-obsidian` | `internal-ops-obsidian-vault` | Herramienta interna de operaciones. |
| `joyan-n8n` | `internal-ops-n8n-server` | Herramienta interna de operaciones. |
| `joyan-twenty-serv` | `internal-ops-twenty-server` | Herramienta interna de operaciones. |
| `n8n-template` | `template-ops-n8n-workflow` | Plantilla para flujos de automatización. |
| `tars-backend` | `project-labs-tars-backend` | Proyecto piloto de I+D de Labs. |
| `tars-frontend` | `project-labs-tars-frontend` | Proyecto piloto de I+D de Labs. |
| `amanto-landing` | `public-mkt-amanto-landing` | Proyecto público gestionado por Marketing. |
| `demo-exp-odoo_v19-erp` | `demo-exp-odoo-v19-erp` | Estandarizar a guiones (-) vs (_). |
| `template-labs-nest_service` | `template-labs-nest-service` | Estandarizar a guiones (-) vs (_). |

---

*Este README es parte del Sistema Operativo Joyan y está diseñado para evolucionar con nuestro ecosistema.*
