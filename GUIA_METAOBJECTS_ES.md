# Guía: Gestión de Categorías con Metaobjects

Esta guía explica cómo agregar, editar y eliminar **categorías** y **subcategorías** del sitio Terrapartes usando Metaobjects de Shopify.

> **Ventaja**: Usted puede gestionar todas las categorías y subcategorías directamente desde Shopify Admin, sin necesidad de tocar código ni contratar un desarrollador.

---

## Índice

1. [Configuración Inicial (una sola vez)](#1-configuración-inicial-una-sola-vez)
2. [Crear Subcategorías](#2-crear-subcategorías)
3. [Crear Categorías](#3-crear-categorías)
4. [Activar en la Página Principal](#4-activar-en-la-página-principal)
5. [Editar Categorías y Subcategorías](#5-editar-categorías-y-subcategorías)
6. [Agregar Nuevas Categorías](#6-agregar-nuevas-categorías)
7. [Eliminar Categorías](#7-eliminar-categorías)
8. [Datos Iniciales a Ingresar](#8-datos-iniciales-a-ingresar)

---

## 1. Configuración Inicial (una sola vez)

### Paso 1.1: Crear la definición de `tp_subcategoria`

1. Vaya a **Settings** → **Custom data** → **Metaobjects**
2. Haga clic en **Add definition**
3. Configure así:

| Campo | Valor |
|-------|-------|
| **Name** | `tp_subcategoria` |
| **Type** (automático) | `tp_subcategoria` |

4. Agregue estos **campos** (haga clic en "Add field" para cada uno):

| Nombre del campo | Tipo de campo | Requerido |
|------------------|---------------|-----------|
| `nombre` | **Single line text** | ✅ Sí |
| `imagen` | **File** (Media → File) | No |
| `descripcion` | **Single line text** | No |

5. En **Access** → **Storefronts**, active **Online Store**
6. Haga clic en **Save**

### Paso 1.2: Crear la definición de `tp_categoria`

1. En **Settings** → **Custom data** → **Metaobjects**, haga clic en **Add definition**
2. Configure así:

| Campo | Valor |
|-------|-------|
| **Name** | `tp_categoria` |
| **Type** (automático) | `tp_categoria` |

3. Agregue estos **campos**:

| Nombre del campo | Tipo de campo | Requerido | Notas |
|------------------|---------------|-----------|-------|
| `nombre` | **Single line text** | ✅ Sí | Nombre visible de la categoría |
| `imagen` | **File** (Media → File) | No | Imagen de fondo del banner |
| `icono` | **File** (Media → File) | No | Ícono SVG (opcional) |
| `descripcion` | **Single line text** | No | Texto breve bajo el título |
| `subcategorias` | **Metaobject reference** → `tp_subcategoria` | No | ⚠️ Marcar como **List** |

> **IMPORTANTE**: El campo `subcategorias` debe ser tipo **List of metaobject references** apuntando a `tp_subcategoria`. Al agregar el campo, seleccione "Metaobject reference", luego seleccione `tp_subcategoria`, y marque la opción **List**.

4. En **Access** → **Storefronts**, active **Online Store**
5. En **Access** → **Online Store**, active **Web page** (esto genera URLs para cada categoría)
6. Haga clic en **Save**

---

## 2. Crear Subcategorías

> **Primero cree las subcategorías**, luego las categorías (porque las categorías hacen referencia a subcategorías).

1. Vaya a **Content** → **Metaobjects** → **tp_subcategoria**
2. Haga clic en **Add entry**
3. Complete los campos:

| Campo | Ejemplo |
|-------|---------|
| **nombre** | `Pastillas de freno` |
| **imagen** | (Suba una foto del producto) |
| **descripcion** | `Pastillas cerámicas y semi-metálicas` |

4. Haga clic en **Save**
5. **Repita** para cada subcategoría

### Ejemplo: Subcategorías para "Sistema de Frenos"

Cree estas 6 entradas:
- Pastillas de freno
- Discos de freno
- Booster
- Bombas de freno
- Kit de caliper y tambor
- Zapatas

---

## 3. Crear Categorías

1. Vaya a **Content** → **Metaobjects** → **tp_categoria**
2. Haga clic en **Add entry**
3. Complete los campos:

| Campo | Ejemplo |
|-------|---------|
| **nombre** | `Sistema de Frenos` |
| **imagen** | (Suba una imagen de fondo para el banner) |
| **icono** | (Opcional: suba un SVG) |
| **descripcion** | `Pastillas, discos, tambores y componentes de freno` |
| **subcategorias** | Seleccione: Pastillas de freno, Discos de freno, Booster, Bombas de freno, Kit de caliper y tambor, Zapatas |

4. En el campo **Handle** (URL), escriba un nombre corto: `sistema-de-frenos`
5. Haga clic en **Save**

> **Nota sobre imágenes**: Puede subir archivos JPG, PNG, WebP o SVG. Tamaño recomendado:
> - **Imagen de categoría (banner)**: 1920 x 600 px
> - **Imagen de subcategoría**: 400 x 400 px
> - **Ícono**: 64 x 64 px (SVG preferido)

---

## 4. Activar en la Página Principal

### Reemplazar la sección de categorías actual:

1. Vaya a **Online Store** → **Themes** → **Customize**
2. En la página **Home page**:
   - Busque la sección **TP Categorias** actual
   - Haga clic en el ícono de ojo (👁️) para **ocultarla** (o elimínela)
3. Haga clic en **Add section**
4. Busque y seleccione **TP Categorias (Meta)**
5. Configure el título y colores si lo desea
6. Haga clic en **Save**

> Las categorías aparecerán automáticamente. No necesita seleccionarlas manualmente — todas las `tp_categoria` creadas se mostrarán.

---

## 5. Editar Categorías y Subcategorías

### Editar una categoría:
1. **Content** → **Metaobjects** → **tp_categoria**
2. Haga clic en la categoría que desea editar
3. Modifique nombre, imagen, descripción o subcategorías
4. **Save**

### Editar una subcategoría:
1. **Content** → **Metaobjects** → **tp_subcategoria**
2. Haga clic en la subcategoría
3. Modifique nombre, imagen o descripción
4. **Save**

### Cambiar el orden de subcategorías dentro de una categoría:
1. Edite la categoría (`tp_categoria`)
2. En el campo **subcategorias**, arrastre las entradas para reordenar
3. **Save**

---

## 6. Agregar Nuevas Categorías

Para agregar una nueva categoría (ejemplo: "Eléctrico"):

### Paso 1: Cree las subcategorías primero
1. **Content** → **Metaobjects** → **tp_subcategoria** → **Add entry**
2. Cree: Bobinas, Bujías de precalentamiento, Bujías, Sensores, Alternadores, Reguladores/Relay/Fusibles
3. Suba imagen para cada una

### Paso 2: Cree la categoría
1. **Content** → **Metaobjects** → **tp_categoria** → **Add entry**
2. Nombre: `Eléctrico`
3. Suba imagen de banner
4. En subcategorias: seleccione todas las que creó en el paso 1
5. **Save**

> ✅ La nueva categoría aparecerá automáticamente en la página principal y tendrá su propia página de detalle.

---

## 7. Eliminar Categorías

### Eliminar una categoría:
1. **Content** → **Metaobjects** → **tp_categoria**
2. Seleccione la categoría → **Delete**

### Eliminar una subcategoría:
1. Primero **quítela** de cualquier categoría que la contenga
2. Luego vaya a **Content** → **Metaobjects** → **tp_subcategoria**
3. Seleccione la subcategoría → **Delete**

---

## 8. Datos Iniciales a Ingresar

### Categorías principales (6):

| # | Nombre | Handle | Subcategorías |
|---|--------|--------|---------------|
| 1 | **Suspensión y Dirección** | `suspension-y-direccion` | Compensadores, Rótulas, Hules y Bujes (Bushing), Ejes/puntas de eje y botas, Tijeretas, Terminales de dirección, Cremalleras, Espirales, Galletas de compensador, Roles y Bocinas |
| 2 | **Sistema de Frenos** | `sistema-de-frenos` | Pastillas de freno, Discos de freno, Booster, Bombas de freno, Kit de caliper y tambor, Zapatas |
| 3 | **Partes de Motor** | `partes-de-motor` | Fajas, Empaques, Tapones de radiador, Bombas de aceite, Soportes de motor, Pistones, Kit de clutch, Plato de presión, Rol de empuje e hidraclutch, Anillos, Bombas de gasolina, Bearing biela y bancada |
| 4 | **Eléctrico** | `electrico` | Bobinas, Bujías de precalentamiento, Bujías, Sensores, Alternadores, Reguladores/Relay/Fusibles |
| 5 | **Enfriamiento** | `enfriamiento` | Radiadores, Bombas de agua, Termostatos, Mangueras, Ventiladores, Condensadores |
| 6 | **Filtración** | `filtracion` | Filtros de aceite, Filtros de aire, Filtros de combustible, Filtros aire acondicionado |

### Total de entradas a crear:
- **6** entradas de `tp_categoria`
- **~48** entradas de `tp_subcategoria`

### Orden recomendado de trabajo:
1. Crear todas las subcategorías de una categoría
2. Crear la categoría y vincular las subcategorías
3. Repetir para la siguiente categoría

---

## Resumen Visual del Flujo

```
Shopify Admin
├── Settings > Custom data > Metaobjects
│   ├── tp_subcategoria (definición)    ← Crear UNA VEZ
│   └── tp_categoria (definición)       ← Crear UNA VEZ
│
├── Content > Metaobjects
│   ├── tp_subcategoria                 ← Agregar/editar subcategorías AQUÍ
│   │   ├── Pastillas de freno
│   │   ├── Discos de freno
│   │   └── ...
│   └── tp_categoria                    ← Agregar/editar categorías AQUÍ
│       ├── Sistema de Frenos → [Pastillas, Discos, ...]
│       ├── Suspensión y Dirección → [Compensadores, Rótulas, ...]
│       └── ...
│
└── Online Store > Themes > Customize
    └── Home page
        └── TP Categorias (Meta)        ← Se muestra automáticamente
```

---

## Preguntas Frecuentes

**P: ¿Puedo agregar más categorías sin un desarrollador?**
R: Sí. Solo cree las subcategorías, luego la categoría, y aparecerá automáticamente.

**P: ¿Puedo cambiar las imágenes?**
R: Sí. Edite la categoría o subcategoría en Content > Metaobjects y suba una nueva imagen.

**P: ¿Cuántas categorías puedo tener?**
R: No hay límite práctico. Puede tener tantas como necesite.

**P: ¿Qué pasa si creo una subcategoría pero no la asigno a ninguna categoría?**
R: No aparecerá en el sitio. Debe asignarla al campo "subcategorias" de al menos una categoría.

**P: ¿El botón de WhatsApp se configura automáticamente?**
R: Sí. Cada subcategoría genera un mensaje de WhatsApp automático con el nombre de la subcategoría y la categoría.
