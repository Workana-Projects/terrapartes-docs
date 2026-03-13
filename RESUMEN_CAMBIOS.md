# Resumen de Cambios - Tema Terrapartes

## Cambios Realizados

### 1. Colores Globales Configurables

Se agregaron configuraciones de colores en **Configuracion del Tema > Terrapartes**:

- Color Principal (Naranja) - para botones y acentos
- Color Principal Oscuro - para hover de botones
- Color Oscuro (Azul Marino) - para topbar, footer, titulos
- Color de Texto - texto general
- Color de Fondo - fondo principal
- Color de Fondo Claro - secciones alternas

**Archivo modificado:** `config/settings_schema.json`

---

### 2. Seccion de Proveedores (antes Marcas de Carros)

La seccion "TP Marcas" ahora se llama "TP Marcas / Proveedores" y permite:

- **Subir logos de imagen** (PNG recomendado)
- Elegir entre mostrar logos o texto
- Configurar colores de fondo y titulos

**Archivo modificado:** `sections/tp-brand-logos.liquid`

---

### 3. Barra Superior (Topbar) Configurable

Ahora puede cambiar:

- Color de fondo
- Color de texto
- Texto del lado izquierdo
- Texto del telefono

**Archivo modificado:** `sections/tp-topbar.liquid`

---

### 4. Pie de Pagina (Footer) Configurable

Ahora puede cambiar:

- Color de fondo
- Color de texto
- Color de enlaces
- Color de linea divisora
- Logo
- Texto de copyright
- Enlaces de navegacion (agregar/quitar/reordenar)

**Archivo modificado:** `sections/tp-footer.liquid`

---

### 5. Categorias Configurables

Ahora puede cambiar:

- Titulo y palabra destacada
- Subtitulo (nuevo)
- Colores de fondo, titulo y palabra destacada
- Imagen de cada categoria
- Nombre de cada categoria

**Archivo modificado:** `sections/tp-categories.liquid`

---

### 6. Hero Configurable

Se agregaron opciones de colores:

- Color del overlay
- Color del texto
- Color del texto destacado
- Opacidad del overlay

**Archivo modificado:** `sections/tp-hero.liquid`

---

### 7. Header Configurable

Ahora puede cambiar:

- Logo (con altura ajustable)
- Color de fondo
- Color de enlaces
- Enlaces del menu (agregar/quitar/reordenar)

**Archivo modificado:** `sections/tp-header.liquid`

---

## Documentacion Creada

1. **GUIA_EDICION_SITIO.md** - Guia completa con instrucciones detalladas
2. **GUIA_RAPIDA.md** - Referencia rapida para cambios comunes

---

## Como Usar

1. Ir a Shopify Admin > Tienda Online > Temas > Personalizar
2. Seleccionar la seccion que desea editar
3. Usar los controles para cambiar colores, textos e imagenes
4. Guardar los cambios

Para cambiar colores globales:
- Hacer clic en el icono de engranaje (abajo izquierda)
- Buscar "Terrapartes"
- Editar los colores deseados
- Guardar

---

## Archivos Modificados

| Archivo | Cambio |
|---------|--------|
| `config/settings_schema.json` | Configuracion de colores globales |
| `config/settings_data.json` | Valores por defecto |
| `layout/theme.liquid` | Variables CSS dinamicas |
| `assets/terrapartes.css` | Estilos para logos |
| `sections/tp-brand-logos.liquid` | Soporte para logos de imagen |
| `sections/tp-topbar.liquid` | Colores configurables |
| `sections/tp-footer.liquid` | Colores configurables |
| `sections/tp-categories.liquid` | Colores y subtitulo |
| `sections/tp-hero.liquid` | Colores del hero |
| `sections/tp-header.liquid` | Logo, colores y menu editable |
| `templates/index.json` | Template actualizado |

---

*Fecha: Marzo 2026*
