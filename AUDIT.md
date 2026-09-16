# Audit record

- Artifact: `deepseek_asm.prg`
- Format: CBM PRG
- Load address: `$0801`
- BASIC entry: `SYS 4608` (`$1200`)
- Original SHA-256: `ae15601d57b7ca41be95570f46087f7a148a0ccea45b6fb3411a80749404fe7c`
- Corrected build SHA-256: `cb120e887fe74f7a9d2e4383ec1b3f38b34d2ef8bc5cfb2972583ae8a6346318`

The supplied image is preserved exactly under `original/`. Its matching v9 source was
audited separately: the corrected source emits two explicit charsets at
`$2000`/`$2800`, removes missing/unsupported input directives, and builds with
strict ACME checks. This binary-only repository does not silently replace the
original release image.
