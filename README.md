# Workflow Docker

**Autor:** Brian Aravena Quezada  
**DockerHub:** [brx2b/ev2_devops](https://hub.docker.com/r/brx2b/ev2_devops)  
**Proyecto:** Workflow de Evaluación 2 - Ingeniería de DevOps

---

## Descripción

Este workflow automatiza la integración y despliegue de la aplicación Node.js utilizando Docker, asegurando calidad y seguridad del código antes de subir la imagen a DockerHub.

---

## ¿Qué hace el workflow?

1. **Ejecución de ESLint**  
   Analiza el código para mantener consistencia y buenas prácticas de estilo.

2. **Ejecución de pruebas con Karma**  
   Permite verificar que los componentes de la aplicación funcionen correctamente.

3. **Escaneo con Snyk**  
   Detecta vulnerabilidades en las dependencias del proyecto para garantizar seguridad.

4. **Escaneo con SonarQube**  
   Evalúa la calidad del código, detecta bugs, code smells y mejora la mantenibilidad.

5. **Login y subida a DockerHub**  
   Construye la imagen de Docker y la sube a DockerHub para su despliegue.

---

## Nota

Este workflow está pensado para **automatizar pruebas y despliegues locales** y en CI/CD, promoviendo buenas prácticas en DevOps y asegurando un código más seguro y mantenible.
