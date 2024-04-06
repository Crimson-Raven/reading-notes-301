# Author: Rebecca Childs
## Reading Notes:
### Lab 12

### Explain the role of a Domain Controller?
A Domain Controller (DC) is the boss in a Windows network domain, keeping things secure and organized. Imagine it as a high-security club bouncer, manager, and IT chief all rolled into one.
Authentication: The DC checks usernames and passwords to make sure only authorized users get in.
Authorization: Even with valid credentials, the DC controls what actions users can take (read, edit, full control) based on their role.
Active Directory: The DC stores user and group information in a central database, like a digital phonebook for the network.
Group Policy: The DC sets rules (e.g., security settings) for everyone in the domain, ensuring consistency.
Security Updates: The DC can distribute security updates to keep all machines protected.
Replication: To avoid downtime if one DC fails, information is copied to backups so another DC can take over.
Overall, the DC ensures a secure and orderly network by controlling access, permissions, and security policies.

### What is the benefit of being able to login with the same username and password on any computer joined to the domain? What are the security risks?
Using the same login credentials across all domain-joined computers offers convenience (one login for all machines) and centralized management, but comes with security risks.
Benefits: Easy for users, easier management of passwords across the domain, potentially roaming user profiles.
Risks: One compromised login compromises everything the user has access to, weaker passwords due to ease of use, and potential for hackers to move laterally within the network.
To mitigate these risks, use strong password policies, multi-factor authentication, and the principle of least privilege (give users minimum access needed). Ideally, move towards more secure login methods like MFA in the future.

### Describe how group policies are used in domains?
Group Policy in domains is like a company handbook for computers.
Group Policy Objects (GPOs): These are containers that hold settings like security, software installations, or desktop layouts.
Active Directory: This directory links GPOs to users, groups, or departments (OUs) in the domain.
Application: When a user or computer logs in and their Active Directory object is linked to a GPO, those settings are applied.
This allows administrators to centrally manage settings across the domain for:
Security: Enforce strong passwords, restrict folder access, configure security software, Software Management: Deploy and update software automatically, Desktop Management: Control wallpaper, screensavers, or taskbar layouts, and Network Settings: Configure printers, folder redirection, or internet access.
Benefits include:
Centralized control for less work, consistent settings across the domain, easy management of settings for many users/computers, and improved security through central enforcement.

### In what other ways can you think of that domains could be used beyond what was presented in the reading?
Domains aren't limited to just traditional Windows networks. Here are some additional uses:
Cloud Domain Services: Manage user access and identities for both cloud-based applications (like Office 365) and on-premises resources using Azure Active Directory.
Web Application Access Control: Some web apps can use domain credentials for login, simplifying the process and leveraging existing security measures.
Research/Education Environments: Domains can control access to shared computing resources, research data, or software licenses based on user roles (e.g., students vs. professors).
Domain-joined IoT Devices: Domains can be used to manage and secure internet-connected devices (like smart sensors or building automation systems).
Domain-based Mobile Device Management: Some mobile device management solutions can integrate with domains for access control and security management using existing credentials and policies.
As technology evolves, so will the ways domains are used. The core idea of centralized control for authentication, authorization, and management can extend beyond traditional Windows networks.

## Things I want to learn more about:
N/A
