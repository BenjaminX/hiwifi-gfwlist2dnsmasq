# hiwifi-gfwlist2dnsmasq
gfwlist to dnsmasq rules


cd /etc/gw-redsocks/gw-shadowsocks && wget https://raw.githubusercontent.com/BenjaminX/hiwifi-gfwlist2dnsmasq/master/gfw.txt && cat gfw.txt >> gw-shadowsocks.dnslist && /etc/init.d/dnsmasq restart


