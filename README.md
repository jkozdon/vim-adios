# vim-adios
adios.vim -- a vim plugin for browsing
[adios](https://www.olcf.ornl.gov/center-projects/adios/) bp files

# Usage:
Editing an adios file `*.bp` will cause the file to be read with bpls.

pressing ENTER on the variable will run bpdump on the variable.

pressing ENTER in the opened file will jump between variable definition

# Requirements:
`bpls` and `bpdump` must be in your path

Installation:
Place this file, adios.vim, in your `$HOME/.vim/plugin` directory, and
either restart vim, or execute `:source $HOME/.vim/plugin/adios.vim`

Alternatively, it can be installed with pathogen:
```
cd ~/.vim/bundle
git clone git://github.com/jkozdon/vim-adios.git
```

# License:
This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org/>

# Inspiration:
This plugin is inspired by the tar plugin
<http://www.vim.org/scripts/script.php?script_id=522>
