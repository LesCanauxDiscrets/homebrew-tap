# Homebrew Options Tap

This repository contains Homebrew “formulae” that include options, which Homebrew project maintainers [removed][] as of Homebrew version 2.0. It is a fork of the Justin MAYER one;

For the moment, this repository consists of a single formula: FFmpeg

## Installation

If the formula has already been installed from homebrew-core, you will first need to uninstall it:

    brew uninstall ffmpeg

Then look at the formula source and choose which options you want — the options shown below are only examples. Then install via:

    brew tap LesCanauxDiscrets/tap
    brew tap-pin LesCanauxDiscrets/tap
    brew install ffmpeg --with-aom --with-chromaprint --with-fdk-aac --with-libass --with-srt

Alternatively, you can install the formula by naming it explicitly:

    brew install ffmpeg --with-aom --with-chromaprint --with-fdk-aac --with-libass --with-librsvg --with-libsoxr --with-tesseract --with-libvidstab --with-libvmaf --with-rtmpdump --with-srt --with-webp --with-zvbi


[removed]: https://github.com/Homebrew/homebrew-core/issues/31510
