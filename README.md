Auto-correct British (en-GB) spellings to their Oxford (en-GB-oed) equivalents

To enable auto-correction, run this command:

    :Oxfordize

This creates [abbreviations][] for common words whose spelling differs between British and Oxford English, such as organise/organize, and so on. If you type 'organise', Vim will auto-correct it to 'organize'. The abbreviations applied by the `:Oxfordize` command are local to the active buffer. 

This plugin depends on Tim Pope's [abolish][] plugin. If the `:Abolish` command isn't available, then the `:Oxfordize` command will do nothing.

This plugin is forked from Drew Neil's [americanize](https://github.com/nelstrom/vim-americanize) plugin.

[abolish]: http://github.com/tpope/vim-abolish
[abbreviations]: http://vimdoc.sourceforge.net/htmldoc/map.html#abbreviations
