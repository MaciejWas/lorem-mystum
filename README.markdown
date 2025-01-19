# lorem-mystum

## Introduction

*Lorem MySTum* is a [lorem ipsum] generator for [MyST] flavour of the markdown language.

[lorem ipsum]: http://www.lipsum.com/
[markdown]: http://daringfireball.net/projects/markdown/
[myst]: https://mystmd.org/

## Credit

This is a modified version of [Lorem Markdownum](https://github.com/jaspervdj/lorem-markdownum) authored by [Jasper Van der Jeugt](https://github.com/jaspervdj)

## Building and running from source

- Install [stack](https://docs.haskellstack.org/en/stable/install_and_upgrade/).
- Issue `stack build --copy-bins` to build the project.  This will put the
  executable in `~/.local/bin`.
- Use `mkdir log` to ensure that directory exists.
- Run using e.g. `lorem-markdownum-web 127.0.0.1 8080`.
