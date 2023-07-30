# My workstation configs

- The colorscheme is a combmination of both gruvbox and gruvbox-material in my configs

## Package List

### **Descriptions:**

- **OS:** Arch Linux
- **Window Manager:** i3,qtile
- **Bar:** polybar
- **Launcher:** rofi
- **Compositor:** picom-pijulius
- **Terminal:** Kitty
- **Lockscreen:** i3lock
- **File Manager:** pcmanfm
- **Fonts:** roboto-condensed (for rofi and polybar), font-awesome (for rofi and polybar), monospace, jetbrainsmono, jetbrainsmono nerd fonts, firacode nerd font (for terminal,qtile bar)
- **Policykit:** mate-polkit

---

## Scripts you need to make executable:

- .config/autostart/autostart.sh
- .config/i3/scripts/power.sh
- .config/qtile/scripts/power.sh
- .config/polybar/i3_bar.sh

---

## Apps in each workspace

| Workspace Number |   Assigned Apps    |
| :--------------: | :----------------: |
|        1         |      Terminal      |
|        2         |      Browser       |
|        3         | Development/Coding |
|        4         |    File Manager    |
|        5         |        Chat        |
|        6         |    Design tools    |
|        7         |    Office tools    |
|        8         |    System tools    |

---

## Screenshots

### Qtile

![qtile](https://github.com/bibjaw99/workstation/blob/master/screenshots/qtile.png?raw=true)

## Keybindings For Qtile

| Keybindings |         Actions         |
| :---------: | :---------------------: |
|    mod+d    |        rofi drun        |
|    alt+d    |        rofi rum         |
|    alt+d    |      rofi windows       |
| mod+Shift+e |       Power Menu        |
| mod+Shift+o |     toggle layouts      |
| mod+Shift+x |    Betterlockscreen     |
| mod+return  |     Kitty terminal      |
| mod+Shift+q |     Kills a window      |
|  mod+ctrl   | resize window(vim keys) |
|    mod+m    |    toggle fullscreen    |
|  mod+space  |     floating window     |
|    mod+w    |         firefox         |
|    mod+n    |         pcmanfm         |
|   mod+Tab   |    next active group    |
|   alt+tab   |  previous active group  |

---

### i3-wm and polybar

![i3_poly](https://github.com/bibjaw99/workstation/blob/master/screenshots/i3.png?raw=true)

![poly](https://github.com/bibjaw99/workstation/blob/master/screenshots/polybar.png?raw=true)

## Keybindings For i3

|    Keybindings    |        Actions        |
| :---------------: | :-------------------: |
|       mod+t       |      Tiling Mode      |
|       mod+e       |       Tab Mode        |
|       mod+s       |     Stacking Mode     |
|       mod+d       |       rofi drun       |
|       alt+d       |       rofi run        |
|       alt+w       |     rofi windows      |
|    mod+Shift+e    |      Power Menu       |
|    mod+return     |    Kitty terminal     |
|    mod+Shift+q    |    Kills a window     |
| mod+ctrl+vim keys |     resize window     |
|       mod+z       |      horizontal       |
|       mod+a       |       vertical        |
|       mod+f       |   toggle fullscreen   |
|     mod+space     |    floating window    |
|       mod+q       | focus floating window |
|       mod+p       |     focus parent      |
|       mod+w       |        firefox        |
|       mod+n       |        pcmanfm        |

---

### Neovim

![nvim](https://github.com/bibjaw99/workstation/blob/master/screenshots/codex.png?raw=true)

#### Neovim File tree

```
.
├── init.lua
└── lua
    ├── core
    │   ├── init.lua
    │   ├── keymaps.lua
    │   ├── lazy.lua
    │   └── options.lua
    └── plugins
        ├── alpha-nvim.lua
        ├── autopairs.lua
        ├── bufferline.lua
        ├── cmp.lua
        ├── colorizer.lua
        ├── comments.lua
        ├── diagonistic-signs.lua
        ├── indent-blankline.lua
        ├── init.lua
        ├── lorem-nvim.lua
        ├── lsp.lua
        ├── lsp-saga.lua
        ├── lualine.lua
        ├── notify.lua
        ├── null-ls.lua
        ├── nvim-tree.lua
        ├── telescope.lua
        ├── toggleterm.lua
        ├── transparent-nvim.lua
        ├── treesitter.lua
        └── whichkey.lua
```
