# AUDIO - Proyecto Musical

## Descripcion
Proyecto de produccion musical: remix de "Te Quedas" por Luciano (7 anos) y Gabriel (padre).
Genero: Trap emotivo/melodico.

## Estructura del Proyecto
- `*.aup` - Proyectos de Audacity (archivos pequenos, se commitean)
- `*_data/` - Datos de audio de Audacity (pesados, ignorados por git)
- `*.wav` / `*.mp3` - Pistas de audio descargadas (pesadas, ignoradas por git)
- `*.md` - Documentacion (letra, recursos, notas)

## Archivos Clave
- `TE-QUEDAS-REMIX.md` - Letra completa de la cancion
- `RECURSOS-BEATS-TRAP.md` - Fuentes de beats trap sin copyright
- `TE-QUEDAS-Beat-Emotional-Trap.wav` - Beat principal (no en git)
- `GROOVE-TechHouse-Beat.wav` - Beat alternativo tech house (no en git)

## Herramientas
- **Editor de audio**: Audacity (formato .aup)
- **Descarga de audio**: yt-dlp
- **Sistema**: Linux Mint

## Git
- Los archivos de audio (WAV, MP3) NO se commitean (superan limite de 100MB de GitHub)
- Los directorios `*_data/` de Audacity tampoco se commitean
- Solo se commitean: `.aup` (proyectos), `.md` (documentacion), `.gitignore`
- Repositorio: https://github.com/gabrielpantoja-cl/audio.git

## Workflow
1. Descargar beats con yt-dlp o desde sitios sin copyright
2. Importar WAV en Audacity
3. Editar/mezclar pistas
4. Grabar voces de Luciano y Gabriel
5. Exportar mezcla final
