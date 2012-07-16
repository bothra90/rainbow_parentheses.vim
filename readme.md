# Better Rainbow Parentheses

### Options:

```vim
let g:rbpt_colorpairs = [
    \ ['brown',       'RoyalBlue3'],
    \ ['Darkblue',    'SeaGreen3'],
    \ ['darkred',     'SeaGreen3'],
    \ ['darkmagenta', 'DarkOrchid3'],
    \ ['brown',       'firebrick3'],
    \ ['gray',        'RoyalBlue3'],
    \ ['darkmagenta', 'DarkOrchid3'],
    \ ['Darkblue',    'firebrick3'],
    \ ['darkred',     'DarkOrchid3'],
    \ ['red',         'firebrick3'],
    \ ]
```

```vim
let g:rbpt_max = 16
```

```vim
let g:rbpt_loadcmd_toggle = 0
```

### Commands:

```vim
:RainbowParenthesesToggle       " Toggle it on/off
:RainbowParenthesesLoadRound    " (), the default when toggling
:RainbowParenthesesLoadSquare   " []
:RainbowParenthesesLoadBraces   " {}
:RainbowParenthesesLoadChevrons " <>
```

### Always On:

```vim
au VimEnter * RainbowParenthesesToggle
au Syntax * RainbowParenthesesLoadRound
au Syntax * RainbowParenthesesLoadSquare
au Syntax * RainbowParenthesesLoadBraces
```
