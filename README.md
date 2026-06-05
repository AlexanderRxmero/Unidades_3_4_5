# Chef Recetas — Sistema de Gestión Gastronómica

## 1. Nombre del Sistema y Descripción
**Chef Recetas** es una aplicación de escritorio desarrollada en **C# (Windows Forms)** bajo el patrón de arquitectura **Modelo-Vista-Controlador (MVC)**[cite: 1]. El sistema está diseñado para centralizar y optimizar la administración de recetas culinarias, permitiendo un control estructurado de categorías, ingredientes individuales, pasos detallados de preparación y almacenamiento de imágenes (fotografías) en formato binario directo en la base de datos[cite: 1]. 

### Características Principales
*   **Gestión Integral de Recetas:** Registro completo que incluye tiempos de preparación, porciones y niveles de dificultad (`fácil`, `media`, `difícil`)[cite: 1].
*   **Control de Almacenamiento BLOB:** Carga y lectura dinámica de archivos de imagen tanto para los ingredientes como para el resultado final de los platillos[cite: 1].
*   **Módulo de Autenticación Seguro:** Acceso restringido mediante inicio de sesión con encriptación de contraseñas en SHA-256 a nivel de servidor[cite: 1].
*   **Arquitectura MVC Separada por Capas:** Estructura limpia que independiza la interfaz de usuario (Views), la lógica de negocio (Controllers), el mapeo de objetos (Models) y el acceso a datos (DAL)[cite: 1].
*   **Persistencia de Datos Relacional:** Conectividad directa y eficiente con un servidor MySQL mediante el conector nativo `MySql.Data`[cite: 1].

---

## 2. Integrantes del Equipo
El desarrollo e implementación de este proyecto fue realizado por los siguientes integrantes:

*   **Chavira Ruiz** Jazmín
*   **Durán Tolentino** Amanda Nohemí
*   **García Espinoza** Andrea
*   **Romero Ramírez** Alexander
*   **Villalobos Villarreal** Naiby Adriana
