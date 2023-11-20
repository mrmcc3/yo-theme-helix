# yo-theme-helix

[Helix][helix] themes inspired by [Zenbones][zenbones] &
[Alabaster][alabaster]. Uses [Radix Colors][radix].

### Notes

- Ideas from alabaster.
  - Comments should stand out.
  - Use color sparingly. The rules should be simple.
    - avoid font variants where possible.
- Alabaster essentially only higlights comments/constants and strings. 
  - It doesn't highlight keywords (reserved words) or types. (which to be fair isn't really an issue for
  clojure)
  - Yo doesn't go quite as far on this point.
  - Instead it takes the minimal zenbones approach to highlight the remaining code.
    - subtle colors & contrast.
    - vibrant colors are left for diagnostics.
- The default yo themes use the following:
  - **Green** for strings (same as alabaster)
  - **Purple** for constant (same as alabaster)
  - **Blue** for info (comments & LSP info/hints)
  - **Red/Amber** LSP error/warnings
  - **Gray/Bronze** Everything else zenbones style
- I'm not a designer and don't like my chances of making something look good by
  tweaking colors so instead i'll let the pros handle it.
  - [Radix Colors][radix] are very well deisgned. with clear instructions for
    how to apply them.
  - Designed for **automatic light/dark mode**.
- Variants.
  - It should be straightforward to use helix theme inheritance to swap out the
    default color palette with other radix color combinations without losing the
    principles of the theme. (see the berry variant)
- If you find languages that aren't highlighted nicely or have a suggestion for
  improvements please open an issue.

### Changes

#### 2023-11-21

- Update colors to radix colors 3.0
- Add a new default theme. Move the old default to yo_sand with some color tweaks
    
### Screenshots

| **yo** | **yo_light** |
|:-:|:-:|
|<img width="698" alt="yo" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/0566f2bb-47ae-4cd9-a07d-e4aca7e77800">|<img width="700" alt="yo_light" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/d5158316-94ca-4b52-949f-eda71550c8fe">|

| **yo_berry** | **yo_berry_light** |
|:-:|:-:|
|<img width="699" alt="yo_berry" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/a405d474-0619-4880-813f-803119b8b0e1">|<img width="701" alt="yo_berry_light" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/41271dc3-7afe-455c-a6a0-a4917708347a">|

| **yo_sand** | **yo_sand_light** |
|:-:|:-:|
|<img width="697" alt="yo_sand" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/d19f95f1-5faa-44e0-be66-394c1e659d6a">|<img width="699" alt="yo_sand_light" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/9737acfb-3811-4060-a44e-8550c458c864">|

[helix]: https://helix-editor.com/
[zenbones]: https://github.com/mcchrish/zenbones.nvim
[alabaster]: https://github.com/tonsky/vscode-theme-alabaster
[radix]: https://www.radix-ui.com/colors
