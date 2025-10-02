# 📘 **Day-3: Azure Networking Services**

1. **Azure Virtual Network (VNet)**

   * Private network in Azure
   * Supports subnets, IP addressing, route tables
   * Like AWS VPC

2. **Subnets & Network Security Groups (NSG)**

   * Subnets divide VNets into smaller segments
   * NSGs control inbound/outbound traffic per subnet or VM

3. **Azure Load Balancer**

   * Distributes traffic to VMs
   * Layer 4 (TCP/UDP) load balancing
   * Public & Internal load balancers

4. **Azure Application Gateway**

   * Layer 7 (HTTP/HTTPS) load balancer
   * Includes Web Application Firewall (WAF)

5. **Azure DNS**

   * Domain Name System service
   * Host and manage custom domains

6. **Azure Traffic Manager**

   * DNS-based traffic routing
   * Supports geographic routing & failover

7. **VPN Gateway**

   * Connect on-premises network to Azure via VPN

8. **ExpressRoute**

   * Private connection between on-premises and Azure
   * Higher reliability & lower latency vs public internet

9. **Azure Front Door**

   * Global HTTP load balancing
   * CDN + SSL termination + WAF

10. **Service Endpoints & Private Link**

    * Secure access to Azure services via private IPs
    * Similar to AWS VPC Endpoints

11. **Hands-On Practice**

    * Create a VNet with 2 subnets
    * Attach NSG to subnet and allow/deny ports
    * Deploy VM in subnet and test connectivity
    * (Optional) Set up Load Balancer for 2 VMs
    * Explore Traffic Manager & Front Door basics

---