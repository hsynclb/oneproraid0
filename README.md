# oneproraid0

Talimatlar

Debian/Ubuntu:
apt update
apt install -y xz-utils openssl gawk file

RedHat/CentOS:
yum install -y xz openssl gawk file

Alttaki dosyayı indir:

wget --no-check-certificate -qO oneproraid0.sh 'https://github.com/hsynclb/oneproraid0/blob/main/oneproraid0.sh'
chmod a+x oneproraid0.sh


Örnek Debian9：
bash oneproraid0.sh -d 9 -v 64 -a

Örnek Ubuntu18.04：
bash oneproraid0.sh -u 18.04 -v 64 -a

Örnek Centos 7 Kurulum:
bash oneproraid0.sh -c 7.9.2009 -v 64 -a

Password değiştir.


Özel görüntü kullanarak centos yükleme:
bash install-raid0.sh -c 7 -v 64 -a --mirror 'http://mirror.centos.org/centos'
bash install-raid0.sh -c 7.9.2009 -v 64 -a
