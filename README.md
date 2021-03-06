# qlplayground
[![MIT Lincese](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE)

`qlplayground` is a QuickLook plugin for Swift files.

![preview](img/preview.png)
![thumbnail](img/thumbnail.png)

## Features
- Support `.playground` containing multiple pages
- Support `.swift`
- Support Preview and Thumbnail
- Syntax highlight by [Highlight.js](https://github.com/isagalaev/highlight.js)

## Requirements
- OS X 10.10.5 or later

## Installation

### Using [Homebrew Cask](http://caskroom.io)
```sh
brew cask install qlplayground
```

### Manual
1. Download [qlplayground.qlgenerator-0.2.zip](http://github.com/norio-nomura/qlplayground/releases/download/0.2/qlplayground.qlgenerator-0.2.zip) (2015/09/21 updated)
2. Unzip it
3. Move `qlplayground.qlgenerator` to `~/Library/QuickLook` folder
4. run `qlmanage -r` in `Terminal.app`

## Configuration
Change style to `dark`:
```sh
defaults write io.github.norio-nomura.qlplayground HighlightStyle dark
```

Style list is [here](http://github.com/norio-nomura/qlplayground/tree/master/qlplayground/highlight/styles/).

## Author

Norio Nomura

## License

`qlplayground` is available under the MIT license. See the LICENSE file for more info.
