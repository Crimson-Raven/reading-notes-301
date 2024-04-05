# Author: Rebecca Childs
## Reading Notes:
### Lab 06

### What is the main purpose for implementing NAT on a network?
The main reason for NAT is to stretch the limited supply of public internet addresses. It lets you connect many devices inside your network (like your phone, computer, etc.) to the internet using just one public address, like a family sharing one mailbox.

### At what layer of the OSI model does NAT happen?
NAT is mainly considered a layer 3 function.

### What happens to packets when NAT runs out of addresses in the pool of available IPs?
When a NAT runs out of IP addresses, it can't translate internal traffic to the internet. Packets typically get dropped, meaning the connection attempt fails. In rare cases, the NAT might block all new connections or even replace an old connection to make space. The bottom line is, things won't work smoothly until the NAT gets more addresses.

### What disadvantage does using NAT pose for routers?
NAT can mess up with some apps on your router. Because it translates addresses, applications that rely on direct connections or specific IP addresses can malfunction. This includes things like peer-to-peer file sharing, VPNs, and some security features in apps.

## Things I want to learn more about:
N/A
