# gtags-cscope
gtags-cscope.vim from gnu global https://www.gnu.org/software/global/manual/global.html
Ported auto update from gtags.vim to gtags-cscope.vim. When a file is modified
and saved, global -u --single-update is called to update tags.

Add following to use VimPlug to install:
Plug 'multilobyte/gtags-cscope'


Configure following variables in $HOME/.vimrc.
"
" To use the default key/mouse mapping:
"	let GtagsCscope_Auto_Map = 1
" To ignore letter case when searching:
"	let GtagsCscope_Ignore_Case = 1
" To use absolute path name:
"       let GtagsCscope_Absolute_Path = 1
" To deterring interruption:
"	let GtagsCscope_Keep_Alive = 1
" If you hope auto loading:
"	let GtagsCscope_Auto_Load = 1
" To use 'vim -t ', ':tag' and '<C-]>'
"	set cscopetag
" To auto update tags when a file is saved
"       let GtagsCscope_Auto_Update = 1

then run the following in Vim:
:source %
:PlugInstall
