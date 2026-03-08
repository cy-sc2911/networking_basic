### Network Testing Utilities

## Troubleshooting Commands
# ipconfig Command
    When a device does not get an IP address, or has an incorrect IP configuration, it cannot communicate on the network or access the internet. On Windows device, the IP configuration information can be viewed with the 'ipconfig' command at the command prompt. The 'ipconfig' command has several options that are helpful including, '/all', '/release', and '/renew'.

        ipconfig
            The 'ipconfig' command is used to display the current IP configuration information for a host. Issuing this command from the command prompt will display the basic configuration information including IP address, subnet mask, and default gateway.

        /all
            The command 'ipconfig /all' displays additional information including the MAC address, IP addresses of the default gateway, and the DNS servers. It also indicates if DHCP is enabled, the DHCP server address, and lease information.
            How can this assit in the troubleshooting process? Without an appropriate IP configuration, a host cannot participate in communications on a network. If the host does not know the location of the DNS server, it cannot translate names into IP addresses.

        ipconfig /release and ipconfig /renew
            If IP addressing information is assigned dynamically, the command 'ipconfig release' will release the current DHCP bindings. 'ipconfig /renew' will reqyest fresh configuration information from the DHCP server. A host may contain faulty or outdated IP configuration information and a simple renewal of this information is all that is required to regain connectivity.
            If, after releasing the IP configuration, the host is unable to obtain fresh information from the DHCP server, it could be that there is no connectivity. Verify that the NIC has an illuminated link light, indicating that it has a physical connections to the network. If this does not solve the proble, it may be an issue with the DHCP server or network connections to the DHCP server.
