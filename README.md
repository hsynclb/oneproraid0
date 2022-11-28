# oneproraid0

Talimatlar

Debian/Ubuntu:<br>
apt update<br>
apt install -y xz-utils openssl gawk file<br>

RedHat/CentOS:<br>
yum install -y xz openssl gawk file<br>

Alttaki dosyayı indir:<br>
<br>
wget --no-check-certificate -qO oneproraid0.sh 'https://raw.githubusercontent.com/hsynclb/oneproraid0/main/oneproraid0.sh'<br>
chmod a+x oneproraid0.sh<br>


Örnek Debian9：<br>
bash oneproraid0.sh -d 9 -v 64 -a<br>

Örnek Ubuntu18.04：<br>
bash oneproraid0.sh -u 18.04 -v 64 -a<br>

Örnek Centos 7 Kurulum:<br>
bash oneproraid0.sh -c 7.9.2009 -v 64 -a<br>

Password değiştir.


Özel görüntü kullanarak centos yükleme:<br>
bash oneproraid0.sh -c 7 -v 64 -a --mirror 'http://mirror.centos.org/centos'<br>
bash oneproraid0.sh -c 7.9.2009 -v 64 -a<br>
