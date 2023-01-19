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
    
### Screenshots

| **yo** | **yo_light** |
|:-:|:-:|
|![yo](https://user-images.githubusercontent.com/4220099/213587637-47feb9cb-16f1-4a0e-998d-5e684321a6b6.png)|![yo_light](https://user-images.githubusercontent.com/4220099/213587651-824ab69b-9c67-49d4-b045-cd17b540fb2f.png)|

| **yo_berry** | **yo_berry_light** |
|:-:|:-:|
|![yo_berry](https://user-images.githubusercontent.com/4220099/213587643-8cdf4995-cb78-44f4-a0f4-a1221d59bb22.png)|![yo_berry_light](https://user-images.githubusercontent.com/4220099/213587646-d4141b57-322d-4e1f-9d43-1d33e755bc96.png)|


[helix]: https://helix-editor.com/
[zenbones]: https://github.com/mcchrish/zenbones.nvim
[alabaster]: https://github.com/tonsky/vscode-theme-alabaster
[radix]: https://www.radix-ui.com/colors
