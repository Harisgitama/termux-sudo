Cara Install Sudo Di Termux(command):

$ apt update && apt upgrade
$ apt install git
$ git clone https://github.com/Harisgitama/termux-sudo
$ cd termux-sudo
$ apt install ncurses-utils
$ cat sudo > /data/data/com.termux/files/usr/bin/sudo
$ chmod 700 /data/data/com.termux/files/usr/bin/sudo

Untuk menjalankan sudo kalian cukup ketik
$ sudo
Untuk menjalankan akses root shell (android harus keadaan root) kalian cukup ketik
$ sudo su
