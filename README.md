# Entradas Mestalla - WordPress + WooCommerce

Tienda online de venta de entradas para el Estadio de Mestalla (Valencia). Proyecto de clase.

## Contenido del repositorio

| Archivo | Que contiene |
|---|---|
| backup_*-db.gz | Base de datos completa (paginas, productos, pedidos, usuarios, ajustes) |
| backup_*-plugins.zip | Plugins: WooCommerce, Contact Form 7, Joinchat, UpdraftPlus |
| backup_*-themes.zip | Temas (Twenty Twenty-Five personalizado) |
| backup_*-uploads.zip | Imagenes subidas |
| backup_*-others.zip | Resto de wp-content |

Copia hecha con UpdraftPlus.

## Funcionalidades

| Punto | Como esta hecho |
|---|---|
| Dominio local | http://192.168.1.121 (entradas-mestalla.local en el archivo hosts) |
| 3 usuarios | Youssef1 (administrador), Youssef2 (gestor de la tienda), Youssef3 (cliente) |
| Tema | Twenty Twenty-Five con colores blanco, negro y naranja, cabecera y pie propios |
| Servicios WordPress | Acceso/Mi cuenta (login y registro) y formulario de contacto (Contact Form 7) |
| Mapa | Google Maps embebido en Estadio y Contacto |
| Chat | Boton de WhatsApp (Joinchat) |
| Productos por categorias | Liga, Copa del Rey, Abonos, Tour del estadio, Merchandising |
| Resenas | Valoraciones con estrellas en los productos |
| Pago | Bizum (transferencia, datos ficticios) y Pago en taquilla |
| Envios | Correos, SEUR, MRW, envio gratis +100 EUR, recogida en taquillas |

## Como restaurarlo

Paso 1: instalar WordPress limpio.

Paso 2: instalar y activar el plugin UpdraftPlus.

Paso 3: subir los archivos backup_* en UpdraftPlus > Copias de seguridad existentes > Subir archivos de copia de seguridad.

Paso 4: pulsar Restaurar.
