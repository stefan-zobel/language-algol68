# Changelog

## 0.3.0

First version as a repository of its own. Before, the grammar was part of
[a68j](https://github.com/stefan-zobel/a68j), where it is still generated.

- One grammar for UPPER stropping (Revised Report, Algol 68 Genie 3.5.9,
  ga68 with `-fstropping=upper`) and SUPPER stropping (ga68, a68j). The
  first word that tells the two apart decides the regime for the whole file.
- Checked token by token against the scanner of a68j, which follows ga68.
- VS Code: brackets and indentation for the reserved words in both
  regimes (`begin`/`end` and `BEGIN`/`END`, ...).
