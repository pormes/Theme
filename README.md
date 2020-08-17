# Theme
Theme Termux

Copy paste the script on nano .bashrc & nano bash.bashrc

Command :

Open sesion 1
$ termux-setup-storage
$ pkg install && pkg update && pkg upgrade
$ pkg install ruby
$ pkg install cowsay
$ pkg install toilet
$ pkg install figlet
$ pkg install nano
$ pkg install screenfetch
$ gem install lolcat
$ pkg install git
$ git clone https://github.com/pormes/blue-yellow-theme.git

Open sesion 2
$ nano .bashrc (copy paste file)
using app text editor and copy file from "nano .bashrc" to GNU screen
ctrl x y enter

Open sesion 3
$ cd ../
$ ls
$ cd usr/etc
$ ls
$ nano bash.bashrc (copy paste file)
using app text editor and copy file from "nano .bashrc" to GNU screen
ctrl x y enter

Open new sesion
And like a pro your theme on termux

See my youtube channels "PORMES CHANNELS"
www.youtube.com/c/pormes17

clear
R='\033[1;31m'
B='\033[1;34m'
C='\033[0;36m'
G='\033[1;32m'
W='\033[1;37m'
Y='\033[1;33m'
NOW=`date "+%d.%m.%Y"`TIME=`date "+%H:%M"`

echo -e $C        "█▀█░█▀█░█▀█░█▀█░█░█░█▄█░█▀█░█░█░█▀▀"
echo -e $C        "█▀█░█░█░█░█░█░█░░█░░█░█░█░█░█░█░▀▀█"
echo -e $C        "▀░▀░▀░▀░▀▀▀░▀░▀░░▀░░▀░▀░▀▀▀░▀▀▀░▀▀▀"

if [ -x /data/data/com.termux/files/usr/libexec/termux/command-not-found ]; then
        command_not_found_handle() {
                /data/data/com.termux/files/usr/libexec/termux/command-not-found "$1"
        }
fi

PS1='\033[01;36m\]┌──\[\033[01;36m\] MR.PORMES17\[\033[01;36m\] |MASTER| \[\033[01;36m\]\h\[\033[01;                 
└╼\[\033[01;36m\] \# ●○● \[\033[01;36m\]'
