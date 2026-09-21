# Política de privacidad de Acompañar

Este repo existe por una sola razón: **Google Play exige una URL pública con la política de
privacidad**, y la app maneja datos de salud (medicación, presión arterial, consultas
médicas), así que la revisan con más detalle que la de una app común.

Es `index.html` y nada más, servido por GitHub Pages:

<https://betososa930.github.io/acompanar-privacidad/>

## Por qué está separado del repo de la app

El repo de Acompañar (`betososa930/acompanar`) es **privado** y va a seguir siéndolo. Este
tiene que ser público para que Pages lo sirva, y lo único que contiene es un documento que
es público por definición.

Separarlo además desacopla la política del backend: si Render se cae, si se migra a otro
lado o si el servicio se borra, la URL que figura en la ficha de Play sigue viva. Una
política de privacidad caída es motivo de suspensión de la ficha.

## Cómo se publica

En GitHub: **Settings → Pages → Source: Deploy from a branch → `main` / `/ (root)`**.
Tarda un par de minutos la primera vez.

## Si cambia la app, cambia esto

La política tiene que coincidir con el formulario de **Seguridad de los datos** de Play.
Si dejan de coincidir, Play rechaza la actualización. Volver acá cuando:

- se guarde un dato nuevo de la persona o del familiar;
- entre un proveedor nuevo (hoy: Google/FCM para el push, Render para el servidor, Neon
  para la base);
- se agregue publicidad, analytics o cualquier SDK de terceros — hoy no hay nada de eso, y
  es media política;
- cambie un permiso de Android;
- cambie la forma de borrar los datos.

Al editarla hay que **subir la fecha de arriba y la del pie**.
