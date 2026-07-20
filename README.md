# CrossInk Fonts

This repository stores font assets used by [CrossInk](https://github.com/uxjulia/CrossInk) firmware.

## Repository Layout

- `cpfonts/` contains downloadable zip files for CrossInk fonts.
- `fonts/` contains a subset of source font files, only used by CrossInk to be served when downloading from the reader.

Each font family currently includes sizes `8`, `9`, `10`, `12`, `14`, `16`, `18`, and `20`.

## Available Fonts

- Alegreya
- AtkinsonHyperlegibleNext
- Bitter
- ChareInk
- Domitian
- GentiumBookPlus
- IBMPlexMono
- IBMPlexSans
- IBMPlexSerif
- Inter
- Lexend Deca
- LexicaUltralegible
- LibreBaskerville
- Literata
- Lora
- Merriweather
- NotoSansExtended
- NotoSerifExtended
- OpenDyslexic
- SourceCodePro
- SourceSans3
- SourceSerif4
- Tinos
- Vollkorn

## Adding a Font

1. Download the `.zip` for the font you want
2. Unzip it and place the font folder into `.fonts` or `fonts` on your SD card, example: `E:/.fonts/Bitter/` where the contents would be: `E:/.fonts/Bitter/Bitter_10.cpfont`, etc.

## Notes

- Keep spaces in family names only when CrossInk expects that exact display name, such as `Lexend Deca`.
