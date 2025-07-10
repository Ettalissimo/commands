# commands

### to get the permissions

echo 'nadad ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers

sudo tee /nadad

tail /etc/sudoers

### create virtual py env 

python3 -m venv nom_env

source venv/bin/activate 

### in order to fully take the ownership of the virtual py env

sudo chown -R $USER:$USER path/to/virtPy



docker build -t px4-ros2-gazebo-yolov8-env -f Dockerfile.env .



### Q Ground Controller

sudo usermod -a -G dialout $USER

sudo apt-get remove modemmanager -y

sudo apt install gstreamer1.0-plugins-bad gstreamer1.0-libav gstreamer1.0-gl -y

sudo apt install libfuse2 -y

sudo apt install libxcb-xinerama0 libxkbcommon-x11-0 libxcb-cursor-dev -y
