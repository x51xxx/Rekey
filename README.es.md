# Rekey

**Nunca más escribas en el idioma equivocado.**

Rekey es una app gratuita para la barra de menús de macOS que detecta cuando una palabra ha salido
con la distribución de teclado equivocada y la reescribe en el sitio; después cambia la
distribución por ti, así que solo tienes que seguir escribiendo. Es un cambiador automático de
distribución de teclado para Mac y una alternativa nativa a Punto Switcher y Caramba Switcher,
creada por [Taras Trishchuk](https://trishchuk.com/) y publicada en
[trishchuk.com/rekey](https://trishchuk.com/rekey/es/).

![Rekey corrige una palabra escrita con la distribución equivocada](assets/rekey-demo.gif)

*Una sola secuencia de teclas sin cortes, nada preparado. `ghbdsn` escrito con la distribución
inglesa se convierte en `привіт` y la distribución pasa a ucraniano; `Цщкдв` escrito con la
distribución ucraniana se convierte en `World` y vuelve a cambiar.*

## Descargar

### [⬇ Descargar Rekey para macOS](https://trishchuk.com/rekey/download/Rekey.dmg)

macOS 13 Ventura o posterior · una compilación universal para Apple Silicon e Intel · gratis

Esto es una beta pública. Se actualiza sola y, en las versiones beta, envía por defecto informes
de fallos anónimos para que los problemas se corrijan de verdad; ambas cosas se pueden desactivar
en Ajustes.

## Qué hace

- **Corrige la palabra sin cortarte el ritmo.** Cuando una palabra puntúa muchísimo mejor en otro
  idioma que en el que la escribiste, Rekey la borra, cambia la distribución y la vuelve a
  escribir bien. Sin diálogos ni confirmaciones.
- **Frases enteras, no solo palabras sueltas.** Una palabra corta que no se puede juzgar por sí
  sola se retiene hasta que la siguiente resuelve la duda, así que `f yt` se convierte en `а не`
  en lugar de quedarse como estaba.
- **Deshacer le enseña.** Pulsa ⌘Z en los cinco segundos siguientes a una corrección y Rekey
  añade esa palabra a su lista de ignoradas. No comete dos veces el mismo error con la misma
  palabra.
- **También cambio manual.** Doble pulsación de Shift por defecto, o Control, Option, Command,
  ⌃Space, ⌘Space, ⌥⌘Space.
- **No estorba.** Los campos de contraseña, los terminales y los editores de código están
  excluidos por defecto, y se salta el texto que parece una URL, una ruta o código.

## Idiomas

34 idiomas con escritura latina, cirílica, griega, hebrea, árabe, armenia, georgiana y coreana,
entre ellos ucraniano, inglés, alemán, francés, español, polaco y checo. La lista completa está
en Ajustes ▸ Idiomas.

La detección no es una tabla de equivalencias: cada palabra se puntúa según las frecuencias de
pares y tríos de letras de cada idioma más un diccionario, construidos con datos reales de corpus
y no con una lista de palabras que alguien tecleó a mano.

## Cómo se compara Rekey

| | **Rekey** | Caramba Switcher | Punto Switcher |
|---|---|---|---|
| Idiomas admitidos | **34** | EN + RU | EN + RU |
| Lo que escribes no sale del Mac | ✓ | ✓ | ✕ |
| Corrección de frases completas | ✓ | ✕ | ✕ |
| Respeta los campos de contraseña | ✓ | ✓ | ✕ |
| Excluye editores de código por defecto | ✓ | ✓ | ✕ |
| Deshacer al instante (⌘Z) | ✓ | ✓ | ✕ |
| Swift nativo, sin Electron | ✓ | ✓ | ✕ |
| Hecho para el macOS moderno | ✓ | ✓ | ✕ |
| Precio | **Gratis** | $6.99/año | Gratis |

Comparación basada en información pública, junio de 2026.

## Alternativa a Punto Switcher y Caramba Switcher para Mac

¿Buscas una **alternativa a Punto Switcher para Mac**? Eso es exactamente Rekey, con una
diferencia: está hecho para quienes escriben en más de dos idiomas. Punto Switcher es una
herramienta de Windows de Yandex; su antigua versión para Mac ya no se mantiene y no funciona de
forma fiable en Apple Silicon. Caramba Switcher funciona en el macOS actual, pero se centra en
inglés y ruso y se vende por suscripción.

Análisis más extensos en la web:

- [Punto Switcher para Mac — alternativa nativa con Rekey](https://trishchuk.com/rekey/es/punto-switcher-para-mac/)
- [Las mejores alternativas a Punto Switcher para Mac, comparadas](https://trishchuk.com/rekey/es/alternativas-a-punto-switcher/)
- [Las mejores alternativas a Caramba Switcher para Mac, comparadas](https://trishchuk.com/rekey/es/alternativas-a-caramba-switcher/)
- Cara a cara (en inglés): [Rekey vs Caramba Switcher](https://trishchuk.com/rekey/compare/rekey-vs-caramba-switcher/) ·
  [Rekey vs Boomkey](https://trishchuk.com/rekey/compare/rekey-vs-boomkey/) ·
  [Rekey vs Keyboop](https://trishchuk.com/rekey/compare/rekey-vs-keyboop/) ·
  [Rekey vs MLSwitcher](https://trishchuk.com/rekey/compare/rekey-vs-mlswitcher/) ·
  [Rekey vs Flipio](https://trishchuk.com/rekey/compare/rekey-vs-flipio/)
- Si vienes de Windows (en inglés): [Alternativa a Mahou](https://trishchuk.com/rekey/alternatives/mahou/) ·
  [Alternativa a EveryLang](https://trishchuk.com/rekey/alternatives/everylang/)

## Preguntas frecuentes

**¿Existe Punto Switcher para Mac?**
No en una versión actual. La antigua versión de Punto Switcher para Mac ya no se mantiene y no
funciona de forma fiable en Apple Silicon. Rekey hace lo mismo —corrige el texto escrito con la
distribución equivocada y cambia la distribución— como app nativa en Swift para el macOS actual.

**¿Rekey es gratis?**
Sí. Es gratis, sin cuenta y sin suscripción. Ahora mismo es una beta pública.

**¿Funciona en Apple Silicon?**
Sí. Una única compilación universal funciona en Mac con Apple Silicon e Intel con macOS 13
Ventura o posterior.

**¿Qué idiomas admite?**
34 idiomas, entre ellos ucraniano, inglés, alemán, francés, español, polaco, checo, griego,
hebreo y árabe. Funciona con cualquier par o conjunto de distribuciones que tengas instaladas, no
solo con inglés y ruso.

**¿Envía a algún sitio lo que escribo?**
No. Cada palabra se analiza en tu Mac. En [Privacidad](#privacidad) está la breve lista de lo que
sí sale del equipo.

**¿Puedo seguir cambiando la distribución a mano?**
Sí. Doble pulsación de Shift por defecto, o elige en su lugar Control, Option, Command, ⌃Space,
⌘Space o ⌥⌘Space.

## Privacidad

Tus pulsaciones se analizan en tu Mac y nunca se transmiten. Rekey no tiene cuenta, ni
sincronización, ni procesamiento de texto en un servidor.

Cuatro cosas pueden salir del equipo, y nada más:

1. **La comprobación de actualizaciones** — la app pregunta a la web si hay una versión más
   reciente.
2. **Un único aviso de instalación** — un solo mensaje al terminar la pantalla de bienvenida, que
   registra qué permisos concediste y si completaste la configuración. No lleva ningún
   identificador, ni siquiera uno aleatorio, así que las instalaciones no se pueden distinguir
   entre sí ni contar dos veces.
3. **Informes de fallos** — en las versiones beta, activados por defecto y desactivables en
   Ajustes.
4. **Tu dirección de correo** — solo si la escribes durante la configuración y marcas una casilla.

Texto completo: [Política de privacidad](https://trishchuk.com/rekey/privacy.html) (en inglés).

## Comentarios

Los comentarios sobre la beta van en [Issues](../../issues): errores, correcciones indebidas, un
idioma que puntúa mal. Si Rekey estropeó una palabra que debería haber dejado en paz, es lo más
útil que puedes reportar: incluye la palabra, las dos distribuciones y la app en la que estabas
escribiendo.

[Cómo informar de un problema](https://trishchuk.com/rekey/es/feedback/) explica qué incluir. Las
nuevas incidencias parten de una de tres plantillas: **Bug report** (informe de error),
**Language not detected well** (idioma mal detectado) e **Idea or feedback** (idea o
comentario). Los problemas de seguridad van por un informe privado; consulta
[SECURITY.md](SECURITY.md).

## Sobre este repositorio

Rekey no es de código abierto por ahora. Este repositorio existe para las versiones publicadas y
el seguimiento de incidencias; el código fuente está en otro sitio. La app es gratuita y se
distribuye como compilación firmada y notarizada directamente desde
[trishchuk.com/rekey](https://trishchuk.com/rekey/es/).

Hay otras apps que se llaman Rekey. Esta la hace Taras Trishchuk y solo se publica en
[trishchuk.com/rekey](https://trishchuk.com/rekey/es/) y en este repositorio.

---

[Sitio web](https://trishchuk.com/rekey/es/) · [Privacidad (en inglés)](https://trishchuk.com/rekey/privacy.html)

[English](README.md) · [Українська](README.uk.md) · [Deutsch](README.de.md) · [Polski](README.pl.md) · [Español](README.es.md) · [Français](README.fr.md) · [Nederlands](README.nl.md) · [Ελληνικά](README.el.md) · [Türkçe](README.tr.md) · [עברית](README.he.md) · [العربية](README.ar.md)
