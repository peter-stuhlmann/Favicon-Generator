# Favicon Generator

[![MIT License](https://img.shields.io/github/license/peter-stuhlmann/Favicon-Generator.svg)](https://github.com/peter-stuhlmann/Favicon-Generator/blob/master/LICENSE)
![Code size](https://img.shields.io/github/languages/code-size/peter-stuhlmann/Favicon-Generator.svg)
[![open issues](https://img.shields.io/github/issues/peter-stuhlmann/Favicon-Generator.svg)](https://github.com/peter-stuhlmann/Favicon-Generator/issues?q=is%3Aopen+is%3Aissue)
[![closed issues](https://img.shields.io/github/issues-closed/peter-stuhlmann/Favicon-Generator.svg)](https://github.com/peter-stuhlmann/Favicon-Generator/issues?q=is%3Aissue+is%3Aclosed)

> Bash script that creates favicons and apple touch icons in multiple sizes from an image (.png and .ico).

## Syntax

To run this script you have to install [ImageMagick](https://imagemagick.org/) or make sure that it is already installed.

To only create the icons call the script and give your picture as the first argument. The dimensions of your picture should be at least 512x512 pixels.

`$ ./favicon.sh image.png`

You can also create a list with all tags of the created favicons with the flag `-x` as the second argument. A file favicons.txt will be created for this. You can simply insert the content of this file into the `<head>` of your html page.

`$ ./favicon.sh image.png -x`

## The following files will be created by this script

- favicon.ico _(16x16 32x32 64x64 96x96)_
- favicon-16x16.png _(16x16)_
- favicon-32x32.png _(32x32)_
- favicon-64x64.png _(64x64)_
- favicon-96x96.png _(96x96)_
- favicon-128x128.png _(128x128)_
- favicon-256x256.png _(256x256)_
- favicon-512x512.png _(512x512)_
- apple-touch-icon-152x152.png _(152x152)_
- apple-touch-icon-167x167.png _(167x167)_
- apple-touch-icon-180x180.png _(180x180)_

---

## License

Licensed under the [MIT](https://github.com/peter-stuhlmann/Favicon-Generator/blob/master/LICENSE) license by [Peter R. Stuhlmann](https://peter-stuhlmann-webentwicklung.de).
