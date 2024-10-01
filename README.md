# Office Network Setup and Configuration Using Simulation and Network Analysis Tools

## Overview
This project involves setting up and configuring a simulated office network using industry-standard network simulation and analysis tools. The goal is to design, implement, and troubleshoot a network that includes routers, switches, and other essential components, ensuring secure and efficient connectivity.

## Objective
To design and configure a small office network using advanced simulation tools, and to document the network design, implementation, and troubleshooting steps.

## Skills Learned
- Network design and documentation
- Router and switch configuration
- VLAN setup and management
- IP addressing and subnetting
- Network troubleshooting and traffic analysis

## Tools Used
- **Cisco Packet Tracer**: For network simulation, device configuration, and routing protocol implementation.
- **Wireshark**: For capturing and analyzing network traffic in real-time.
- **draw.io**: For creating network diagrams and documenting the architecture.

## Steps and References

1. **Network Planning and Design**
   - Used **draw.io** to create a detailed network diagram, outlining the physical and logical layout of the network, including IP addressing schemes and subnetting.  
     ![Network Diagram Placeholder](path/to/network_diagram.png)  
     **Reference:** Network diagram created with draw.io.

2. **Simulation Setup in Cisco Packet Tracer**
   - Built the network topology in **Cisco Packet Tracer**, adding routers, switches, PCs, and servers according to the design.  
     ![Packet Tracer Topology Placeholder](path/to/packet_tracer_topology.png)  
     **Reference:** Network topology setup in Packet Tracer.

3. **Router and Switch Configuration**
   - Configured routers with appropriate interfaces, IP addresses, and routing protocols (e.g., OSPF or EIGRP).
   - Set up switches with VLANs to segment network traffic and improve security.  
     ![Router Configuration Placeholder](path/to/router_configuration.png)  
     **Reference:** Router and switch configuration scripts in Packet Tracer.

4. **IP Addressing and Subnetting**
   - Assigned IP addresses to all devices based on the subnetting plan.
   - Ensured that devices within the same VLAN/subnet can communicate.  
     ![IP Addressing Placeholder](path/to/ip_addressing.png)  
     **Reference:** IP addressing table and device configurations.

5. **VLAN Configuration**
   - Created multiple VLANs on switches to isolate network traffic based on department or function (e.g., VLAN for HR, Finance, IT).
   - Configured trunk ports to allow VLAN traffic between switches and ensure scalability.  
     ![VLAN Configuration Placeholder](path/to/vlan_configuration.png)  
     **Reference:** VLAN setup and port assignments.

6. **Inter-VLAN Routing**
   - Configured inter-VLAN routing on routers or multilayer switches to enable communication between different VLANs.  
     ![Inter-VLAN Routing Placeholder](path/to/intervlan_routing.png)  
     **Reference:** Inter-VLAN routing configuration.

7. **Network Connectivity Testing**
   - Used **ping** and **traceroute** commands in Packet Tracer to test connectivity between devices.
   - Verified that devices in the same VLAN can communicate and that inter-VLAN routing works as expected.  
     ![Connectivity Testing Placeholder](path/to/connectivity_testing.png)  
     **Reference:** Connectivity test results.

8. **Network Traffic Analysis with Wireshark**
   - Integrated **Wireshark** within Packet Tracer to capture and analyze network packets.
   - Monitored traffic to verify that data is routed correctly and that VLAN tagging is functioning as designed.  
     ![Wireshark Analysis Placeholder](path/to/wireshark_analysis.png)  
     **Reference:** Wireshark capture files and analysis.

9. **Security Configuration**
   - Implemented security measures such as setting up passwords for device access, enabling SSH, and disabling unused ports.
   - Configured firewalls to filter incoming and outgoing traffic, ensuring network security.  
     ![Security Configuration Placeholder](path/to/security_configuration.png)  
     **Reference:** Security configurations on network devices.

10. **Documentation**
    - Compiled all configurations, diagrams, and testing results into a comprehensive report for network documentation.  
      ![Documentation Placeholder](path/to/documentation.png)  
      **Reference:** Project documentation and summary report.

## Challenges and Solutions
- **Challenge:** Understanding the intricacies of VLANs and inter-VLAN routing.
  - **Solution:** Researched Cisco documentation and tutorials to correctly configure VLANs and troubleshoot routing issues.
  
- **Challenge:** Capturing live traffic in a simulated environment.
  - **Solution:** Utilized Packet Tracer's built-in simulation mode and Wireshark integration to analyze packet flows.

## Results
- Successfully designed and implemented a simulated office network.
- Demonstrated proficiency in network device configuration and troubleshooting.
- Gained experience in network documentation and use of advanced simulation tools.

## Learning Outcomes
- Enhanced understanding of network design principles and best practices.
- Improved skills in configuring network devices using Cisco IOS commands.
- Gained practical experience in network troubleshooting and traffic analysis.

## Next Steps
- Explore more advanced topics like dynamic routing protocols (e.g., BGP), network security features (e.g., ACLs, NAT), and WAN technologies.
- Implement the network in a real-world lab environment using physical devices or more advanced simulators like GNS3.

