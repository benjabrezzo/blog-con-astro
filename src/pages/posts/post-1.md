---
title: 'Como iniciar un proyecto Astro'
pubDate: 20-02-2024
description: 'En este blog explicaré paso a paso como iniciar un nuevo proyecto en Astro'
author: 'Benjamin Brezzo'
image:
    url: 'https://docs.astro.build/assets/full-logo-light.png'
    alt: 'El logotipo completo de Astro.'
tags: ["astro", "bloguear", "aprender en público"]
---
# Cómo iniciar un proyecto en Astro
[Volver](/blog/)

Publicado el: 20-02-2024

En este blog voy a explicar paso a paso y detalladamente como iniciar un nuevo proyecto en Astro.

**Se necesita tener instalado Node.js**
``` bash
node -v
// Ejemplo de salida
v20.11.0
```
**Instalar extensión oficial de Astro en VS Code**

---

## Inicia el asistente de configuración de Astro
1. En la línea de comandos se ejecuta el siguiente comando: 
``` bash
npm create astro@latest 
```
2. Confirmamos con `y` para instalar `create-astro`.

3. Nos va a preguntar "`Where would you like to create your new project?`", acá escribimos el nombre de la carpeta para crear un nuevo directorio para el proyecto, por ejemplo `./proyecto-con-astro`.

**NOTA**:
**Un nuevo proyecto de Astro sólo puede crearse en una carpeta completamente vacía, así que hay que elegir el nombre de una carpeta que no exista.**

4. Aparecerá una lista de plantillas de inicio entre las que se puede elegir. Con las teclas de flechas podemos navegar hasta la opción "Empty" y luego presionamos Enter para continuar.

5. Cuando pregunte "`Would you like to install dependencies?`", escribimos `y`.

6. Cuando nos pregunte si planeamos escribir con TypeScript escribimos `n`.

7. Cuando nos pregunte si queremos inicializar un nuevo repositorio git le escribimos `y`.

8. Ya está, vamos a `VS Code`. Bueno, abrimos la carpeta del proyecto Astro en `VS Code`.

### Ejecutar Astro en modo de desarrollo
Para poder previsualizar los archivos del proyecto *como un sitio web* mientras trabajamos, necesitamos que Astro se ejecute en modo desarrollo (dev).

``` bash
npm run dev
```
Luego de ejecutar este comando deberiamos ver qeu Astro está siendo ejecutado en modo dev. 🚀

### Vista previa
Astro utiliza por defecto: http://localhost:4321