# INSTALACIÓN EN ABLETON LIVE — CONCRETE FREQUENCY

## 1. Drum Rack: importación rápida de un kit

1. Abre Ableton Live y crea una pista MIDI.
2. Inserta un **Drum Rack** vacío.
3. Navega hasta `02_ABLETON_24_PAD_STARTER_KITS` y selecciona un kit.
4. Selecciona **los 24 archivos `.wav`** del kit en orden numérico (no selecciones el `.sfz`).
5. Arrastra la selección al pad **C1 / MIDI 36** del Drum Rack. Live distribuye los archivos seleccionados sobre pads cromáticamente ascendentes: 36, 37 ... 59.
6. Puedes guardar el Drum Rack terminado como preset `.adg` desde Live.
7. Para comprobar el kit, importa el MIDI de `04_MIDI_AUDITION_LOOPS` con el mismo nombre de kit. También puedes abrir cualquier MIDI de nuestros packs anteriores: las notas 36–59 coinciden con los pads.

**Importante**: la nomenclatura de octavas cambia entre algunos DAWs, por eso lo inequívoco es el número **MIDI 36**. Asegúrate de que la muestra `036_Kick.wav` caiga en MIDI 36 y `059_AirHit.wav` en MIDI 59.

## 2. Pistas de bajo, acid y rave

- Para usar un bass stab puntual, arrastra un WAV a Simpler y dispara el MIDI correspondiente. Ajusta la nota raíz si lo vas a tocar cromáticamente.
- Para un bajo real con legato, portamento o acid resonante, usa Operator, Wavetable o tu sintetizador favorito: estos one-shots son materia prima, no un preset completo que recree un 303.
- Los drones son estéreo; en mezcla controla el contenido grave y aplica sidechain si es necesario.

## 3. Compatibilidad MIDI

| Nota | Pad | Nota | Pad |
|---:|---|---:|---|
| 36 | Kick | 48 | Rim |
| 37 | Ghost/Rumble | 49 | FM Zap |
| 38 | Snare | 50 | Clave Metal |
| 39 | Clap | 51 | Shaker |
| 40 | Low Tom | 52 | Tight Hat |
| 41 | Metal Perc 1 | 53 | Reverse |
| 42 | Closed Hat | 54 | Click |
| 43 | Noise Perc | 55 | Scrape |
| 44 | Metal Perc 2 | 56 | Sub Trigger |
| 45 | Impact | 57 | Long Noise |
| 46 | Open Hat | 58 | Low Thump |
| 47 | Ride | 59 | Air Hit |

## 4. Mezcla recomendada

- Kick: ajusta tuning y longitud; analiza el bajo para evitar batidos muy fuertes.
- Rumble y sub: sidechain desde el kick; evita duplicar demasiado contenido por debajo de 100 Hz.
- Hats y ride: high-pass según el sonido, controla transitorios agudos y de-ess si es necesario.
- Metal y rims: puedes usar delays cortos y reverbs filtradas para generar movimiento sin ensuciar el bombo.
- FX y drones: automatiza volumen y filtros, utiliza panorama estéreo con moderación.
- Las demos WAV son ejemplos rápidos; no sustituyen a los MIDI ni son pistas terminadas.

## 5. Notas de compatibilidad

Los archivos `.sfz` son un **extra para reproductores SFZ de terceros**: Ableton Live no los carga nativamente. La vía nativa recomendada es arrastrar los WAV al Drum Rack, como se indica arriba.
