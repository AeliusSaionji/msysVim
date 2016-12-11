# msysVim
Add `Edit with Vim` to your Windows context menu- using vim from `msys2`.

## Install
1. Install msys2 to `c:\tools`, or adjust the registry file and batch script.
2. Import the [provided registry entry](msysVim.reg).
3. Copy `msysVim` to msys2's `/usr/bin`.
4. (Optional) Associate desired extensions with `msysVim.bat`.
5. (Optional) Create a .profile with any vim-specific settings you may have in other shells. Or, modify the registry file and batch script to use your shell of choice. If you don't understand what I'm saying, you probably don't have any vim-specific settings in your profile. Why do I specifically invoke `sh`? In msys2, `sh.exe` is just a copy of `bash.exe`, meaning this distinction is meaningless to most. However, those who install `dash` and overwite `sh.exe` with a copy of `dash.exe` will gain a slight speedup in launching vim.

![Context](context.png)
![Shell](shell.png)
