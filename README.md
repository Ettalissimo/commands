# commands

# to get the permissions

echo 'nadad ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers
sudo tee /nadad
tail /etc/sudoers

# in order to fully take the ownership of the virtual py env
sudo chown -R $USER:$USER path/to/virtPy



