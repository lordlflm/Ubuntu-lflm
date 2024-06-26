# Ubuntu-lflm

## Install
Download [here](https://drive.google.com/file/d/1YhzVU6GGS2hdXN0GI8MahotBQTLKQkKn/view?usp=sharing)

Checksum is 3761449545afe283b12401ea02a79693

When booted, set up terminal preferences by running `p10k conmfigure`

## Shell
Default shell is `/bin/zsh` using `oh-my-zsh` framework configuration
Plugins are :
  - zsh-autosuggestions
  - zsh-syntax-highlighting
  - powerlevel10k

## Tmux
Using `gpakosz/.tmux` (oh my tmux) configuration

For exemple :
  - `<prefix>` is `ctrl + a`
  - `<prefix>-` to split pane horizontally
  - `<prefix>_` to split pane vertically
  - `<prefix>c` to create new session
  - `<prefix>2` to jump to session 2 (or mouse)

Mouse mode is enabled by default

See more key bindings by checking his github in the links section below

## Neovim
Using `nvim-lua/kickstart.nvim` configuration

Plugin manager is `folke/lazy.nvim` :
  - `:Lazy` to manage plugins
  - check github in the links section below

Manage LSPs :
  - `:Mason`, press `i` to install one

Filetree plugin is `nvim-neo-tree/neo-tree.nvim` :
  - open filetree with `space + a`
  - check github in the links section below

-- TODO : provide cheatsheet for this nvim setup's basic commands

## Some basic packages
- git
- cmake
- curl
- docker engine
- tmux
- neovim (aliased as vim)
- pip
- pwntools
- gdb peda
- rust

## Links
tmux config : https://github.com/gpakosz/.tmux

neovim config : https://github.com/nvim-lua/kickstart.nvim

Neotree : https://github.com/nvim-neo-tree/neo-tree.nvim

Lazy.nvim : https://github.com/folke/lazy.nvim

