# ruscmd.nvim



## Description

This plugin will let you enter command mode (NORMAL) commands using Russian keyboard layout. Also it will let you enter few most used commands in command line mode in safe way (only full commands translated). This is usually enough to avoid switching between Russian and English layouts just to control Vim.

Works only with Unicode.

This plugin is a lua-fork of ![this plugin](https://github.com/powerman/vim-plugin-ruscmd)



## Install

Install with ![vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'aveplen/ruscmd.nvim'
```

Install with ![packer](https://github.com/wbthomason/packer.nvim)

```lua
use 'aveplen/ruscmd.nvim'
```



## Setup

Vimscript

```vim
lua << EOF
require('ruscmd').setup{}
EOF
```j

Lua

```lua
require('ruscmd').setup{}
```



## Configuration

```lua
require('ruscmd').setup{
  -- provide ex-command abbreviation
  -- example: ':й' -> ':q'
  abbreviations = true | false, -- default true

  -- provide NORMAL-mode translation
  -- example: 'ц' -> 'w'
  keymaps = true | false, -- default true
}
```

