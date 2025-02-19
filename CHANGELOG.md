
0.5.0 / 2019-09-07
==================

### Formatting changes

  * convert tabs to spaces (#143)

## Features

  * add --explain mode to expose the engine rewrite decisions (#142)

### Other

  * replace #[macro_use] extern crate with modern syntax (#141)
  * incorporate recent rnix renamings (#144)
  * nix: use naersk so hashes are always up to date (#145)

0.4.0 / 2019-08-31
==================

### Formatting changes

* Don't force newline before ++ anymore (#139)
* Always indent concatenated lists
* Add line break after comment in list

### Features

* Add ability to print syntax tree in JSON format
* Format directories out of the box. Eg: `nixpkgs-fmt .`
* Refactor input handling, makes formatting 4x faster

### Changes

* Add test to make sure the output is idempotent

### Other

* BREAKING: Remove the --in-place flag

0.3.1 / 2019-08-23
==================

  * fix the release process

0.3.0 / 2019-08-23
==================

  * First lambda arg is on the line with brace

0.2.0 / 2019-08-23
==================

First release!
