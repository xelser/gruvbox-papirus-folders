# Gruvbox Material Papirus Folders
This is based on [Catppuccin's papirus-folders](https://github.com/catppuccin/papirus-folders)
## Usage

1. Make sure You have [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) installed
2. Clone this repository and change to cloned directory:
    ```
    git clone https://github.com/xelser/gruvbox-papirus-folders.git
    cd papirus-folders
    ```
3. Copy content of `src` to `/usr/share/icons/Papirus/`:
    ```
    sudo cp -r src/* /usr/share/icons/Papirus  
    ```
4. Use modified `papirus-folders` script to set colors of folders. For example to set Blue folders for Papirus-Dark theme:
    ```
    ./papirus-folders -C gruv-mat-hard-dark-blue --theme Papirus-Dark
    ```
## All available additional colors form this script:
```
gruv-mat-hard-dark-aqua
gruv-mat-hard-dark-blue
gruv-mat-hard-dark-green
gruv-mat-hard-dark-orange
gruv-mat-hard-dark-purple
gruv-mat-hard-dark-red
gruv-mat-hard-dark-yellow
```
### Visit [Papirus-folders](https://github.com/PapirusDevelopmentTeam/papirus-folders) and [Catppuccin Papirus-Folders](https://github.com/catppuccin/papirus-folders) to learn more about this script

# Credits
- https://github.com/catppuccin/papirus-folders
- https://github.com/PapirusDevelopmentTeam
- https://github.com/sainnhe/gruvbox-material
- https://github.com/morhetz/gruvbox


