# watch-dogs-boot-animation-centos
Boot animation adapted from the ubuntu version. *Tested for CentOS 8 (minimal installation)*. 

#### To install:

```
yum install plymouth-plugin-script

If you want do download it via git:
yum install git
```

##### For CentOS 8

All in one:
```
cd /usr/share/plymouth/themes
sudo git clone https://github.com/dietleintech/watch-dogs.git
cd watch-dogs/
sudo bash install.sh
```
Pick the theme number when prompted.

OR

Copy the whole folder to /usr/share/plymouth/themes. (***remember the root permission is needed***).
Then locate and run the bash script in the folder ; named "install.sh".

```bash
bash install.sh
```
or
```bash
./install.sh
```
Pick the theme number when prompted.

**Note** : *The whole animation will run in the computer which boots slower (well, fast computers are FAST)*.
