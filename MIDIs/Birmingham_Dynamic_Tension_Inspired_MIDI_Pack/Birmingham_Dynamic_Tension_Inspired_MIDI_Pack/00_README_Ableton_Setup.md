# Birmingham / Dynamic Tension Inspired MIDI Pack

Pack MIDI original para Ableton Live inspirado en rasgos generales de techno británico, Birmingham techno,
Counterbalance/Dynamic Tension-era pressure, loops secos, percusión metálica, bajo funcional y mutaciones lentas.

Importante: el contenido es original. No contiene samples, audio, melodías copiadas ni transcripciones exactas
de temas concretos. Está pensado como gramática de trabajo: groove, densidad, disposición rítmica y estructuras.

## Tempo

Todos los MIDI están a 136 BPM, 4/4, resolución 480 PPQ.

## Cómo usarlo en Ableton

1. Crea una pista MIDI con Drum Rack.
2. Mapea el Drum Rack con la tabla de abajo.
3. Arrastra los archivos de `01_`, `02_`, `03_` o `04_` a clips MIDI.
4. Para los archivos `full_groove_` y `arrangement_`, Ableton puede importar varias pistas: una para Drum Rack y otra para bajo.
5. Usa loop en clips de 8 compases para los grooves.
6. En los arreglos de 64/128 compases, usa los marcadores como guía estructural.

## Mapeo Drum Rack recomendado

| Nota MIDI | Nombre práctico | Uso |
|---:|---|---|
| 36 / C1 | Kick | Kick principal seco y duro |
| 37 / C#1 | GhostKick | Ghost kick o trigger de rumble |
| 38 / D1 | SnareIndustrial | Snare seco/industrial |
| 39 / D#1 | DryClap | Clap seco y corto |
| 40 / E1 | LowTom | Tom/percusión grave |
| 41 / F1 | MetalHit1 | Golpe metálico/FM |
| 42 / F#1 | ClosedHat | Hat cerrado |
| 43 / G1 | NoisePerc | Ruido/percusión procesada |
| 44 / G#1 | MetalHit2 | Segundo golpe metálico |
| 45 / A1 | Impact | Impacto o golpe de transición |
| 46 / A#1 | OpenHat | Hat abierto/offbeat |
| 47 / B1 | RideNoise | Ride o hat ruidoso |

## Notas de bajo

Las líneas de bajo usan canal MIDI 1 y notas graves alrededor de F1, Eb1, Gb1 y C2. Funcionan mejor con:
- sinte mono,
- filtro bajo,
- glide corto opcional,
- saturación/distorsión,
- sidechain fuerte contra el kick,
- envolvente corta para los patrones `bass_*`,
- cadena de reverb/delay filtrada para los patrones `rumble_*`.

## Tratamiento recomendado

### Kick
Corto, seco, con cuerpo. Si usas rumble, que el MIDI active una cadena separada, no el mismo kick.

### Hats
No los cuantices todos a la misma velocity. Este pack ya trae velocities desiguales. Funciona bien con saturación ligera, EQ agresiva y decay corto.

### Percusión metálica
Los archivos con `5step`, `7step` o `polyrhythm` están pensados para que el patrón parezca desplazarse aunque el proyecto siga en 4/4.

### Bajo
Evita hacerlo demasiado melódico. La intención es presión, rozamiento tonal y empuje, no hook.

## Estructura sugerida de tema

- 0:00 Intro con kick + hats mínimos.
- 1:00 Entra percusión metálica desplazada.
- 2:00 Entra bajo corto o rumble.
- 3:00 Mutación de hats y filtrado.
- 4:00 Break con kick fuera o filtrado.
- 4:30 Re-entry.
- 6:00 Outro DJ-friendly.

## Carpetas

- `01_LaReal_Counterbalance`: loops más rectos, secos y funcionales.
- `02_MidnightClub`: grooves compactos, nocturnos, club.
- `03_BadHands`: patrones más rotos, industriales y agresivos.
- `04_Fills`: transiciones, rolls y re-entradas.
- `05_Arrangements`: esqueletos completos de 64 y 128 compases.
- `06_Bonus`: herramientas de layering y polirritmia.
