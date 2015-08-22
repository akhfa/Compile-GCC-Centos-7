# Compile-GCC-Centos-7<br>
source: https://www.vultr.com/docs/how-to-install-gcc-on-centos-6<br>
minimum ram 1 GB or 512 RAM + 512 SWAP.<br>
Not tested in centos 6 but it should be fine.<br>
Maybe will be fine for another gcc version. Just change 4.9.3 with the version you want.<br>
Change numproc value with your number of processor to make compiling faster. Check processor number with "nproc" command.<br>

# To Compile<br>
yum install screen -y<br>
>git clone https://github.com/akhfa/Compile-GCC-Centos-7.git<br>
cd Compile-GCC-Centos-7/<br>
chmod +x compile.sh<br>
screen<br>
./compile.sh >& log.compile<br>
>Ctrl + a + d<br>

# To see log<br>
tail -f log.compile
