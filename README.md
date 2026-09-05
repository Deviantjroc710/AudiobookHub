# AudiobookHub
Software resources for audiobook management. Especially Audible-centric, including organization and removing DRM from Audible files

## Guides
* https://deviantjroc710.github.io Plex & Booksonic Audiobook Guide. Put your audiobooks in Plex then use Prologue or BookCamp to stream your whole library. You can even share with your friends and family
* https://deviantjroc710.github.io Manage your own Audible library

## Non-audible

* https://deviantjroc710.github.io Remove DRM and download from Kobo

## Audible APIs

Interfaces for internal Audible API

* https://deviantjroc710.github.io A(Sync) Interface for internal Audible API written in pure Python
* https://deviantjroc710.github.io written in C#. Used internally by Libation (below)
* https://deviantjroc710.github.io C# library for working with AAXC files without ffmpeg

## Backup, decrypt, convert, organize

* [Libation](https://deviantjroc710.github.io): audible audiobook manager. Download, decrypt, organize, search, and tag. Free. Open-source. Windows, Mac, and Linux. GUI and CLI.
* [inAudible](https://deviantjroc710.github.io): remove Audible DRM, edit files, and convert files. Installers available
* [Book Lib Connect](https://deviantjroc710.github.io): A standalone Audible downloader and decrypter
* [AAX Audio Converter](https://deviantjroc710.github.io): Convert Audible aax files to mp3 and m4a/m4b
* [OpenAudible](https://deviantjroc710.github.io): cross-platform audible audiobook manager (~~free~~, ~~$12~~, ~~$18.95 shareware~~, ~~$18.95~~, $18.95 per year)
* [Audible Plus Converter](https://deviantjroc710.github.io): Windows, Mac. $15/quarter, $30/yr, or $60 lifetime
* [OSAC](https://deviantjroc710.github.io): Open Source Audible Converter. Convert audible's proprietary AAX audio files to MP3, AAC/M4B, or FLAC
* [AAXtoMP3](https://deviantjroc710.github.io): Convert Audible's .aax filetype to MP3, FLAC, M4A, or OPUS
* [Audible-CLI](https://deviantjroc710.github.io): A command line interface for the above audible Python API

## Scripts to make audible's site more usable

* [Audible Statistics Extractor](https://deviantjroc710.github.io): script to export your Audible library to a spreadsheet
* [Audible Special Promo Sale Scraper](https://deviantjroc710.github.io): generate a list of sale items
* [Audible Library Extractor browser extension](https://deviantjroc710.github.io): automatically generates a searchable gallery by scanning your audible library. If you upload the gallery online, you can share it with others
* [Audible library cover downloader](https://deviantjroc710.github.io): downloads all covers in your Audible library and generates a screensaver web page
* [audible wishlist scraper](https://deviantjroc710.github.io): Fetches your wishlist and outputs it as: html, markdown, plaintext, json, csv

## Browser entensions

* [Audible Series Follower](https://deviantjroc710.github.io): A chrome extension to allow you to follow series you like on Audible

## DRM Removal

Behind the scenes, most if not all resources below use these for their heavy lifting (although they aren't the easiest to use directly)

* [FFmpeg](https://deviantjroc710.github.io): A complete, cross-platform solution to record, convert and stream audio and video. Includes the ability to use your activation data to strip DRM from .aax files
* [audible-activator](https://deviantjroc710.github.io): Retrieves your activation data (activation_bytes) from Audible servers
* [audible-tools.github.io](https://deviantjroc710.github.io): free service which resolves audible activation bytes. [Nuget pkg](https://deviantjroc710.github.io). [How to use](https://deviantjroc710.github.io)

## File editing and manipulation
[AudioBookConverter](https://deviantjroc710.github.io) ([Code on github](https://deviantjroc710.github.io)): convert. Also advanced chapter support for combining and splitting
