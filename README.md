# 🌌 My Neovim Setup 🌌

## 📋 Table of Contents

- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Plugin Overview](#plugin-overview)
- [Contributing](#contributing)

## ✨ Features

- **Effortless File Navigation** 🌲
- **Powerful Code Autocompletion** ✍️
- **Syntax Highlighting** 🖍️ for various languages
- **Git Integration** 🚀 for quick version control
- **LSP Support** 🔧 (Language Server Protocol)
- **Theme Options** 🎨 with support for multiple color schemes

## 🔧 Requirements

Ensure you have the following installed:

- **Neovim** (>= 0.5.0)
- **Node.js** (for LSP servers)
- **You might want to install other services if you want support for other programming languages**

## ⚙️ Installation

To set up this configuration:

1. Clone the repository into your Neovim config directory:
   ```sh
   git clone https://github.com/atomicpunk1/nvim_setup.git ~/.config/nvim
   ```
2. Open Neovim and type
    ```sh
    :Lazy
    ```
    Lazy Nvim will install all packages

# 🔌 Plugin Overview

| Plugin File             | Plugin Name              | Description                                    |
|-------------------------|--------------------------|------------------------------------------------|
| `alpha.lua`             | alpha-nvim               | Start screen and session management            |
| `auto-session.lua`      | auto-session             | Automatic session handling                     |
| `autopairs.lua`         | nvim-autopairs           | Auto-closing brackets and quotes               |
| `bufferline.lua`        | bufferline.nvim          | Tabline for buffers                            |
| `colorscheme.lua`       | tokyonight.nvim          | Theme and color schemes configuration          |
| `comment.lua`           | nvim-comment             | Easy code commenting                           |
| `dressing.lua`          | dressing.nvim            | UI improvements for Neovim prompts             |
| `git-conflict.lua`      | git-conflict.nvim        | Resolve Git merge conflicts                    |
| `gitsigns.lua`          | gitsigns.nvim            | Git integration and signs                      |
| `indent-blankline.lua`  | indent-blankline.nvim    | Display indentation guides                     |
| `lazygit.lua`           | lazygit.nvim             | Integration with Lazygit CLI                   |
| `linting.lua`           | nvim-lint                | Linting support for multiple languages         |
| `lualine.lua`           | lualine.nvim             | Status line with custom themes                 |
| `nvim-cmp.lua`          | nvim-cmp                 | Completion plugin                              |
| `nvim-tree.lua`         | nvim-tree.lua            | File explorer                                  |
| `substitute.lua`        | substitute.nvim          | Enhanced substitution mappings                 |
| `surround.lua`          | nvim-surround            | Text object surrounding support                |
| `telescope.lua`         | telescope.nvim           | Fuzzy finder for files and more                |
| `todo-comments.lua`     | todo-comments.nvim       | Highlight and manage TODO comments             |
| `treesitter.lua`        | nvim-treesitter          | Enhanced syntax highlighting                   |
| `trouble.lua`           | trouble.nvim             | Diagnostics list UI                            |
| `vim-maximizer.lua`     | vim-maximizer            | Maximizing and restoring windows               |
| `which-key.lua`         | which-key.nvim           | Keybinding hints and mappings                  |

# 🤝 Contributing

Feel free to open issues or submit pull requests if you have suggestions for improvement or new features!
