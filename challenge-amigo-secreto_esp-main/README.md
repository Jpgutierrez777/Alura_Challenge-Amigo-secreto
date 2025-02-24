# Amigo Secreto

**Amigo Secreto** es una aplicación web sencilla que permite agregar nombres de amigos a una lista y sortear un nombre aleatorio de esa lista. Ideal para organizar juegos de "Amigo Secreto" o sorteos rápidos entre amigos.

## Características
- **Agregar amigos**: Ingresa nombres en una lista de participantes.
- **Sortear un amigo**: Selecciona un nombre aleatorio de la lista con un solo clic.
- **Interfaz simple**: Diseño limpio y fácil de usar.
- **Validaciones**: Evita nombres vacíos o duplicados.

## Tecnologías utilizadas
- **HTML5**: Estructura de la página.
- **CSS**: Estilos personalizados (en `style.css`, no incluido aquí).
- **JavaScript**: Lógica para agregar nombres y realizar el sorteo.
- **Google Fonts**: Fuentes `Inter` y `Merriweather` para una tipografía elegante.

## Requisitos
- Un navegador web moderno (Chrome, Firefox, Edge, etc.).
- Conexión a internet para cargar las fuentes de Google Fonts (opcional si descargas las fuentes localmente).

## Instalación y uso
1. **Clonar o descargar el proyecto**:
   - Descarga los archivos o clona el repositorio si está alojado en GitHub.
   
2. **Estructura de archivos**:
amigo-secreto/
├── assets/
│   ├── amigo-secreto.png       # Imagen del banner
│   └── play_circle_outline.png # Icono del botón de sorteo
├── style.css                   # Hoja de estilos 
└── index.html                  # Archivo principal

3. **Abrir la aplicación**:
- Abre `index.html` en tu navegador favorito.

4. **Cómo usar**:
- Escribe un nombre en el campo de texto y haz clic en "Añadir" para agregarlo a la lista.
- Repite hasta que tengas todos los nombres que deseas.
- Haz clic en "Sortear amigo" para ver un nombre aleatorio en pantalla.

## Capturas de pantalla
- Lista de amigos:  
![[Pasted image 20250223190739.png]]  
- Resultado del sorteo:  
![[Pasted image 20250223190813.png]]

## Notas
- El sorteo muestra un solo nombre aleatorio cada vez que haces clic en "Sortear amigo".
- Los nombres no se eliminan de la lista tras ser sorteados (puedes modificarlo si lo deseas).
- El archivo `style.css` no está incluido; personalízalo según tus preferencias.

## Contribuir
¡Las mejoras son bienvenidas! Si quieres contribuir:
1. Haz un *fork* del repositorio (si está en GitHub).
2. Crea una rama para tu cambio: `git checkout -b mi-mejora`.
3. Realiza tus cambios y haz un *commit*: `git commit -m "Descripción del cambio"`.
4. Envía un *pull request* con tus sugerencias.


## Licencia
Este proyecto es de código abierto

## Autor
Creado por Jean Paul Gutiérrez - Alura cursos.
