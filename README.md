# briefpair

Simply pair completion in nvim, less feature, mainly use for enhancing builtin function.

Requires neovim 0.61

## Install

### [packer.nvim](https://github.com/wbthomason/packer.nvim)

```lua
use {
    'Moukubi/briefpair',
    config = require 'briefpair'.setup()
}
```

## Usage

```lua
require'briefpair'.setup{
    jump_leftside_pair = '<M-,>',
    jump_rightside_pair = '<M-;>'
}
```
