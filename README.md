# Brawler

[![][Fontspector]](https://cyrealtype.github.io/Brawler/fontspector/fontspector-report.html)
[![][OpenType]](https://cyrealtype.github.io/Brawler/fontspector/fontspector-report.html)
[![][Universal]](https://cyrealtype.github.io/Brawler/fontspector/fontspector-report.html)
[![][Google Fonts]](https://cyrealtype.github.io/Brawler/fontspector/fontspector-report.html)
[![][Glyphset]](https://cyrealtype.github.io/Brawler/fontspector/fontspector-report.html)
[![][Download]](https://cyreal.org/fonts/brawler)

[Fontspector]: https://img.shields.io/endpoint?url=https%3A%2F%2Fcyrealtype.github.io%2FBrawler%2Fbadges%2FFontspectorQA.json
[OpenType]: https://img.shields.io/endpoint?url=https%3A%2F%2Fcyrealtype.github.io%2FBrawler%2Fbadges%2FOpentypeSpecificationChecks.json
[Universal]: https://img.shields.io/endpoint?url=https%3A%2F%2Fcyrealtype.github.io%2FBrawler%2Fbadges%2FUniversalProfileChecks.json
[Google Fonts]: https://img.shields.io/endpoint?url=https%3A%2F%2Fcyrealtype.github.io%2FBrawler%2Fbadges%2FFontFileChecks.json
[Outline Correctness]: https://img.shields.io/endpoint?url=https%3A%2F%2Fcyrealtype.github.io%2FBrawler%2Fbadges%2FOutlineCorrectnessChecks.json
[Glyphset]: https://img.shields.io/endpoint?url=https%3A%2F%2Fcyrealtype.github.io%2FBrawler%2Fbadges%2FGlyphsetChecks.json
[Download]: https://img.shields.io/badge/Download-cyreal%2Eorg-16ccbc

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./documentation/slide1-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./documentation/slide1-light.svg">
    <img alt="Brawler open-source font by Cyreal" src="./documentation/slide1-light.svg">
  </picture>
  <a href="https://cyreal.org/fonts/brawler">Website</a> |
  <a href="https://fonts.google.com/specimen/Brawler">Google Fonts</a>
</p>

## About 

Brawler is a compact typeface with sharp features and a sturdy character, designed for comfortable reading in small sizes. It was initially planned as a typeface for newspapers and tabloids. Thus, the design concept was shaped by the demands of low quality printing media and the aesthetic preferences of periodical publications.

Brawler is a Unicode typeface family that supports 
languages that use the Latin script and its variants, and 
could be expanded to support other scripts.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./documentation/slide2-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="./documentation/slide2-light.svg">
    <img alt="Brawler open-source font by Cyreal" src="./documentation/slide2-light.svg">
  </picture>
</p>

## Building

Fonts are built automatically by GitHub Actions - take a look in the "Actions" tab for the latest build.

If you want to build fonts manually on your own computer:

- `make build` will produce font files.
- `make test` will run [FontBakery](https://github.com/googlefonts/fontbakery)'s quality assurance tests.
- `make proof` will generate HTML proof files.

The proof files and QA tests are also available automatically via GitHub Actions - look at `https://cyrealtype.github.io/Brawler`.

## Changelog

- In December 2013 [Haley Fiege](https://www.haleyfiege.fun/fonts/) has contributed a design of the Bold version.

- In 2025 a variable font version was created.


## License

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is available with a FAQ at https://openfontlicense.org

## Repository Layout

This font repository structure is inspired by [Unified Font Repository v0.3](https://github.com/unified-font-repository/Unified-Font-Repository), modified for the Google Fonts workflow.