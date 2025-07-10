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

follow this documentation (ubuntu)

https://docs.qgroundcontrol.com/master/en/qgc-user-guide/getting_started/download_and_install.html

however we used the old version its no longer on the website (the new version seems to have some pbs)


### to move from a terminal to an other one 

ctrl + B + (click right after on the right arrow key )
