[Spanish](https://github.com/m1gu3l-d3v/dotfiles/blob/main/README-ES.md)

# BSPWM

This repository contains my customized configuration for the BSPWM window manager. It includes templates for various color schemes with integration to:

- Bspwm
- Polybar
- Dunst
- Alacritty
- Rofi
- Ly Display Manager
- GTK [(oomox - themix-gui)](https://github.com/themix-project/themix-gui)
- QT [(oomox - themix-gui)](https://github.com/themix-project/themix-gui)

## Installation

To install and configure BSPWM, follow these steps:
##### Note 1: [installer.sh](https://github.com/m1gu3l-d3v/dotfiles/blob/main/installer.sh) will only work on Linux Debian and its derivative distributions. However, you can manually copy the dotfiles to their respective locations. The installer.sh should work if you comment out the parts that involve package manager usage (sudo apt install) and adapt it for your specific distribution.

1. Clone this repository into your home directory:
    ```bash
    cd ~/ && git clone https://github.com/m1gu3l-d3v/dotfiles && cd ~/dotfiles
    ```

2. Grant execute permission to the installation script:

    ```bash
    chmod +x installer.sh
    ```

3. Run the installation script:

    ```bash
    ./installer.sh
    ```

4. Basic Utilities:
   ```bash
   sudo apt install xfce4-settings thunar-archive-plugin scrot tty-clock btop neofetch neovim wget geany ristretto mpv libreoffice libreoffice-gtk3
   ```

## Available Themes

You can choose from the following themes by executing any of the following lines in the terminal:

- Catppuccin Frappe
  ```bash
  colorscheme CatppuccinFrappe
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinFrappe1.png)
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinFrappe2.png)
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinFrappe3.png))

- Catppuccin Latte
  ```bash
  colorscheme CatppuccinLatte
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinLatte1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinLatte2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinLatte3.png))

- Catppuccin Machiato
  ```bash
  colorscheme CatppuccinMachiato
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinMachiato1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinMachiato2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinMachiato3.png))

- Catppuccin Mocha
  ```bash
  colorscheme CatppuccinMocha
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinMocha1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinMocha2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/CatppuccinMocha3.png))

- Dracula
  ```bash
  colorscheme Dracula
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Dracula1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Dracula2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Dracula3.png))

- Everblush
  ```bash
  colorscheme Everblush
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Everblush1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Everblush2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Everblush3.png))

- Everforest
  ```bash
  colorscheme Everforest
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Everforest1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Everforest2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Everforest3.png))

- Gruvbox Dark
  ```bash
  colorscheme GruvboxDark
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/GruvboxDark1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/GruvboxDark2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/GruvboxDark3.png))

- Gruvbox Material
  ```bash
  colorscheme GruvboxMaterial
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/GruvboxMaterial1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/GruvboxMaterial2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/GruvboxMaterial3.png))

- Monokai Pro Ristretto
  ```bash
  colorscheme MonokaiProRistretto
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/MonokaiProRistretto1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/MonokaiProRistretto2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/MonokaiProRistretto3.png))

- Monokai Pro
  ```bash
  colorscheme MonokaiPro
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/MonokaiPro1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/MonokaiPro2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/MonokaiPro3.png))

- Nord
  ```bash
  colorscheme Nord
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Nord1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Nord2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/Nord3.png))

- OneDark
  ```bash
  colorscheme OneDark
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/OneDark1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/OneDark2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/OneDark3.png))

- RosePine
  ```bash
  colorscheme RosePine
  ```
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/RosePine1.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/RosePine2.png))
  ![](https://github.com/m1gu3l-d3v/dotfiles/blob/main/screnshots/RosePine3.png))


## Keyboard Shortcuts

<table>
    <tr>
        <th>Keys</th>
        <th>Action</th>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>Return</kbd></td>
        <td>Launch Alacritty</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>d</kbd></td>
        <td>Rofi for launching programs</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>ctrl</kbd> + <kbd>d</kbd></td>
        <td>Rofi to view open windows</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>alt</kbd> + <kbd><kbd>q</kbd> / <kbd>r</kbd></kbd></td>
        <td>Close/Restart BSPWM</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>q</kbd> / <kbd>shift</kbd> + <kbd>q</kbd></kbd></td>
        <td>Close/Kill current window</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>t</kbd> / <kbd>shift</kbd> + <kbd>t</kbd> / <kbd>f</kbd> / <kbd>m</kbd> / <kbd>s</kbd></kbd></td>
        <td>Modify window state to tiled/pseudo_tiled/fullscreen/monocle/float</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>z</kbd> / <kbd>shift</kbd> + <kbd>z</kbd></kbd></td>
        <td>Focus next/previous window</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>[</kbd> / <kbd>]</kbd></kbd></td>
        <td>Switch to previous/next desktop on current monitor</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>Left</kbd> / <kbd>Down</kbd> / <kbd>Up</kbd> / <kbd>Right</kbd></kbd></td>
        <td>Move window focus in specified direction</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>shift</kbd> + <kbd><kbd>Left</kbd> / <kbd>Down</kbd> / <kbd>Up</kbd> / <kbd>Right</kbd></kbd></td>
        <td>Send focused window to specified direction</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>1-9</kbd></td>
        <td>Switch to specified desktop 1-9</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>1-9</kbd></td>
        <td>Move focused window to desktop 1-9</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>grave</kbd></td>
        <td>Focus last used window</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>shift</kbd> + <kbd>Tab</kbd></td>
        <td>Focus last used desktop</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>alt</kbd> + <kbd><kbd>Left</kbd> / <kbd>Down</kbd> / <kbd>Up</kbd> / <kbd>Right</kbd></kbd></td>
        <td>Adjust window position in specified direction</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>alt</kbd> + <kbd>shift</kbd> + <kbd><kbd>Left</kbd> / <kbd>Down</kbd> / <kbd>Up</kbd> / <kbd>Right</kbd></kbd></td>
        <td>Shrink floating window by moving one of its sides inward</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>ctrl</kbd> + <kbd><kbd>Left</kbd> / <kbd>Down</kbd> / <kbd>Up</kbd> / <kbd>Right</kbd></kbd></td>
        <td>Preselect direction of next window to open</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>ctrl</kbd> + <kbd>1-9</kbd></td>
        <td>Adjust window preselection ratio</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>ctrl</kbd> + <kbd>space</kbd></td>
        <td>Cancel current window preselection</td>
    </tr>
    <tr>
        <td><kbd>XF86MonBrightness <kbd><kbd>Up</kbd> / <kbd>Down</kbd></kbd></td>
        <td>Increase/Decrease screen brightness</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>w</kbd></td>
        <td>Open Firefox</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>n</kbd></td>
        <td>Open Thunar</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>a</kbd> / <kbd>shift</kbd> + <kbd>a</kbd> / <kbd>ctrl</kbd> + <kbd>a</kbd></kbd></td>
        <td>Scrot select/full/window screenshot mode</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>e</kbd></td>
        <td>Open Neovim</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd><kbd>y</kbd> / <kbd>shift</kbd> + <kbd>y</kbd></kbd></td>
        <td>Run Sysfetch/Neofetch</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>c</kbd></td>
        <td>Open Clock</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>shift</kbd> + <kbd>p</kbd></kbd></td>
        <td>Show/Hide polybar</td>
    </tr>
    <tr>
        <td><kbd>super</kbd> + <kbd>p</kbd></td>
        <td>Show restart/shutdown menu</td>
    </tr>
</table>