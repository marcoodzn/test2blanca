# Web para pedirle salir a Blanca

## Concepto
Álbum de cromos (a lo Panini del Mundial), inspirado en vuestra propia
foto abriendo sobres en el coche. Cada recuerdo es un "cromo" numerado,
y la pregunta final juega con que "falta un cromo por conseguir".

## Cómo verla
Abre `index.html` con doble clic.

## Cómo editarla
- Textos de cada cromo: dentro de `index.html`, array `CROMOS` en el `<script>`.
  Los que llevan "(revisa esto)" son mi mejor suposición al ver la foto;
  corrígelos por lo que pasó de verdad.
- Fotos: ya están puestas (`fotos/cromo1.jpg` a `cromo7.jpg`), en este orden:
  1. Coche con los sobres del Mundial
  2. Comida con pulseras azules (viaje)
  3. Espejo en blanco y negro
  4. Espejo arreglados
  5. Festival, beso en la mejilla
  6. Festival, beso de frente
  7. Grupo a hombros
  Para cambiar alguna, sustituye el archivo manteniendo el mismo nombre.
  Si quieres reordenarlas, cambia el orden de los objetos en `CROMOS`
  (el número `n` decide qué foto `cromoN.jpg` carga cada uno).

## Nota sobre el formato de las fotos
Me dijiste 16:9, pero las que me llegaron son verticales de móvil
(la mayoría 3:4, un par 9:16). Encajan bien igualmente porque el
diseño usa un formato de cromo/carta vertical — si me mandas fotos
realmente en 16:9 luego, dímelo y ajusto el recorte.

## Cómo subirla a internet
Arrastra esta carpeta entera a GitHub Pages, Netlify o Vercel, igual
que hiciste con tu web de regalonavidad.
