# Guia de Edicion del Sitio Web - Terrapartes

Esta guia le explica como editar todos los elementos de su sitio web desde el panel de administracion de Shopify, **sin necesidad de tocar codigo**.

---

## Tabla de Contenidos

1. [Acceder al Editor del Tema](#1-acceder-al-editor-del-tema)
2. [Cambiar Colores Globales](#2-cambiar-colores-globales)
3. [Editar la Barra Superior (Topbar)](#3-editar-la-barra-superior-topbar)
4. [Editar el Encabezado (Header)](#4-editar-el-encabezado-header)
5. [Editar las Categorias de Productos](#5-editar-las-categorias-de-productos)
6. [Editar Pagina de Detalle de Categoria](#6-editar-pagina-de-detalle-de-categoria)
7. [Subir Logos de Proveedores](#7-subir-logos-de-proveedores)
8. [Editar Pagina de Garantias](#8-editar-pagina-de-garantias)
9. [Editar Pagina Nosotros](#9-editar-pagina-nosotros)
10. [Editar el Pie de Pagina (Footer)](#10-editar-el-pie-de-pagina-footer)
11. [Configurar WhatsApp y Contacto](#11-configurar-whatsapp-y-contacto)
12. [Subir Imagenes](#12-subir-imagenes)
13. [Consejos Importantes](#13-consejos-importantes)

---

## 1. Acceder al Editor del Tema

1. Inicie sesion en su panel de administracion de Shopify
2. En el menu lateral izquierdo, haga clic en **Tienda Online** (o "Online Store" en ingles)
3. Haga clic en **Temas** (o "Themes")
4. En su tema activo (Terrapartes), haga clic en el boton **Personalizar** (o "Customize")

Esto abrira el **Editor Visual del Tema** donde puede ver los cambios en tiempo real.

---

## 2. Cambiar Colores Globales

Los colores principales del sitio se pueden cambiar desde la configuracion del tema.

### Pasos:

1. En el Editor del Tema, haga clic en **Configuracion del tema** (icono de engranaje en la esquina inferior izquierda)
2. Busque la seccion **"Terrapartes"**
3. Vera las siguientes opciones de color:

| Opcion | Que controla |
|--------|--------------|
| **Color Principal (Naranja)** | Botones, enlaces, acentos |
| **Color Principal Oscuro** | Hover de botones |
| **Color Oscuro (Azul Marino)** | Topbar, footer, titulos |
| **Color de Texto** | Texto general del sitio |
| **Color de Fondo** | Fondo principal |
| **Color de Fondo Claro** | Fondo de secciones alternas |

4. Haga clic en cada color para abrir el selector de colores
5. Elija el color deseado o ingrese el codigo hexadecimal (ej: `#E8491D`)
6. Haga clic en **Guardar** en la esquina superior derecha

---

## 3. Editar la Barra Superior (Topbar)

La barra azul oscura en la parte superior del sitio.

### Pasos:

1. En el Editor del Tema, haga clic en la barra superior o busque **"TP Barra Superior"** en la lista de secciones
2. Podra editar:

| Opcion | Descripcion |
|--------|-------------|
| **Texto izquierdo** | El texto junto a los iconos sociales (ej: "Siguenos") |
| **Texto del telefono** | El texto del enlace de telefono (ej: "Llamanos Ahora") |
| **Color de fondo** | Color de fondo de la barra |
| **Color de texto** | Color del texto y enlaces |

3. Guarde los cambios

---

## 4. Editar el Encabezado (Header)

El encabezado con el logo y menu de navegacion.

### Cambiar el Logo:

1. Haga clic en la seccion del encabezado o busque **"TP Header"**
2. En **Logo del sitio**, haga clic en **Seleccionar imagen**
3. Suba su nuevo logo o elija uno de la biblioteca
4. Ajuste la **Altura del logo** con el control deslizante si es necesario

### Editar los Enlaces del Menu:

Los enlaces del menu se editan como bloques:

1. Haga clic en cada enlace para editarlo
2. Puede cambiar:
   - **Texto del enlace** (ej: "REPUESTOS", "CONTACTO")
   - **URL** - Deje vacio para usar URLs automaticas, o ingrese una URL personalizada
3. Para agregar un nuevo enlace, haga clic en **Agregar bloque** > **Enlace de Menu**
4. Para eliminar un enlace, seleccionelo y haga clic en el icono de basura
5. Para reordenar, arrastre los bloques

### Cambiar Colores del Header:

- **Color de fondo** - Color de fondo del encabezado
- **Color de enlaces** - Color de los textos del menu

---

## 5. Editar las Categorias de Productos

La seccion con las tarjetas de categorias (Frenos, Motor, etc.)

### Pasos:

1. Navegue a la pagina de inicio en el editor
2. Busque la seccion **"TP Categorias"**
3. Configuracion general:

| Opcion | Descripcion |
|--------|-------------|
| **Titulo de la seccion** | Ej: "Nuestras Lineas de Productos" |
| **Palabra destacada** | La palabra que aparece en color (ej: "Productos") |
| **Subtitulo** | Texto descriptivo opcional |
| **Color de fondo** | Color de fondo de la seccion |
| **Color del titulo** | Color del texto del titulo |
| **Color de palabra destacada** | Color de la palabra resaltada |

### Editar cada Categoria:

1. Haga clic en una categoria (bloque) para editarla
2. Puede cambiar:
   - **Nombre de la categoria** (ej: "Frenos", "Motor")
   - **ID interno** - Identificador sin espacios (ej: "frenos", "motor")
   - **Imagen de la categoria** - Haga clic en **Seleccionar imagen** y suba una imagen

### Agregar una Nueva Categoria:

1. Haga clic en **Agregar bloque** > **Categoria**
2. Complete los campos requeridos
3. Suba una imagen para la categoria

### Eliminar una Categoria:

1. Seleccione la categoria
2. Haga clic en el icono de basura

### Reordenar Categorias:

1. Arrastre los bloques de categoria hacia arriba o abajo para cambiar el orden

---

## 6. Editar Pagina de Detalle de Categoria

Cada categoria tiene su propia pagina de detalle con productos pre-configurados que puede editar facilmente desde el panel de administracion.

### Plantillas Disponibles

Cada categoria tiene su propia plantilla con productos apropiados:

| Categoria | Plantilla | Pagina |
|-----------|-----------|--------|
| Frenos | `page.frenos` | /pages/frenos |
| Suspension y Direccion | `page.suspension` | /pages/suspension |
| Motor | `page.motor` | /pages/motor |
| Sistema de Enfriamiento | `page.enfriamiento` | /pages/enfriamiento |
| Filtracion | `page.filtracion` | /pages/filtracion |
| Clutch y Transmision | `page.clutch` | /pages/clutch |
| Puntas y Ejes | `page.puntas-ejes` | /pages/puntas-ejes |
| Aceites y Liquidos | `page.aceites-liquidos` | /pages/aceites-liquidos |

### IMPORTANTE - Asignar la Plantilla Correcta

Para que los productos correctos aparezcan en cada categoria:

1. Vaya a **Shopify Admin** > **Tienda Online** > **Paginas**
2. Seleccione la pagina de categoria (ej: "Suspension")
3. En el panel derecho, busque **"Plantilla de tema"** (o "Theme template")
4. Seleccione la plantilla correcta (ej: `page.suspension` para la pagina de suspension)
5. Haga clic en **Guardar**

### Como acceder al Editor:

1. En el Editor del Tema, use el selector de paginas arriba (donde dice la pagina actual)
2. Navegue a **Paginas** > seleccione la categoria que desea editar (ej: "Frenos", "Suspension")
3. O vaya a la URL de la categoria directamente en su navegador y haga clic en **Personalizar**

### Editar el Banner Superior:

1. Haga clic en la seccion **"TP Categoria Detalle"**
2. En **Hero Banner**, puede editar:

| Opcion | Descripcion |
|--------|-------------|
| **Titulo de la categoria** | El titulo grande (ej: "SUSPENSION Y DIRECCION") |
| **Subtitulo** | Texto opcional debajo del titulo |
| **Imagen del hero** | **Haga clic en "Seleccionar"** para subir una nueva imagen de fondo |
| **URL externa de imagen** | Alternativa si no puede subir imagen |

### Editar los Productos de una Categoria:

Cada plantilla ya tiene productos pre-configurados. Para editarlos:

1. En la seccion "TP Categoria Detalle", vera una lista de bloques **"Producto"**
2. Haga clic en cualquier producto para editarlo:
   - **Nombre del producto** - Cambie el nombre que aparece en la tarjeta
   - **Imagen del producto** - Haga clic en **Seleccionar** para subir su propia imagen

### Agregar un Producto Nuevo:

1. Haga clic en **"Agregar bloque"**
2. Seleccione **"Producto"**
3. Ingrese el **Nombre del producto** (ej: "Amortiguadores Delanteros")
4. En **"Imagen del producto"**, haga clic en **Seleccionar** y suba su imagen
5. **Guarde los cambios**

### Eliminar un Producto:

1. Seleccione el bloque del producto
2. Haga clic en el icono de basura
3. Guarde

### Reordenar Productos:

1. Arrastre los bloques de producto hacia arriba o abajo para cambiar el orden

### Recomendaciones para Imagenes de Productos:

- **Tamano recomendado**: 400x400 pixeles
- **Formato**: JPG o PNG
- **Fondo**: Preferiblemente blanco o transparente

---

## 7. Subir Logos de Proveedores

La seccion donde aparecen los logos de las marcas de repuestos que maneja.

### Configuracion de la Seccion:

1. Busque la seccion **"TP Marcas / Proveedores"** en el editor
2. Configuracion general:

| Opcion | Descripcion |
|--------|-------------|
| **Titulo** | Ej: "Nuestros Proveedores" |
| **Palabra destacada** | La palabra en color |
| **Subtitulo** | Texto descriptivo |
| **Mostrar como** | Seleccione **"Logos / Imagenes"** para mostrar logos |
| **Colores** | Fondo, titulo, destacado |

### Como Agregar un Logo de Proveedor:

1. En la seccion "TP Marcas / Proveedores", haga clic en **Agregar bloque**
2. Seleccione **"Marca / Proveedor"**
3. Complete los campos:
   - **Nombre de la marca** - Nombre del proveedor (se usa como texto alternativo)
   - **Logo de la marca** - Haga clic en **Seleccionar imagen**
4. En el selector de imagenes:
   - Haga clic en **Subir** para cargar el logo desde su computadora
   - Seleccione el archivo PNG o JPG del logo
   - Espere a que se cargue
   - Haga clic en **Seleccionar**
5. Opcionalmente, marque **"Destacar esta marca"** para resaltarla con un borde
6. Haga clic en **Guardar**

### Cambiar un Logo Existente:

1. Haga clic en el bloque del proveedor que desea editar
2. En **Logo de la marca**, haga clic en **Cambiar**
3. Suba el nuevo logo o seleccione uno de la biblioteca
4. Guarde los cambios

### Eliminar un Proveedor:

1. Seleccione el bloque del proveedor
2. Haga clic en el icono de basura
3. Guarde los cambios

### Reordenar Proveedores:

1. Arrastre los bloques hacia arriba o abajo para cambiar el orden de aparicion

### Recomendaciones para Logos:

- **Formato**: PNG con fondo transparente (recomendado) o JPG
- **Tamano**: Minimo 200x100 pixeles
- **Peso**: Menos de 500KB por imagen
- Los logos se mostraran en escala de grises y se colorean al pasar el mouse

---

## 8. Editar Pagina de Garantias

La pagina de garantias y politicas de devolucion es completamente editable. Sigue el estilo de automas.cr con secciones claras.

### Como acceder:

1. En el Editor del Tema, use el selector de paginas arriba
2. Navegue a **Paginas** > **Garantia** (o la pagina de politicas)

### Editar el Contenido:

1. Haga clic en la seccion **"TP Politicas y Garantias"**
2. Configuracion principal:

| Opcion | Descripcion |
|--------|-------------|
| **Titulo de la pagina** | Titulo principal (ej: "Politicas de Devolucion y Garantia") |
| **Texto introductorio** | Parrafo opcional de introduccion |
| **Colores** | Fondo, titulo, texto de secciones |

### Editar Secciones de Politica:

Cada seccion (GARANTIAS, DEVOLUCION, etc.) es un bloque editable:

1. Haga clic en un bloque de **"Seccion de Politica"**
2. Edite:
   - **Titulo de la seccion** - Ej: "GARANTIAS", "DEVOLUCION"
   - **Contenido de la seccion** - Texto con formato
3. En el editor de contenido puede usar:
   - **Negritas** (seleccione texto y presione B)
   - **Cursivas** (seleccione texto y presione I)
   - **Listas con puntos** (icono de lista)
   - **Listas numeradas** (icono de lista numerada)

### Agregar Nueva Seccion:

1. Haga clic en **"Agregar bloque"**
2. Seleccione **"Seccion de Politica"**
3. Complete el titulo y contenido
4. Guarde

### Eliminar o Reordenar Secciones:

- Para eliminar: seleccione el bloque y haga clic en el icono de basura
- Para reordenar: arrastre los bloques hacia arriba o abajo

### Llamada a la Accion:

Al final de la pagina hay un boton de WhatsApp opcional:

1. Active/desactive con **"Mostrar boton de contacto"**
2. Edite el texto sobre el boton y el texto del boton

---

## 9. Editar Pagina Nosotros

La pagina "Acerca de Nosotros" tambien es editable.

### Como acceder:

1. En el Editor del Tema, navegue a **Paginas** > **Nosotros**

### Secciones de la Pagina:

#### TP Hero de Pagina (Banner Superior):

| Opcion | Descripcion |
|--------|-------------|
| **Titulo** | Titulo de la pagina |
| **Subtitulo** | Texto secundario |
| **Imagen de fondo** | Suba una imagen de fondo |
| **Altura minima** | Ajuste la altura del banner |
| **Color del overlay** | Color que oscurece la imagen |
| **Opacidad del overlay** | Que tan oscuro es el overlay |
| **Colores de texto** | Color del titulo y subtitulo |

#### TP Sobre Nosotros (Informacion de la Empresa):

| Opcion | Descripcion |
|--------|-------------|
| **Nombre de la empresa** | Nombre comercial |
| **Nombre legal** | Razon social (opcional) |
| **Slogan** | Frase de la empresa |
| **Descripcion con formato** | Use el editor para crear texto con formato, listas, etc. |
| **Imagen de la empresa** | Foto del equipo, instalaciones, etc. |
| **Colores** | Fondo, titulo, slogan, texto |

#### TP Por Que Elegirnos (Caracteristicas):

Muestra las razones para elegir Terrapartes.

1. Haga clic en cada **"Caracteristica"** para editar:
   - **Icono** - Seleccione de la lista
   - **Titulo** - Ej: "Asesoria Tecnica"
   - **Descripcion** - Texto descriptivo

2. Agregue nuevas caracteristicas con **"Agregar bloque"** > **"Caracteristica"**

3. Configure colores del titulo y fondo

---

## 10. Editar el Pie de Pagina (Footer)

La seccion inferior del sitio con el logo, enlaces y redes sociales.

### Pasos:

1. Desplacese hasta el final de la pagina en el editor o busque **"TP Footer"**
2. Configuracion disponible:

| Opcion | Descripcion |
|--------|-------------|
| **Logo** | Version blanca del logo para fondo oscuro |
| **Texto de copyright** | El texto legal en la parte inferior |
| **Color de fondo** | Color del footer |
| **Color de texto** | Color del texto |
| **Color de enlaces** | Color de los enlaces de navegacion |
| **Color de linea divisora** | Color de la linea entre secciones |

### Editar Enlaces del Footer:

1. Cada enlace es un bloque que puede editar
2. Haga clic en un enlace para cambiar:
   - **Texto** (ej: "Contacto")
   - **URL** (deje vacio para URLs automaticas)
3. Agregue nuevos enlaces con **Agregar bloque** > **Enlace**
4. Elimine enlaces seleccionandolos y haciendo clic en el icono de basura

---

## 11. Configurar WhatsApp y Contacto

Estos ajustes se encuentran en la configuracion global del tema.

### Pasos:

1. Haga clic en **Configuracion del tema** (engranaje inferior izquierdo)
2. Busque la seccion **"Terrapartes"**
3. En la subseccion **WhatsApp**:

| Opcion | Descripcion |
|--------|-------------|
| **Numero de WhatsApp** | Solo numeros, sin + ni espacios (ej: `50621015631`) |
| **Numero visible** | Como se muestra al usuario (ej: `+506 2101-5631`) |
| **Mensaje general** | Mensaje predeterminado al abrir WhatsApp |
| **Plantilla por producto** | Mensaje con variables `{product_name}` y `{category_name}` |

4. En la subseccion **Contacto**:

| Opcion | Descripcion |
|--------|-------------|
| **Numero de telefono** | Para el enlace de llamada |
| **Email de contacto** | Direccion de correo |

5. En la subseccion **Redes Sociales**:

| Opcion | Descripcion |
|--------|-------------|
| **Facebook URL** | Enlace completo a su pagina de Facebook |
| **Instagram URL** | Enlace completo a su perfil de Instagram |

---

## 12. Subir Imagenes

### Como subir imagenes:

1. Haga clic en cualquier campo de **imagen** en el editor
2. Seleccione **Subir** para cargar desde su computadora
3. O seleccione **Biblioteca** para usar imagenes ya subidas

### Formatos recomendados:

| Tipo de imagen | Formato | Tamano recomendado |
|----------------|---------|-------------------|
| Logo principal | PNG (transparente) | 300x150 px |
| Logo blanco (footer) | PNG (transparente) | 300x150 px |
| Logos de proveedores | PNG (transparente) | 200x100 px |
| Imagenes de categorias | JPG o PNG | 600x450 px |
| Imagen del hero | JPG | 1920x800 px |

### Comprimir imagenes:

Para que su sitio cargue rapido, comprima las imagenes antes de subirlas:
- [TinyPNG](https://tinypng.com/) - Gratis, comprime PNG y JPG
- [Squoosh](https://squoosh.app/) - Gratis, de Google

---

## 13. Consejos Importantes

### Guardar cambios:
- **SIEMPRE** haga clic en **Guardar** (boton verde en la esquina superior derecha) despues de hacer cambios
- Los cambios no se aplican hasta que guarde

### Vista previa:
- Use los iconos de dispositivos (telefono/computadora) arriba para ver como se ve en movil
- Los cambios se muestran en tiempo real en el editor

### Deshacer cambios:
- Si comete un error, puede hacer clic en **Descartar** antes de guardar
- Shopify guarda versiones anteriores del tema si necesita restaurar

### Reordenar secciones:
- Arrastre las secciones en el panel izquierdo para cambiar el orden
- Haga clic en el icono de ojo para ocultar una seccion temporalmente

### Problemas comunes:

| Problema | Solucion |
|----------|----------|
| No veo los cambios | Guarde y recargue la pagina |
| La imagen no se ve | Verifique el formato (PNG/JPG) y tamano |
| El color no cambia | Asegurese de guardar despues de cambiar |
| El texto esta cortado | Reduzca la longitud del texto |

---

## Resumen de Secciones Editables

| Seccion | Que puede editar |
|---------|------------------|
| **Barra Superior** | Colores, textos |
| **Header** | Logo, altura, colores, enlaces del menu |
| **Hero** | Titulo, subtitulo, boton, imagen de fondo, colores |
| **Categorias** | Titulo, subtitulo, colores, imagenes y nombres de cada categoria |
| **Detalle de Categoria** | Imagen del banner, productos con imagenes individuales |
| **Proveedores** | Titulo, subtitulo, colores, logos de cada proveedor |
| **Pagina Garantias** | Titulo, secciones de politica con texto formateado |
| **Pagina Nosotros** | Informacion de empresa, imagen, caracteristicas |
| **Footer** | Logo, copyright, colores, enlaces |
| **Configuracion Global** | WhatsApp, telefono, email, redes sociales, colores del sitio |

---

*Ultima actualizacion: Marzo 2026*
