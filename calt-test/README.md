## Motivation
- Feature request opened in MonaLisa font: https://github.com/MonoLisaFont/feedback/issues/191
- Demonstrate differences between MonaLisa font and FiraCode font in Kitty with `disable_ligatures cursor` set.

## Steps performed
- The source was modified to print ligatures converted to calt in [calt.clj](../clojure/fira_code/calt.clj)
- Executed
```
clj -Sverbose -m fira-code.main
```
- Parsed/formatted output:
  - [calt-ligatures.txt](./calt-ligatures.txt) format: `Name | Symbols | Ligatures`
  - [calt-names.txt](./calt-names.txt) format: `Name`
  - [calt-symbols.txt](./calt-symbols.txt) format: `Symbols | Ligatures`

## Demo (Kitty with `disable_ligatures cursor` set)
### FiraCode Calt Demo
[FiraCode Calt Demo](https://user-images.githubusercontent.com/10135646/213957329-e9d1863b-f2fd-47d0-9555-5d9af00e9461.mov)
### MonaLisa Calt Demo
[MonaLisa Calt Demo](https://user-images.githubusercontent.com/10135646/213957342-77d2d04b-78b6-4e4c-961c-78c4c4c60ec4.mov)

