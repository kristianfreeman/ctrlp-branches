# ctrlp-branches

Git branch search using [ctrlp.vim](https://github.com/kien/ctrlp.vim).

## INSTALLATION

1. Install using your favorite Vim plugin manager. In Vundle, installation looks something like this:

  ```
  echo "Bundle 'imkmf/ctrlp-branches'" >> ~/.vimrc
  vim -c "BundleInstall"
  ```

2. Add 'branches' to `g:ctrlp_extensions`:

  ```vim
  let g:ctrlp_extensions = [
  \ 'branches',
  \ ]
  ```

3. Run `:CtrlP` and move to the 'branches' mode, or run `:CtrlPBranches`.

Optionally, map `CtrlPBranches` to a key:

```vim
nmap <C-g> :CtrlPBranches<CR>
```

## TROUBLESHOOTING

This was hacked together on a Monday morning in about an hour. Bug reports are very helpful!


