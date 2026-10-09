# CONCRETE FREQUENCY — TECHNO LOOP LIBRARY V1

**Original hybrid techno loop library**, conceived as a modular companion to the previous full MIDI EP. This is NOT an album of songs: all clips loop over 8 or 16 bars.

## Alcance real

- **100 kits/identidades rítmicas** con la misma numeración K001 a K100 en todas las carpetas.
- **19 categorías x 100 kits x 4 variaciones = 7.600 MIDI** de 8 compases.
- **200 MIDI extra** de 16 compases para evolución de kit, disponibles en `20_EXTENDED_16BAR_LIVE_LOOPS/`.
- **7.800 archivos MIDI** en total, más guías e índices CSV/JSON.
- Formato **SMF1, 480 PPQ, 4/4**; se usan `LOOP_START`, `PHRASE_B`, `LOOP_END`, tempo y marcadores en conductor.
- 10 arquetipos musicales originales: warehouse, broken rave, acid, Detroit, industrial, 2-step, rave peak, hipnótico, dub y break emotivo.
- Tempos entre **134 y 150 BPM** según cada kit.
- Sin audio, presets, samples, plugins, .als ni sonidos incorporados.

## Variaciones por kit

- `A_CORE`: núcleo sobrio de 8 compases, con aire para combinar pistas.
- `B_GROOVE`: más ghost notes, acentuación, hats y movimiento.
- `C_PRESSURE`: más densidad y empuje de pista.
- `D_TURNAROUND`: transición discreta y acentos concentrados al terminar frase.

Las variaciones son **datos MIDI diferentes**, no copias con el BPM cambiado.

## Cómo usarlo en Ableton Live — en menos de un minuto

1. Abre `18_HYBRID_KITS_MULTITRACK` y elige un kit, por ejemplo `K042` variación `B_GROOVE`.
2. Ajusta el BPM indicado en el nombre. Arrastra el `.mid` al compás 1 de Arrangement View en un set vacío; Live puede importar las pistas por separado.
3. Asigna sonidos a cada pista con los instrumentos de tu librería (Drum Rack, Sampler, Operator, Wavetable, etc.).
4. Usa la pista de CC solo si tienes ruteadas esas macros; de lo contrario, ignórala.
5. Para más control, prueba `17_DRUM_STACKS_MULTITRACK` o abre las carpetas 01–16 y arrastra los stems individuales con **el mismo código K042 y la misma variación**.
6. Repite una frase, alterna `A_CORE` / `B_GROOVE` / `C_PRESSURE` y coloca `D_TURNAROUND` al final; así creas una estructura sin depender de canciones ya compuestas.

## Compatibilidad de familias

Cada ID K001–K100 usa el mismo **BPM, centro tonal y vocabulario rítmico** en todas las carpetas. Ejemplo:
- `K042` kick, hats, percusión, bajo, acid y stab encajan con sus correspondientes `K042`.
- También puedes cruzar IDs a mano; comprueba BPM/tonalidad cuando mezcles instrumentos tonales.
- Las carpetas 17 y 18 incluyen MIDI multipista, NO audio. Pueden contener varias pistas independientes dentro de un `.mid`.

## Cómo encontrar lo que buscas

Abre `00_KIT_MATRIX_100.csv` para filtrar por estilo y tempo; abre `00_LIBRARY_INDEX_7800.csv` para conocer cada archivo, familia, variante y número de notas.

## Advertencias técnicas

- Las pistas de `08_RUMBLE_SUB_TRIGGERS` son **triggers MIDI**, no un rumble renderizado. Necesitan sampler o cadena con reverb filtrada, saturación y ducking.
- `11_ACID_303` necesita un sintetizador monofónico resonante y automatización para sonar acid. No hay preset incluido.
- `19_MACRO_CC_LOOPS` tiene CC70, CC71, CC74, CC76, CC91 y CC93; **no controlarán automáticamente** efectos o macros si no están mapeados.
- MIDI usa ticks/duraciones y velocidades; groove final depende del instrumento y del sonido asignado.
- Muchos clips MIDI contienen dos mensajes `CC119 = 0` para preservar inicio/final del bucle durante la importación; son anclas inocuas y pueden borrarse.
- El grid está preparado para 480 PPQ. El swing sutil se aplica selectivamente a hats y percusiones, no al bombo principal.
- Los pads 41–59 son un **mapeo custom de Drum Rack**, no todos corresponden al General MIDI típico.
- Para techno denso, prueba un Drum Group con las pistas 01–08 y mutea `07_BREAKBEAT_SHUFFLE` si ya tienes un kick recto; algunos kits multipista ya evitan ese solapamiento.

## Originalidad

Los MIDI son generativos y originales, basados en rasgos amplios de techno warehouse, breakbeat, acid, Detroit, rave e industrial; no son transcripciones de canciones ni pretenden reproducir grabaciones identificables de ningún artista.
