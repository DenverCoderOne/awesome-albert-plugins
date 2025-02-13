# Awesome Albert Plugins

<a href="https://travis-ci.com/bergercookie/awesome-albert-plugins" alt="Build Status">
<img src="https://travis-ci.com/bergercookie/awesome-albert-plugins.svg?branch=master"></a>
<a href="https://www.codacy.com/manual/bergercookie/awesome-albert-plugins">
<img src="https://api.codacy.com/project/badge/Grade/dbefc49bb5f446488da561c7497bb821"/></a>
<a href=https://github.com/bergercookie/awesome-albert-plugins/blob/master/LICENSE alt="LICENCE">
<img src="https://img.shields.io/github/license/bergercookie/awesome-albert-plugins.svg" /></a>
<a href="https://github.com/psf/black">
<img alt="Code style: black" src="https://img.shields.io/badge/code%20style-black-000000.svg"></a>

## Description

This is a collection of plugins and themes for the
[Albert](https://albertlauncher.github.io/) launcher.

## Demos

| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/emoji/misc/demo0.png) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/emoji/misc/demo1.png) |
| :----------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------: |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/jira/misc/demo-basic.png) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/taskwarrior/misc/demo.gif) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/anki/misc/anki.gif) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/anki/misc/anki0.png) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/misc/albert-suggestions-demo.gif) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/misc/albert-suggestions-demo2.gif) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/misc/errno_lookup.png) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/misc/ipshow.png) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/pulse_control/misc/pulse-demo1.png) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/pulse_control/misc/pulse-demo2.png) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/misc/albert-suggestions-demo3.gif) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/colors/misc/colors1.png) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/timezones/misc/demo1.png) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/killproc/misc/demo0.png) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/words/misc/demo0.png) | ![](https://raw.githubusercontent.com/bergercookie/awesome-albert-plugins/master/misc/tldr.gif) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/harakiri/misc/demo0.png) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/image_search/misc/demo0.png) |
| ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/meme_generator/misc/demo.gif) | ![](https://github.com/bergercookie/awesome-albert-plugins/blob/master/plugins/clock/misc/clock.png) |

## Plugins

Currently the list of plugins includes:

- Anki card generator: Generate Basic, Basic-Reverse and Cloze cards for [Anki](https://apps.ankiweb.net/)
- Bluetooth - Enable/disable the bluetooth module
- Meme-generator: Generate memes and copy them directly to clipboard for easy
  paste
- Image_search: Search, preview and directly copy-to-clipboard images from the web
- Harakiri - Create temporary email addresses at [harakirimail.com](https://harakirimail.com/)
- Words - Get the definition, synonyms and antonyms for a word
- Emoji - Quickly lookup and copy emojis to your clipboard
- Killproc - Kill process(es); allows killing multiple processes with the same
  name or based on a glob - Improved version of the original albert plugin
- Timezones - Fuzzy-search timezones
- Colors - Lookup the RGB triplet or the hex code for the given color
- Jira - Issue Tracking
- Saxophone - Listen to internet Radio Streams
- Zoopla - Search Property to Buy, Rent, House Prices
- Xkcd - Fetch xkcd comics like a boss
- Taskwarrior - Interact with Taskwarrior
- Remmina - Search and start remmina connections easily
- Google Maps - Fetch instructions from/to a specific place
- Google Translate - Improved version of original albert plugin - avoids
  occasional IP blocking by Google
- [TL;DR](https://github.com/tldr-pages/tldr) pages lookup
- Get 2FA codes using [totp-cli](https://github.com/bergercookie/totp-cli)
- Lookup HTTP URL status codes
- Lookup errno status codes
- Show Internal, External IPs, Default Gateways
- Suggestions-enabled search using [googler](https://github.com/jarun/googler) on a variety of websites. For example:

  - Google
  - Amazon
  - Youtube
  - Github
  - Ebay
  - Imdb
  - Urban dictionary: Word/Slang definitions lookup
  - Python, OpenCV, Dlib, C++ documentation lookup
  - ...
  - :warning: To avoid getting blocked by Google, a search request is only sent
    when there is a 0.3 seconds difference between keystrokes. Thus, it's
    common when you actually want to send a request to wait a bit and then
    append a space character at the end of the query.

  - Install `google-chrome` or `chromium-browser` to add an "Open in incognito
    mode" option

- PulseAudio - Select pulseaudio input/output devices, sound card profiles
- Improved implementations of the original `Pass`, `Pomodoro` plugins
- Create stopwatches and countdowns

Plugins have been tested with the Albert python `v0.4` interface. If you're
looking for a version that works with earlier versions of the plugin, see the
`prior-to-v0.4` branch. I'm using Python `3.6.8`.

### Themes

- [Mozhi](https://github.com/Hsins/Albert-Mozhi) - A flat, transparent and dark
  theme for Albert.
  ([DEMO](https://github.com/Hsins/Albert-Mozhi/blob/master/demo/demo.gif))

## Motivation

It's really so easy writing plugins and automating parts of your workflow using
Albert and its python extensions. That's the very reason I started writing them.

## Installation

Requirements:

- Linux (tested on Ubuntu)
- Albert - [Installation instructions](https://albertlauncher.github.io/docs/installing/)
  - Albert Python Interface: `v0.4`

Clone this repository under your local Albert python plugins directory. By
default the that is: `~/.local/share/albert/org.albert.extension.python/modules`.

Then go to the Albert settings and enable the plugins that you are interested in
using. Beware that you may need to install some more dependencies depending on
the plugins you use. These dependencies will probably be pointed out either when
you enable, or when you run the plugin for the first time. Refer to the
directory of the corresponding plugin for more details.

### `Googler`-based plugins

The search plugins that use googler have not been committed to this repo. You
can generate them offline using the `create_googler_plugins.py` script provided.
Make sure you have Python >= 3.6 installed:

```
pip3 install --user --upgrade secrets requests googler cookiecutter
./create_googler_plugins.py
```

This will generate an Albert plugin for each one of the search engines specified
in `create_googler_plugins.py`. Adjust the latter as required if you want to
add more or remove plugins.

```py
generate_plugins_only_for = [
    "alternativeto",
    "amazon",
    "askubuntu",
    "aur.archlinux",
    ...
    ]
```

### I don't want to setup all the plugins, just a few

Very well, then after cloning this repo, just symlink or copy the plugin of
choice under your local python plugins directory. For example for the `jira`
plugin:

```sh
cp -r plugins/jira ~/.local/share/albert/org.albert.extension.python/modules/jira
```

After that, enable the plugin from the Albert settings.

## Self Promotion

If you find this tool useful, please [star it on
Github](https://github.com/bergercookie/awesome-albert-plugins)

## TODO List

See [ISSUES list](https://github.com/bergercookie/awesome-albert-plugins/issues) for the things
that I'm currently either working on or interested in implementing in the near
future. In case there's something you are interesting in working on, don't
hesitate to either ask for clarifications or just do it and directly make a PR.

### Ideas List (feel free to contribute)

- :construction: Giphy - https://github.com/Giphy/giphy-python-client
- :construction: Devdocs.io/Zeal/Dash search
- :construction: Manage your VPN connections - Frontend to `WireGuard`?
- :construction: Spotify mini player - similar to [this](https://github.com/vdesabou/alfred-spotify-mini-player)
- :construction: [Radio Paradise player](https://radioparadise.com/player)
  - Sign-in - grab password from `pass` as in `Jira` plugin
  - Ability to mark as favorite / change stream
- :construction: Movie search and ratings - be able to sign in to various
  services and (e.g., imdb) and submit a rating for a movie
- :construction: An alternative to [Alfred's pkgman](https://github.com/willfarrell/alfred-pkgman-workflow)
- :construction: Vagrant start/stop boxes - see [this](https://github.com/m1keil/alfred-vagrant-workflow)
- :construction: Assembly instructions lookup - use [this](https://github.com/asmjit/asmdb)
  - Use googler asynchronously to get links to pages: `adcs site:developer.arm.com`
