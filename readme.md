# 🛸 Rick and Morty - Buscador de Personajes

Aplicación web interactiva que permite explorar y buscar personajes de la serie Rick and Morty utilizando su API oficial.

## 📋 Descripción

Este proyecto consume la [API de Rick and Morty](https://rickandmortyapi.com/) para mostrar información detallada de los personajes de la serie, incluyendo su estado, especie, género, origen y ubicación actual.

## 🚀 Características

- **Búsqueda de personajes**: Encuentra personajes por nombre
- **Paginación**: Navega entre las diferentes páginas de resultados
- **Modo oscuro/claro**: Alterna entre temas con persistencia en localStorage
- **Diseño responsive**: Adaptable a dispositivos móviles, tablets y desktop
- **Indicador de estado**: Colores visuales para el estado del personaje (Alive, Dead, Unknown)
- **Accesibilidad**: Soporte para navegación por teclado y lectores de pantalla

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (Variables CSS, Flexbox, Grid, Media Queries)
- JavaScript (ES6+, Fetch API, Async/Await)
- API REST de Rick and Morty

## 📁 Estructura del Proyecto

```
Proyecto_Integrador/
├── index.html    # Estructura HTML de la página
├── style.css     # Estilos y diseño responsive
├── index.js      # Lógica y consumo de API
└── readme.md     # Documentación
```

## 🔧 Instalación y Uso

### Usando Live Server (Recomendado) ✅
Este proyecto utiliza **Live Server** para el desarrollo:

1. Instala la extensión "Live Server" en VS Code
2. Abre el proyecto en VS Code
3. Haz clic derecho en `index.html`
4. Selecciona **"Open with Live Server"**
5. El proyecto se abrirá automáticamente en `http://127.0.0.1:5500`

> 💡 **Ventaja**: Los cambios en el código se reflejan automáticamente en el navegador sin necesidad de recargar.

### Opción Alternativa: Abrir directamente
1. Descarga o clona el repositorio
2. Abre el archivo `index.html` en tu navegador

## 📖 Guía de Uso

### Buscar un Personaje
1. Escribe el nombre del personaje en el campo de búsqueda
2. Haz clic en el botón **Buscar** o presiona Enter
3. Los resultados aparecerán en tarjetas debajo

### Navegar entre Páginas
- Usa los botones **Anterior** y **Siguiente** para moverte entre páginas
- El indicador muestra la página actual y el total de páginas

### Cambiar el Tema
- Haz clic en el switch ☀️/🌙 en la esquina superior derecha
- El tema seleccionado se guardará automáticamente

### Cargar Primeros Personajes
- Haz clic en **Cargar primeros** para volver a la primera página y limpiar la búsqueda

## 🎨 Información de las Tarjetas

Cada tarjeta de personaje muestra:

| Campo | Descripción |
|-------|-------------|
| **Imagen** | Foto del personaje |
| **Nombre** | Nombre completo |
| **Estado** | Alive (verde), Dead (rojo), Unknown (naranja) |
| **Especie** | Human, Alien, etc. |
| **Género** | Male, Female, Genderless, Unknown |
| **Origen** | Lugar de origen |
| **Ubicación** | Última ubicación conocida |

## 🌐 API Utilizada

Este proyecto utiliza la API pública de Rick and Morty:
- **URL Base**: `https://rickandmortyapi.com/api/character`
- **Documentación**: [rickandmortyapi.com/documentation](https://rickandmortyapi.com/documentation)

## 👨‍💻 Autor

**Juan Pablo Morales R.**

Proyecto Integrador - Módulo 1 JavaScript

## 📄 Licencia

Este proyecto es de uso educativo.