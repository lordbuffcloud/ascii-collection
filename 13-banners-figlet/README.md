# Banners and Figlet Fonts

Each file contains 20 sample words rendered in one figlet font. **All output here was generated with [pyfiglet](https://github.com/pwaller/pyfiglet) 1.0.4 using the canonical font definitions** — these are not handwritten and they will render byte-perfect in any monospace font.

Sample words used for every font: `HELLO`, `WORLD`, `WELCOME`, `README`, `ASCII`, `BUILD`, `DEPLOY`, `READY`, `DONE`, `ERROR`, `OK`, `YES`, `NO`, `WIN`, `FAIL`, `PASS`, `DEBUG`, `WARN`, `INFO`, `404`.

| File | Font |
|---|---|
| [standard.txt](standard.txt) | standard |
| [slant.txt](slant.txt) | slant |
| [smslant.txt](smslant.txt) | smslant |
| [big.txt](big.txt) | big |
| [block.txt](block.txt) | block |
| [shadow.txt](shadow.txt) | shadow |
| [small.txt](small.txt) | small |
| [banner.txt](banner.txt) | banner3 |
| [doom.txt](doom.txt) | doom |
| [isometric.txt](isometric.txt) | isometric1 |
| [starwars.txt](starwars.txt) | starwars |
| [speed.txt](speed.txt) | speed |
| [cyberlarge.txt](cyberlarge.txt) | cyberlarge |
| [graffiti.txt](graffiti.txt) | graffiti |
| [bubble.txt](bubble.txt) | bubble |
| [digital.txt](digital.txt) | digital |
| [lean.txt](lean.txt) | lean |
| [ogre.txt](ogre.txt) | ogre |
| [rounded.txt](rounded.txt) | rounded |
| [chunky.txt](chunky.txt) | chunky |

## Generate your own

```bash
# CLI
figlet -f slant "your text here"
toilet -f mono12 "your text here"

# Python
pip install pyfiglet
python -c "import pyfiglet; print(pyfiglet.figlet_format('hello', font='slant'))"
```

pyfiglet ships with 500+ fonts. List them with `python -c "import pyfiglet; print('\n'.join(pyfiglet.FigletFont.getFonts()))"`.
