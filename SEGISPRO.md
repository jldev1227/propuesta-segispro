# 📌 Planificación del Proyecto – Plataforma Inteligente SEGISPRO

**Cliente:** EGISPRO INGENIERÍA SAS  
**Responsable de desarrollo:** Julián López (Tecnólogo ADS)  
**Duración total:** 3 meses (12 semanas)  
**Presupuesto total:** $10.000.000 COP (sin incluir APIs, OCR, Azure, hosting)  

---

## 🎯 Objetivo General
Desarrollar una plataforma inteligente que permita a EGISPRO centralizar, automatizar y dar trazabilidad a las órdenes de servicio asignadas por las ARL, reduciendo pérdidas operativas (~10% anual) y optimizando la gestión de profesionales, clientes y reportes.

---

## 📂 Entregables del Proyecto
- **Módulo de gestión de órdenes ARL** con trazabilidad completa.  
- **BOT AI** con Puppeteer/Playwright para ingresar a portales ARL y extraer órdenes.  
- **OCR con Azure Cognitive Services** para lectura de documentos.  
- **Calendario interno y externo** (Google/Outlook API).  
- **Notificaciones automáticas** vía WhatsApp API y Outlook SMTP.  
- **Módulo de profesionales** (internos y externos, agenda y asignaciones).  
- **Reportes** en Excel/PDF con métricas y trazabilidad.  
- **Documentación técnica + manual de usuario.**

---

# 📅 Plan de Proyecto – 12 semanas / 12 fases

### 🔹 **Semana 1 – Análisis de Requerimientos**

- Reunión con gerencia y equipo de EGISPRO.
    
- Levantamiento de procesos actuales y flujos con las ARL.
    
- Definición de roles de usuario (admin, profesional, cliente).
    
- Documentación inicial de alcance.
    

---

### 🔹 **Semana 2 – Diseño de Arquitectura**

- Diagramas de arquitectura (frontend, backend, base de datos, integraciones externas).
    
- Selección de stack definitivo (Next.js, Node, Prisma, PostgreSQL, Azure).
    
- Configuración de repositorios y entorno de desarrollo.
    

---

### 🔹 **Semana 3 – Modelado de Base de Datos**

- Diseño de entidades (Órdenes, Profesionales, Clientes, Actividades, Documentos).
    
- Creación de esquema inicial con Prisma + PostgreSQL.
    
- Migraciones iniciales y validación de relaciones.
    

---

### 🔹 **Semana 4 – Mockups y UX/UI**

- Diseño de pantallas principales: dashboard, órdenes, calendario.
    
- Prototipo visual en Figma o similar.
    
- Validación de interfaz con gerencia.
    

---

### 🔹 **Semana 5 – Backend Inicial**

- Configuración de API GraphQL/REST.
    
- Endpoints base para Órdenes y Profesionales.
    
- Autenticación JWT y roles.
    

---

### 🔹 **Semana 6 – BOT AI (Scraping ARL)**

- Desarrollo del bot (Puppeteer/Playwright).
    
- Automatización de login y consulta de órdenes.
    
- Registro automático en la base de datos.
    

---

### 🔹 **Semana 7 – OCR y Documentos**

- Integración de Azure Cognitive Services (OCR).
    
- Extracción de datos de documentos de soporte.
    
- Validación de estructura de archivos y almacenamiento en Azure.
    

---

### 🔹 **Semana 8 – Notificaciones**

- Integración con Outlook SMTP para correos.
    
- Integración con API de WhatsApp Business.
    
- Sistema de recordatorios automáticos.
    

---

### 🔹 **Semana 9 – Calendario y Profesionales**

- Integración con Google/Outlook Calendar API.
    
- Módulo de agenda de profesionales.
    
- Vista mensual con actividades programadas.
    

---

### 🔹 **Semana 10 – Dashboard y Reportes**

- Dashboard central con métricas de estado de servicios.
    
- Exportación de reportes en PDF y Excel.
    
- Gráficas con estadísticas de pérdidas/ahorros.
    

---

### 🔹 **Semana 11 – Pruebas y QA**

- Pruebas unitarias y de integración.
    
- Ajustes de seguridad (tokens, permisos).
    
- Corrección de bugs.
    

---

### 🔹 **Semana 12 – Despliegue y Capacitación**

- Deploy final en Vercel + Azure.
    
- Entrenamiento a personal de EGISPRO.
    
- Entrega de manual de usuario y documentación técnica.
