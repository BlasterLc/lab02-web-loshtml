# Lab 02 - Web "Los HTML" 🚀

Proyecto grupal para la asignatura de **Aplicaciones y Tecnologías de la Web**. Este repositorio contiene el portafolio del equipo "Los HTML" de la Universidad San Sebastián.

## 👥 Integrantes

- **Matías Pérez** (Líder de proyecto)
- **Matías Rodríguez**
- **Ignacio Castro**
- **Ignacio Veloso**
- **Jhonatan Godoy**

## 🛠️ Tecnologías utilizadas

- **HTML5 / CSS3**: Estructura y diseño del sitio.
- **Docker**: Contenerización mediante servidor Nginx.
- **WSL2 (Ubuntu)**: Entorno de desarrollo.
- **Git / GitHub**: Control de versiones y colaboración.

## 🐳 Cómo ejecutar con Docker

Para desplegar este proyecto localmente en el puerto **8080**, sigue estos pasos en tu terminal:

1. **Construir la imagen:**

   ```bash
   docker build -t portafolio-los-html .

   ```

2. **Levantar el contenedor:**

   ```bash
   docker run -d -p 8080:80 --name mi-sitio-web  portafolio-los-html

   ```

3. **Ver el sitio:**
   Abre tu navegador en http://localhost:8080
