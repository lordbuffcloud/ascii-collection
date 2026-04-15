# One-Liners

Single-line ASCII art and kaomoji you can drop anywhere: chat, commit messages, code comments, terminal banners, espanso replacements, status updates.

| File | Contents |
|---|---|
| [oneliners.txt](oneliners.txt) | 500+ one-liners across 30+ themed sections (faces, creatures, combat, magic, programmer) |
| [oneliners-vol2.txt](oneliners-vol2.txt) | 500+ more across new themes (winking, dev/git, hacker, RPG, chess, chemistry, zodiac, weather, progress bars, dividers, building blocks) |

## Sections

- Classic emoticons (`:)`, `:D`, `:P`)
- Classic sad (`:(`, `T_T`, `;_;`)
- Kawaii happy (`(^_^)`, `\(^o^)/`, `(◕‿◕)`)
- Sad / crying (`(╥﹏╥)`, `(´;ω;`)`)
- Angry / mad (`(ಠ_ಠ)`, `凸(￣ヘ￣)`)
- Love / hearts / kisses (`<3`, `(♥ω♥)`, `(˘⌣˘)♡`)
- Cool / smug / shades (`(⌐■_■)`, `(¬‿¬)`)
- Lenny face variants (`( ͡° ͜ʖ ͡°)` and friends)
- Disapproval / judgment (`ಠ_ಠ`, `ಠ_ರೃ`)
- Confused / wat (`(◎_◎;)`, `(´д｀)`)
- Surprised / shock (`(°o°)`, `∑(O_O；)`)
- Sleepy / dead / tired (`(=_=)`, `(x_x)`, `(@_@)`)
- Hug / wave / greet (`(づ｡◕‿‿◕｡)づ`, `(￣ω￣)ﾉ`)
- Cats (`=^.^=`, `(=^･ｪ･^=)`, `ฅ(•ㅅ•❀)ฅ`)
- Dogs (`U・ᴥ・U`, `ヽ(o^ω^o)ﾉ`)
- Bears (`ʕ•ᴥ•ʔ`, `ʕっ•ᴥ•ʔっ`)
- Fish and sea (`><(((°>`, `<コ:彡`)
- Birds / owls (`(•ө•)`, `(ʘᴥʘ)`)
- Rabbits / bunnies (`(\(\`, `(='.'=)`)
- Spiders / bugs (`/╲/\(•̀ ω •́)/\╱\`)
- Other animals
- Dragons / dinos
- Robots (`d[o_0]b`, `[¬º-°]¬`)
- Aliens / UFO
- Ghosts / skulls / dead
- Witches / wizards / magic (`(ﾉ◕ヮ◕)ﾉ*:･ﾟ✧`)
- Combat / fighting (`(ง •̀_•́)ง`, `ᕦ(ò_óˇ)ᕤ`)
- Weapons (`︻╦╤─`, `o==[]::::::::>`)
- Table flips (`(╯°□°)╯︵ ┻━┻`)
- Dance / party
- Run / move
- Music notes
- Hadouken / throwing (`༼つಠ益ಠ༽つ ─=≡ΣO))`)
- Flexing / strong
- Pray / thanks / bowing (`m(_ _)m`, `orz`)
- Celebration / win
- Sparkles / magic effects
- Hearts / love symbols
- Arrows / pointers
- Misc weird and cool
- Programmer / coder ones (with code comments)

## Use with espanso

The format here pairs naturally with [espanso](https://espanso.org/) text expansion. Example:

```yaml
matches:
  - trigger: ":lenny"
    replace: "( ͡° ͜ʖ ͡°)"
  - trigger: ":flip"
    replace: "(╯°□°)╯︵ ┻━┻"
  - trigger: ":bear"
    replace: "ʕ•ᴥ•ʔ"
```

## Note on rendering

Many of these use Japanese / Cyrillic / extended Latin glyphs. They render correctly anywhere that supports Unicode, which is basically everywhere modern. If you see boxes or `?` marks, your font lacks coverage for that glyph. Cascadia Code, Fira Code, JetBrains Mono, Noto Sans Mono, and DejaVu Sans Mono all handle these well.
