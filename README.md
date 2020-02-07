# My NeoVim Config 



Please **DO NOT** just copy this config without really looking at it! Please, at least, read this README file!


## After Installation, You Need To:
**!!!! Important for some plugins like coc** <++>
- [ ] Install `pynvim` (pip)
- [ ] Install `nodejs`, and do `npm install -g neovim`
- [ ] Install nerd-fonts (actually it's optional but it looks real good)

## After Installation, You Might Want To:
#### First of all
- [ ] Do `:checkhealth`

#### Config `Python` path
- [ ] Well, make sure you have python
- [ ] See `_machine_specific.vim`

#### For Code AutoComplete - coc
Python:
- [ ] Do `pip3 install flake8` (for linting)

#### For Taglist:
- [ ] Install `ctags` for function/class/variable list

#### For Denite:
- [ ] Install `ripgrep`
- [ ] Install `fd`

#### And also...
- [ ] Install `figlet` for inputing text ASCII art
- [ ] Install `xclip` for system clipboard access (`Linux` and `xorg` only)

## Keyboard Shortcuts
### Just after all auto-install and click `?` and check out the keyboard shortcuts and try to learn it.
## Custom Snippets
#### Markdown
| Shortcut | What it creates     |
|----------|---------------------|
| `,n`     | ---                 |
| `,b`     | **Bold** text       |
| `,s`     | ~~sliced~~ text     |
| `,i`     | *italic* text       |
| `,d`     | `code block`        |
| `,c`     | big `block of code` |
| `,m`     | - [ ] check mark    |
| `,p`     | picture             |
| `,a`     | [link]()            |
| `,1`     | # H1                |
| `,2`     | ## H2               |
| `,3`     | ### H3              |
| `,4`     | #### H4             |
| `,l`     | --------            |

`,f` to go to the next `<++>` (placeholder)

`,w` to go to the next `<++>` (placeholder) and then press `Enter` for you

## Other Weird Stuff
#### Press `tx` and enter your text
`tx Hello<Enter>`
```
 _   _      _ _
| | | | ___| | | ___
| |_| |/ _ \ | |/ _ \
|  _  |  __/ | | (_) |
|_| |_|\___|_|_|\___/
```

