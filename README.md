# El Ahorcado

Juego clásico de adivinar la palabra: vas fallando letras y el dibujo del ahorcado se va completando.

## Qué hace

- Saca una palabra al azar de `palabras.js` (galaxia, guitarra, chocolate…)
- Teclado de letras y guiones de la palabra
- El SVG del ahorcado se rellena con cada error
- Avisa cuando ganas o cuando se acaba la partida

## Cómo probarlo

Sin instalación: abre `index.html` en el navegador (o la demo).

Demo: https://moussijoelle.github.io/ahorcado-joelle-html/

## Cómo lo construí

HTML, JavaScript y Tailwind por CDN. La lista de palabras está aparte en `palabras.js` y el poste/muñeco es un SVG dentro del HTML. Tipografía Playfair Display para el título.

## Cómo verificarlo

Juego una partida acertando y otra fallando a propósito, para ver que el dibujo y el mensaje final cuadren.

---

Moussi Joelle  
https://github.com/moussijoelle/ahorcado-joelle-html
