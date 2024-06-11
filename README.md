# eu4-diffs

## Table of Contents

[1.36.2-1.37.1](https://eu4diffs.iscccc.eu.org/1.36.2-1.37.1/)

[1.30.4-1.36.2](https://eu4diffs.iscccc.eu.org/1.30.4-1.36.2/)

## Previous versions diffs

For diffs of previous versions ( 1.34.2,1.34.3,1.34.4,1.34.4,1.35.0,1.35.1,1.35.2,1.36.0,1.36.1,1.36.2 ), you may check out [eu4-diffs by maxice8](https://maxice8.github.io/eu4-diffs/).

## How to generate?

Inspired by [eu4-diffs](https://maxice8.github.io/eu4-diffs/), I try to use ```git diff``` & [diff2html](https://github.com/rtfpessoa/diff2html) to generate it.

Commands eg:

```cmd
git diff HEAD^ map/ > 1.diff | diff2html -i file -o stdout -- 1.diff > 1.html
```
