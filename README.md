
# Configuraciones básicas para un workflow

## Estructura básica de un workflow
Archivo de configuración:

1. Los workflows se definen en archivos YAML (generalmente en .github/workflows/). El nombre del archivo puede ser algo como ci.yml.
Eventos:

2. Un workflow se activa por eventos, como push, pull_request, o schedule. Por ejemplo, puedes hacer que se ejecute cada vez que se envía un nuevo commit a la rama main.
Jobs:

3. Un workflow puede contener uno o más "jobs". Cada job se ejecuta en un entorno (por ejemplo, un contenedor o máquina virtual).
Steps:

4. Cada job contiene "steps", que son las tareas individuales que deseas ejecutar, como ejecutar scripts, instalar dependencias, o ejecutar pruebas.