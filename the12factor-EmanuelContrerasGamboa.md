# The Twelve-Factor App – Factores más relevantes

Para los proyectos que estamos desarrollando (usando Git, Docker y herramientas de desarrollo colaborativo), los siguientes 4 factores del modelo Twelve-Factor App son los más importantes:

---

## 1. Codebase (Base de código)

Cada aplicación debe tener una única base de código gestionada con un sistema de control de versiones como Git.

**Importancia:**
- Permite llevar historial de cambios
- Facilita el trabajo en equipo
- Evita duplicación o versiones inconsistentes del proyecto

En nuestros proyectos, Git es esencial para mantener el control y la organización del código.

---

## 2. Config (Configuración)

Toda la configuración debe estar separada del código fuente y gestionarse mediante variables de entorno.

Incluye:
- credenciales
- URLs de bases de datos
- rutas o configuraciones específicas del entorno

**Importancia:**
- Permite ejecutar la misma aplicación en distintos entornos (dev, test, prod)
- Evita exponer información sensible en el código

---

## 3. Build, Release, Run

El ciclo de despliegue debe dividirse en tres etapas claras:

- **Build:** compilar el código y resolver dependencias
- **Release:** combinar el build con la configuración del entorno
- **Run:** ejecutar la aplicación en producción

**Importancia:**
- Permite despliegues ordenados y reproducibles
- Facilita el uso de herramientas como Docker y CI/CD
- Reduce errores en producción

---

## 4. Dev/Prod Parity (Paridad entre desarrollo y producción)

Los entornos de desarrollo y producción deben ser lo más similares posible.

**Importancia:**
- Evita el problema de “en mi máquina funciona”
- Reduce errores por diferencias de versiones o configuración
- Herramientas como Docker ayudan a replicar entornos reales

---

## Conclusión

Estos cuatro factores son clave porque permiten construir aplicaciones:

- organizadas (Codebase)
- configurables (Config)
- desplegables de forma segura (Build/Release/Run)
- consistentes entre entornos (Dev/Prod Parity)