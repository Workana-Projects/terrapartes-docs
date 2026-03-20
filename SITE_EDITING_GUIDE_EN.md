# Website Editing Guide - Terrapartes

This guide explains how to edit all elements of your website from the Shopify admin panel, **without touching any code**.

---

## Table of Contents

1. [Accessing the Theme Editor](#1-accessing-the-theme-editor)
2. [Changing Global Colors](#2-changing-global-colors)
3. [Editing the Top Bar](#3-editing-the-top-bar)
4. [Editing the Header](#4-editing-the-header)
5. [Editing Product Categories](#5-editing-product-categories)
6. [Editing Category Detail Page](#6-editing-category-detail-page)
7. [Uploading Supplier Logos](#7-uploading-supplier-logos)
8. [Editing the Warranty Page](#8-editing-the-warranty-page)
9. [Editing the About Us Page](#9-editing-the-about-us-page)
10. [Editing the Footer](#10-editing-the-footer)
11. [Configuring WhatsApp and Contact](#11-configuring-whatsapp-and-contact)
12. [Uploading Images](#12-uploading-images)
13. [Important Tips](#13-important-tips)

---

## 1. Accessing the Theme Editor

1. Log in to your Shopify admin panel
2. In the left sidebar menu, click on **Online Store**
3. Click on **Themes**
4. On your active theme (Terrapartes), click the **Customize** button

This will open the **Visual Theme Editor** where you can see changes in real time.

---

## 2. Changing Global Colors

The main site colors can be changed from the theme settings.

### Steps:

1. In the Theme Editor, click on **Theme settings** (gear icon in the bottom left corner)
2. Look for the **"Terrapartes"** section
3. You will see the following color options:

| Option | What it controls |
|--------|------------------|
| **Primary Color (Orange)** | Buttons, links, accents |
| **Dark Primary Color** | Button hover states |
| **Dark Color (Navy Blue)** | Topbar, footer, headings |
| **Text Color** | General site text |
| **Background Color** | Main background |
| **Light Background Color** | Alternate section backgrounds |

4. Click on each color to open the color picker
5. Choose the desired color or enter the hex code (e.g., `#E8491D`)
6. Click **Save** in the top right corner

---

## 3. Editing the Top Bar

The dark blue bar at the top of the site.

### Steps:

1. In the Theme Editor, click on the top bar or look for **"TP Barra Superior"** in the sections list
2. You can edit:

| Option | Description |
|--------|-------------|
| **Left text** | Text next to social icons (e.g., "Follow us") |
| **Phone text** | Phone link text (e.g., "Call Us Now") |
| **Background color** | Bar background color |
| **Text color** | Text and links color |

3. Save your changes

---

## 4. Editing the Header

The header with logo and navigation menu.

### Changing the Logo:

1. Click on the header section or look for **"TP Header"**
2. In **Site logo**, click **Select image**
3. Upload your new logo or choose from the library
4. Adjust **Logo height** with the slider if needed

### Editing Menu Links:

Menu links are edited as blocks:

1. Click on each link to edit it
2. You can change:
   - **Link text** (e.g., "PARTS", "CONTACT")
   - **URL** - Leave empty for automatic URLs, or enter a custom URL
3. To add a new link, click **Add block** > **Menu Link**
4. To delete a link, select it and click the trash icon
5. To reorder, drag the blocks

### Changing Header Colors:

- **Background color** - Header background color
- **Link color** - Menu text color

---

## 5. Editing Product Categories

The section with category cards (Brakes, Engine, etc.)

### Steps:

1. Navigate to the home page in the editor
2. Look for the **"TP Categorias"** section
3. General settings:

| Option | Description |
|--------|-------------|
| **Section title** | E.g., "Our Product Lines" |
| **Highlighted word** | Word that appears in color (e.g., "Products") |
| **Subtitle** | Optional descriptive text |
| **Background color** | Section background color |
| **Title color** | Title text color |
| **Highlight color** | Highlighted word color |

### Editing Each Category:

1. Click on a category (block) to edit it
2. You can change:
   - **Category name** (e.g., "Brakes", "Engine")
   - **Internal ID** - Identifier without spaces (e.g., "brakes", "engine")
   - **Category image** - Click **Select image** and upload an image

### Adding a New Category:

1. Click **Add block** > **Category**
2. Fill in the required fields
3. Upload an image for the category

### Deleting a Category:

1. Select the category
2. Click the trash icon

### Reordering Categories:

1. Drag the category blocks up or down to change the order

---

## 6. Editing Category Detail Page

All category pages use the same template (`page.category`), but **each page can have its own different products**. Shopify saves the configuration for each page separately.

### How It Works

In Shopify Online Store 2.0:
- All category pages use the `page.category` template
- When you customize a page in the Theme Editor, changes are saved ONLY for that page
- Each page can have completely different products, images, and text

### Creating a New Category Page

1. Go to **Shopify Admin** > **Online Store** > **Pages**
2. Click **"Add page"**
3. Enter the **Title** for the category (e.g., "Suspension y Direccion")
   - This title will automatically appear as the page title
4. In the right panel, look for **"Theme template"**
5. Select **`page.category`**
6. Click **Save**

### Customizing Products for a Category

1. In the Theme Editor, use the page selector at the top
2. Navigate to **Pages** > select the category (e.g., "Suspension y Direccion")
3. Click on the **"TP Categoria Detalle"** section

### Editing the Top Banner:

| Option | Description |
|--------|-------------|
| **Category title** | Leave empty to automatically use the page title |
| **Subtitle** | Optional text below the title |
| **Hero image** | **Click "Select"** to upload a background image |
| **External image URL** | Alternative if you cannot upload |

### Adding Products:

1. Click **"Add block"** (or "Agregar bloque")
2. Select **"Producto"**
3. Enter the **Product name** (e.g., "Front Shock Absorbers")
4. In **"Product image"**, click **Select** and upload your image
5. Repeat for all products in this category
6. **Save your changes**

**IMPORTANT:** Products you add here will only appear on THIS category page, not on others.

### Editing an Existing Product:

1. Click on the product block
2. Change the name or upload a new image
3. Save

### Deleting a Product:

1. Select the product block
2. Click the trash icon
3. Save

### Reordering Products:

1. Drag product blocks up or down

### Configuration Example

For the "Suspension y Direccion" category, you would add products like:
- Front Shock Absorbers
- Rear Shock Absorbers
- Upper Ball Joints
- Lower Ball Joints
- Tie Rod Ends
- Control Arms
- etc.

For the "Frenos" (Brakes) category, you would add products like:
- Front Brake Pads
- Rear Brake Pads
- Brake Discs
- etc.

### Product Image Recommendations:

- **Recommended size**: 400x400 pixels
- **Format**: JPG or PNG
- **Background**: Preferably white or transparent

---

## 7. Uploading Supplier Logos

The section where your parts brand logos appear.

### Section Configuration:

1. Look for the **"TP Marcas / Proveedores"** section in the editor
2. General settings:

| Option | Description |
|--------|-------------|
| **Title** | E.g., "Our Suppliers" |
| **Highlighted word** | Word in color |
| **Subtitle** | Descriptive text |
| **Display as** | Select **"Logos / Images"** to show logos |
| **Colors** | Background, title, highlight |

### How to Add a Supplier Logo:

1. In the "TP Marcas / Proveedores" section, click **Add block**
2. Select **"Marca / Proveedor"** (Brand / Supplier)
3. Fill in the fields:
   - **Brand name** - Supplier name (used as alt text)
   - **Brand logo** - Click **Select image**
4. In the image picker:
   - Click **Upload** to load the logo from your computer
   - Select the PNG or JPG logo file
   - Wait for it to upload
   - Click **Select**
5. Optionally, check **"Highlight this brand"** to add a colored border
6. Click **Save**

### Changing an Existing Logo:

1. Click on the supplier block you want to edit
2. In **Brand logo**, click **Change**
3. Upload the new logo or select from library
4. Save changes

### Deleting a Supplier:

1. Select the supplier block
2. Click the trash icon
3. Save changes

### Reordering Suppliers:

1. Drag the blocks up or down to change display order

### Logo Recommendations:

- **Format**: PNG with transparent background (recommended) or JPG
- **Size**: Minimum 200x100 pixels
- **File size**: Less than 500KB per image
- Logos will display in grayscale and colorize on mouse hover

---

## 8. Editing the Warranty Page

The warranty and return policy page is completely editable. It follows the automas.cr style with clear sections.

### How to access:

1. In the Theme Editor, use the page selector at the top
2. Navigate to **Pages** > **Garantia** (or your policy page)

### Editing the Content:

1. Click on the **"TP Politicas y Garantias"** section
2. Main settings:

| Option | Description |
|--------|-------------|
| **Page title** | Main title (e.g., "Return and Warranty Policies") |
| **Introductory text** | Optional introduction paragraph |
| **Colors** | Background, title, section text |

### Editing Policy Sections:

Each section (WARRANTIES, RETURNS, etc.) is an editable block:

1. Click on a **"Policy Section"** block
2. Edit:
   - **Section title** - E.g., "WARRANTIES", "RETURNS"
   - **Section content** - Formatted text
3. In the content editor you can use:
   - **Bold** (select text and press B)
   - **Italic** (select text and press I)
   - **Bullet lists** (list icon)
   - **Numbered lists** (numbered list icon)

### Adding a New Section:

1. Click **"Add block"**
2. Select **"Policy Section"**
3. Fill in the title and content
4. Save

### Deleting or Reordering Sections:

- To delete: select the block and click the trash icon
- To reorder: drag blocks up or down

### Call to Action:

At the end of the page there's an optional WhatsApp button:

1. Enable/disable with **"Show contact button"**
2. Edit the text above the button and the button text

---

## 9. Editing the About Us Page

The "About Us" page is also editable.

### How to access:

1. In the Theme Editor, navigate to **Pages** > **Nosotros**

### Page Sections:

#### TP Page Hero (Top Banner):

| Option | Description |
|--------|-------------|
| **Title** | Page title |
| **Subtitle** | Secondary text |
| **Background image** | Upload a background image |
| **Minimum height** | Adjust banner height |
| **Overlay color** | Color that darkens the image |
| **Overlay opacity** | How dark the overlay is |
| **Text colors** | Title and subtitle color |

#### TP About Us (Company Information):

| Option | Description |
|--------|-------------|
| **Company name** | Business name |
| **Legal name** | Legal entity name (optional) |
| **Slogan** | Company phrase |
| **Formatted description** | Use the editor for formatted text, lists, etc. |
| **Company image** | Team photo, facilities, etc. |
| **Colors** | Background, title, slogan, text |

#### TP Why Choose Us (Features):

Shows reasons to choose Terrapartes.

1. Click on each **"Feature"** to edit:
   - **Icon** - Select from the list
   - **Title** - E.g., "Technical Advice"
   - **Description** - Descriptive text

2. Add new features with **"Add block"** > **"Feature"**

3. Configure title and background colors

---

## 10. Editing the Footer

The bottom section of the site with logo, links, and social media.

### Steps:

1. Scroll to the bottom of the page in the editor or look for **"TP Footer"**
2. Available settings:

| Option | Description |
|--------|-------------|
| **Logo** | White version of logo for dark background |
| **Copyright text** | Legal text at the bottom |
| **Background color** | Footer color |
| **Text color** | Text color |
| **Link color** | Navigation links color |
| **Divider color** | Line color between sections |

### Editing Footer Links:

1. Each link is a block you can edit
2. Click on a link to change:
   - **Text** (e.g., "Contact")
   - **URL** (leave empty for automatic URLs)
3. Add new links with **Add block** > **Link**
4. Delete links by selecting them and clicking the trash icon

---

## 11. Configuring WhatsApp and Contact

These settings are found in the global theme settings.

### Steps:

1. Click on **Theme settings** (gear icon, bottom left)
2. Look for the **"Terrapartes"** section
3. In the **WhatsApp** subsection:

| Option | Description |
|--------|-------------|
| **WhatsApp number** | Numbers only, no + or spaces (e.g., `50621015631`) |
| **Display number** | How it shows to users (e.g., `+506 2101-5631`) |
| **General message** | Default message when opening WhatsApp |
| **Product template** | Message with `{product_name}` and `{category_name}` variables |

4. In the **Contact** subsection:

| Option | Description |
|--------|-------------|
| **Phone number** | For the call link |
| **Contact email** | Email address |

5. In the **Social Media** subsection:

| Option | Description |
|--------|-------------|
| **Facebook URL** | Full link to your Facebook page |
| **Instagram URL** | Full link to your Instagram profile |

---

## 12. Uploading Images

### How to upload images:

1. Click on any **image** field in the editor
2. Select **Upload** to load from your computer
3. Or select **Library** to use already uploaded images

### Recommended formats:

| Image type | Format | Recommended size |
|------------|--------|------------------|
| Main logo | PNG (transparent) | 300x150 px |
| White logo (footer) | PNG (transparent) | 300x150 px |
| Supplier logos | PNG (transparent) | 200x100 px |
| Category images | JPG or PNG | 600x450 px |
| Hero image | JPG | 1920x800 px |

### Compressing images:

To make your site load faster, compress images before uploading:
- [TinyPNG](https://tinypng.com/) - Free, compresses PNG and JPG
- [Squoosh](https://squoosh.app/) - Free, by Google

---

## 13. Important Tips

### Saving changes:
- **ALWAYS** click **Save** (green button in top right corner) after making changes
- Changes are not applied until you save

### Preview:
- Use the device icons (phone/computer) at the top to see mobile view
- Changes are shown in real time in the editor

### Undoing changes:
- If you make a mistake, you can click **Discard** before saving
- Shopify saves previous theme versions if you need to restore

### Reordering sections:
- Drag sections in the left panel to change order
- Click the eye icon to temporarily hide a section

### Common problems:

| Problem | Solution |
|---------|----------|
| I don't see changes | Save and refresh the page |
| Image doesn't show | Check the format (PNG/JPG) and size |
| Color doesn't change | Make sure to save after changing |
| Text is cut off | Reduce text length |

---

## Summary of Editable Sections

| Section | What you can edit |
|---------|-------------------|
| **Top Bar** | Colors, texts |
| **Header** | Logo, height, colors, menu links |
| **Hero** | Title, subtitle, button, background image, colors |
| **Categories** | Title, subtitle, colors, images and names for each category |
| **Category Detail** | Banner image, products with individual images |
| **Suppliers** | Title, subtitle, colors, logos for each supplier |
| **Warranty Page** | Title, policy sections with formatted text |
| **About Us Page** | Company info, image, features |
| **Footer** | Logo, copyright, colors, links |
| **Global Settings** | WhatsApp, phone, email, social media, site colors |

---

*Last updated: March 2026*
