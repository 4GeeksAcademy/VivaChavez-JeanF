# VivaChavez - Entrega Rehecha (Tailwind + 5 vistas)

Este proyecto fue rehecho para cumplir la retroalimentacion de entrega:

- Se elimino el CSS manual pesado.
- Se implemento Tailwind CSS por CDN en todas las vistas.
- Se dividio el sitio en 5 archivos HTML separados por vista.
- Se mantuvieron mejoras SEO (meta tags y Schema.org en vistas clave).

## Tecnologias

- HTML5
- Tailwind CSS v4 via CDN

## Estructura de vistas (5 archivos)

- index.html - Inicio
- coleccion.html - Catalogo
- producto.html - Detalle de producto
- carrito.html - Vista de carrito
- checkout.html - Proceso de pago

## Ejecucion local

```bash
pip3 install flask && python3 server.py
```

Luego abre en el navegador:

- http://127.0.0.1:3000/index.html

## SEO implementado

- title y meta description por vista
- canonical por vista
- Open Graph en inicio
- Schema.org tipo WebSite en inicio
- Schema.org tipo Product en producto

## Evidencia de PageSpeed (requerida para entrega)

Se dejo la carpeta evidencias para adjuntar la captura solicitada:

- evidencias/pagespeed-mobile.png
- evidencias/pagespeed-desktop.png

Nota: las capturas deben generarse corriendo el sitio y evaluando cada vista en PageSpeed Insights.
