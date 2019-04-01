# fish-gruvbox
[gruvbox] theme for [fish shell]

# Install
With [fisherman]
```
fisher jomik/fish-gruvbox
```

This will expose the function called `theme_gruvbox`.
It is a simple function that takes two arguments.
The first is the mode, either `light` or `dark`.
The second is the contrast, `soft`, `medium` or `hard`.
The defaults are `light` and `medium`.

To automatically apply this theme, call `theme_gruvbox` from your `config.fish`.

[gruvbox]: https://github.com/morhetz/gruvbox
[fish shell]: http://fishshell.com/
[fisherman]: https://github.com/fisherman/fisherman
