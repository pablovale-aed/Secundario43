# Emprendedores en Acción 2026

Página de la expo anual de emprendimientos del **Colegio Secundario N° 43 "Puerto Argentino"**
(Alto Comedero, San Salvador de Jujuy). Viernes 13 de noviembre de 2026, de 10 a 15 h. Entrada libre y gratuita.

## Qué tiene

- Stands con filtros, estrellas de "ganas de probar", corazones y ranking en vivo.
- Modal con el menú de cada stand.
- Registro de asistencia.
- Cuenta regresiva, cómo llegar y preguntas frecuentes.

Los votos y el registro se guardan en Firebase Realtime Database. Las reglas de seguridad están en
`database.rules.json` (se pegan en Firebase → Realtime Database → Reglas).

## Editar los stands

Todo está en `index.html`, en la lista `STANDS` dentro del `<script>`. Para cargar el menú de un stand:

```js
menu: { imagen: 'img/stand/MenuX.jpg', items: [['Producto', '$precio']] }
```
