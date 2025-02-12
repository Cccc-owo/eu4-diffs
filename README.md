# eu4-diffs

It is recommended to view the diffs locally.

## Table of Contents

[1.37.4-1.37.5](1.37.4-1.37.5)

[1.37.3-1.37.4](1.37.3-1.37.4)

[1.37.2-1.37.3](1.37.2-1.37.3)

[1.37.1-1.37.2](1.37.1-1.37.2)

[1.36.2-1.37.1](1.36.2-1.37.1)

[1.30.4-1.36.2](1.30.4-1.36.2)

## Previous versions diffs

For diffs of previous versions (1.34.2, 1.34.3, 1.34.4, 1.34.4, 1.35.0, 1.35.1, 1.35.2, 1.36.0, 1.36.1, 1.36.2), you may check out [eu4-diffs by maxice8](https://maxice8.github.io/eu4-diffs/).

## How to generate?

Inspired by [eu4-diffs](https://maxice8.github.io/eu4-diffs/), I try to use ```git diff``` & [diff2html-cli](https://github.com/rtfpessoa/diff2html-cli) to generate it.

Commands eg:

```cmd
git diff HEAD^ map/ > index.diff
diff2html -i file -F index.html -- index.diff
```
