# 📦 Facturación SyEventos — Festejos y Montajes Emisael F.P

![Status](https://img.shields.io/badge/Status-Desarrollo%20Finalizado-success?style=for-the-badge)
![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)
![WPF](https://img.shields.io/badge/WPF-512BD4?style=for-the-badge&logo=.net&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)

Facturación SyEventos es una solución empresarial de alto nivel diseñada para la gestión administrativa y operativa integral de la empresa **Festejos y Montajes Emisael F.P**. Este software representa la digitalización total de los procesos de facturación y logística de eventos, sustituyendo flujos de trabajo manuales por una arquitectura robusta capaz de manejar transacciones multimoneda en tiempo real con una interfaz de grado premium.

El sistema actúa como un motor de inteligencia operativa, permitiendo automatizar el cálculo de presupuestos complejos y el seguimiento de activos (alquileres) con una precisión quirúrgica mediante una experiencia de usuario optimizada en C# y WPF.

---

## 🌐 Motor de Sincronización Cambiaria (BCV Scraper)

Dada la naturaleza económica del entorno operativo, el sistema integra un módulo de automatización financiera crítica:

* **Web Scraping en Tiempo Real:** Implementación de `HtmlAgilityPack` para la extracción automatizada de la tasa oficial desde el portal del Banco Central de Venezuela (BCV).
* **Gestión Multimoneda Dinámica:** Capacidad para procesar documentos en USD y VES simultáneamente mediante vistas especializadas (`FacturaUsdWindow`). El sistema recalcula montos al instante garantizando transparencia financiera.
* **Manejo de Resiliencia de Red:** Algoritmos de validación y manejo de excepciones que aseguran la estabilidad del sistema ante fallos de conexión o cambios en el portal externo.

---

## 🏗️ Arquitectura de Persistencia y Seguridad

El diseño de la base de datos ha sido estructurado bajo estándares de integridad para soportar operaciones comerciales críticas:

* **Motor SQLite de Alta Velocidad:** Optimizado para transacciones locales atómicas, garantizando latencia nula en la búsqueda de productos y clientes.
* **Integridad Referencial ACID:** Configuración estricta de `PRAGMA foreign_keys = ON` y reglas de **Borrado en Cascada** (`ON DELETE CASCADE`) para mantener la coherencia absoluta entre facturas y sus detalles.
* **Blindaje contra Inyecciones:** Implementación obligatoria de **Consultas Parametrizadas** en toda la capa de datos, neutralizando vulnerabilidades de SQL Injection.

---

## ✨ Características Destacadas

* 📊 **Dashboard Estratégico:** Panel visual que muestra el flujo de facturación y el estado de los alquileres activos para una toma de decisiones informada.
* ⚡ **Presupuestos "Flash" con Plantillas:** Sistema de carga rápida de datos basado en plantillas predefinidas, permitiendo emitir cotizaciones complejas en segundos.
* 🖨️ **Módulo de Reportes PDF Pro:** Generación de documentos nativos en PDF que integran la identidad corporativa de la empresa, listos para entrega inmediata al cliente.
* 👥 **Gestión de Proveedores y Contactos:** Agenda centralizada para el manejo de logística de suministros y contactos clave del negocio.
* ⚡ **Arquitectura Asíncrona (Async/Await):** Procesos de carga de datos y web scraping ejecutados en segundo plano para mantener la fluidez de la interfaz.

---

## 🛠️ Stack Tecnológico

* **Core & Runtime:** C# bajo el ecosistema .NET.
* **Interfaz de Usuario (UI):** WPF (Windows Presentation Foundation) con diseño minimalista y navegación fluida.
* **Persistencia de Datos:** SQLite bajo una arquitectura de Capa de Acceso a Datos (DAL), utilizando `DatabaseContext` para desacoplar la lógica de negocio.
* **Librerías Clave:**
    * **HtmlAgilityPack:** Extracción y procesamiento de datos web.
    * **Microsoft.Data.Sqlite:** Manipulación segura de la base de datos.
    * **QuestPDF:** Generación de reportes estructurales en PDF de alta calidad.

---

## 👤 Autor

**Enzo Rodríguez** — *Junior Analista de Sistemas* - *Estudiante de Ingeniería de Sistemas*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-rodr%C3%ADguez-47756a404/)

---
## 🖥️ System Showcase: Facturación SyEventos
<div align="center">
  <video src="[https://github.com/user-attachments/assets/530f049c-44fe-4eac-9b13-9fad66bde46d](https://github.com/user-attachments/assets/89458030-27f4-47f7-938b-b12802092506)">
  </video>
</div>
