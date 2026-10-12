# translation

Traductor web de una sola página («Coolest Translator») para inglés ↔ español, con una paleta inspirada en DeepL. Es un único fichero HTML con todo el CSS y el JavaScript dentro.

## Estructura

- `cool_trans.html` — la aplicación entera (clase `TranslationApp`).
- `.gitignore`

## Funciones

- Traduce entre inglés y español, con botón para intercambiar los idiomas.
- Intenta primero un endpoint no oficial de DeepL (`www2.deepl.com/jsonrpc`) y, si falla, recurre a otros servicios (`translate.googleapis.com`, `libretranslate.de`).
- Trocea los textos largos (`translateLargeText`).
- Copiar y pegar del portapapeles; atajos de teclado.

## Uso

Abrir `cool_trans.html` en el navegador. No hay build ni servidor.

## Estado

- Un solo commit: «Initial commit» (11-oct-2026).
- El HTML es del 5-mar-2026.
- Sin remoto configurado.
