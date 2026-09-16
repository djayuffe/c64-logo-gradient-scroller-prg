# DeepSeek C64 v9 PRG

Private preservation repository for the supplied v9 `deepseek_asm.prg` image.

## Artifacts

- `deepseek_c64_v9.prg` — corrected rebuild from the audited v9 source.
- `original/deepseek_asm.prg` — exact supplied binary, preserved byte-for-byte.
- `source/deepseek_c64_v9_acme.s` — matching corrected source snapshot.

Both images are CBM PRGs loaded at `$0801` with `SYS 4608` (`$1200`). The
corrected image removes missing/unsupported charset inputs and uses explicit
charset placement. The original is never silently replaced.

## Verification

`AUDIT.md` records the original and corrected SHA-256 values. Run
`shasum -a 256 -c SHA256SUMS.txt` to verify all tracked files.
