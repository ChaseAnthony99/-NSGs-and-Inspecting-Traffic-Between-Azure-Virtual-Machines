<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

Create Network Security Groups (NSGs).

Associate NSGs with Virtual Machines (VMs).

Define inbound and outbound security rules in NSGs.

Use Azure Network Watcher or monitoring tools.

Inspect and monitor network traffic between VMs.

Set up network monitoring and logging.

Implement network security best practices.

Enable Azure's network security features.



<h2>Actions and Observations</h2>


Actions:

Create NSGs to define inbound and outbound security rules.

Associate NSGs with Azure VMs' network interfaces.

Define rules to allow or deny specific protocols, ports, or IP addresses in NSGs.

Set up network monitoring using Azure Network Watcher or third-party tools.

Enable logging and monitoring features for network traffic analysis.

Regularly update NSG rules based on security requirements and assessments.

Observations:

Monitor incoming and outgoing traffic to VMs based on NSG rules.

Identify and analyze any unauthorized or suspicious network traffic.

Check for compliance with security policies and regulations.

Detect and respond to anomalies or security incidents in network traffic.

Review logs and reports to assess network security posture and performance.

Continuously evaluate and refine NSG configurations for optimal security.

