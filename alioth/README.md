<div align="center">
<h1>Alioth dotfiles</h1>
<p><strong>Alioth is an arch linux rice customized with dracula theme running on manjaro i3 community edition</strong></p>
  <img width="50%" src="./resources/gifs/manjaro-i3-rice.gif" /><br>
  <p><strong>Screenshots</strong><p>
  <img width="45%" src="./resources/screenshots/6.png">
  <img width="45%" src="./resources/screenshots/2.png">
  <img width="45%" src="./resources/screenshots/4.png">
  <img width="45%" src="./resources/screenshots/7.png">
</div>
<h2>Prerequisites</h2>
<p>Install the following packages: </p>
<li><code>i3lock-color</code></li>
<li><code>i3-status</code></li>
<li><code>rofi</code></li>
<li><code>picom</code></li>
<li><code>neovim</code></li>
<li><code>kitty</code></li>
<li><code>dunst</code></li>
<li><code>ttf-fira-code</code></li>
<li><code>nerd-fonts-source-code-pro</code></li>
<li><code>ttf-font-awesome</code></li>
<br>
<p><strong>NOTE: </strong><em>Assuming that manjaro i3 community edition is running on the system, most of the above packages might be already installed. To check if a package is installed: </em><code>sudo pacman -Q | grep PACKAGE_NAME</code></p>
<h2>Installation</h2>
<p><strong>Manual</strong></p>
<li>Install the requirements.</li>
<li>Clone this repository: <code>git clone https://github.com/Nirbhay-Gaur/dotfiles/master/alioth.git && cd alioth</code></li>
<li>Copy all the files from alitoh directory to $HOME directory: <code>cp * $HOME/</code></li>
<li>Restart your computer for changes to take effect</li>
<br>
<p><strong>Using install.sh</strong></p>
<li>Install the requirements.</li>
<li>Clone this repository: <code>git clone https://github.com/Nirbhay-Gaur/dotfiles/master/alioth.git && cd alioth</code></li>
<li>Run the installation script: 
<code>
sudo chmod +x install.sh
./install.sh
</code>
</li>

## About
- A minimal but useable desktop environment for my personal use.
- Supports live theme changing.

Key                     | Value
------------------------|-----------------------------------
Os                      | Artix/Arch
Tiling window manager   | i3-gaps
Shell (bin/sh)          | Dash
Shell (Login)           | Fish
Terminal                | St (https://github.com/ocdy1001/st-cody)
Launcher                | Dmenu (https://github.com/ocdy1001/dmenu-cody)
Status bar              | Shapebar (https://github.com/ocdy1001/shapebar)
Prompt                  | Starship (https://github.com/starship/starship)
Text Editor             | NeoVim
Compositor              | Picom
AUR Helper              | Paru
Keymap                  | Physical: QMK (https://github.com/ocdy1001/qmk-cody)
Notable Utils           | Scrot, Slock, Feh, Fzf, Ag, Bat, Exa, Dust
Themes                  | Space, Nord, Gruvbox, Hawkrad
