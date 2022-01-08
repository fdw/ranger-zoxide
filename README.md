# Zsh & Ranger & Zoxide
This plugin for [zsh](https://www.zsh.org) adds just one shortcut, but unfolds the magic of both [Zoxide](https://github.com/ajeetdsouza/zoxide) and [ranger](https://github.com/ranger/ranger) 🧙
Without arguments, `r` just opens ranger. If you supply an argument that is a directory, ranger is opened in that directory. But if you supply anything else as an argument, `zoxide` is called with the argument and `ranger` is opened there. This is the efficiency you always wanted.

# Installation
Install the zsh plugin using your favorite plugin manager, for example [zgen](https://github.com/tarjoilija/zgen): `zgen load fdw/ranger_zoxide`.

# History
Peviously, this repository also contained a plugin for ranger to use Zoxide. This has now been merged with [ranger+zoxide](https://github.com/jchook/ranger-zoxide/), so check that out, too.
