# Author: Rebecca Childs
## Reading Notes:
### Lab 03

### What is CIDR notation? a CIDR block?
A CIDR block is a range of IP Addresses, and a CIDR notation is a way of representing a CIDR block. 
### How many octets are found in an IPv4 address?
four 8-bit decimal numbers or “octets” separated by dots.
### Setting binary aside and using the decimal system, what is the range of numbers found in an octet?
An octet can represent numbers from 0 to 255.
### What does the final digit after the “/” represent in an IPv4 address?
“/” represents how many bits make up the mask.
### How many IP addresses are in the CIDR block 10.0.0.0/24?
 10.0.0.0/24 will give us a range of 10.0.0.0–10.0.0.255, which is just 256 (or 2⁸) IP addresses.


### In your own words, describe network segmentation.
Picture a house party. Network segmentation is like separating different areas for different vibes.
The living room is the Guest Zone. It's open to everyone, but they can't access the private stuff in the bedrooms (servers).
The kitchen is the Snack Station. Gaming consoles and smart TVs (IoT devices) can connect here for maximum munchie-fueled fun, but they're firewalled off from messing with the music system (critical systems).
Your room is the VIP Lounge. Only your close friends (authorized devices) get the wifi password for access to the best speakers and streaming services.
This way, if the punch bowl overflows in the kitchen (a device gets hacked), the party in the VIP lounge (your secure network) keeps going strong. Plus, everyone can still connect and have a good time without causing any connection chaos!

### Network segmentation isn’t important as long as the network is using a well configured firewall. Do you agree? Why or why not?
No, network segmentation is still important even with a well-configured firewall. Think of a firewall as the bouncer at the club (network). They check IDs (data packets) to see if they're legit. But even with a good bouncer, someone might sneak in or get a fake ID. Segmentation creates separate VIP sections (secure zones) to make it harder for unauthorized people to access sensitive areas, even if they get past the initial check.
### What is a screened subnet?
Think of it like this, instead of letting the DJ walk straight into your party, they wait in a secure area (DMZ Subnet) and only interact with your friends through a designated point of contact (controlled connection). This way, even if the DJ tries something suspicious, your friends and your party are safe inside the VIP lounge (internal network).
### Cameras, ID card scanners, locked doors and biometrics are just a few examples of what type of security?
Physical security. This type of security focuses on protecting physical spaces, people, and assets from unauthorized access, theft, damage, or other threats. It achieves this through a combination of:
Deterrence: Measures that discourage potential threats, like security cameras and signs.
Access control: Systems that restrict entry to authorized individuals only, like ID scanners, locked doors, and biometrics.
Detection: Alarms, sensors, and other tools that identify and alert authorities of a security breach.
Delay: Measures that slow down intruders, giving security personnel time to respond, such as strong doors and fences.

### Things I want to learn more about:
I need to find another way to understand IP Addresses, octets, and masks better.
