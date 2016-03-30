1. Install Kali
2. Set Network interface for host & bridge

# The primary network interface in /etc/network/interfaces
allow-hotplug eth0
iface eth0 inet static
address 192.168.59.100
netmask 255.255.255.0
network 192.168.59.0
broadcast 192.168.59.255

3. Install Openssh & Add navneetk public key in Authorized keys & SSH config in client
4. Install OhMyZSH

