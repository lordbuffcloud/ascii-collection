```
                    _ _                  _ _           _   _
   __ _ ___  ___(_|_)   ___ ___ | | | ___  ___| |_(_) ___  _ __
  / _` / __|/ __| | |  / __/ _ \| | |/ _ \/ __| __| |/ _ \| '_ \
 | (_| \__ \ (__| | | | (_| (_) | | |  __/ (__| |_| | (_) | | | |
  \__,_|___/\___|_|_|  \___\___/|_|_|\___|\___|\__|_|\___/|_| |_|
```

# ASCII Collection

A curated library of one-line ASCII art, kaomoji, figlet banners, and box/border glyphs. Built for quick lookup, copy-paste, and terminal art.

**Scope note:** this collection deliberately focuses on what renders reliably across machines. That means single-line art (kaomoji, emoticons, weapon glyphs, table flips), figlet output generated from canonical fonts, and Unicode box drawing. It does **not** include freehand multi-line scenes (cats, ships, castles, etc.) because reproducing those accurately from memory is unreliable, and the alternative (scraping copyrighted artist work) is something this repo does not do. If you want a multi-line cat, generate it with `figlet`, `cowsay`, or `boxes`, or browse a curated archive that has explicit permissions in place.

## Structure

| Folder | Contents |
|---|---|
| [13-banners-figlet](13-banners-figlet/) | 20 figlet fonts × 20 sample words, generated with pyfiglet 1.0.4 |
| [14-borders](14-borders/) | ASCII and Unicode boxes, frames, dividers |
| [15-text-faces](15-text-faces/) | happy, sad, angry, love, kaomoji |
| [16-misc](16-misc/) | hearts, arrows, flags, symbols (single-line only) |
| [17-oneliners](17-oneliners/) | 1000+ single-line ASCII art and kaomoji across 60+ themed sections |

## Usage

Every file is plain UTF-8 text. Grab a piece with:

```bash
cat 17-oneliners/oneliners.txt
```

Pipe a chunk to your clipboard:

```bash
sed -n '15,30p' 13-banners-figlet/slant.txt | clip     # Windows
sed -n '15,30p' 13-banners-figlet/slant.txt | pbcopy   # macOS
sed -n '15,30p' 13-banners-figlet/slant.txt | xclip    # Linux
```

Pair the one-liners with [espanso](https://espanso.org/) text expansion to wire them up to triggers like `:lenny` and `:flip`.

## Generate your own banners

```bash
pip install pyfiglet
python -c "import pyfiglet; print(pyfiglet.figlet_format('hello', font='slant'))"
```

pyfiglet ships with 500+ fonts. List them with `python -c "import pyfiglet; print('\n'.join(pyfiglet.FigletFont.getFonts()))"`.

## Fonts and rendering

ASCII art only renders correctly in a **monospace font** (Cascadia Mono, Consolas, Menlo, Fira Code, JetBrains Mono, DejaVu Sans Mono). Many one-liners use Japanese / Cyrillic / extended Latin glyphs and need a font with broad Unicode coverage.

GitHub renders `.txt` files in a monospace viewer when you click through, so everything here looks right in-browser.

## Licensing

See [LICENSE](LICENSE) and [ATTRIBUTION.md](ATTRIBUTION.md). Originals are CC0. Figlet output is generated from public-domain font definitions. Kaomoji and emoticons are folklore commons that have circulated on Usenet, BBSes, and IRC for decades.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
