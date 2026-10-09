# ABLETON — RECETA DE USO PROFESIONAL

## Opción 1: arrastre inmediato multipista

1. Busca el archivo `Kxxx_*_B_GROOVE_08BAR.mid` en `18_HYBRID_KITS_MULTITRACK`.
2. En Live, abre Arrangement View y pon el tempo del kit. Importa en la primera barra de un set vacío.
3. Ableton admite SMF1 multipista, aunque su comportamiento exacto al arrastrar puede variar entre versiones.
4. Asigna Drum Racks a pistas de percusión y sintes a pistas tonales. Los clips no contienen sonidos.
5. Loop 8 bars (o arrastra el bloque de 16 en la carpeta 20) y construye arreglos propios.

## Opción 2: stems por pista

- `01_KICK_ENGINES` -> Drum Rack o Sampler kick (MIDI 36 y ghost 37)
- `02_SNARE_CLAP_RIM` -> Drum Rack snare/clap/rim (38,39,48)
- `03_CLOSED_TIGHT_HATS` -> Drum Rack hats 42 y 52
- `04_OPEN_HATS_RIDES` -> open hat 46 y ride 47
- `05_METALLIC_PERCUSSION` -> 41,44,48,43,50,55
- `06_TOMS_LOW_BODY` -> 40,58
- `07_BREAKBEAT_SHUFFLE` -> Drum Rack 36,38,42,48 (puede sustituir al kick 4x4)
- `08_RUMBLE_SUB_TRIGGERS` -> Drum Rack 37 y 56 con otra cadena de efectos
- `09_SUB_BASS` -> Operator mono (root grave)
- `10_ROLLING_BASS` -> Wavetable/Operator mono
- `11_ACID_303` -> sintetizador monofónico resonante
- `12_MONO_SYNTH_PULSES` -> sintetizador mono percusivo
- `13_RAVE_CHORD_STABS` -> instrumento polifónico
- `14_FX_NOISE_SIGNALS` -> Drum Rack dedicado a 45,49,53,55,57,59
- `15_DRONES_ATMOSPHERES` -> pads/granular/analog synth
- `16_FILLS_REENTRIES` -> Drum Rack de fills (mejor superponer sobre otro groove)
- `17_DRUM_STACKS_MULTITRACK` -> estructura multipista de drums, sin elementos tonales
- `18_HYBRID_KITS_MULTITRACK` -> drums, bass/synth y CC en un archivo
- `19_MACRO_CC_LOOPS` -> MIDI CC sólo; routear controles según dispositivo

Todos los stems de igual kit ID tienen su **bar 1** y longitud completa de 8 compases. Los silencios están previstos.

## Modelo de construcción de un tema de 6–7 minutos (sin que el pack lo imponga)

- 0–16: A_CORE (kick + hats + poco metal)
- 16–48: B_GROOVE (bajo progresivo)
- 48–80: C_PRESSURE (abre ride, añade break/acid)
- 80–96: strip (quita kick y bajo, deja texturas)
- 96–128: B_GROOVE o C_PRESSURE
- 128–160: alterna acid, rave stabs, breaks y groove
- 160–192: C_PRESSURE con fills D_TURNAROUND cada 16 compases
- 192–224: outro por sustracción

Solo es una receta. Los archivos del ZIP siguen siendo **loops, no temas precompuestos**.

## Recomendaciones para sonar convincente

- Usa acentos de velocity pero considera qué hace la velocity en cada sampler.
- Kick, rumble y sub deben ocupar funciones distintas. Controla fases y sidechain.
- Filtra toda la percusión metálica que no deba competir con el low end.
- Automatiza filtros, decay, envíos y panoramas en Live aunque ya tengas MIDI CC.
- Si un loop está cargado, quita antes un elemento de añadir otro. En techno, el silencio cuenta.
