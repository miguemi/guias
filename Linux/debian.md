# Fix GDM

```bash
# go and open this file
sudo vi /lib/systemd/system/gdm.service

# add this piece into the config file
[Install]
WantedBy=graphical.target

# finally enable gdm
sudo systemctl enable gdm  && sudo systemctl enable gdm3
```