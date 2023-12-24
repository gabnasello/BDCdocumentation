# Mount KUL drives

Run the command below to mount all KUL drives (L-, K-, J-, ...) associated to your unumber

`sudo gbiomed-mount`

You can access the KUL drives at  `/media/YOUR-UNUMBER/`. If you want to access data in a KUL drive, the most convenient way is to copy files (or directories) locally.

Don't forget to **delete files and directories after use**, as the space in the workstation is limited!

### Copy files to the workstation

`cp "/media/YOUR-UNUMBER/L-drive/GBW-0001_Cranium/Users/.../file" /your/path`

### Copy directories  to the workstation

`cp -r "/media/YOUR-UNUMBER/L-Drive/GBW-001_Cranium/Users/.../directory/" /your/path/`
