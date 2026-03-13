# jetdark.nvim

A JetBrains-inspired dark colorscheme for Neovim.

Ported from IntelliJ IDEA / PyCharm's dark theme with full support for Treesitter, LSP diagnostics, and popular plugins.

![jetdark](./screenshot.png)

## Installation

### [lazy.nvim](https://github.com/folke/lazy.nvim)

```lua
{
  'Malvi1697/jetdark.nvim',
  priority = 1000,
  config = function()
    vim.cmd.colorscheme('jetdark')
  end,
}
```

## Supported Plugins

- [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter)
- [nvim-tree.lua](https://github.com/nvim-tree/nvim-tree.lua)
- [telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim)
- [lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)

## Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| ![#bcbec4](https://placehold.co/15x15/bcbec4/bcbec4.png) | `#bcbec4` | Foreground |
| ![#1e1f22](https://placehold.co/15x15/1e1f22/1e1f22.png) | `#1e1f22` | Background |
| ![#cf8e6d](https://placehold.co/15x15/cf8e6d/cf8e6d.png) | `#cf8e6d` | Keywords |
| ![#56a8f5](https://placehold.co/15x15/56a8f5/56a8f5.png) | `#56a8f5` | Functions |
| ![#6aab73](https://placehold.co/15x15/6aab73/6aab73.png) | `#6aab73` | Strings |
| ![#2aacb8](https://placehold.co/15x15/2aacb8/2aacb8.png) | `#2aacb8` | Numbers |
| ![#8888c6](https://placehold.co/15x15/8888c6/8888c6.png) | `#8888c6` | Types |
| ![#c77dbb](https://placehold.co/15x15/c77dbb/c77dbb.png) | `#c77dbb` | Properties |
| ![#7a7e85](https://placehold.co/15x15/7a7e85/7a7e85.png) | `#7a7e85` | Comments |
| ![#d5b778](https://placehold.co/15x15/d5b778/d5b778.png) | `#d5b778` | HTML tags |
