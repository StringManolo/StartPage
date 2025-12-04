# StartPage

**StartPage** es una página de inicio minimalista y personalizable que permite acceder rápidamente a tus enlaces favoritos mediante autocompletado. Todos los datos se guardan localmente en tu navegador y puedes exportarlos/importarlos.

## Características

- **Búsqueda con autocompletado**: Encuentra enlaces rápidamente o escribe URLs para navegar directamente.
- **Organización por categorías**: Agrupa tus enlaces en apartados personalizados.
- **Personalización completa**: Cambia colores, iconos y disposición de todos los elementos.
- **Drag & Drop**: Reordena categorías y enlaces arrastrando y soltando.
- **Modo edición**: Activa/desactiva el modo edición para personalizar tu página.
- **Guardado automático**: Todo se guarda en el almacenamiento local de tu navegador.
- **Importar/Exportar**: Lleva tu configuración a cualquier dispositivo.

## Configuración como página de inicio

### Chrome Android

1. Abre Chrome y toca los tres puntos (⋮) en la esquina superior derecha
2. Ve a "Configuración"
3. Busca "Página de inicio"
4. Actívala y selecciona "Introducir una dirección personalizada"
5. Introduce: `https://stringmanolo.github.io/StartPage`

### Cromite (recomendado para Android)

Cromite es un fork de Bromite con más características y actualizaciones de seguridad frecuentes. Permite configurar tanto la página de inicio como la nueva pestaña.

1. Instala Cromite desde [https://github.com/uazo/cromite](https://github.com/uazo/cromite)
2. Abre Cromite y ve a Configuración → Página de inicio
3. Introduce: `https://stringmanolo.github.io/StartPage`
4. (Opcional) En Configuración → Nueva pestaña, selecciona "Página de inicio"

### Chrome/Edge/Brave en escritorio

1. Ve a Configuración → Al inicio → Abrir una página específica
2. Añade: `https://stringmanolo.github.io/StartPage`

### Firefox

1. Ve a Configuración → Inicio → URLs personalizadas
2. Introduce: `https://stringmanolo.github.io/StartPage`

## Uso

### Búsqueda

- Escribe en la barra de búsqueda para ver sugerencias de tus enlaces
- Escribe una URL completa (con https://) y presiona Enter para ir directamente
- Escribe un término sin URL para buscar en Google

### Modo edición

Activa/desactiva el modo edición con el botón "Editar" en la esquina superior derecha.

**En modo edición:**
- Arrastra categorías desde el icono ☰ para reordenarlas
- Arrastra enlaces para reordenarlos o moverlos entre categorías
- Haz doble clic en nombres de categorías o enlaces para editarlos
- Usa los botones que aparecen (+, ✏️, 🗑️) para añadir, editar o eliminar
- Triple clic en cualquier elemento para cambiar su color (doble clic para restablecer)

### Añadir nueva categoría

1. Haz clic en el botón "Nuevo" en la esquina superior derecha
2. Introduce el nombre y guarda

### Añadir nuevo enlace

1. En modo edición, haz clic en el botón "+" dentro de una categoría
2. Introduce nombre, URL y selecciona un icono del grid

### Cambiar colores

1. Activa el modo edición
2. Haz triple clic en cualquier elemento (fondo, categoría, enlace, etc.) para abrir el selector de color
3. Elige un color y aplica
4. Haz doble clic en un elemento con color personalizado para restablecerlo

### Exportar/Importar configuración

- **Exportar**: Haz clic en el icono de exportar (📤) al lado del botón "Editar". Se descargará un archivo JSON con toda tu configuración.
- **Importar**: Haz clic en el icono de importar (📥) y selecciona un archivo JSON previamente exportado.

## Preguntas frecuentes

### ¿Dónde se guardan mis datos?

Todos los datos se guardan en el almacenamiento local de tu navegador (localStorage). No se envían a ningún servidor.

### ¿Puedo usar StartPage en múltiples dispositivos?

Sí, exporta tu configuración desde un dispositivo e impórtala en el otro.

### ¿Qué pasa si borro el cache del navegador?

Perderás tus datos. Exporta regularmente tu configuración como backup.

### ¿Funciona sin conexión?

Sí, una vez cargada la página, funciona completamente offline.

## Contribuir

Si encuentras un error o tienes una sugerencia, abre un issue en el repositorio de GitHub. Las pull requests son bienvenidas.

## Enlace

[https://stringmanolo.github.io/StartPage](https://stringmanolo.github.io/StartPage)
