# 🌐 Proyecto WordPress - ConquerBlocks

Este repositorio contiene el código fuente del sitio web de **ConquerBlocks**, desarrollado en WordPress.

## 🧱 Descripción

El proyecto fue creado con el CMS WordPress, e incluye el tema, plugins y personalizaciones necesarias para el sitio. Está pensado como una solución modular y escalable, fácil de mantener y actualizar.

> ⚠️ Este repositorio **no incluye archivos de respaldo** (.wpress), ni bases de datos SQL por motivos de tamaño y seguridad.

---

## 📁 Estructura del proyecto

```
wp-content/
├── plugins/           → Plugins instalados y personalizados
├── themes/            → Tema activo y otros temas instalados
├── uploads/           → Archivos multimedia del sitio
└── ai1wm-backups/     → Carpeta ignorada para evitar subir respaldos
```

---

## ⚙️ Requisitos

- Servidor con PHP 7.4+ o superior
- MySQL/MariaDB
- Apache o Nginx
- WordPress 6.x instalado
- [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) (opcional para restaurar desde backup)

---

## 🚀 Instalación local (opcional)

1. Clona el repositorio:

```bash
git clone https://github.com/Balti2003/Proyecto_wordpress_conquerblocks.git
```

2. Instala WordPress en tu entorno local (XAMPP, MAMP, Laragon, etc.).
3. Copia la carpeta `wp-content/` en tu instalación de WordPress.
4. Restaura una base de datos compatible (no incluida en este repositorio).
5. Configura el archivo `wp-config.php` según tu entorno local.

---

## 🚫 Exclusiones importantes

Este repositorio ignora por defecto:

- Archivos de respaldo `.wpress`
- Bases de datos `.sql`
- Archivos comprimidos `.zip`

> Consultá `.gitignore` para ver la lista completa.

---

## 👤 Autor

- **Baltasar**  
- [GitHub](https://github.com/Balti2003)

---

## 📝 Licencia

Este proyecto se comparte con fines educativos. Para uso comercial, consultar derechos del contenido y licencias de plugins/temas utilizados.
