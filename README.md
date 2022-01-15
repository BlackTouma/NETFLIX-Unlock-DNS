# NETFLIX-Unlock-DNS

使用方法：

wget https://github.com/BlackTouma/NETFLIX-Unlock-DNS/raw/main/unlock.sh

chmod +x unlock.sh

./unlock.sh x.x.x.x 208.67.222.2 208.67.220.2


chattr +i /etc/resolv.conf	#DNS上锁


chattr -i /etc/resolv.conf	#DNS解锁



## PS: x.x.x.x替换为可以解锁NETFLIX的DNS
