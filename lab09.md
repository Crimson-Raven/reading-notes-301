# Author: Rebecca Childs
## Reading Notes:
### Lab 09

## What are the differences between SPAN and TAP?
### SPAN (Switched Port Analyzer):
Function: Mirrors traffic from one or more ports on a switch to a designated monitoring port.
Data Capture: Limited visibility. SPAN may not capture all packets, especially under high network load. It might also miss errors or alter packet timing.
Impact on Network: Can consume switch resources and potentially degrade network performance if not configured properly.
Security: Not ideal for highly secure environments as it relies on switch configuration and might not capture all traffic.
Cost-Effective: Built into most managed switches, making it a cost-effective option for basic monitoring needs.

### TAP (Test Access Point):
Function: Creates a physical copy of the network traffic, passing it through two separate ports for monitoring tools.
Data Capture: Provides a complete and unaltered copy of all network traffic, including errors.
Impact on Network: No impact on network performance or switch resources as it's a separate device.
Security: More secure as it provides a dedicated and isolated monitoring path.
Cost: Requires purchasing additional hardware, making it more expensive than SPAN.

SPAN: Like watching a recording of a traffic light intersection on a single camera. You might miss some details or have blurry spots during heavy traffic.
TAP: Like having two separate cameras perfectly capturing all lanes of traffic at the intersection, providing a complete and unaltered view.

### What types of network devices can support network traffic mirroring?
Managed switches are the main devices that support this. You can configure them to copy traffic from specific ports to a monitoring tool.
Unmanaged switches, routers, and WAPs typically don't have this feature.
If you need more robust monitoring, you can use a separate device; a network TAP.

### How can network traffic mirroring be used for network security?
Traffic mirroring is like having security cameras on your network. It copies traffic for security tools to analyze, helping to:
Spot attacks (intrusion detection)
Find weaknesses (vulnerability detection)
Investigate security incidents
Monitor user activity
This helps security professionals identify and respond to security threats before they cause problems.

### Are there any legal or ethical considerations when using network traffic mirroring?
Legally: There are privacy laws like  GDPR (General Data Protection Regulation) and HIPAA (Health Insurance Portability and Accountability Act) and employee monitoring laws to consider. Make sure you follow them when collecting and using data from mirrored traffic. Some countries have laws restricting the interception of communications. Mirroring network traffic could be considered interception in some cases. Understanding these laws is crucial to avoid legal issues.
Ethically: Be transparent with users about mirroring and only capture what's necessary for security purposes. For user privacy, security professionals handling mirrored traffic containing personal data should be trained on handling such data responsibly and securely, to minimize the risk of privacy breaches.

## Things I want to learn more about:
N/A
