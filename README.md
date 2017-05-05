## RPI qemu emulation for preparing burn-ready .img files 

This project aims to help my other rpis stuff to faster, easier, more complex preparing system components, burn it straight to SD card and just run.


## Requirements

* Linux/Mac
* Python3.5
* pip3


## Installation

* run setup.sh
```sh
bash setup.sh
```

If You want, firstly use Python virtualenv for keeping Python dependencies in separate location. Global is default.


## Usage

* Mounting image:
```sh
python3 rpiem.py mount -p PATH_TO_IMG
```

* Umounting image:
```sh
python3 rpiem.py umount
```

* Spawn shell:
```sh
python3 rpiem.py shell
```

More info at --help

# Milestones:
* emulate rpi using .img file in chroot environment (DONE)
* ansible support to run simple localhost playbooks
* easy-burn command
