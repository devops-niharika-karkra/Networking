# Classes of IP Addressing
## The 32-bit IP address is divided into five sub-classes. These are given below:
  - Class A
  - Class B
  - Class C
  - Class D
  - Class E

### Class A
  - Class A IP addresses are assigned to networks that require a very large number of hosts.
  - The default subnet mask for Class A is 255.0.0.0.
  - The IP address range for Class A is 0.0.0.0 to 127.255.255.255.

### Class B
  - Class B IP addresses are assigned to medium to large-sized networks.
  - The default subnet mask for Class B is 255.255.0.0.
  - The IP address range for Class B is 128.0.0.0 to 191.255.255.255.

### Class C

  - Class C IP addresses are assigned to small-sized networks.
  - The default subnet mask for Class C is 255.255.255.0.
  - The IP address range for Class C is 192.0.0.0 to 223.255.255.255.

### Class D
  - Class D IP addresses are reserved for multicast communication.
  - No subnet mask is defined for Class D addressing.
  - The IP address range for Class D is 224.0.0.0 to 239.255.255.255.

### Class E
  - Class E IP addresses are reserved for experimental and research purposes.
  - No subnet mask is defined for Class E addressing.
  - The IP address range for Class E is 240.0.0.0 to 255.255.255.255.

## Range of Special IP Addresses
  - **169.254.0.0 – 169.254.255.255**: Used as link-local addresses when a device cannot obtain an IP address from a DHCP server.
  - **127.0.0.0 – 127.255.255.255**: Reserved for loopback addresses, used to test network functionality on the local machine.
  - **0.0.0.0 – 0.255.255.255 (0.0.0.0/8)**: Represents the current network and is used during initialization before a device is assigned a valid IP address.
