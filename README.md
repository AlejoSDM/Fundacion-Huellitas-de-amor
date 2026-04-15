# 🐾 Huellitas de Amor — Fundación Animalista

### FIGMA: https://www.figma.com/design/nwRKIbnka1hqD54uCT7AyW/FUNDACION-HUELLITAS-DE-AMOR?node-id=12-71&t=anBXNHkh8dpemZOt-1
### Maqueta Web Estática (HTML + CSS)

Proyecto web desarrollado con HTML y CSS puro que representa la identidad digital de la fundación **Huellitas de Amor**, enfocada en el rescate, cuidado y adopción de animales en situación de vulnerabilidad.

La página permite a los usuarios conocer la labor de la fundación, ver cómo ayudar y navegar entre distintas secciones como adopción, voluntariado, donaciones y contacto.

---

## 🔍 Problemática que aborda

Muchas fundaciones animalistas realizan un trabajo importante en rescate y adopción de animales, pero no cuentan con una presencia digital clara que les permita llegar a más personas.

Esto dificulta que la comunidad conozca su labor, reduzca las oportunidades de adopción y limite la participación en actividades como donaciones o voluntariado.

Este proyecto busca solucionar esto mediante una maqueta web estática, visualmente atractiva y organizada.

---

## 🎯 Objetivo del proyecto

Desarrollar una página web que:

* Refleje la identidad de la fundación 🐶
* Permita conocer su misión, visión y labor
* Facilite la navegación entre secciones clave
* Simule interactividad usando únicamente CSS
* Sea responsive (adaptable a distintos dispositivos)

---

## ✨ Funcionalidades implementadas

✔ Navbar de navegación entre páginas
✔ Carrusel automático de imágenes con `@keyframes` (sin JavaScript)
✔ Sección de presentación con llamado a la acción
✔ Separadores visuales tipo “olas” usando SVG
✔ Sección “Nuestra labor” con tarjetas informativas
✔ Páginas conectadas mediante enlaces internos
✔ Formularios simulados (Contacto, Donaciones, Voluntariado)
✔ Footer con información usando Flexbox

---

## 📄 Páginas del sitio

El proyecto cuenta con múltiples páginas conectadas entre sí:

* **Inicio (index.html)** → Página principal con presentación y navegación
* **Adopción (adopta.html)** → Informacion de los animales disponibles para adoptar
* **Voluntariado (voluntario.html)** → Formulario para participar
* **Donaciones (donaciones.html)** → Información para apoyar económicamente
* **Contacto (contactanos.html)** → Formulario de contacto general
* **Perfiles (perfil de animales)** → Carpeta que tiene el perfil de todos los animales de adopcion

---

## 🧱 Estructura del proyecto

```
📁 huellitas-de-amor
│
├── 📁 assets
│   ├── 📁 img
│   │   ├── carrusel1.jpg
│   │   ├── rescate1.jpeg
│   │   ├── ...
│   │
│   ├── 📁 css
│   │   ├── styles.css
│   │   ├── formularios.css
│   │   ├── tarjetas.css
│   │   ├── donaciones.css
│   │   └── adopta.css
│
├── 📁 pages
│   ├── adopta.html
│   ├── voluntario.html
│   ├── donaciones.html
│   ├── contactanos.html
│   │
│   ├── 📁 animales
│   │   ├── agatha.html
│   │   ├── cr7.html
│   │   ├── manchas.html
│   │   ├── messi.html
│   │   ├── negro.html
│   │   ├── titan.html
│   │   ├── totto.html
│   │   └── zoe.html
│
├── index.html
└── README.md

```

---

## 🎨 Diseño y características

El diseño utiliza una paleta de colores amigable:

* 💚 Verde (#4CAF50) → naturaleza y esperanza
* 💗 Rosado (#FF6F91) → amor y empatía
* 🤍 Blanco / gris claro → limpieza visual

Características principales:

* Uso de **Flexbox** para distribución
* Animaciones CSS para carruseles
* Efectos hover para interacción
* Separadores con **SVG** tipo ola
* Diseño limpio y organizado

---

## 📱 Responsive Design

El sitio se adapta a diferentes dispositivos:

* 📱 Móviles → elementos en columna
* 💻 Tablets → distribución intermedia
* 🖥️ Escritorio → layout completo

---

## 🧪 Tecnologías utilizadas

| Herramienta   | Uso                       |
| ------------- | ------------------------- |
| HTML5         | Estructura del sitio      |
| CSS3          | Estilos y animaciones     |
| Flexbox       | Organización de elementos |
| Grid          | Galerías                  |
| SVG           | Separadores visuales      |
| Media Queries | Responsive                |

---

## 🚀 Cómo ejecutar el proyecto

1. Clonar el repositorio:

```bash
git https://github.com/AlejoSDM/Fundacion-Huellitas-de-amor.git
cd Fundacion-Huellitas-de-amor
```

2. Abrir el archivo:

```bash
index.html
```

👉 Abrir directamente en el navegador.

---

## 🧠 Autor

Proyecto desarrollado por **Alejandro Solano Durán** como parte de su formación en desarrollo web.

---

## 📫 Contacto

📧 [alejosdml@gmail.com](mailto:alejosdml@gmail.com)

---

## 📌 Licencia

Proyecto con fines educativos y de demostración no se autoriza para usos publicos.