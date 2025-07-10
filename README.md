```sh
mv ~/dotfiles ~/.dotfiles
cd ~/.dotfiles
chmod +x move.sh
./move.sh
```

`move.sh` creates symlinks for each package.
If destination folders already exist, delete them before executing `move.sh`, otherwise an error
will occur.
