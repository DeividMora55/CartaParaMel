# Una coincidencia en el multiverso 🕷️🌌

Una miniaventura interactiva en una sola página HTML: Spider-Man contra Darth Vader, efectos de combate, botones troll, cuatro mensajes ocultos y una carta para una amiga.

## Abrir la página

Abre `index.html` en Chrome, Edge, Firefox o Safari. No requiere instalar librerías, servidores ni herramientas.

## Publicar en GitHub Pages

1. Crea un repositorio público en GitHub, por ejemplo `carta-para-ti`.
2. Sube `index.html` a la **raíz** del repositorio (puedes subir también este README).
3. Ve a **Settings → Pages → Build and deployment**.
4. Selecciona **Deploy from a branch**, rama **main**, carpeta **/(root)**, y guarda.
5. Comparte la URL `https://TU-USUARIO.github.io/carta-para-ti/` cuando GitHub Pages la muestre.

## Personalizar firma

Abre `index.html` y busca al final el siguiente fragmento:

```js
const DATOS = { firma: 'Tu amigo' };
```

Reemplaza `Tu amigo` con tu nombre, guarda el archivo y súbelo de nuevo a GitHub.

## Notas

- Las ilustraciones de los personajes son dibujos SVG estilizados integrados en el código, y todos los sonidos son sintetizados en el navegador.
- La página está diseñada para celulares y computadoras. Los efectos de sonido están apagados al entrar; el usuario puede activarlos.
- No utiliza fuentes ni librerías externas: funciona directamente desde el archivo descargado.
- No incluyas información personal que quieras mantener privada en un repositorio público.
