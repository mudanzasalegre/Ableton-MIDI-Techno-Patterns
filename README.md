# Ableton MIDI Techno Patterns

Colección de patrones MIDI, herramientas de arreglo y sonidos para producir techno en **Ableton Live**. Incluye grooves de batería, percusión, bajos, rumble triggers, sintetizadores, texturas, transiciones y clips de control MIDI CC, además de una librería de muestras WAV de Concrete Frequency.

Los documentos de los packs describen el material como original y generativo, inspirado en rasgos generales de techno hipnótico, industrial, Birmingham, warehouse, acid, dub y broken techno. Los nombres de artistas sirven como referencias estilísticas; no implican afiliación ni material oficial.

## Contenido de la colección

Inventario de esta versión:

| Contenido | Archivos |
|---|---:|
| MIDI en los 14 packs de `MIDIs/` | 10.318 |
| MIDI de prueba en los dos packs de `Samples/` | 16 |
| **Total MIDI** | **10.334** |
| WAV, incluyendo copias de kits y previews | 1.012 |
| Presets SFZ opcionales | 16 |
| Índices CSV | 19 |
| Índices y metadatos JSON | 21 |
| Guías Markdown de los packs | 36 |

El contenido de `MIDIs/` y `Samples/` ocupa aproximadamente **222 MiB** sin comprimir. Los recuentos corresponden a archivos presentes, no a sonidos únicos: los kits incluyen copias de muestras y el pack de kits reducido repite contenido de la librería completa.

Este repositorio distribuye archivos musicales y documentación. No incluye proyectos `.als`, Drum Racks `.adg`, plugins ni código fuente de los generadores.

## Descargar

Puedes usar **Code → Download ZIP** en GitHub y extraerlo, o clonar el repositorio:

```bash
git clone https://github.com/mudanzasalegre/Ableton-MIDI-Techno-Patterns.git
cd Ableton-MIDI-Techno-Patterns
```

En Windows, algunos nombres anidados producen rutas largas. Para clonar con soporte de rutas largas desde el principio:

```powershell
git clone -c core.longpaths=true https://github.com/mudanzasalegre/Ableton-MIDI-Techno-Patterns.git C:\Music\Ableton-MIDI-Techno-Patterns
```

Si ya tienes el repositorio y Git muestra `Filename too long`, ejecuta dentro de él:

```powershell
git config --local core.longpaths true
```

Una carpeta de destino corta también ayuda a otros programas y al descomprimir el ZIP. Los archivos MIDI y WAV se almacenan directamente en Git; esta versión no requiere Git LFS.

## Estructura

```text
Ableton-MIDI-Techno-Patterns/
├── README.md
├── .gitattributes
├── .gitignore
├── MIDIs/
│   └── <nombre_del_pack>/
│       └── <nombre_del_pack>/
│           ├── guías e índices
│           └── carpetas de patrones .mid
└── Samples/
    ├── Concrete_Frequency_Original_Techno_Sound_Library_V1/
    │   └── Concrete_Frequency_Original_Techno_Sound_Library_V1/
    │       ├── 01_SOUND_LIBRARY_WAV/
    │       ├── 02_ABLETON_24_PAD_STARTER_KITS/
    │       ├── 03_AUDIO_PREVIEWS/
    │       └── 04_MIDI_AUDITION_LOOPS/
    └── Concrete_Frequency_8_Ableton_Starter_Drum_Kits/
        └── Concrete_Frequency_Original_Techno_Sound_Library_V1/
            ├── 02_ABLETON_24_PAD_STARTER_KITS/
            ├── 03_AUDIO_PREVIEWS/
            └── 04_MIDI_AUDITION_LOOPS/
```

Se conserva el doble nivel de carpetas de los packs originales. Las guías específicas están dentro de la carpeta interior.

## Catálogo de packs MIDI

Los enlaces abren cada pack. Dentro encontrarás su guía de configuración y sus índices CSV/JSON.

| Pack | MIDI | Enfoque |
|---|---:|---|
| [Birmingham / Dynamic Tension](MIDIs/Birmingham_Dynamic_Tension_Inspired_MIDI_Pack/Birmingham_Dynamic_Tension_Inspired_MIDI_Pack/) | 27 | Grooves secos, percusión metálica, bajos y arreglos; 136 BPM |
| [Concrete Frequency Professional Loops V1](MIDIs/Concrete_Frequency_Professional_Techno_Loops_V1/Concrete_Frequency_Professional_Techno_Loops_V1/) | 7.800 | 100 identidades de kit, cuatro variantes, stems y MIDI multipista; 134–150 BPM |
| [Oscar Mulero Drums — Pack 01](MIDIs/Oscar_Mulero_Drums_Dark_Functional_Tools_Pack_01/Oscar_Mulero_Drums_Dark_Functional_Tools_Pack_01/) | 187 | Batería oscura y herramientas funcionales; tempo principal 136 BPM |
| [Oscar Mulero Low-End — Pack 02](MIDIs/Oscar_Mulero_Low_End_Rumble_Sub_Bass_Pulses_Pack_02/Oscar_Mulero_Low_End_Rumble_Sub_Bass_Pulses_Pack_02/) | 180 | Rumble triggers, sub, bajos y drones graves; tempo principal 136 BPM |
| [Oscar Mulero Mental Synths — Pack 03](MIDIs/Oscar_Mulero_Mental_Synths_Textures_Pack_03/Oscar_Mulero_Mental_Synths_Textures_Pack_03/) | 208 | Secuencias, stabs, FM y texturas; tempo principal 136 BPM |
| [Oscar Mulero Transitions — Pack 04](MIDIs/Oscar_Mulero_Transitions_Arrangements_Live_Mutations_Pack_04/Oscar_Mulero_Transitions_Arrangements_Live_Mutations_Pack_04/) | 267 | Transiciones, arreglos multipista, mutaciones y CC; tempo principal 136 BPM |
| [Oscar Mulero Ambient — Pack 05](MIDIs/Oscar_Mulero_Ambient_Experimental_Dark_Interludes_Pack_05/Oscar_Mulero_Ambient_Experimental_Dark_Interludes_Pack_05/) | 264 | Drones, interludios y material experimental; tempo principal 110 BPM |
| [Oscar Mulero Linear Hypnotic — Pack A](MIDIs/Oscar_Mulero_Linear_Hypnotic_Fast_Drums_Percussion_Pack_A/Oscar_Mulero_Linear_Hypnotic_Fast_Drums_Percussion_Pack_A/) | 301 | Batería y percusión lineal e hipnótica; tempo principal 140 BPM |
| [Oscar Mulero Linear Hypnotic — Pack B](MIDIs/Oscar_Mulero_Linear_Hypnotic_Fast_Drums_Percussion_Pack_B/Oscar_Mulero_Linear_Hypnotic_Fast_Drums_Percussion_Pack_B/) | 362 | Células rodantes, rim/clave y microvariaciones; tempo principal 142 BPM |
| [Surgeon Extended References V2](MIDIs/Surgeon_Extended_References_MIDI_Pack_V2/Surgeon_Extended_References_MIDI_Pack_V2/) | 29 | Grooves, arreglos largos y clips CC |
| [Techno Hi-Hats & Rides](MIDIs/Techno_HiHats_Rides_Cymbal_Groove_Extensive_MIDI_Pack/Techno_HiHats_Rides_Cymbal_Groove_Extensive_MIDI_Pack/) | 385 | Hats y rides con acentos y micro-swing; tempo principal 136 BPM |
| [Tensal Cyclic Modern V3](MIDIs/Tensal_Cyclic_Modern_Techno_MIDI_Pack_V3/Tensal_Cyclic_Modern_Techno_MIDI_Pack_V3/) | 28 | Batería, bajos, sintes cíclicos, arreglos y CC; 136 BPM |
| [Tensal Drums Only V4](MIDIs/Tensal_Drums_Only_Extensive_MIDI_Pack_V4/Tensal_Drums_Only_Extensive_MIDI_Pack_V4/) | 121 | Drums, percusión y arreglos largos; tempo principal 136 BPM |
| [Tensal Drums Only V5](MIDIs/Tensal_Drums_Only_Second_Extensive_MIDI_Pack_V5/Tensal_Drums_Only_Second_Extensive_MIDI_Pack_V5/) | 159 | Kick engines, top loops, warehouse, broken y fills; tempo principal 136 BPM |

## Empezar en Ableton Live

1. Descarga y extrae la colección. Añade la carpeta a **Places / Lugares** en el navegador de Live si quieres acceder a ella desde tus sets.
2. Elige un pack y lee su archivo `00_README_*.md` o `00_START_HERE.md` para conocer tempo, duración y mapeo de notas.
3. Crea una pista MIDI con un Drum Rack para batería, o un instrumento para bajos, sintes y texturas.
4. Arrastra un `.mid` a la pista. Para archivos multipista, prueba la importación en Arrangement View de un set vacío y asigna un instrumento a cada pista importada.
5. Ajusta el tempo del set según el nombre del archivo o su índice. Comprueba el inicio, final y longitud del loop en el editor de clips.
6. Combina patrones, ajusta velocities y alterna variaciones para construir tu propio arreglo.

**Un archivo MIDI necesita un instrumento para sonar.** Los patrones de rumble y sub disparan notas; debes asignarles un sampler, sintetizador o cadena de efectos adecuada. Los clips que contienen solo CC necesitan ruteo y asignación a parámetros compatibles.

### Concrete Frequency: trabajar por identidad de kit

La biblioteca de 7.800 MIDI contiene 19 categorías con 100 IDs de kit y cuatro variaciones (**7.600 loops de 8 compases**), más **200 loops de 16 compases**. Los IDs van de `K001` a `K100`.

- `A_CORE`: núcleo del patrón.
- `B_GROOVE`: acentos, ghost notes y movimiento.
- `C_PRESSURE`: mayor densidad.
- `D_TURNAROUND`: variación para cerrar o cambiar de frase.

Para empezar, abre `18_HYBRID_KITS_MULTITRACK` y busca, por ejemplo, `K004` con variante `B_GROOVE`. Importa el MIDI y asigna sonidos. Para sustituir capas, busca **el mismo ID y variante** en las carpetas individuales. El ID mantiene BPM y centro tonal coherentes dentro de la biblioteca.

Consulta [los 10 kits de inicio](MIDIs/Concrete_Frequency_Professional_Techno_Loops_V1/Concrete_Frequency_Professional_Techno_Loops_V1/00_10_STARTER_KITS.md), [el flujo de trabajo](MIDIs/Concrete_Frequency_Professional_Techno_Loops_V1/Concrete_Frequency_Professional_Techno_Loops_V1/00_ABLETON_PRO_WORKFLOW.md) y los índices `00_KIT_MATRIX_100.csv` y `00_LIBRARY_INDEX_7800.csv` para filtrar por estilo, tempo, familia y variante.

## Librería de samples y Drum Racks

| Pack | WAV | MIDI de prueba | SFZ | Contenido |
|---|---:|---:|---:|---|
| [Librería completa](Samples/Concrete_Frequency_Original_Techno_Sound_Library_V1/Concrete_Frequency_Original_Techno_Sound_Library_V1/) | 812 | 8 | 8 | 612 muestras de la librería, 192 copias para ocho kits y 8 previews |
| [Ocho starter kits](Samples/Concrete_Frequency_8_Ableton_Starter_Drum_Kits/Concrete_Frequency_Original_Techno_Sound_Library_V1/) | 200 | 8 | 8 | Los ocho kits de 24 pads y sus 8 previews, también incluidos en la librería completa |

Según la documentación del pack, los WAV son **PCM de 24 bits a 48 kHz**. Los one-shots son mono; las transiciones, drones y previews pueden ser estéreo. El catálogo completo incluye duración, canales y métricas de nivel.

### Montar un kit de 24 pads

1. Crea una pista MIDI e inserta un **Drum Rack** vacío.
2. Abre un kit de `02_ABLETON_24_PAD_STARTER_KITS`.
3. Selecciona sus **24 WAV en orden numérico**, excluyendo el `.sfz`.
4. Arrástralos al pad de **nota MIDI 36** (C1 en la nomenclatura usada por la guía de Live).
5. Comprueba que los samples ocupan las notas **36–59** usando `00_24_PAD_KIT_MATRIX.csv`.
6. Importa el loop del mismo kit desde `04_MIDI_AUDITION_LOOPS` y escucha su preview en `03_AUDIO_PREVIEWS`.
7. Guarda el Drum Rack como `.adg` desde Live si quieres reutilizarlo.

La guía de la librería propone este mapeo. Revisa también la guía del pack MIDI que uses, ya que algunas notas tienen funciones específicas:

| MIDI | Sonido | MIDI | Sonido |
|---:|---|---:|---|
| 36 | Kick | 48 | Rim |
| 37 | Ghost / Rumble | 49 | FM Zap |
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

Los números MIDI evitan ambigüedades entre programas con distinta nomenclatura de octavas. Los presets SFZ son opcionales para reproductores compatibles de terceros; la guía del pack indica que Live no los carga de forma nativa y propone usar los WAV en Drum Rack.

Consulta la [guía de samples en Ableton](Samples/Concrete_Frequency_Original_Techno_Sound_Library_V1/Concrete_Frequency_Original_Techno_Sound_Library_V1/00_ABLETON_SETUP.md) para bajos, afinación, mezcla y sidechain.

## Compatibilidad y problemas habituales

Los formatos `.mid` y `.wav` permiten usar el contenido en otros DAWs que los importen. Los flujos de trabajo de las guías se orientan a Ableton Live; no se incluye una certificación por versión o edición de Live. La disponibilidad de instrumentos como Operator o Wavetable depende de tu instalación; puedes asignar otros instrumentos compatibles.

| Problema | Qué revisar |
|---|---|
| El clip MIDI no suena | Asigna un instrumento y comprueba notas, salida MIDI y monitorización. |
| Suenan pads incorrectos | Comprueba el mapeo de la guía; usa números MIDI y la matriz del kit. |
| Un clip CC no dispara sonidos | Puede contener solo controladores. Configura su destino y el mapeo de parámetros. |
| El loop queda demasiado largo o corto | Revisa Loop Start/End y la duración indicada en el nombre o índice. |
| La importación crea varias pistas | Es un MIDI multipista; asigna instrumentos a las pistas necesarias. |
| El bajo o acid suena como un golpe aislado | Un one-shot necesita configuración de sampler; para legato, slide o cutoff dinámico usa un sinte adecuado. |
| Un patrón de rumble no produce rumble | Asigna el trigger a un sonido o cadena con reverb filtrada, saturación y ducking. |
| Aparece `Filename too long` en Git | Activa `core.longpaths` y utiliza una ruta de destino corta; consulta la sección Descargar. |

En Concrete Frequency, algunos clips usan `CC119 = 0` como anclas de inicio y final. Los loops de macros emplean CC70, CC71, CC74, CC76, CC91 y CC93; su efecto depende del instrumento y del ruteo. El swing, la dinámica y el resultado sonoro también dependen de los sonidos asignados.

## Originalidad y condiciones de uso

Consulta las notas de cada pack antes de utilizar o redistribuir su contenido:

- [Notas creativas de Birmingham](MIDIs/Birmingham_Dynamic_Tension_Inspired_MIDI_Pack/Birmingham_Dynamic_Tension_Inspired_MIDI_Pack/LEGAL_AND_CREATIVE_NOTES.md) y los archivos `LEGAL_AND_CREATIVE_NOTES.md` de las demás colecciones MIDI.
- [Originalidad y uso de Concrete Frequency MIDI](MIDIs/Concrete_Frequency_Professional_Techno_Loops_V1/Concrete_Frequency_Professional_Techno_Loops_V1/00_LICENSE_ORIGINALITY.md).
- [Notas creativas y de uso de los samples](Samples/Concrete_Frequency_Original_Techno_Sound_Library_V1/Concrete_Frequency_Original_Techno_Sound_Library_V1/00_CREATIVE_AND_LICENSE_NOTES.md).

Las notas describen MIDI generativos y WAV sintetizados sin muestras externas, y permiten transformar los MIDI e integrar los sonidos en producciones musicales. Las notas de samples piden evitar distribuir el pack íntegro como una librería exclusiva independiente. Este README resume esas notas; no añade una licencia global ni amplía sus permisos.

## Aportaciones

Puedes abrir un issue para comunicar problemas de importación, errores en índices o documentación. Incluye el pack, la ruta del archivo, el DAW y su versión, y los pasos para reproducirlo. Para proponer cambios, utiliza una rama y un pull request; mantén coherentes los nombres, las guías y los índices afectados.

Conserva los archivos MIDI y WAV como binarios. El archivo `.gitattributes` evita que Git aplique conversiones de fin de línea a estos formatos.
