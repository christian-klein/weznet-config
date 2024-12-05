# Install

Symlink .wezterm.lua from your home directory to here.
```
ln -s /Users/christian.klein/git/weznet-config/.config/wezterm/.wezterm.lua /Users/christian.klein/.wezterm.lua
```

Install monaspace font:

https://github.com/githubnext/monaspace

Mac, using homebrew:
```
brew install --cask font-monaspace
```

Install wezterm session manager:

https://github.com/danielcopper/wezterm-session-manager/tree/main

`git clone https://github.com/danielcopper/wezterm-session-manager.git ~/.config/wezterm/wezterm-session-manager`

Install wezterm.nvim:

https://github.com/aca/wezterm.nvim

Add to .bashrc/.zshrc:

```
[ -n "$WEZTERM_PANE" ] && export NVIM_LISTEN_ADDRESS="/tmp/nvim$WEZTERM_PANE"
```

.config/fish/config.fish

```
if not set -q $WEZTERM_PANE
  set -x NVIM_LISTEN_ADDRESS "/tmp/nvim$WEZTERM_PANE"
end
```

# Other installed items:

## lsd:

https://github.com/eza-community/eza

Add eza as alias for ls / l:
```
l='lsd -lAh --color=always'
ls='lsd -lAh --color=always'
```

## Lazydocker

## bat

https://github.com/sharkdp/bat

```
brew install bat

```
ln -s /Users/christian.klein/git/weznet-config/.config/bat/config /Users/christian.klein/.config/bat/config
```

```

## Mac:

```
brew install --cask font-monaspace
brew install helm p7zip tree watch neovim eza ncurses luajit tree-sitter git-gui lpeg openssl@3 ca-certificates lazydocker bat
```
### Other:

- gettext
- libtommath
- libvterm
- luv
- libunistring
- msgpack
- tcl-tk
- tcl-tk@8
- unibilium

Dot files sample:

https://github.com/TomDeneire/dotfiles

# Settings:

ctrl-click to follow links

[Cheat Sheet](CHEATSHEET.md)

