# commands

### to get the permissions

```bash

echo 'nadad ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers
sudo tee /nadad
tail /etc/sudoers
```

### create virtual py env 

go to the root project folder and execute the following commands

```bash
python3 -m venv nom_env
source venv/bin/activate 
```

in order to fully take the ownership of the virtual py env

```bash
sudo chown -R $USER:$USER path/to/virtPy
```




### Q Ground Controller

The Old version
```bash
sudo usermod -a -G dialout $USER
sudo apt-get remove modemmanager -y
sudo apt install gstreamer1.0-plugins-bad gstreamer1.0-libav gstreamer1.0-gl -y
sudo apt install libfuse2 -y
sudo apt install libxcb-xinerama0 libxkbcommon-x11-0 libxcb-cursor-dev -y
```

Download this executable [github link]

Install and run the following command 

```bash
chmod +x ./QGroundControl.AppImage
./QGroundControl.AppImage  (or double click)
```


OR follow this documentation (ubuntu)

https://docs.qgroundcontrol.com/master/en/qgc-user-guide/getting_started/download_and_install.html

however we used the old version its no longer on the website (the new version seems to have some pbs)


### to move from a terminal to an other one 

ctrl + B + (click right after on the right arrow key )
