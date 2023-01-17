
# yo-theme-helix

A [Helix][helix] theme inspired by [Zenbones][zenbones] &
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
    principles of the theme.
    
### Screenshots

| **yo_dark** | **yo_light** |
|:-:|:-:|
| ![yo_dark](https://user-images.githubusercontent.com/4220099/212813139-25b402b9-d069-4852-8bf6-991fa315d028.png) | ![yo_light](https://user-images.githubusercontent.com/4220099/212813150-2487a515-9144-47be-a2d0-b4e06cdc15da.png) |

[helix]: https://helix-editor.com/
[zenbones]: https://github.com/mcchrish/zenbones.nvim
[alabaster]: https://github.com/tonsky/vscode-theme-alabaster
[radix]: https://www.radix-ui.com/colors
