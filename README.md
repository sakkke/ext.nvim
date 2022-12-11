# ext.nvim
[![ext.nvim's Tech Stack](https://github-readme-tech-stack.vercel.app/api/cards?title=ext.nvim's%20Tech%20Stack&lineCount=1&theme=github_dark&align=left&line1=lua,lua,auto;)](https://github-readme-tech-stack.vercel.app/api/cards?title=ext.nvim's%20Tech%20Stack&lineCount=1&theme=github_dark&align=left&line1=lua,lua,auto;)

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
