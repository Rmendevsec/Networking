

## Topics

- Introduction to networking
- Classification of networks
- IP Address
- Mac Address
- OSI Model
- TCP and UDP protocols
- TCP/IP Model
- Networking tools

## Introduction to network

- A **Network** is when two or more devices are connected to share resources and information.
- A **Computer Network** lets computers **communicate** and **share files, internet or, printers** either in the same network or across different ones.
- Networking makes device work together more efficiently
- Computers on a network can act as a **client** or a **server**

## Client Computer

- A client is a computer that requests for resources.

## Server Computer

- A server computer is a computer that controls and provides access to resources.
- But have higher RAM, CPU, and STORAGE.

## Server rack

- It **holds and organize** hardware used in networking and data centers.
- Common components:
	- Switch:- Connects multiple devices in a network
	- Modem:- Connects the network to the internet
	- Servers:- Store, manage, and process data
	- Firewall:- Protects the network from threats
	- Display:- Monitor for managing or troubleshooting devices.
## Need of Networking

- Networks are important because they:
	- Enhance communication (email, chat, calls)
	- Share Resource (files, printers ,internet)
	- Enable centralized management (control users/devices)
	- Provide internet access and global connectivity

## Classification of Network

1. Classification by network Geography
2. Classification by component roles


## I) Classification by network Geography

- Networks grouped by how much area they cover:

	- **LAN**: SMALL ARE LIKE HOME OR OFFICE
		- It is inexpensive to install and also provide higher speeds. 
	- **MAN(METROPOLITAN AREA NETWORK)**: CITY-WIDE NETWORK
		- The cost of installation and operation is higher 
		- It uses high speed connections like (fiber optics)
		- Ideal for connecting multiple buildings or offices in a city
		- Faster than LAN, but costlier to install it 
	- **WAN(WIDE AEA NETWORK)**: COVERS LARGE AREAS OR COUNTRIES
		- Covers **Large areas(like countries or continents)**
		- **More expensive** than MAN or LAN
		- **Internet** is the best example of WAN

## II) Classification by component roles

- Networks are grouped by the **roles of devices**
- Main types:
	- **Peer-to-peer** - All devices are equal
	- **Server-based** - One or more servers provide services
	- **Client-based** - Clients request services from servers

## Peer-to-Peer Network

- All components are equal
- Each can act as **client or server**
- **Cheap and easy** to set up
- Ideal for **homes or small offices**
- Supports up to **10 devices**
- Devices **share resources** directly with each other.

## Server based

- Uses **central server** to control the network
- Designed for **secure and organized** operations 
- The server stores **data, apps and resources**
- Clients connect to the server to access what they need 

## Client-Based network

- **Clients send requests,** servers return results
- Uses the **Processing power** of both client and server
- Efficient for tasks like databases or web browsing

## IP Address

- **IP** stands for internet protocol
- It's used to **identify devices** on a network
- Each device has a unique IP Address
- Works at the **network layer** of communication
- Used for:
	- **Connecting devices**
	- Sharing files, internet, emails
	- **Identifying computers**

## Types of IP

- **IPv4** - 32-bit, written like 192.169.0.1
- **IPv6** - 128-bit, written like FE80::1A2B:3C4D
- IPs are given by:
	- **DHCP(automatic)**
	- **Manual(static)**

## Structure of IPv4

- 4 sections (octets), each 8 bits (0-255)
- Split into:
	- **Network part** - like our neighborhood
	- **Host part** - like our house (device)
- The first **host** is called the **Gatetway**

## Private vs Public Ip

- **Private IP** - used inside our home or office (LAN)
- **Public IP** - used on the internet (WAN)

>> Every device has both: one private + one public

## IP Classes


| Class | Used For         | Host Bit | Example use          | First Octet Address Range |
| ----- | ---------------- | -------- | -------------------- | ------------------------- |
| A     | Governments      | 24       | Large Networks       | 0-127                     |
| B     | Medium Companies | 16       | Universities         | 128-191                   |
| C     | Small Companies  | 8        | Home, School, Office | 192-223                   |
| D     | Multicasting     | __       | Streaming services   |                           |
| E     | Research/Future  | __       | Reserved             |                           |

## Reserved IPs (cannot be used)

- **127.0.0.1** -> **Loopback** (our own machine)
- **0.0.0.0** -> Default/unknown
- **255.255.255.255** -> **Broadcast**

## IPv6

- It is a newer version of IP
- It uses a **128-bit** alphanumeric address
- Written with **colons (:)** -> e.g. `FE80:CD00:0000:....`
- Provides **more address space** than IPv4 (128-bit vs 32-bit)
- IPs are often **auto-generated**
## How to check Our IP

- Windows: **ipconfig**
- Linux: **ifconfig** or **ip a**
- Public IP: Search "What is my IP" on **browser**

## Mac address

- MAC = **Media Access Control** Address
- Give by the **device manufacturer**
- Unique to our **network adapter** (wifi or Ethernet)
- Format: **00-15-C5-49-04-A9** (48-bit hex)

## Mac Address Structure

- First 24 bits -> **Manufacturer ID (e.g. Dell)**
- Last 24 bits -> **Device ID** (unique per device)
	- MAC = hardware ID
	- IP = Software ID (can change)


## OSI(Open System Interconnecting) Reference Model

- **OSI** is a standard model for how networks work
- Created to help **different devices communicate**
- Defined in **ISO 7498**
- It has **7 layers**
- Shows **how data moves** from one device to another

## OSI Layers

- **Layers 1-4** -> Handle **data transfer** (Communication)
- **Layer 5-7** -> Handle **user interaction** (applications)
- Senders uses the layers **top to bottom**
- Receiver uses them **bottom to top**

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUehhHEXF2i22Xoz202WJey81FVynzlXvvpUOXxfpcShKMmEl-ziShFSavcsQZMYa-nJR1BtKap5oyH-qR1BJBiQwoRzZsSXcDCCktbfXUSERUwsSECLOKhe7Y7yta-ZcFOo4ntjc6yc5kpGrBC6snXb94m3zgma=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## The way data transfer

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUeKLBmqLh7URZOy9YeUOpKAaDuZaI1iaTPCfm9ec1RNxXKrw-5DX3K5INuaoYBMZN76LKNvkbAN2vKqYaoTH6gzYFJf3kVDHEK71wyc_QTR86H-L_NjD65tJPbpg82FnNR97jDq67hpZTZuwV2XKHPVMAZYmvjR=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## Layer 7: Application Layer

- Closest to the **user** 
- Provides **network services** to apps like browsers, email, file sharing
- Our info is treated as **DATA**

Examples:

- **HTTP**(web)
- **FTP** (file transfer)
- **SMTP** (email)

## Layer 6: Presentation Layer

- Handles **how data presented**
- Translates, **encrypts and compress** data
- Makes data is in a **readable format** for the receiver
- Our data is still **DATA**

Example:

- **SSL** (for secure data)

## Layer 5: Session Layer

- Manages **sessions** between two devices
- Controls **start, use and end** of communication
- Handles **dialog control, timing, and sync** 
- Used in **file transfer, remote login,** etc..
- Our data is still **DATA**

Example:

- **RPC**
- **NETBIOS**

## Layer 4: Transport Layer

- Manages **data delivery** between devices
- **Splits** data into packets (sender)
- **Reassembles** packets (receiver)
- Handles **errors, resends lost data, and ensure correct order**
- Our data is called **SEGMENT**

==Protocols==

- **TCP** - Reliable
- **UDB** - Fast, no guarantee

## Layer 3: Network Layer

- Handles **IP addressing** and **routing**
- Finds **best path** for data to travel
- Manages **traffic, congestion, and packet delivery**
- Translates **logical** <-> **physical addresses**
- Our data is called **PACKET**

==Protocols==

- **IP, ICMP, ARP, NAT**

## Layer 2: Data Link Layer

- Converts **raw bits** into **frames**(structured data)
- Ensures **reliable delivery** over the physical link
- Waits for **acknowledgment, and resends** if needed
- Works directly with hardware (like switches)
- Our data is called **FRAMES**

==Protocols==

- **PPP, NDP, CDP**

## Layer 1: Physical Layer

- Sends **raw bit** (0s and 1s) through wires or signals
- Defines **cables, voltages, connectors, and signals**
- Controls **how data is physically sent** over the medium
- Our data is called **BITS**

==Protocols/Devices:==

- **RS-449, cables hubs, NICs, repeaters**

## TCP and UDP

## ==TCP (Transmission Control Protocol )==

- **Reliable and Connection-Oriented**
- Creates a connection before sending data (3-way handshake)
- Makes sure all data arrives **correctly and in order**
- Used for:
	- Emails
	- Chat apps
	- Online videos
	- Web browsing

## ==UDP (User Datagram Protocol)==

- **Connectionless** (no handshake)
- Less **reliable**, but faster
- Sends data without checking if it arrives
- Used for:
	- Online gaming
	- Live streaming
	- Voice/Video calls

## TCP/IP Model

- A **reference model** like OSI, but **more practical**
- It is the **most widely used** model today
- Has **4 layers** (used to be 5)

### 4 Layers of TCP/IP

1. **Application** - (Apps, HTTP, FTP, DNS)
2. **Transport** - (TCP, UDP)
3. **Internet** - (IP, ICMP)
4. **Network Access** - (MAC, hardware-level communication)

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUd1J7_18aKZJAFBrfbv_lMishFx8FJ7bOPFCVoUwXHq0Sm1ypc8VXTxucGEDEytBDQpqBTluB88fgApbaDwg6DTjikqy7ZlwmWNPsMT6gdK8mmL-EbWVSl8yuGKOkYO00j0kwgaY5R8R74rpNoNmqfPVgTsZikd=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcq27xY9vPhc7vRNtklsGoEfoehNvfK3oyFNrCjHWHEQpK4wlyvWWCRcMTz-MJdpnYhlfa06aJCEXLk_i9WqpS1c9oFNtHwsQ6TEgngAw_fa7nthmdfTtvNKEqObPuoFcnpTTIEl5mwbKwgqWvZUpCrVt_cm581=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

- In the **TCP/IP** model, some OSI models are **combined**.
	- **Application Layer** = OSI's **Application + Presentation**
	- **Network Access Layer** = OSI's **Data Link + Physical**

## Firewall

- It is a security tool that **controls network traffic**
	- It **allows or blocks** data based on **rules**
	- Protects our system for **unauthorized access**
	- Works like a **gatekeeper** for our network
- Example: Blocks access to certain hosts from outside network


**![What is Firewall? - An Introduction Guide](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcoO9I2650KbAQ3qxuBg7dLiXJmx4nOFLvUaQ1DzQHmexbdjOffHMe3kSPi2sl_0tkYB-sasFxnQeyEfUirNfS28alsmKu-9pgMnsUGdRz6d9VHXfBFVFiyLpeM5Et8B2a8IXFHzX0PtgMkaH3gPAwoOI_I0r1t=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## Firewall hardware
**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUe9tDLi0yYGhoVbTZgYT2NI1TUU6VrDb7D7Cjia6OxL3eTI3aYAne5MX50t7tW_4-o-CVgSfy8SvwLnFwbBGNFXKqfZ01HUUSRYCKKcV_uWdzSon98yhTW_L0_BR7gt8QJ6Nk1If4hQssGxTdolCwp8lJKq3qnI=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

==But every OS have firewall Built-in==

## Networking tools

## 1. The Switches

- It **connects multiple devices in a Local Area Network(LAN)**
- It **forwards data** only in the device it's meant for (unlike hubs)
- Works at **OSI Layer 2 (Data Link Layer)**
- Improves **speed, efficiency, and security** in a network

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcZziL9w1QfcPyp_i4le5gpmc9w7w6fOmIR9l9TBU_s_K30VGoi-x4nkK7GZgKgaHEhkDnm0NUapa6bP9a8O3vfXBROqL89Mk6MEvpmD4Z-F2jPxdt63K7QmjzMZjebXglbK70wZQNUEjGeA2hWsHHryLuGizk=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## 2. Switches/Hub and Routers

- **Switch:** Connects devices within a LAN, sends data only to the right device
- **HUB**: Connects devices but sends data to all devices (less efficient)
- **Router:** Connects different networks (like our home network to the internet) and directs data between them
**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUcajRXQyKbXiwKqWhGU99vJrWD5akETo61HMhDaZIODPLlQgSA8gBg8njywjorU2W3aTS_BOIztIWQ7AkFcu-ehpHjewzHNDm9rRTY3aC3T_f4GZqufBB-LRswFls1Do0t2dpp8Bxm5ThvwvC8ynponE-n9-lg=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## 3. Modem WIFI Routers

- Combines **router + switch + wireless access point**
- Provides **WIFI access** and connects wired & wireless devices
- Often includes **firewall** and other security features

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUftkq0OyDdgbnJpWMnVicMF2vNyjPfsC0BAKhhQs8r8dnTq9Y8_bhcObBRDOTcIiFTKxiDL8BXEsNKeiqqDXZITmdvDCaPrXhqA_a9DWtu5jF4Ad7zgEYErLpYRuOKFP7tY9c-qGDzgQ1KISyERb9unzT6GZ8za=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## 4. Repeater 

- Boosts or **amplifies WiFi/internet signals**
- Extends network range over long distance

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUe0WFaCaWh8G0q9csD5zvImUGlqR9N0v-PKy4iKys3DOLzwUcqwdA2TuKj6JGyBuwq6uq7GNPZ_YLePr9jN-ffWx0hbVR3HPVaY_IfFsGfBYOzp2bCEDf00gxd0Wm50rHIgD3LLOmQjLiAh4cxq6r51aEOsPL1u=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

## 5. Bridge

- Connects **two or more LANs** together
- Makes multiple networks act like one

**![](https://lh7-rt.googleusercontent.com/slidesz/AGV_vUdj1DsdyO2PnsJdlr9wfWjMzPGwjixAHhBY_BvliVYVHutn05tiBrtM2jiAH2yAMjPp2oYEmojLQluxOcfYj0CLJVMKLzn9gCVzG4M88M7SfNT8WY0CCT99nnhhYzoPW-FcDB2d0E1JN-Ic8bwKpPg149O4OGrJ=s2048?key=3mKeAVmgaSEe6t6etgR_Eg)**

