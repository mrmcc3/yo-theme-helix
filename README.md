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
|<img width="710" alt="yo" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/11a18910-1a90-4196-bc8b-475ee8718b57">|<img width="717" alt="yo_light" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/9dc6eb1c-7464-41e8-9cce-00e9ac52532d">|

| **yo_berry** | **yo_berry_light** |
|:-:|:-:|
|<img width="698" alt="yo_berry" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/e87955b9-8328-4ec6-a390-90c241007541">|<img width="696" alt="yo_berry_light" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/0cf211f5-86ea-4d0b-a6ed-697a7d446030">|

| **yo_sand** | **yo_sand_light** |
|:-:|:-:|
|<img width="705" alt="yo_sand" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/4da47cbb-af45-484e-bfb5-7f7f81e96e5a">|<img width="696" alt="yo_sand_light" src="https://github.com/mrmcc3/yo-theme-helix/assets/4220099/5acd80ea-a678-4f52-b0eb-cdda2d0cfac9">|

[helix]: https://helix-editor.com/
[zenbones]: https://github.com/mcchrish/zenbones.nvim
[alabaster]: https://github.com/tonsky/vscode-theme-alabaster
[radix]: https://www.radix-ui.com/colors
