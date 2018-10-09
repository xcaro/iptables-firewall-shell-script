# Iptables Firewall shell script for Standalone Server

### How do i install this scripts?
After download script following command as root server:
```bash
~$ cd /root
~$ git clone https://github.com/xcaro/iptables-firewall-shell-script.git scripts
~$ cd scripts
~$ chmod +x *.fw
```
Then, you can edit firewall rules as per your requirements:
```bash
~$ vi /root/scripts/start.fw
```
Install firewall:
```bash
~$ echo '/root/scripts/start.fw' >> /etc/rc.local
```

### How do i use this scripts?
Start firewall from a shell prompt:
```bash
~$ /root/scripts/start.fw
```
Stop firewall from a shell prompt:
```bash
~$ /root/scripts/stop.fw
```