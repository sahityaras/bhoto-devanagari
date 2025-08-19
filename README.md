# Bhoto Devanagari
Bhoto devanagari font is a derivative of Noto devanagari, licensed under the SIL Open Font License. It contains BhotoSansDevanagari and BhotoSerifDevanagari. It doesnot have BhotoSansDevanagariUI. 

Till now, modification are only made to the OpenType features. No new Glyphs are added. 


## Building
(As given in the README.md of Noto Devanagari)

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at https://notofonts.github.io/devanagari.

For information on how to work on Noto fonts, how the build process
works and how to maintain it, see [the README file of the
notofonts.github.io
repository](https://github.com/notofonts/notofonts.github.io/blob/main/README.md)

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at
https://scripts.sil.org/OFL
