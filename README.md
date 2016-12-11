# msysVim
Add `Edit with Vim` to your Windows context menu- using vim from `msys2`.

## Install
1. Install msys2 to `c:\tools`, or adjust the registry file and batch script.
2. Import the [provided registry entry](msysVim.reg).
3. Copy `msysVim` to msys2's `/usr/bin`.
4. (Optional) Associate desired extensions with `msysVim.bat`.
5. (Optional) Create a .profile with any vim-specific settings you may have in other shells. Or, modify the registry file and batch script to use your shell of choice. `sh.exe` is just a copy of `bash.exe`. By installing `dash` and overwiting `sh.exe` with a copy of `dash.exe`, you gain a slight speedup in launching vim.

![Context](context.png)
![Shell](shell.png)
