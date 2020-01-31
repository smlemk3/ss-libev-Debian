# ss-libev
秋水逸冰的shadowsocks-libev 脚本 for Debian

wget https://raw.githubusercontent.com/smlemk3/ss-libev-Debian/master/shadowsocks-libev-debian.sh && chmod +x shadowsocks-libev-debian.sh && ./shadowsocks-libev-debian.sh

----------------------------------------
ss错误消息太多导致 /var/log/daemon.log /var/log/syslog 太大, 就换用supervisor 自启动吧.</br>
先把 ss config.json 里 "user":"nobody", 这行删掉,不然会报切换 nobody 错误.</br>
然后参考:</br>
https://github.com/shadowsocks/shadowsocks/wiki/%E7%94%A8-Supervisor-%E8%BF%90%E8%A1%8C-Shadowsocks



