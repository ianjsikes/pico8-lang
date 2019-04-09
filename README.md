# pico8-lang

This extension adds language support for lua files to be used in [PICO-8][1] by lexaloffle.

The PICO-8 fantasy console uses lua with some small changes. [This gist][2] by josefnpat covers the differences from Lua 5.2.

By default, PICO-8 code is written directly in the `.p8` file produced by the program. However, it is possible to write
this code in regular `.lua` files and copy it into the `.p8` file manually or with a build tool. Here are some good build tools you can use:

- [pico-build][3] - a very basic build script I wrote that supports PICO-8's built-in editor tabs.
- [picotool][4] - a collection of tools for manipulating PICO-8 carts. Supports `require()` which some may prefer over the standard file concatenation approach.
- [picobu][5] - a simple build tool that supports a watch mode.

## Known Issues

## Release Notes

### 0.0.1

Initial release of `pico8-lang`

[1]: https://www.lexaloffle.com/pico-8.php
[2]: https://gist.github.com/josefnpat/bfe4aaa5bbb44f572cd0
[3]: https://github.com/ianjsikes/pico-build
[4]: https://github.com/dansanderson/picotool
[5]: https://github.com/Divoolej/picobu
