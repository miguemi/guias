# Install AppImage

```bash
# example with neovim app image
wget clone https://github.com/neovim/neovim/releases/download/v0.9.1/nvim.appimage

chmod +x nvim.appimage
sudo mv nvim.appimage /opt/
# create symbolic link
sudo ln -s /opt/nvim.appimage /usr/local/bin/nvim
# refresh bashrc
source ~/.bashrc
```
