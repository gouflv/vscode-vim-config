# A minimal config for VSCode Vim Extension - [VSCodeVim](http://aka.ms/vscodevim)

Custom several commands and key bindings to make VSCodeVim more efficient.

## Basic Settings

```json
{
  "vim.leader": "<space>",
  "vim.useSystemClipboard": true,
  "vim.hlsearch": true,
  "vim.highlightedyank.enable": true,
  "vim.foldfix": true
}
```

## Commands

### General Commands

| Command | Description                        |
| ------- | ---------------------------------- |
| ;       | Show all commands                  |
| [c      | Go to previous change              |
| ]c      | Go to next change                  |
| g;      | Go Back in navigation locations    |
| g'      | Go Forward in navigation locations |

### Language Commands

| Command    | Description            |
| ---------- | ---------------------- |
| <leader>ca | Source actions         |
| <leader>cf | Quick fix              |
| <leader>rn | Rename                 |
| <leader>fm | Format                 |
| gd         | Go to definition       |
| gr         | Go to references       |
| [d         | Go to previous problem |
| ]d         | Go to next problem     |
| K          | Hover info             |

### Fold Commands

| Command | Description         |
| ------- | ------------------- |
| zz      | Toggle fold         |
| z0      | Unfold all          |
| z1~z5   | Fold to level       |
| zk      | Go to previous fold |
| zj      | Go to next fold     |

### Window and tab Commands

| Command                  | Description                 |
| ------------------------ | --------------------------- |
| <leader>h \| j \| k \| l | Move cursor to other window |
| <leader>n \| p           | Move cursor to other tab    |

### Finder Commands

| Command    | Description                                |
| ---------- | ------------------------------------------ |
| <leader>po | Toggle file explorer                       |
| <leader>pO | Toggle file explorer and focus active file |
| <leader>ff | FInd files                                 |
| <leader>fc | Search in files                            |

### Explorer Commands

Inspired by `neovim-tree`

| Command | Description                |
| ------- | -------------------------- |
| a       | New file                   |
| A       | New Folder                 |
| c       | Copy file                  |
| x       | Cut file                   |
| p       | Paste file                 |
| d       | Delete file                |
| r       | Rename file                |
| escape  | Move cursor back to editor |

### Panel Commands

| Command    | Description                |
| ---------- | -------------------------- |
| <leader>tt | Open terminal              |
| <leader>tn | Open new terminal          |
| <leader>th | Toggle panel               |
| escape     | Move cursor back to editor |
