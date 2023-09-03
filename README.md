# setup-espanso

[中文版](README-zh.md)

Lacewing's [Espanso](https://espanso.org) setup.

## Usage
[Espanso](https://espanso.org) allows you to use system-wide snippets.
Of course they are customizable and configurable.
Read [the documentation](https://espanso.org/docs/get-started/) to get started.

This repo contains Lacewing's personal setup Espanso setup.
You can expect **general snippets** such as date and time.
Moreover, there are snippets for **writing**, for **gaming**, specifically for **Terraria** and **tModLoader**, or simply for **fun**.
Some of the snippets are only written for **Simplified Chinese** at this point (translations are welcomed).

To use those snippet, you can scan through the `trigger`s, `triggers`s and `regex`s or use Espanso's search bar (<kbd>Alt</kbd>/<kbd>Opt</kbd> + <kbd>Space</kbd>) to get an idea of the snippets.
If you want only a part of these snippets, or a deviated version of them, feel free to modify them.
Also, the [documentation](https://espanso.org/docs/get-started/) is always there!

## Prerequisites
- having [Espanso](https://espanso.org) installed
- some snippets require additional shell commands, search `ALERT` in this repo for more information

## Installation
1. clone this repo to `~/.config/espanso/`
2. make sure you have imported the configs to Espanso in `base.yml`
   ```yml
   imports:
     - "~/.config/espanso/"
   ```
3. read the config files and profit!
