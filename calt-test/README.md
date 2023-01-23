## Motivation
- Feature requrest opened in MonaLisa font: https://github.com/MonoLisaFont/feedback/issues/191
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
  - [calt-symbols.txt](./calt-symbols.txt)format: `Symbols | Ligatures`

## Demo
- FiraCode vs MonaLisa in Kitty with `disable_ligatures cursor` set
![calt-demo-firacode-vs-monalisa.mov](./calt-demo-firacode-vs-monalisa.mov)
