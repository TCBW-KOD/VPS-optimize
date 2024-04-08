# VPS-optimize
chmod a+rx debian.sh

### dhcp模式
sudo ./debian.sh --cdn --network-console --ethx --bbr --user root --password 123456 --version 12 --timezone Asia/Shanghai

### 静态IP模式
sudo ./debian.sh --cdn --network-console --ethx --bbr --ip 192.168.50.10 --netmask 255.255.255.0 --gateway 192.168.50.1 --dns '223.5.5.5 119.29.29.29' --user root --password 123456 --version 12 --timezone Asia/Shanghai
