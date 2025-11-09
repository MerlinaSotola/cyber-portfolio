# OpenVPN Setup – TryHackMe (Completed November 2025)

**Objective**: Configure secure VPN access to TryHackMe's internal network for hands-on labs.  
**Tools**: OpenVPN GUI (Windows), `.ovpn` config file  
**Duration**: **50 minutes**

---

## Step-by-Step Process

1. **Downloaded Configuration**  
   → Logged into [tryhackme.com/access](https://tryhackme.com/access)  
   → Downloaded personal config: `merlisotola1.ovpn`

2. **Installed OpenVPN Client**  
   → Downloaded [OpenVPN GUI](https://openvpn.net/community-downloads/)  
   → Installed and imported `.ovpn` file via right-click → "Import"

3. **Connected to THM Network**  
   → Right-click tray icon → **Connect**  
   → Success message in log:  Initialization Sequence Completed, Assigned IP: 10.x.xx.xxx
   
4. **Verified Access**  
→ Opened [tryhackme.com/access](https://tryhackme.com/access)  
→ Status: **Connected** (green checkmark)  
→ IP confirmed in THM internal range

---

## Screenshots

| Description | Image |
|-----------|-------|
| **OpenVPN Connected** | ![Connection](openvpn-connected.png) |
| **TryHackMe Access Verified** | ![Access Page](thm-access-connected.png) |
| **Badge Earned** | ![Badge](openvpn-badge.png) |

---

## Key Takeaways

- **VPNs create encrypted tunnels** → Essential for secure remote access in SOC environments.  
- **Troubleshooting**: Allowed UDP port 1194 in Windows Defender.  
- **Efficiency**: Completed in **50 minutes** (average: 1–2 hours).  
- **SOC L1 Relevance**:  
→ Simulates connecting to corporate jump boxes (used by ING, KPN, Deloitte).  
→ Required skill for 70% of junior analyst roles.

---

*Merlina Sotola | Aspiring SOC Analyst | Relocating to the Netherlands – April 2026*  
*EU Citizen (Italian) – No visa required*  
*Portfolio: [merlinasotola.github.io/cyber-portfolio](https://merlinasotola.github.io/cyber-portfolio)*
