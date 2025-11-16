This repo includes a list fo handy tools. Most of them are implemented in rust.

## Text Processing
[exa](https://github.com/ogham/exa) - ls alternative

[ripgrep](https://github.com/BurntSushi/ripgrep) - fast alternative to grep

[bat](https://github.com/sharkdp/bat) - cat alternative with colored outputs

[xsv](https://github.com/BurntSushi/xsv) - handle CSV files `xsv table` to tabulate outputs

[sd](https://github.com/chmln/sd) - sed alternative, e.g. `echo "sample with /path/" | sd '.*(/.*/)' '$1'`, much eaiser than `sed`: `echo "sample with /path/" | sed -E 's|.*(/.*/)|\1|g'`

[cat](https://github.com/sstadick/hck) - cat alternative

[jless](https://jless.io) - JSON viewer, similar to [fx](https://github.com/antonmedv/fx) but faster.

[jnv](https://github.com/ynqa/jnv) - interactive JSON filter using jq (requires clang to build).

[huniq](https://github.com/koraa/huniq) - replacement for `sort|uniq` and it is much faster.

[sk](https://github.com/lotabout/skim) - fuzzy finder, a rust implementation of fzf. 

[gron](https://github.com/TomNomNom/gron) - Make JSON greppable!


## File Processing
[fd](https://github.com/sharkdp/fd) - find alternative `cargo install fd-find`

[diskus](https://github.com/sharkdp/diskus) - a parallel version of `du -sh`

[crabz](https://github.com/sstadick/crabz) - gzip parallel compression/decompression tool 

[onefetch](https://github.com/o2sh/onefetch) - command-line Git information tool

[xleak](https://github.com/bgreenwell/xleak)) - A fast terminal Excel viewer with an interactive TUI


## Data Processing
[histoterm](https://github.com/zhanxw/histoterm) - Draw histogram in terminal

[visidata](https://www.visidata.org) - VisiData is an interactive multitool for tabular data

[textql](https://github.com/dinedal/textql) - Execute SQL against structured text like CSV or TSV




## Programming Related
[hexyl](https://github.com/sharkdp/hexyl) - a hex viewer

[git-cliff](https://github.com/orhun/git-cliff) - generate git changelogs

[tokei](https://github.com/orhun/git-cliff) - count lines of codes

## System Utilities
[hyperfine](https://github.com/sharkdp/hyperfine) - simple benchmark tool
