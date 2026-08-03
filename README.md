# brokynvim

My personal Neovim configuration, built with `vim.pack`, LSP, Treesitter, Telescope, and more.

Leader key is `<space>`.

## Keybindings Cheatsheet

### General
| Key | Mode | Action |
| --- | --- | --- |
| `<Esc>` | Normal | Clear search highlighting |
| `<Esc><Esc>` | Terminal | Exit terminal mode |
| `<leader>q` | Normal | Open diagnostics in quickfix list |

### Window Navigation
| Key | Mode | Action |
| --- | --- | --- |
| `<C-h>` | Normal | Move focus to the left window |
| `<C-j>` | Normal | Move focus to the lower window |
| `<C-k>` | Normal | Move focus to the upper window |
| `<C-l>` | Normal | Move focus to the right window |

### Search (Telescope)
| Key | Mode | Action |
| --- | --- | --- |
| `<leader><leader>` | Normal | Find existing buffers |
| `<leader>/` | Normal | Fuzzily search in the current buffer |
| `<leader>sh` | Normal | Search help |
| `<leader>sk` | Normal | Search keymaps |
| `<leader>sf` | Normal | Search files |
| `<leader>ss` | Normal | Select a Telescope picker |
| `<leader>sw` | Normal, Visual | Search current word |
| `<leader>sg` | Normal | Search by grep |
| `<leader>s/` | Normal | Live grep in open files |
| `<leader>sd` | Normal | Search diagnostics |
| `<leader>sr` | Normal | Resume last Telescope search |
| `<leader>s.` | Normal | Search recent files |
| `<leader>sc` | Normal | Search commands |
| `<leader>sn` | Normal | Search Neovim config files |

### LSP
| Key | Mode | Action |
| --- | --- | --- |
| `grd` | Normal | Go to definition |
| `gri` | Normal | Go to implementation |
| `grr` | Normal | Find references |
| `grn` | Normal | Rename symbol |
| `grD` | Normal | Go to declaration |
| `grt` | Normal | Go to type definition |
| `gra` | Normal, Visual | Code action |
| `gO` | Normal | Open document symbols (Telescope) |
| `gW` | Normal | Open workspace symbols (Telescope) |
| `<leader>th` | Normal | Toggle inlay hints |

### Formatting
| Key | Mode | Action |
| --- | --- | --- |
| `<leader>f` | Normal, Visual | Format buffer (conform.nvim) |

### Autocompletion (blink.cmp)
| Key | Mode | Action |
| --- | --- | --- |
| `<C-y>` | Insert | Accept completion |
| `<C-space>` | Insert | Open completion menu / docs |
| `<C-n>` / `<C-p>` | Insert | Select next / previous item |
| `<C-e>` | Insert | Hide completion menu |
| `<C-k>` | Insert | Toggle signature help |
| `<Tab>` / `<S-Tab>` | Insert | Navigate snippet expansion |
| `<Up>` / `<Down>` | Insert | Select next / previous item |

### Text Objects & Surround (mini.nvim)
| Key | Mode | Action |
| --- | --- | --- |
| `aa` | Normal | Select around next textobject |
| `ii` | Normal | Select inside next textobject |
| `sa<motion>` | Normal | Add surroundings (e.g. `sa iw )`) |
| `sd<char>` | Normal | Delete surroundings (e.g. `sd '`) |
| `sr<old><new>` | Normal | Replace surroundings (e.g. `sr ) '`) |
