# My NeoVim Config


This is just a backup of my nvim config, feel free to use it yourself or adapt it to your needs.


## Installation

To setup everything you first need to install Vim-plug and the init.lua file in the correct locations. The commands bellow will do this for you.

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim

curl -fLo ~/.config/nvim/init.lua --create-dirs \
    https://raw.githubusercontent.com/CapinAhab/neovim-config/main/init.lua

```

To finish the installation open nvim and run the command `:PlugInstall` to install all plugins. The next time it launches everything should be installed and working correctly

## Plugins

- [Vimplug](https://github.com/junegunn/vim-plug)
- [Vim Sensible](https://github.com/tpope/vim-sensible)
- [Nvim Tree](https://github.com/nvim-tree/nvim-tree.lua)
- [Project](https://github.com/ahmedkhalf/project.nvim)
- [Auto pairs](https://github.com/jiangmiao/auto-pairs)
- [Plenary (Dependency for telescope)](https://github.com/nvim-lua/plenary.nvim)
- [Telescope](https://github.com/nvim-telescope/telescope.nvim)
- [Emmet](https://github.com/mattn/emmet-vim)
- [Nvim Cmp](https://github.com/hrsh7th/nvim-cmp)


## UI Plugins
- [Noice](https://github.com/folke/noice.nvim)
- [Dashboard](https://github.com/nvimdev/dashboard-nvim)
- [Treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [Tokyo Night Colour Scheme](https://github.com/folke/tokyonight.nvim)
- [Rose Pine Colour Scheme](https://github.com/rose-pine/neovim)
- [Indent Blankline](https://github.com/lukas-reineke/indent-blankline.nvim)
- [Nui (Dependency for noice)](https://github.com/MunifTanjim/nui.nvim)
- [Noice](https://github.com/folke/noice.nvim)
