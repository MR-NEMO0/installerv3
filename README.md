#!/bin/bash

#Variables
b="\033[1m"
u="\033[4m"
bl="\033[30m"
r="\033[31m"
g="\033[32m"
bu="\033[34m"
m="\033[35m"
c="\033[36m"
w="\033[37m"
endc="\033[0m"
enda="\033[0m"
blue="\033[1;34m"
cyan="\033[1;36m"
red="\033[1;31m"

clear
sleep 1
echo "Loading..." | lolcat
sleep 2
clear
echo "Welcome..." | lolcat
sleep 2
clear
echo "============================================================================
author : Mr. NEM0
Github : https://github.com/Mr.NEM0/istallerv3
ytube  : Mr. NEM0
==================================================================================

##################################################################################
# CTRL + C
##################################################################################
trap ctrl_c INT
ctrl_c() {
clear
echo" *[#] detected ctrl+c exit..."
echo" *[#] Tools ini Hanya Hiburan Bukan Untuk di Salah Gunakan"
sleep 1
echo"
echo *[#] Mr. NEM0

echo "Makasih..."
sleep 1
exit
}

lagi=1
while [$lagi -it 3];
do
echo"
echo"
echo"1. hack fb | lolcat
echo"-------------------------------"
echo"2. hack camera | lolcat
echo"-------------------------------"
echo"3. deface | lolcat
echo"-------------------------------"
echo"00. exit" | lolcat
read -p "pilih no : " pill;

case $pill in
git clone https://github.com/Mr.NEM0/installerv3/fbbrute
cd fbbrute
pip2 install mechanize
python2 force.py

;;

2)clear
git clone https://github.com/Mr.NEM0/installerv3/camera
cd camera
sh camera.sh

;;

3)clear
git clone https://github.com/Mr.NEM0/installerv3/deface
cd deface
sh deface.sh

;;

00)clear
echo "Jangan Lupa Subscribe Chanel Saya Mr. NEM0"
exit
;;

esac
done
done

