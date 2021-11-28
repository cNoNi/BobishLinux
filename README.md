# BobishLinux
The light weight linux distro based on archlinux. It's using kde plasma and sddm as an display manager. That's simple and don't have any random useless packages.


### Compilation
You need this packages to start compiling this os.
```
sudo pacman -S arch-install-scripts awk dosfstools e2fsprogs /
erofs-utils findutils gzip libarchlive libisoburn mtools/
openssl pacman sed squashfs-tools shellcheck
```
If you are ready start compiling.
```
git clone https://github.com/cNoNi/BobishLinux.git

cd BobishLinux 

sudo mkarchiso -v -w -o ./
```
