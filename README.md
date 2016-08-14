# RT-N12-tomato
Instructions and firmware for Asus RT-N12D1 router flash

30-30-30 reset
upload firmware and wait for reboot
30-30-30 reset
reboot from firmware upload screen or power cycle
login root/admin
Administration -> Configuration -> Restore Defaults -> Erase NVRAM
Basic -> Network -> Ethernet Port -> Invert
Basic -> Ident change name and hostname to match Acuiseennn sequence
Change Network IP to 192.168.123.1  and dhcp range to 192.168.123.2-251
Change SSID to match router name, Auto Channel, Security to WEP personal/AES
Administration -> Change password for SU
