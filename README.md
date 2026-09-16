# DeepSeek original PRG

Private preservation repository for the supplied `deepseek_asm.prg` binary.

The exact CBM PRG is retained unchanged. It loads at `$0801` and its BASIC
stub invokes `SYS 4608` (`$1200`). The matching corrected v9 source variants
are maintained in the separate private repositories
`deepseek-asm-v9-logo-grad-scroller-acme` and `deepseek-asm-v9-logo-grad-scroller-segfix`.

This repository is intentionally binary-focused: `AUDIT.md` documents the
header, entry point, checksum, and source/build relationship without rewriting
the supplied release artifact.
