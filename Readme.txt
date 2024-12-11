# 🚗 Inventario de Productos - Dark Theme

Una aplicación web moderna para gestionar un inventario de productos con un elegante tema oscuro. Desarrollada como parte del Challenge AluraGeek G7 2024.

## ✨ Características

- **Diseño Dark Mode** con tema elegante y moderno
- **Gestión completa de productos:**
  - Visualización en grid responsivo
  - Agregación de nuevos productos
  - Edición de productos existentes
  - Eliminación con confirmación
- **Búsqueda en tiempo real** de productos
- **Vista previa de imágenes** en modal
- **Diseño completamente responsivo**
- **Interfaz intuitiva y animaciones suaves**

## 🛠️ Tecnologías Utilizadas

- HTML5
- CSS3 (con variables CSS y flexbox/grid)
- JavaScript (ES6+)
- JSON Server (API REST simulada)
- Font Awesome para iconos
- Google Fonts (Poppins)

## 📋 Prerequisitos

- Node.js (versión 12 o superior)
- npm (viene con Node.js)

## 🚀 Instalación

1. Clona el repositorio
```bash
git clone https://github.com/jotaid/AluraGeek.git
cd inventario-productos
```

2. Instala las dependencias
```bash
npm install
```

3. Inicia el servidor JSON
```bash
npm start
```

4. Abre `index.html` en tu navegador o usa un servidor local como Live Server

## 💻 Uso

### Agregar un Producto
1. Completa el formulario con:
   - Nombre del producto
   - Precio
   - Descripción
   - URL de la imagen
2. Haz clic en "Agregar"

### Editar un Producto
1. Haz clic en el icono de edición (lápiz) en cualquier producto
2. Modifica los campos necesarios
3. Guarda los cambios

### Eliminar un Producto
1. Haz clic en el icono de eliminación (papelera)
2. Confirma la eliminación en el diálogo

### Buscar Productos
- Utiliza la barra de búsqueda en la parte superior
- Los resultados se filtran en tiempo real

## 📱 Responsive Design

La aplicación está optimizada para diferentes tamaños de pantalla:
- Desktop (>1200px)
- Tablet (768px - 1200px)
- Mobile (<768px)

## 🎨 Características del Diseño

- **Tema Oscuro**: Diseño moderno con paleta de colores oscuros
- **Animaciones**: Transiciones suaves en tarjetas y modales
- **Accesibilidad**: Alto contraste y elementos interactivos claros
- **Consistencia**: Sistema de diseño unificado en toda la aplicación

## 🛡️ Estructura del Proyecto

```
/
├── index.html
├── styles/
│   ├── reset.css
│   └── style.css
├── js/
│   ├── controllers/
│   │   └── main.js
│   └── services/
│       └── product-services.js
└── db.json
```

## 👤 Autor

**Jose Idrobo Daza**
- Challenge AluraGeek G7 2024

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para detalles

## 🙌 Agradecimientos

- Alura Latam por el challenge
- A la comunidad de desarrolladores por el apoyo
