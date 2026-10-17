# KULTURA360 – Web del curs anterior

Web del festival cultural **KULTURA360**, desenvolupada el curs passat. Presenta el festival amb una portada (dates, FAQ, contacte i formulari de registre), una galeria d'imatges d'edicions anteriors amb carrusel i visor ampliat, i una pàgina d'informació legal.

## Tecnologies utilitzades

- HTML5
- CSS3 (fitxer `public/css/styles.css`)
- JavaScript (fitxer `public/js/main.js`): modal, carrusel i lightbox
- Font Awesome i Google Fonts (Poppins) des de CDN
- Firebase Hosting per a la publicació

## Estructura

```
public/
├── index.html      Portada del festival
├── galeria.html    Galeria d'esdeveniments anteriors
├── legal.html      Informació legal
├── 404.html        Pàgina d'error
├── css/styles.css
├── js/main.js
└── img/            Imatges i logotips
firebase.json       Configuració de Firebase Hosting
.firebaserc         Projecte de Firebase
```

## Obrir-la localment

Opció 1: obrir directament `public/index.html` amb el navegador.

Opció 2: servir-la amb un servidor local (recomanat):

```bash
npx http-server public
```

o bé amb l'emulador de Firebase:

```bash
firebase emulators:start --only hosting
```

## Desplegament

```bash
firebase login
firebase deploy --only hosting
```

## Web publicada

https://practica-1-antigua.web.app
