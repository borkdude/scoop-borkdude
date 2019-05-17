# borkdude's scoop-bucket

This repo provides easy installation of
[clj-kondo](https://github.com/borkdude/clj-kondo/) on Windows in the form of a
[scoop](https://scoop.sh/) bucket.

## Add bucket

    scoop bucket add borkdude https://github.com/borkdude/scoop-bucket

## Install clj-kondo

    scoop install clj-kondo

You can now use `clj-kondo`:

``` shellsession
C:\>echo (inc) | clj-kondo --lint -
<stdin>:1:1: error: wrong number of args (0) passed to clojure.core/inc
linting took 8ms, errors: 1, warnings: 0
```

## Upgrade clj-kondo

    scoop update clj-kondo
