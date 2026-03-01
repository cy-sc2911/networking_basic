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
        
