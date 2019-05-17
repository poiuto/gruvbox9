# Gruvbox 8 - Vim Colorscheme

This is a simplified and optimized<sup>*</sup> version of
[Gruvbox](https://github.com/morhetz/gruvbox) that I have developed
to address some issues I had with the official colorscheme.

 These are the main differences compared to the official Gruvbox:

- by default, no plugin and filetype highlight groups to avoid messing up syntax
  highlighting after switching colorschemes (they can be enabled through options);
- reduced number of options;
- all options are documented;
- slightly different (and, IMHO, better) 256-color palette;
- no 16-color version;
- support for transparent backgrounds in terminals;
- no autoload folder, no shell scripts;
- up to date highlight group definitions (e.g., includes `ToolbarLine`
  and `ToolbarButton`);
- defines `g:terminal_ansi_colors`;
- generated by [Colortemplate](https://github.com/lifepillar/vim-colortemplate),
  i.e., easily hackable.

<sup>*</sup> Loads in ~1.5ms compared to the >9ms required by Gruvbox.

## Hacking

Do you want to hack the theme? Install
[Colortemplate](https://github.com/lifepillar/vim-colortemplate), edit the
files in the `templates` folder, then rebuild the colorschemes by sourcing
`make_colorschemes.vim`.

