# yerba-mate.nvim

Neovim colorscheme pair — dark and light variants inspired by mate culture.

- **Yerba Mate** (dark) — deep olive-black, ochre and mate-green accents
- **Tererê** (light) — warm butter-paper, amber and terracotta accents

Both themes cover: editor UI, syntax, Treesitter, LSP diagnostics, Git Signs, Telescope, Snacks, nvim-cmp, Which-key, Lazy.nvim, and Alpha/Dashboard.

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{ "nfvelten/yerba-mate.nvim" }
```

## Usage

```lua
-- Dark
vim.cmd("colorscheme yerba-mate")

-- Light
vim.cmd("colorscheme terere")
```

With lazy.nvim + LazyVim:

```lua
-- In lua/plugins/colorscheme.lua
return {
  { "nfvelten/yerba-mate.nvim" },
  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "yerba-mate", -- or "terere"
    },
  },
}
```

## Palettes

### Yerba Mate (dark)

| Role       | Color     |
|------------|-----------|
| Background | `#1c1e13` |
| Foreground | `#dce0d9` |
| Accent     | `#a67c52` |
| Functions  | `#7eb2d1` |
| Strings    | `#8fb339` |
| Keywords   | `#c25d44` |
| Comments   | `#4f5b4a` |

### Tererê (light)

| Role       | Color     |
|------------|-----------|
| Background | `#fbf1c7` |
| Foreground | `#3c3836` |
| Accent     | `#b57614` |
| Functions  | `#076678` |
| Strings    | `#79740e` |
| Keywords   | `#9d0006` |
| Comments   | `#928374` |

## Companion

- Omarchy system theme (dark): [omarchy-yerba-mate](https://github.com/nfvelten/omarchy-yerba-mate)
- Omarchy system theme (light): [omarchy-terere](https://github.com/nfvelten/omarchy-terere)
- Obsidian theme: [obsidian-yerba-mate](https://github.com/nfvelten/obsidian-yerba-mate)
