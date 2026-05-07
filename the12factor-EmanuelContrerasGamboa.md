## Justificación de los 4 factores elegidos

Elegí estos cuatro factores porque son los que mejor se adaptan a la forma en que estamos desarrollando nuestros proyectos con Git, Docker y trabajo en equipo. Cada uno ayuda a resolver problemas comunes en el desarrollo de software moderno y mejora la organización, la portabilidad y la confiabilidad de las aplicaciones.

---

### 1. Codebase (Base de código)

Lo elegí porque en nuestros proyectos es fundamental trabajar con una única base de código gestionada con Git. Esto nos permite tener control de versiones, trabajar en equipo sin conflictos y mantener un historial claro de los cambios del proyecto.

---

### 2. Config (Configuración)

Lo elegí porque es importante separar la configuración del código. En nuestro contexto usamos variables de entorno para manejar credenciales, rutas y conexiones a servicios, lo que nos permite ejecutar la aplicación en distintos entornos sin modificar el código.

---

### 3. Build, Release, Run

Lo elegí porque nos ayuda a entender y organizar el proceso de despliegue. En nuestros proyectos, especialmente con Docker, es clave separar la construcción de la aplicación, su configuración y su ejecución para evitar errores y hacer despliegues más seguros.

---

### 4. Dev/Prod Parity (Paridad entre desarrollo y producción)

Lo elegí porque es importante que el entorno de desarrollo sea lo más parecido posible al de producción. Esto reduce errores como “en mi máquina funciona” y lo logramos usando herramientas como Docker para simular entornos reales de ejecución.