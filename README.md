# yerba-mate.nvim

<p align="center">
  <img width="120" src="https://raw.githubusercontent.com/mateCreations/yerba-mate.nvim/master/images/logo.png" alt="Mate" />
</p>

Neovim colorscheme pair — dark and light variants inspired by mate culture.

- **Yerba Mate** (dark) — deep olive-black, ochre and mate-green accents
- **Tererê** (light) — warm butter-paper, amber and terracotta accents

Both themes cover: editor UI, syntax, Treesitter, LSP diagnostics, Git Signs, Telescope, Snacks, nvim-cmp, Which-key, Lazy.nvim, and Alpha/Dashboard.

## Installation

Using [lazy.nvim](https://github.com/folke/lazy.nvim):

```lua
{ "mateCreations/yerba-mate.nvim" }
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
  { "mateCreations/yerba-mate.nvim" },
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

<p align="center">
  <img src="https://raw.githubusercontent.com/mateCreations/yerba-mate.nvim/master/images/palette-yerba-mate.png" alt="Yerba Mate palette" />
</p>

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

<p align="center">
  <img src="https://raw.githubusercontent.com/mateCreations/yerba-mate.nvim/master/images/palette-terere.png" alt="Tererê palette" />
</p>

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

- Omarchy system theme (dark): [omarchy-yerba-mate](https://github.com/mateCreations/omarchy-yerba-mate)
- Omarchy system theme (light): [omarchy-terere](https://github.com/mateCreations/omarchy-terere)
- Obsidian theme: [obsidian-yerba-mate](https://github.com/mateCreations/obsidian-yerba-mate)
