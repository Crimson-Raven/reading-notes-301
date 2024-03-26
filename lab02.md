# Author: Rebecca Childs
## Reading Notes:
### Lab 02

### What is a port? Describe it with an analogy that would help a family member understand.
Imagine your computer is a cool clubhouse! You and your friends use different doors to get in for different activities.
One door (port) might be for movie nights (video streaming program).
Another door (port) might be for video games (gaming programs).
These special doors, with fun names like "movie door" or "game door" in your head, are actually ports. They help your computer know which program to send the information to, just like you wouldn't use the movie door to enter a game night.
### What does a port scanner send to a port to check the current status?
A port scanner sends a packet of network data to a port to check the current status.
### When a port scanner sends a request to connect, what are the three possible responses? Describe them.
Open, Accepted - This means the port is open and there's a program listening and ready to receive information.
Closed, Not Listening - The computer acknowledges the request but lets the scanner know there's no program actively using that port right now.
Filtered, Dropped, Blocked - The request is received but this leads to no messages or response. This could be because of a firewall blocking the scanner's attempt to connect, making it hard to tell if the port is open or closed.
### What is the difference between TCP and UDP?
TCP and UDP are the two most common protocols in use for Internet Protocol (IP) networks. UDP scans are slower than TCP scans. 
TCP (Reliable): TCP sends each packet in order, complete with error checking, verification, and a 3-way handshake to confirm each packet is successful. Perfect for important messages where everything needs to be correct (like downloading files or sending emails).
UDP (Fast):  Doesn’t have any error checking but tends to be faster. Great for quick chats where a missed word or two isn't a big deal (like online games or video calls).

### List and describe the ports used for the following:
Telnet - TCP Port 23. It lets you control another computer directly, except everything you type is visible. 
SSH - TCP Port 22. This is the more modern way to remotely control a computer. This is similar to Telnet consoles, except all of the information is sent across the network in encrypted form, instead of clearly visible.
DNS - TCP or UDP Port 53. This is like your phone's address book for websites. When you type a web address, DNS translates it into a number the computer understands, like looking up a friend's phone number in your contacts.
SMTP - TCP Port 25. This is the post office for emails. When you hit "send," your email travels through this doorway to reach the recipient's email server.
HTTP - TCP Port 80. When you visit a website, your computer uses this port to talk to the website's server and display the content on your screen.
HTTPS - TCP Port 443. This is like HTTP but with extra security, like a website wearing a padlock. It encrypts information you send and receive, making it harder for other people to see. Important for things like online banking or shopping.
RDP - TCP Port 3389. RDP lets you see and interact with another computer's entire desktop environment remotely, useful for tech support or accessing work applications from home.
Ping - No Port Needed. The computer sends a quick message to another device to check if it's reachable on the network. It doesn't use a specific port because it uses a different language computers understand.

## Things I want to learn more about:
I'm curious to know when, why, and how all of these ports were discovered. Were they faulty at first, or did they always work as intended? 