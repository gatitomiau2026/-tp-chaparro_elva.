# Explorador de Ubicaciones – Rick y Morty

**Autora:** Elva Beatriz Chaparro Noguera  
**Carrera:** Ingeniería en Informática  
**Asignatura:** Fundamentos de Desarrollo Web  
**Año:** 2026  
**Variante:** B – Ubicaciones

## Descripción

Aplicación web de una sola pantalla que permite explorar ubicaciones del universo de Rick y Morty. Consume la API REST pública para buscar ubicaciones por nombre y tipo, y presenta los resultados en tarjetas con su dimensión y cantidad de residentes.

## Tecnologías utilizadas

- HTML5 semántico.
- CSS3, variables CSS, Flexbox, Grid y diseño responsive.
- JavaScript ES6+, Fetch API, async/await y manejo de errores.
- localStorage para conservar y restaurar la última búsqueda.
- API REST: https://rickandmortyapi.com/documentation

## Funcionalidades

- Búsqueda por nombre y tipo de ubicación.
- Combinación de filtros en una misma petición.
- Tarjetas creadas dinámicamente con `createElement` y `textContent`.
- Mensajes de carga, búsqueda sin resultados y errores de conexión.
- Restauración automática de la última búsqueda al recargar la página.
- Diseño adaptable a celulares y computadoras.

## Estructura del proyecto

```text
tp-chaparro-elva/
├── index.html
├── README.md
├── css/
│   └── estilos.css
├── js/
│   └── app.js
└── img/
    └── captura.png
```

## Publicación en GitHub Pages

1. Crear un repositorio público llamado `tp-chaparro-elva`.
2. Subir los archivos y carpetas del proyecto. `index.html` debe quedar en la raíz.
3. Abrir **Settings → Pages**.
4. En **Build and deployment**, seleccionar **Deploy from a branch**.
5. Elegir la rama `main` y la carpeta `/ (root)`, y guardar.
6. Esperar a que GitHub genere el enlace y probar la página publicada.

**Página publicada:** _Agregar aquí el enlace de GitHub Pages._  
**Repositorio:** _Agregar aquí el enlace del repositorio._

## Captura de pantalla

Después de publicar y probar la aplicación, guardar una captura de la página como `img/captura.png` y agregarla aquí:

![Captura de pantalla del explorador](img/captura.png)
