# kitty configuration
- donwload kitty terminal and add this kitty.conf file to the .config/kitty/kitty.conf

# Quick INSTALL to BASHRC (If this doesn't work, please follow Sec 1.3)

git clone --recursive --depth 1 --shallow-submodules https://github.com/akinomyoga/ble.sh.git
make -C ble.sh install PREFIX=~/.local
echo 'source ~/.local/share/blesh/ble.sh' >> ~/.bashrc
