# wkhtmltox on CentOS7


Run as root: 

```sh
yum install -y libpng
yum install -y libjpeg
yum install -y openssl
yum install -y icu
yum install -y libX11
yum install -y libXext
yum install -y libXrender
yum install -y xorg-x11-fonts-Type1
yum install -y xorg-x11-fonts-75dpi

wget https://downloads.wkhtmltopdf.org/0.12/0.12.5/wkhtmltox-0.12.5-1.centos7.x86_64.rpm

rpm -Uvh wkhtmltox-0.12.5-1.centos7.x86_64.rpm
```
