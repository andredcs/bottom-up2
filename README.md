# Network Troubleshooting Methods

## Overview
In networking, troubleshooting is an essential skill that ensures smooth operations, minimises downtime, and maintains optimal performance, my mentor says ***"If you are a problem-solver anything is possible".*** When facing issues within a network, employing a structured approach is key to efficiently identifying and resolving problems. One such approach, known as the "Bottom-Up" troubleshooting method, is particularly effective when dealing with complex network architectures, such as the OSI (Open Systems Interconnection) model.

**The OSI model, with its seven layers representing different aspects of network communication, provides a framework for understanding how data moves through a network.** 

## Description
• Explore advanced troubleshooting methodologies and techniques used in computer networking.

• Develop proficiency in using diagnostic tools and software applications for network analysis to minimises downtime and maintain performance of the network.

• Learn how to identify, diagnose, and resolve complex network issues efficiently.

• Gain practical experience in troubleshooting common and uncommon network problems.

• Understand the impact of network architecture, protocols, and configurations on troubleshooting strategies.

• Enhance communication and collaboration skills for effectively working in multidisciplinary teams.

• Prepare for industry certifications and career advancement opportunities in computer network aiming Cisco technologies.

## Definitions

### OSI Model 

### Physical Layer (Layer 1):

The physical layer is responsible for transmitting raw data bits over the physical medium (e.g., copper wires, optical fibers).
It defines characteristics such as voltage levels, data rates, and physical connectors.
Examples of devices and technologies at this layer include hubs, repeaters, cables, and network interface cards (NICs).

### Data Link Layer (Layer 2):

The data link layer ensures reliable transmission of data frames between adjacent network nodes over a physical link.
It handles tasks such as framing, error detection and correction, and flow control.
Technologies and protocols operating at this layer include Ethernet, Wi-Fi (802.11), and Point-to-Point Protocol (PPP).

### Network Layer (Layer 3):

The network layer is responsible for routing and forwarding data packets between different networks.
It provides logical addressing, network topology identification, and packet switching.
Common network layer protocols include Internet Protocol (IP), Internet Control Message Protocol (ICMP), and Routing Information Protocol (RIP).

### Transport Layer (Layer 4):

The transport layer ensures end-to-end data delivery and reliability across a network.
It segments and reassembles data from upper layers into manageable units (segments or datagrams).
Protocols at this layer include Transmission Control Protocol (TCP) for reliable, connection-oriented communication, and User Datagram Protocol (UDP) for connectionless, unreliable communication.

### Session Layer (Layer 5):

The session layer establishes, manages, and terminates communication sessions between applications on different network nodes.
It handles functions such as session establishment, synchronization, and checkpointing.
Common protocols and technologies associated with the session layer include Remote Procedure Call (RPC) and NetBIOS.

### Presentation Layer (Layer 6):

The presentation layer is responsible for data representation, encryption, and compression.
It ensures that data exchanged between applications is presented in a format that can be understood by both sender and receiver.
Examples of presentation layer protocols include ASCII, JPEG, and SSL/TLS for secure communication.

### Application Layer (Layer 7):

The application layer provides network services directly to end-users and applications.
It includes protocols and services for tasks such as file transfer, email, web browsing, and remote access.
Common application layer protocols include HTTP, FTP, SMTP, and DNS.

![original-seven-layers-of-osi-model-1627523878-JYjV8oybcC](https://github.com/andredcs/bottom-up2/assets/164593389/8d0e32f2-0eb8-4f77-8b10-8398e76854b9)

## Features

### Structured Troubleshooting

**The bottom-up approach:** This approach starts from the OSI model’s physical layer and moves-up toward the application layer.

![Screenshot 2024-03-23 160232](https://github.com/andredcs/bottom-up2/assets/164593389/27d04120-d6dd-4f55-b297-f4014f2b13d3)

Kepner tregoe 5W

1. Who is experiencing the problem?
2. Why is this important, why is this  being done?
3. What are the effects/symptoms – errors/defects or something you expected doesn’t happen?
4. When does the problem occur or when did it start happening?
5. Where does the problem occur?
   
![Screenshodasdt 2024-03-23 151551](https://github.com/andredcs/bottom-up2/assets/164593389/54f6dfba-2088-4028-842a-74ede025ad1b)


## Practice

• To practice we did a Cisco packet tracer lab with a real situation problem.

![Screenshot 2024-03-23 153914](https://github.com/andredcs/bottom-up2/assets/164593389/698a2beb-bfbd-49b9-b72d-8c07fbf4f569)

Bottom-up approach

### Physical Layer (Layer 1):

Begin troubleshooting at the physical layer, which deals with the actual transmission and reception of data signals.
Check for issues such as cable connectivity, signal strength, and physical damage to network devices.
Utilize tools like cable testers and network analyzers to diagnose problems at this level.

### Data Link Layer (Layer 2):

Once physical layer issues are ruled out, move up to the data link layer.
Verify the proper functioning of network interfaces, switches, and MAC addresses.
Look for errors in frame transmission, collision detection, and media access control.

### Network Layer (Layer 3):

Proceed to the network layer, where routing and addressing take place.
Check for IP address conflicts, routing table issues, and routing protocol configurations.
Use diagnostic tools like ping and traceroute to identify connectivity problems and routing issues.

### Transport Layer (Layer 4):

Move up to the transport layer, responsible for end-to-end communication and data reliability.
Verify proper operation of transport layer protocols such as TCP and UDP.
Look for issues related to port numbers, packet loss, and congestion control mechanisms.

### Session, Presentation, and Application Layers (Layers 5-7):

Finally, examine the session, presentation, and application layers collectively.
Check for software-related issues, such as misconfigured applications, firewall rules, and security policies.
Verify the proper functioning of application layer protocols like HTTP, FTP, and SMTP.

## Contributing

To remind the definition of each layer and what is in a frame Ethernet I have this background on my computer which I read whenever I turn on my PC, any better suggestions? :D 

![Hollow Ichigo - OSI](https://github.com/andredcs/bottom-up2/assets/164593389/fc351df3-a58c-4731-8a5d-03928ac841ac)

