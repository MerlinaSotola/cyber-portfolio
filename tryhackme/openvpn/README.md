# OpenVPN Setup – TryHackMe (Completed November 2025)

**Objective**: Securely connect to TryHackMe's network using OpenVPN to access interactive labs.  
**Tools**: OpenVPN GUI (Windows), `.ovpn` config file  
**Duration**: **40 minutes** | **Badge**: [openvpn-badge.png] (Download from THM Profile)

---

## Step-by-Step Process

1. **Downloaded Configuration**  
   → Logged into [tryhackme.com/access](https://tryhackme.com/access)  
   → Downloaded personal config: `merlisotola1.ovpn`

2. **Installed OpenVPN Client**  
   → Downloaded [OpenVPN GUI](https://openvpn.net/community-downloads/)  
   → Installed and imported `.ovpn` file

3. **Connected to THM Network**  
   → Right-click tray icon → **Connect**  
   → Success message: flag{connection_verified}
