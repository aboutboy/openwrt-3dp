if
 pkg install /tmp/shadowsocksr-libev-gfwlist_v20170521-1pre_mipsel_24kc.ipk
Installing shadowsocksr-libev-gfwlist (v20170521-1pre) to root...
Collected errors:

check_data_file_clashes: Package shadowsocksr-libev-gfwlist wants to install file /etc/config/dns-forwarder
But that file is already provided by package * dns-forwarder
check_data_file_clashes: Package shadowsocksr-libev-gfwlist wants to install file /etc/dnsmasq.conf
But that file is already provided by package * dnsmasq-full
check_data_file_clashes: Package shadowsocksr-libev-gfwlist wants to install file /etc/firewall.user
But that file is already provided by package * firewall


put this file to include path and overwrite this file.
