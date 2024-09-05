# kitty configuration
- donwload kitty terminal and add this kitty.conf file to the .config/kitty/kitty.conf

# Quick INSTALL to BASHRC 

git clone --recursive --depth 1 --shallow-submodules https://github.com/akinomyoga/ble.sh.git
make -C ble.sh install PREFIX=~/.local
echo 'source ~/.local/share/blesh/ble.sh' >> ~/.bashrc

# if you want to change defualt shell

  chsh -s /bin/bash

- to change to bash as default from zsh

- 
![Screenshot from 2024-09-05 06-40-07](https://github.com/user-attachments/assets/08fb5a63-8539-4ade-bbf1-badd26da6817)
