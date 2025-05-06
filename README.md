# 💼 AlmaCol – Sistema de Gestión de Inventario Multialmacén

**AlmaCol** es una aplicación diseñada para optimizar la gestión de inventario en empresas que trabajan con múltiples almacenes, como *Ipomajo*, mejorando el control de stock, la consulta en tiempo real, la trazabilidad de movimientos y la comunicación entre vendedores, bodegueros y jefes.

Este sistema nace como solución a problemas identificados en la operación diaria, tales como errores al vender productos agotados, mala visibilidad del stock en cada almacén, productos dañados mal registrados y dificultades al gestionar devoluciones u objetos perdidos.

---

## 📌 Características principales

- Consulta en tiempo real del inventario por almacén
- Registro de productos nuevos, actualizaciones y movimientos
- Reporte y control de productos dañados o devueltos
- Gestión de solicitudes entre almacenes
- Módulo para registrar y administrar **objetos perdidos**
- Control de usuarios por rol: vendedor, bodeguero, jefe de ventas, jefe de almacén
- Alertas de productos agotados
- Compatible con PC, móviles y tabletas (interfaz responsive)

---

## 🎯 Objetivo del Proyecto

**Desarrollar un sistema web que permita controlar eficientemente el inventario distribuido en tres almacenes, con trazabilidad, accesibilidad en tiempo real, control por roles y registro de movimientos detallados.**

---

## 👥 Actores del sistema

- **Vendedor:** Consulta el inventario y registra ventas. Puede reportar objetos perdidos.
- **Bodeguero:** Gestiona entradas, salidas, daños, devoluciones y objetos perdidos.
- **Jefe de almacén:** Supervisa su almacén, aprueba solicitudes y consulta historial.
- **Jefe de ventas:** Visualiza todos los inventarios, movimientos y estadísticas.

---

## 📌 Diagrama de Casos de Uso

![Diagrama de Casos de Uso](ruta/de/tu/diagrama.png)

*Este diagrama muestra las funcionalidades del sistema agrupadas por actor y relaciones entre casos de uso.*

---

## 📋 Requerimientos funcionales y no funcionales

### Funcionales

- RF01 – Registrar productos nuevos
- RF02 – Consultar inventario
- RF03 – Actualizar cantidades
- RF04 – Reportar productos dañados
- RF05 – Registrar devoluciones
- RF06 – Solicitar productos entre almacenes
- RF07 – Reportar objetos perdidos
- RF08 – Consultar objetos perdidos
- RF09 – Registrar entrega de objetos recuperados
- RF10 – Alertas de productos agotados

### No funcionales

- RNF01 – Interfaz responsive (funciona en PC, tablet y móvil)
- RNF02 – Control de acceso por usuario y contraseña
- RNF03 – Tiempo de respuesta menor a 3 segundos
- RNF04 – Registro de acciones por usuario (fecha/hora)
- RNF05 – Seguridad en la base de datos y encriptación de contraseñas
- RNF06 – Compatible con navegadores modernos (Chrome, Firefox, Edge)
- RNF07 – Soporte para 3 almacenes con inventario independiente
- RNF08 – Trazabilidad de movimientos
- RNF09 – Exportación de reportes (Excel/PDF)
- RNF10 – Alta disponibilidad durante horario laboral

---

## 🧩 Tecnologías utilizadas

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python (Flask / Django)
- **Base de datos:** MySQL / PostgreSQL
- **Control de versiones:** Git + GitHub
- **Diseño:** Figma (baja fidelidad) – PlantUML (diagramas)

---

