# hiwifi-gfwlist2dnsmasq
gfwlist to dnsmasq rules


cd /etc/gw-redsocks/gw-shadowsocks && curl -k -o gfw.txt https://raw.githubusercontent.com/BenjaminX/hiwifi-gfwlist2dnsmasq/master/gfw.txt && cat gfw.txt >> gw-shadowsocks.dnslist && /etc/init.d/dnsmasq restart


cd /tmp && curl -k -o shadow.sh https://raw.githubusercontent.com/BenjaminX/hiwifi-gfwlist2dnsmasq/master/shadow.sh && sh shadow.sh && rm shadow.sh

tar -C ./ -czvf hiwifi-ss.tar.gz etc lib usr


