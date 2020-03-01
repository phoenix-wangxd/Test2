# my_vim_config
这是我的vim的配置文件以及配置文件的说明。


## 使用的vim的版本信息
这个配置文件是在mac上写的，vim的版本是8.1，但是应该与其他的vim版本是兼容的。
详细的版本信息如下：
```
VIM - Vi IMproved 8.1 (2018 May 18, compiled Dec 13 2019 14:45:40)
Included patches: 1-503, 505-680, 682-1312
Compiled by root@apple.com
Normal version without GUI.  Features included (+) or not (-):
+acl               +extra_search      -mouse_netterm     -tag_old_static
-arabic            -farsi             +mouse_sgr         -tag_any_white
+autocmd           +file_in_path      -mouse_sysmouse    -tcl
+autochdir         +find_in_path      -mouse_urxvt       -termguicolors
-autoservername    +float             +mouse_xterm       +terminal
-balloon_eval      +folding           +multi_byte        +terminfo
-balloon_eval_term -footer            +multi_lang        +termresponse
-browse            +fork()            -mzscheme          +textobjects
+builtin_terms     -gettext           +netbeans_intg     +textprop
+byte_offset       -hangul_input      +num64             +timers
+channel           +iconv             +packages          +title
+cindent           +insert_expand     +path_extra        -toolbar
-clientserver      +job               -perl              +user_commands
-clipboard         +jumplist          +persistent_undo   -vartabs
+cmdline_compl     -keymap            +postscript        +vertsplit
+cmdline_hist      +lambda            +printer           +virtualedit
+cmdline_info      -langmap           -profile           +visual
+comments          +libcall           +python/dyn        +visualextra
-conceal           +linebreak         -python3           +viminfo
+cryptv            +lispindent        +quickfix          +vreplace
+cscope            +listcmds          +reltime           +wildignore
+cursorbind        +localmap          -rightleft         +wildmenu
+cursorshape       -lua               +ruby/dyn          +windows
+dialog_con        +menu              +scrollbind        +writebackup
+diff              +mksession         +signs             -X11
+digraphs          +modify_fname      +smartindent       -xfontset
-dnd               +mouse             +startuptime       -xim
-ebcdic            -mouseshape        +statusline        -xpm
-emacs_tags        -mouse_dec         -sun_workshop      -xsmp
+eval              -mouse_gpm         +syntax            -xterm_clipboard
+ex_extra          -mouse_jsbterm     +tag_binary        -xterm_save
   system vimrc file: "$VIM/vimrc"
     user vimrc file: "$HOME/.vimrc"
 2nd user vimrc file: "~/.vim/vimrc"
      user exrc file: "$HOME/.exrc"
       defaults file: "$VIMRUNTIME/defaults.vim"
  fall-back for $VIM: "/usr/share/vim"
Compilation: gcc -c -I. -Iproto -DHAVE_CONFIG_H   -DMACOS_X_UNIX  -g -O2 -U_FORTIFY_SOURCE -D_FORTIFY_SOURCE=1
Linking: gcc   -L/usr/local/lib -o vim        -lm -lncurses  -liconv -framework Cocoa
```
你可以在终端中通过输入`vim --version`来获取vim的版本信息。

## 其他推荐
为了更好的使用vim，推荐将键盘中的`Ctrl`和`CapsLock`按键位置进行互换。
