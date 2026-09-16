# DeepSeek original PRG

Private preservation repository for the supplied `deepseek_asm.prg` binary.

The supplied CBM PRG is retained byte-for-byte in `original/`. The top-level
`deepseek_asm.prg` is the corrected rebuild from the matching v9 source and
loads at `$0801` with `SYS 4608` (`$1200`). The corrected source variants are
maintained in the separate private repositories
`deepseek-asm-v9-logo-grad-scroller-acme` and `deepseek-asm-v9-logo-grad-scroller-segfix`.

`AUDIT.md` documents the header, entry point, checksums, and source/build
relationship.
