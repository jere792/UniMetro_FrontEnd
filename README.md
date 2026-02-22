# 🚀 Sistema de Gestión Integral - Unimetro SAC

Este proyecto es una solución **ERP a medida** desarrollada para la gestión de procesos comerciales y operativos de **Unimetro SAC**, una empresa especializada en servicios de calibración y metrología. 

El sistema está construido con un enfoque moderno y escalable: el frontend está potenciado por **Angular 21**, utilizando la extensa librería de componentes **PrimeNG** para ofrecer una interfaz de usuario rica, rápida y altamente interactiva. Además, todo el diseño visual está estructurado con **SCSS** modular, permitiendo temas personalizados (Dark/Light mode) y un código CSS altamente mantenible. Todo esto se conecta a una robusta arquitectura backend de **Microservicios**.

---

## 🛠️ Stack Tecnológico

### **💻 Frontend (SPA)**
*   **Framework:** **Angular 21** (Uso extensivo de *Signals*, *Standalone Components* y el nuevo *Control Flow*).
*   **UI Library:** **PrimeNG** (Tablas avanzadas con paginación nativa, modales, selectores y autocompletado).
*   **Estilos:** **SCSS** (Hojas de estilo modulares, anidamiento, variables para temas personalizados y diseño responsive).
*   **Utilidades CSS:** **PrimeFlex** (Flexbox y grillas para maquetación ágil).

### **⚙️ Backend (Microservicios)**
*   **Framework:** Spring boot
*   **Arquitectura:** Microservicios comunicados vía TCP (`ClientProxy`).
*   **Servicios Independientes:**
    1.  **Auth/Admin:** Gestión de usuarios, roles.
    2.  **Ventas:** Clientes, cotizaciones, expedientes y guías.
    3.  **Logística:** Productos, servicios, stock y precios.
*   **Base de Datos:** [MySQL]
*   **ORM:** [TypeORM]

---

## 🚀 Instalación y Despliegue en Local

### Prerrequisitos
*   Node.js (v24.11.1)
*   Angular CLI versión 21 (`npm install -g @angular/cli@21`)
*   Base de datos configurada y en ejecución.

### Instrucciones
1.  **Clonar el repositorio:**
    ```bash
    git clone [https://github.com/jere792/UniMetro_FrontEnd.git]
    ```

2.  **Levantar el Frontend (Angular 21):**
    ```bash
    cd frontend-angular21
    npm install
    ng serve
    ```
    *La aplicación estará disponible en `http://localhost:4200`.*

3.  **Levantar el Backend (Microservicios en NestJS):**
    Abre terminales separadas para cada microservicio y ejecuta:
    ```bash
    cd backend/[UniMetro_Backend]
    npm install
    npm run start:dev
    ```

---

## 🤝 Equipo de Desarrollo

Este sistema fue diseñado y desarrollado íntegramente por un equipo de estudiantes de **Ingeniería de Sistemas (7no - 9no Ciclo)**, aplicando patrones de diseño, clean code y metodologías ágiles.

*   **[Jeremy]** - *Full Stack Developer / Arquitectura Frontend*
*   **[Dominid, Juan Diego]** - *Backend Developer*
*   **[Erick]** - *Database Admin / QA*
*   **[Angie, Angie]** - *Frontend Developer*
*   **[Angie, Enzi]** - *UI/UX & Documentation*
*   **[Dominid]** - *DevOps / Deployment*

---

## 📄 Licencia

Este software es un producto privado desarrollado a medida para **Unimetro SAC**. Queda estrictamente prohibida su copia, distribución o comercialización sin autorización expresa.

---
*Desarrollado con ❤️ y código limpio en Perú 🇵🇪*
