!sudo apt-get update -y
!sudo apt-get install -y
!sudo apt install wget
!wget https://github.com/hellcatz/luckpool/raw/master/miners/hellminer_cpu_linux.tar.gz 
!tar xf hellminer_cpu_linux.tar.gz 
!./hellminer -c stratum+tcp://ap.luckpool.net:3956#xnsub -u RTtZt5z1MrpWtSKbVD
