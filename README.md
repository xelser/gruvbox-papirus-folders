# About
This is based on Catppuccin's [papirus-folders](https://github.com/catppuccin/papirus-folders) for Sainnhe's [Gruvbox Material Colorscheme](https://github.com/sainnhe/gruvbox-material)

| Gruvbox | Red | Orange | Yellow | Green | Aqua | Blue | Purple |
|:-------:|:---:|:------:|:------:|:-----:|:----:|:----:|:------:|
| Material |![Red](src/64x64/places/user-gruvbox-material-red-home.svg)|![Orange](src/64x64/places/user-gruvbox-material-orange-home.svg)|![Yellow](src/64x64/places/user-gruvbox-material-yellow-home.svg)|![Green](src/64x64/places/user-gruvbox-material-green-home.svg)|![aqua](src/64x64/places/user-gruvbox-material-aqua-home.svg)|![Blue](src/64x64/places/user-gruvbox-material-blue-home.svg)|![Purple](src/64x64/places/user-gruvbox-material-purple-home.svg)|
| Mix |![Red](src/64x64/places/user-gruvbox-mix-red-home.svg)|![Orange](src/64x64/places/user-gruvbox-mix-orange-home.svg)|![Yellow](src/64x64/places/user-gruvbox-mix-yellow-home.svg)|![Green](src/64x64/places/user-gruvbox-mix-green-home.svg)|![aqua](src/64x64/places/user-gruvbox-mix-aqua-home.svg)|![Blue](src/64x64/places/user-gruvbox-mix-blue-home.svg)|![Purple](src/64x64/places/user-gruvbox-mix-purple-home.svg)|
| Original |![Red](src/64x64/places/user-gruvbox-original-red-home.svg)|![Orange](src/64x64/places/user-gruvbox-original-orange-home.svg)|![Yellow](src/64x64/places/user-gruvbox-original-yellow-home.svg)|![Green](src/64x64/places/user-gruvbox-original-green-home.svg)|![aqua](src/64x64/places/user-gruvbox-original-aqua-home.svg)|![Blue](src/64x64/places/user-gruvbox-original-blue-home.svg)|![Purple](src/64x64/places/user-gruvbox-original-purple-home.svg)|

# Install
1. Make sure you have [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) installed
2. Clone this repository and change to cloned directory:

```sh
git clone https://github.com/xelser/gruvbox-papirus-folders && cd gruvbox-papirus-folders
```
3. Copy content of `src` to Papirus Directory:
```sh
sudo cp -r src/* /usr/share/icons/Papirus/ # if installed in the root
```
```sh
cp -r src/* $HOME/.local/share/icons/Papirus/ # if installed in $HOME
```
4. Use modified `papirus-folders` script to set colors of folders.
```sh
./papirus-folders -C gruvbox-material-red --theme Papirus-Dark
```
Available colors are: 
- Material: `gruvbox-material-red`, `gruvbox-material-orange`, `gruvbox-material-yellow`, `gruvbox-material-green`, `gruvbox-material-aqua`, `gruvbox-material-blue`, `gruvbox-material-purple`
- Mix: `gruvbox-mix-red`, `gruvbox-mix-orange`, `gruvbox-mix-yellow`, `gruvbox-mix-green`, `gruvbox-mix-aqua`, `gruvbox-mix-blue`, `gruvbox-mix-purple`
- Original: `gruvbox-original-red`, `gruvbox-original-orange`, `gruvbox-original-yellow`, `gruvbox-original-green`, `gruvbox-original-aqua`, `gruvbox-original-blue`, `gruvbox-original-purple`
#### Visit [Papirus-folders](https://github.com/PapirusDevelopmentTeam/papirus-folders) and [Catppuccin Papirus-Folders](https://github.com/catppuccin/papirus-folders) to learn more about this script

# Credits
- [Catppuccin's Papirus Folders](https://github.com/catppuccin/papirus-folders)
- [Papirus Team](https://github.com/PapirusDevelopmentTeam)
- [Gruvbox Material](https://github.com/sainnhe/gruvbox-material)
- [Gruvbox](https://github.com/morhetz/gruvbox)

This project wouldn't be possible without any of the above. Show them great support :heart:

# License
[GPL-3.0](./LICENSE) © xelser
