# OSI Model

The OSI model is a framework that standardizes the functions of a networking or telecommunication system into seven distinct layers. Each layer represents a specific set of functions and services that work together to facilitate communication between devices and systems. 

## Layer 7 Application
The highest layer interacts directly with user applications, which provide an interface, which provides an interface for applications to access network services such as email, file transfer, remote access, and more. 
Examples: Web browsers, Email clients, Video streaming apps

## Layer 6 Presentation
This layer is responsible for data translation, encryption, compression, and formatting. It ensures that data exchange between different systems is in a format that both sender and receiver can understand.
Examples: Data compression, encryption, and data translation.

## Layer 5 Session
The Session layer establishes, manages, and terminates communication sessions between applications on different devices. It ensures synchronization checkpointing and recovery of data exchange in case of failures.
Examples: Manage logins, maintaining user sessions

## Layer 4 Transport
This layer ensures end-to-end communication and data transfer reliability between two devices on separate networks. It provides mechanisms for segmenting, sequ3encing, and reassembling data, as well as flow control and error corrections. 
Examples: TCP/UDP

## Layer 3 Network
The network layer manages routing and forwarding of data packets between different networks. It handles logical addressing, such as IP addresses, and determines the best path for data to travel from the source to the destination across different network segments.
Examples: IP, Routing protocols like OSPF, NAT

## Layer 2 Datalink
This layer is responsible for framing raw bits into data frames, error detection, and addressing within a local network segment. It ensures reliable point-to-point and point-to-multipoint communication within a single network segment.
Example: Ethernet, MAC address

## Layer 1 Physical 
This is the lowest layer and deals with the physical transmission of raw data bits over the physical medium, such as cables, wires, and wireless signals. It defines attributes like voltage levels, cable types, and bit rates.
Example: Ethernet cables, WiFi

