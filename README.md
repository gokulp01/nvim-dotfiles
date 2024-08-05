# my kickstart.nvim config

Preface: After about 8 years of stubbornly clinging to the same vim config - a monstrosity of over 2000 lines of undocumented code, half of which I couldn't explain if my life depended on it - I've finally decided to bite the bullet and update my config. Because apparently, teaching an old dog new tricks is easier than deciphering my own ancient vim hieroglyphs.

This is simply an updated fork of the excellent kickstart.nvim repository. I've tweaked it with my preferred keybindings (because muscle memory is a cruel mistress), tossed in a few plugins I can't do without, made a few changes to the LSP to work well with cpp and python and naturally, slapped on a fresh coat of paint (read: updated colorscheme). **If you find this useful, please DO NOT star _my_ repository; all credit goes to [kickstart.nvim](https://github.com/nvim-lua/kickstart.nvim?tab=readme-ov-file).** I'm just the guy who added fuzzy dice to the rearview mirror.

To use this config,

```
git clone git@github.com:gokulp01/nvim-dotfiles.git "${XDG_CONFIG_HOME:-$HOME/.config}"/nvim
```
