The uni has two campus, with one DMZ at Main campus. It supposed to be only one server farm and one wireless controller located at Main campus to support both two campus, however pkt doesn't support dhcp relay on ASA firewall, so have to add ones to Branch campus for presenting functioning.

Technology implemented:
• 3 tiers network architect
• IP subnetting
• VLAN
• Inter-vlan trunking (distribution switch SVI)
• Link aggregation (LACP)
• Redundancy and load balancing (HSRP)
• OSPF single area 
• BGP (routing between ISP and Internet)
• Routes redistribution (OSPF & BGP)
• Static default route
• DHCP server (DMZ) and DHCP relay
• Wireless LAN controller & lightweight access points
• Site-to-site IPsec VPN tunnel (on ASA firewall) (As pkt doesn't support NAT exclusion, VPN was configured but disabled to prioritize the functioning of NAT)
• NAT overload (PAT on ASA firewall)
• Zone-based policies (inside, outside, DMZ on ASA firewall)
• Extended access control list (ACL)
• Spanning tree spruning (port cost was modified on D1 to achieve better load balancing)
• SSH (allow only IT engineer access)
• Switch port security (portfast and bpduguard)

<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/e9050429-c137-4c26-bf50-a9a41b91263a" width="800">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/83ccff31-ecb0-4730-854b-68dd6a3797e8" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/bebe371b-5c70-48a4-81d3-50f0f0aa0beb" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/c99eac9d-3cd0-4117-b626-41c9356d156b" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/f8d26891-2dcd-425c-bb42-d0323f9b6510" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/2508dcea-ff55-4370-8a37-725a4ee400db" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/b18d6fd8-37e9-4883-82e4-03b67c4b0c4e" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/dc1aef26-4ca6-4046-9724-df04dab5bfb3" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/9a3d38a1-4800-4072-bc19-43ed2288946b" width="600">
</div>
<br>
<div align = "center">
<img src="https://github.com/Neyko666/university-network-design-and-implementation-project/assets/171580092/07e881eb-95f1-46b4-923a-af7f5831da13" width="600">
</div>
<br>


![a72d92dd147574e224c461dd0935c31](https://github.com/user-attachments/assets/bdbc9806-7c2e-4179-bfba-f04eabf704fb)

