# ruscmd


## Description

This plugin will let you enter command mode (NORMAL) commands using Russian keyboard layout. Also it will let you enter few most used commands in command line mode in safe way (only full commands translated). This is usually enough to avoid switching between Russian and English layouts just to control Vim.

Works only with Unicode.

This plugin is a lua-fork of ![this plugin](https://github.com/powerman/vim-plugin-ruscmd)

---

Этот плагин позволит использовать команды command mode (NORMAL) используя русскую раскладку клавиатуры. В дополнение к этому плагин позволяет не переключаться для ввода наиболее используемых команд. Этого набора обычно достаточно, чтобы управляться с Vim без необходимости переключать раскладку. 

Работает только с Unicode.

Этот плагин является lua-форком ![этого плагина](https://github.com/powerman/vim-plugin-ruscmd)

---

## Install

Install with ![vim-plug](https://github.com/junegunn/vim-plug)

```vim
Plug 'aveplen/ruscmd.nvim'
```

Install with ![packer](https://github.com/wbthomason/packer.nvim)

```lua
use 'aveplen/ruscmd.nvim'
```

---

## Setup

Vimscript

```vim
lua << EOF
require('ruscmd').setup{}
EOF
```

Lua

```lua
require('ruscmd').setup{}
```

---

## Configuration

```lua

```

