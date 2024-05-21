# Mount a hard drive

List information about all available or the specified block devices and find where you hard drive is connected to. Run the command:

`lsblk`

If you hard drive is in `sda1`, you can mount it in your home directory running the command:

`sudo mount /dev/sda1 /home/luna.kuleuven.be/uXXXXXXX/ssd/ -o uid=$(id -u) -o gid=$(id -g)`

To unmount, run the following command:

`sudo umount /dev/sda1 /home/luna.kuleuven.be/uXXXXXXX/ssd/`
