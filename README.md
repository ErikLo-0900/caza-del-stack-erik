# caza-del-stack-SupaBase
# Reporte de Investigación: Supabase

## 1. Entorno de Edición (IDE)
* **IDE:** **VS Code** + **ESLint** + **Prettier**.
* **Justificación:** Utilizan VS Code por su gran ecosistema de extensiones. **Prettier** y **ESLint** son obligatorios en sus repositorios para que el código de cientos de colaboradores mantenga el mismo estilo y evitar errores de sintaxis comunes en **TypeScript**.
* **Evidencia:** ![IDE Evidence](https://github.com/user-attachments/assets/c09310f4-bd21-441e-951b-e04df42f4a6c)

## 2. Ecosistema de Navegación
* **Navegadores:** **Google Chrome (DevTools)** y **Playwright**.
* **Justificación:** Como su panel de administración (Dashboard) es una aplicación web compleja, usan **Playwright** para simular usuarios reales navegando en diferentes navegadores. Esto asegura que una actualización no rompa el acceso a la base de datos de los clientes.

## 3. Gestión de Versiones
* **Plataforma:** **Git** + **GitHub**.
* **Justificación:** Supabase es "Open Source first". **GitHub** no solo hospeda su código, sino que es su plataforma de colaboración masiva donde gestionan miles de Pull Requests y Issues de la comunidad global.
* **Evidencia:**
![GitHub Stats](https://github.com/user-attachments/assets/076821cb-056b-4ab2-b9d8-0a5db8aba3ba)

## 4. Diseño UI/UX
* **Herramienta:** **Figma**.
* **Justificación:** Han desarrollado una integración profunda llamada **Figma Make**, que permite conectar diseños directamente con una base de datos real. Esto acelera el paso de idea a prototipo funcional sin escribir código de backend inicialmente.

## 5. Lenguajes y Herramientas Base
* **Lenguajes:** **TypeScript**, **SQL (PostgreSQL)** y **Go**.
* **Herramientas Modernas:** **Next.js** y **Tailwind CSS**.
* **Justificación:** Usan **TypeScript** para tener un tipado fuerte que evite errores. Su corazón es **PostgreSQL**, aprovechando sus capacidades avanzadas para ofrecer bases de datos relacionales escalables como servicio.
* **Evidencias Técnicas:**
  * **Análisis de package.json:** ![PackageJson](https://github.com/user-attachments/assets/d8253579-175c-4fb3-b8a8-7195314ea1b0)
  * **Requisitos de Vacante:** ![Vacante](https://github.com/user-attachments/assets/2aadd721-9c82-40f6-8e63-4c47f86b8017)
---

## Resumen del Stack Tecnológico

| Categoría | Herramienta Principal | Propósito en Supabase |
| :--- | :--- | :--- |
| **IDE** | VS Code | Desarrollo y estandarización de código. |
| **Navegación** | Google Chrome | Pruebas de renderizado y rendimiento. |
| **Versiones** | GitHub | Colaboración Open Source y control de cambios. |
| **Diseño** | Figma | Prototipado y mantenimiento del sistema de diseño. |
| **Lenguaje** | TypeScript | Programación segura con tipado fuerte. |
| **Herramienta Base** | PostgreSQL | Corazón del sistema y gestión de bases de datos. |

---
## Fin del documento
