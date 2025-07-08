# commands



echo 'nadad ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers
sudo tee /nadad
sudo chmod 440 /etc/sudoers.d/nadad
rm ~/.bash_history
