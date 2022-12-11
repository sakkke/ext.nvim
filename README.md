# ext.nvim
String based simple Neovim plugin manager

## Features
- Install plugins on Neovim startup
- Auto remove unused plugins on Neovim startup
- Zero configuration

## Usage
```lua
-- Basic syntax
ext 'editorconfig/editorconfig-vim'

-- Rename plugin
ext 'catppuccin/nvim as catppuccin'

-- Manual dependencies
ext 'nvim-tree/nvim-tree.lua@nightly'
ext 'nvim-tree/nvim-web-devicons'

-- Duplicates will be ignored
ext 'nvim-tree/nvim-web-devicons'

-- Manual plugins setup
vim.cmd.colorscheme 'catppuccin'
```

## License

MIT
