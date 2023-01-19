# Rokkit
by Vernon Adams

![Sample Image](documentation/image1.png)

Rokkitt is a Free Software Slab Serif font family.

![Sample Image](documentation/image2.png)
![Sample Image](documentation/image3.png)

# Completed tasks:
- Updated version number to V3.000
- Added vertical metrics
- Ran tidied up paths
- Tidied up master compatilibity. This still needs further work
- Add instances
- Fix glyphs, anchors and components

# Todo:
- Improve README.md
- Add TRADEMARKS.md

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you particularly want to build fonts manually on your own computer, you will need to install the [`yq` utility](https://github.com/mikefarah/yq). On OS X with Homebrew, type `brew install yq`; on Linux, try `snap install yq`; if all else fails, try the instructions on the linked page.

Then:

* `make build` will produce font files.
* `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
* `make proof` will generate HTML proof files.

## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at
http://scripts.sil.org/OFL

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.