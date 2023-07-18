# Add user to docker group

`sudo usermod -aG docker uxxxxxxx`

Where you insert the u/r-number of the new user.

To activate the changes to groups

`newgrp docker`

But you have to run it for each new terminal until you do not restart the system:

`sudo shutdown -r now`

More information on the [Docker website](https://docs.docker.com/engine/install/linux-postinstall/)
