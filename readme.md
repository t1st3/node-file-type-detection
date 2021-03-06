
> a list of file-type detection and extension-list modules for Node.js

## About

Modules named `is-*` are conventional detectors for the `file-type.*`. All these modules detect whether the file is of the expected type using Buffer/Uint8Array.

Modules named `*-extensions` are conventional lists of extensions for a category of file types, aggregated in a JSON file.

## Table of Contents

- [Generic](#generic)
- [Archive](#archive)
- [Image](#image)
- [Font](#font)
- [Audio](#audio)
- [Video](#video)
- [Other](#other)


## Generic

One detector to rule them all: this module detects many formats, using Buffer/Uint8Array. It is a generic module; if you want to detect a specific file type, please check below for more specific detectors.

- [file-type](https://github.com/sindresorhus/file-type)

## Archive

### Extension list

- [archive-extensions](https://github.com/sindresorhus/archive-extensions)

### Detectors

- [is-7z](https://github.com/t1st3/is-7z) (which is a duplicate of [is-7zip](https://github.com/kevva/is-7zip))
- [is-bzip2](https://github.com/kevva/is-bzip2)
- [is-gzip](https://github.com/kevva/is-gzip)
- [is-rar](https://github.com/kevva/is-rar)
- [is-tar](https://github.com/kevva/is-tar)
- [is-xz](https://github.com/kevva/is-xz)
- [is-zip](https://github.com/kevva/is-zip)

## Image

### Extension list

- [image-extensions](https://github.com/arthurvr/image-extensions)

### Detectors

- [is-bmp](https://github.com/sindresorhus/is-bmp)
- [is-gif](https://github.com/sindresorhus/is-gif)
- [is-ico](https://github.com/arthurvr/is-ico)
- [is-jpg](https://github.com/sindresorhus/is-jpg)
- [is-jxr](https://github.com/sindresorhus/is-jxr)
- [is-png](https://github.com/sindresorhus/is-png)
- [is-psd](https://github.com/sindresorhus/is-psd)
- [is-svg](https://github.com/sindresorhus/is-svg)
- [is-tif](https://github.com/sindresorhus/is-tif)
- [is-webp](https://github.com/sindresorhus/is-webp)
- [is-xcf](https://github.com/pskupinski/is-xcf)


## Font

### Detectors

- [is-eot](https://github.com/junmer/is-eot)
- [is-ttf](https://github.com/junmer/is-ttf)
- [is-woff](https://github.com/junmer/is-woff)
- [is-woff2](https://github.com/arthurvr/is-woff2)


## Audio

### Extension list

- [audio-extensions](https://github.com/olehkuchuk/audio-extensions)

### Detectors

- [is-flac](https://github.com/hemanth/is-flac)
- [is-m4a](https://github.com/hemanth/is-m4a)
- [is-mp3](https://github.com/hemanth/is-mp3)
- [is-ogg](https://github.com/hemanth/is-ogg)
- [is-opus](https://github.com/t1st3/is-opus)
- [is-wav](https://github.com/hemanth/is-wav)


## Video

### Extension list

- [video-extensions](https://github.com/sindresorhus/video-extensions)

### Detectors

- [is-avi](https://github.com/arthurvr/is-avi)
- [is-flv](https://github.com/arthurvr/is-flv)
- [is-mp4](https://github.com/deepak1556/is-mp4)
- [is-mkv](https://github.com/t1st3/is-mkv)
- [is-mov](https://github.com/arthurvr/is-mov)
- [is-webm](https://github.com/t1st3/is-webm)


## Other

### Detectors

- [is-epub](https://github.com/sindresorhus/is-epub)
- [is-exe](https://github.com/kevva/is-exe)
- [is-postscript](https://github.com/arthurvr/is-postscript)
- [is-pdf](https://github.com/kevva/is-pdf)
- [is-rpm](https://github.com/t1st3/is-rpm)
- [is-sqlite](https://github.com/1000ch/is-sqlite)
- [is-swf](https://github.com/kevva/is-swf)
- [is-torrent](https://github.com/hemanth/is-torrent)


## License

[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [t1st3](http://www.tiste.org) has waived all copyright and related or neighboring rights to this work.
