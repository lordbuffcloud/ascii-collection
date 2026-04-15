```
                    _ _                  _ _           _   _
   __ _ ___  ___(_|_)   ___ ___ | | | ___  ___| |_(_) ___  _ __
  / _` / __|/ __| | |  / __/ _ \| | |/ _ \/ __| __| |/ _ \| '_ \
 | (_| \__ \ (__| | | | (_| (_) | | |  __/ (__| |_| | (_) | | | |
  \__,_|___/\___|_|_|  \___\___/|_|_|\___|\___|\__|_|\___/|_| |_|
```

# ASCII Collection

A curated, organized library of ASCII art covering animals, nature, space, tech, holidays, banners, borders, and more. Built for quick lookup, copy-paste, and terminal art usage.

## Structure

| Folder | Contents |
|---|---|
| [01-animals](01-animals/) | cats, dogs, birds, fish, bears, horses, reptiles, insects, rodents, wild |
| [02-nature](02-nature/) | trees, flowers, mountains, weather, landscapes |
| [03-space](03-space/) | planets, rockets, aliens, stars, ufos |
| [04-tech](04-tech/) | computers, phones, robots, gadgets, keyboards |
| [05-people](05-people/) | faces, figures, skulls, stick-figures |
| [06-food](06-food/) | fruit, drinks, meals, sweets |
| [07-vehicles](07-vehicles/) | cars, planes, ships, trains, bikes |
| [08-buildings](08-buildings/) | houses, castles, landmarks |
| [09-weapons](09-weapons/) | guns, swords, bombs |
| [10-holidays](10-holidays/) | christmas, halloween, easter, valentines, birthday |
| [11-music](11-music/) | instruments, notes |
| [12-sports](12-sports/) | balls, gear |
| [13-banners-figlet](13-banners-figlet/) | figlet-style text banners in multiple fonts |
| [14-borders](14-borders/) | boxes, frames, dividers |
| [15-text-faces](15-text-faces/) | kaomoji, emoticons, one-liners |
| [16-misc](16-misc/) | hearts, arrows, flags, symbols |
| [17-oneliners](17-oneliners/) | 500+ single-line ASCII art and kaomoji across 30+ themed sections |

## Usage

Every file is plain UTF-8 text. Grab a piece with:

```bash
cat 01-animals/cats.txt
```

Or pipe a chunk to your clipboard:

```bash
sed -n '15,30p' 13-banners-figlet/big.txt | clip     # Windows
sed -n '15,30p' 13-banners-figlet/big.txt | pbcopy   # macOS
sed -n '15,30p' 13-banners-figlet/big.txt | xclip    # Linux
```

## Fonts and rendering

ASCII art only renders correctly in a **monospace font** (Consolas, Cascadia Mono, Menlo, Fira Code, DejaVu Sans Mono, etc.). If a piece looks crooked, your renderer is using a proportional font.

GitHub renders `.txt` files in a monospace viewer automatically when you click through, so everything here should look right in-browser.

## Licensing

See [LICENSE](LICENSE) and [ATTRIBUTION.md](ATTRIBUTION.md).

Original pieces in this collection are released under **CC0 1.0 Universal** (public domain). Community-contributed or historical pieces with known authors carry their sigs inline and are included under fair-use curation with attribution preserved. If you are an artist and want a piece removed or re-credited, open an issue.

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
