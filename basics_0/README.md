##NETWORKING BASICS_0

<img width="628" alt="table-tcp-udp" src="https://github.com/user-attachments/assets/6d03159a-bff0-4d3c-96df-0ce6c59de4f7">


## OSI Model

### What it is
The OSI Model (Open Systems Interconnection Model) is a conceptual framework used to understand and implement network protocols in seven layers.

### How many layers it has
The OSI Model has 7 layers:
1. Physical Layer
2. Data Link Layer
3. Network Layer
4. Transport Layer
5. Session Layer
6. Presentation Layer
7. Application Layer

### How it is organized
Each layer in the OSI Model performs a specific function and passes data to the next layer. The Physical Layer deals with the transmission of raw bits over a physical medium, while the Application Layer interacts with software applications.

## LAN (Local Area Network)

### Typical usage
A LAN is typically used to connect devices within a small geographical area, such as a home, office, or group of buildings.

### Typical geographical size
A LAN usually covers a single building or a small group of buildings.

## WAN (Wide Area Network)

### Typical usage
A WAN is used to connect multiple LANs over a large geographical area, such as different cities, countries, or even globally.

### Typical geographical size
A WAN can cover large areas, ranging from cities to continents.

## The Internet

### What it is
The Internet is a global network of networks that connects millions of private, public, academic, business, and government networks.

## IP Address

### What it is
An IP address is a unique numerical identifier assigned to each device connected to a network.

### What are the 2 types of IP address
1. IPv4: The older format, e.g., 192.168.1.1.
2. IPv6: The newer format, e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334.

## Localhost

### What it is
Localhost is a special IP address (127.0.0.1) that refers to the current device. It is used for testing and development purposes.

## Subnet

### What it is
A subnet is a portion of a larger network that shares a common address component. It helps in organizing and managing the network.

## Why IPv6 was created
IPv6 was created to address the limitations of IPv4, such as the exhaustion of IPv4 addresses, and to provide improved security and performance features.

## TCP/UDP

### What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)
1. TCP (Transmission Control Protocol)
2. UDP (User Datagram Protocol)

### What is the main difference between TCP and UDP
TCP provides reliable, ordered, and error-checked delivery of data, while UDP provides best-effort delivery with no guarantee of reliability or ordering.

## Port

### What it is
A port is a number that identifies a specific service or application on a device.

### Memorize SSH, HTTP, and HTTPS port numbers
- SSH: 22
- HTTP: 80
- HTTPS: 443

## Tool/Protocol often used to check if a device is connected to a network

### What it is
The `ping` command, which uses the ICMP (Internet Control Message Protocol), is often used to check if a device is connected to a network.
