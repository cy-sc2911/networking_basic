### TCP and UDP

## TCP and UDP


## Port Numbers
# TCP and UDP Port Numbers
    There are many services that we access through the internet in the course of a day. DNS, web, email, FTP, IM and VoIP are just some of these services that are provided by client/server systems around the world. These services may be provided by a single server or by several servers in large data centers.
    When a message is delivered using either TCP or UDP, the protocols and services requested are identified by a port. A port is a numeric identifier within each segment that is used to keep track of specific conversations between a client and a server. Every message that a host sends contains both a source and destination port.
    When a message is received by a server, it is necessary for the server to be able to determine which service is being requested by the client. Clients are preconfigured to use a destination port that is registered on the internet for each service. An example of this is web browser clients which are preconfigured to send requests to web servers using port 80, the well-known port for HTTP web services.
    Ports are assigned and managed by an organization known as the Internet Corporation for Assigned Names and Numbers (ICANN). Ports are broken into three categories and range in number from 1 to 65,535:

        Well-known Ports
            Destination ports that are associated with common network applications are identified as well-known ports. These ports are in the range of 1 to 1023.
        Registered Ports
           Ports 1024 through 49151 can be used as either source or destination ports. These can be used by organizations to register specific applications such as IM applications.
        Private Ports
            Ports 49152 through 65535 are often used as source ports. These ports can be used by any application.

    Below are some commom well-known port numbers and their associated applications.
        TCP       Port 20   File Transfer Protocol (FTP) - Data
        TCP       Port 32   FTP - Control
        TCP       Port 22   Secure Shell (SSH)
        TCP       Port 23   Telnet
        TCP       Port 25   Simple Mail Transfer Protocol (SMTP)
        UDP/TCP   Port 53   Domain Name Service (DNS)
        UDP       Port 67   Dynamic Host Configuration Protocol (DHCP) - Server
        UDP       Port 68   DHCP - Client
        UDP       Port 69   Trivial File Transfer Protocol (TFTP)
        TCP       Port 80   HyperText Transfer Protocol (HTTP)
        TCP       Port 110  Post Office Protocol version 3 (POP3)
        TCP       Port 143  Internet Message Access Protocol (IMAP)
        UDP       Port 161  Simple Network Management Protocol (SNMP)
        TCP       Port 443  Hypertext Transfer Protocol Secure (HTTPS)

    Some applications may use both TCP and UDP. For example, DNS uses UDP when clients send requests to a DNS server. However, communication between two DNS servers always uses TCP.

# Socket Pairs
    The source and destination ports are placed within the segment.
