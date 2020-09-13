next-closed-fold.vim
====================

Jump to closed folds.

Without polluting the jumplist.


Usage
-----

Jump to the next closed fold *down*

    :NextClosedFold('j')

Jump to the next closed fold *up*

    :NextClosedFold('k')

Replace the default `zk` and `zj` key mappings

    :nnoremap <silent> zj :call NextClosedFold('j')<cr>
    :nnoremap <silent> zk :call NextClosedFold('k')<cr>


Inspired By
-----------

  * https://stackoverflow.com/a/9407015/564406
