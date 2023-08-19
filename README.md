# msysVim

Add `Edit with Vim` to your Windows context menu- using vim from `msys2`.

## Install Methods

### makepkg -i

Use the provided PKGBUILD!


#### PKGBUILD TODO

- [ ] Check for dash
- [ ] Merge/unmerge reg automatically in PKGBUILD install script
- [ ] Include program to execute directly; avoid batch cmd window


### Manual Install

1. Import the [provided registry entry](msysVim.reg).
2. Copy `msysVim` to msys2's `/usr/bin`.
3. (Optional) Associate desired extensions with `msysVim.bat`.
4. (Optional) Create a .profile with any vim-specific settings you may have configured in other shells.  
Or, modify the registry file and batch script to use your shell of choice.


![Context](context.png)
![Shell](shell.png)
