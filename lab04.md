# Author: Rebecca Childs
## Reading Notes:
### Lab 04

### Which network mode in VirtualBox can be used to emulate unplugging the Ethernet cable from the network?
Not Attached: This mode essentially disconnects the virtual network adapter within a virtual machine, simulating the behavior of a physical cable being removed. It's useful for testing scenarios where network connectivity might be lost or applications need to handle interruptions.
### Which network mode would be best if you wanted to run a server on a VM that could be fully accessible from your physical local area network?
Bridged Networking: This gives you full network access: In bridged mode, the virtual machine acts like a separate computer on your physical network. It gets assigned an IP address from your DHCP server (if available) or you can configure a static IP within the same subnet as your physical machine. This allows other devices on your LAN to directly communicate with the server VM, just like any other computer.
### What are the three options of promiscuous mode and what does each do?
Capture filters - used in conjunction with promiscuous mode to refine captured data.
Monitoring mode - wireless equivalent of promiscuous mode.
Packet capture tools - provides an interface to enable promiscuous mode and might have additional configuration options.
### What is Port Forwarding?
Port forwarding, also called port mapping, is a tool used for advanced network users, allowing them to host services or access devices remotely on the local area network (LAN). This also allows users to direct incoming traffic from the internet to a specific device.

## Things I want to learn more about:
N/A