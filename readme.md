# 🚀 Jrdev - Portafolio de Desarrollador Junior 

> "Construyendo el futuro digital: Mi camino como desarrollador junior."

Este repositorio contiene la landing page principal de mi portafolio, `Jrdev`. Sirve como una presentación concisa y visualmente atractiva de mis habilidades, experiencia y proyectos clave mientras avanzo en mi carrera como desarrollador.

[Captura de pantalla de la aplicación de Portfolio](https://jrdev-lscf.vercel.app/assets/images/jrdev-lscf.vercel.app.png)

---

## ✨ Características Principales

* **Diseño Multi-Tema:** Plantilla base con soporte para múltiples temas.
* **Página de Aterrizaje:** Ideal para ser la primera impresión profesional.
* **Secciones Modulares (Pestañas):** Contenido organizado por pestañas para una navegación limpia (Habilidades, Proyectos, Contacto).
* **Diseño Limpio:** Estilizado con Tailwind CSS.

## 🔗 Ver en Vivo

Puedes explorar la demo en producción aquí:

* **URL:** [https://jrdev-lscf.vercel.app/](https://jrdev-lscf.vercel.app/)

---

## 🛠️ Tecnologías Utilizadas

El proyecto fue construido con un enfoque en la simplicidad y el uso de herramientas modernas de frontend:

* **Lenguajes:** HTML, CSS, JavaScript
* **Estilizado:** [Tailwind CSS](https://tailwindcss.com/) (Clases prefijadas con `tw-`)
* **Despliegue:** [Vercel](https://vercel.com/)

---

## 🏗️ Guía de Uso (Personalización)

Esta plantilla se basa en el repositorio original **[awesome-landing-pages de PaulleDemon](https://github.com/PaulleDemon/awesome-landing-pages)**.

### Pestañas (Tabs)

Para añadir nuevas pestañas, sigue la estructura:

1.  **Añadir el Botón de Navegación:**
    ```html
    <button class="tab-btn" onclick="openTab(event, 'newtab')">New tab</button>
    ```

2.  **Añadir la Sección de Contenido:** Usa el atributo `data-tab-name` para vincular el contenido con el botón.
    ```html
    <section class="tab-content tw-w-full tw-h-full max-lg:tw-p-4 tw-flex tw-flex-col tw-overflow-hidden tw-relative"
                data-tab-name="newtab" 
                >
        </section>
    ```

### Uso de Tailwind CSS

Todas las clases de Tailwind están prefijadas con `tw-` para evitar conflictos de estilo.

#### Desarrollo

Para iniciar el modo de desarrollo de Tailwind (requiere Node.js y npm/yarn):
```bash
npm run start:tailwind
