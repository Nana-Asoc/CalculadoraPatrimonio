# Calculadora del patrimonio protegido · N.A.N.A.

Calculadora para familias de niños y niñas con discapacidad: cuánto se ahorra en la declaración de la renta metiendo dinero en el **patrimonio protegido** (Ley 41/2003) y cuánto dinero tendrá el niño o la niña con los años.

Publicada con GitHub Pages: https://nana-asoc.github.io/CalculadoraPatrimonio/

## Archivos

- `index.html`: la calculadora completa (no necesita servidor ni librerías).
- `icon.svg`, `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `icon-maskable-512.png`: iconos de la pestaña y del acceso directo en el móvil.
- `manifest.webmanifest`: permite "Añadir a pantalla de inicio".

## Mantenimiento anual

Los límites legales y supuestos están juntos al principio del `<script>` de `index.html`, en el objeto `CFG`:

- `limitePorPersona` (10.000 €) y `limiteTotal` (24.250 €): art. 54 LIRPF.
- `exencionHijo`: 3 × IPREM anual (21.600 € con el IPREM de 2026).
- `tramos`: escala general aproximada del IRPF.

El carrusel explicativo se edita en Canva y se actualiza solo en la web (constante `CANVA_EMBED`).

## Aviso

Estimación orientativa. No es asesoramiento fiscal ni financiero.

Contacto: nucli.nana@gmail.com · 694 58 70 00
