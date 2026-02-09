### The Access Layer
## Encapsulation and the Ethernet Frame
    - Encapsulation is the process of prepending protocol information with information from another protocol.
    - When an Ethernet frame is sent out an interface, the Destination MAC (Media Access Control) address indicates the MAC address of the device, which is on this network, that will receive the Eternet frame.
    - The Preamble and Start Frame Delimiter (SFD indicate the beginning of an Ethernet frame).
    - Ethernet operates at layer 2, the data link layer, of the OSI model.

# Encapsulation
    - The process of placing one message format (the letter) inside another message format (the envelope) is called encapsulation. De-encapsulation occurs when the process is reversed by the recipient and the letter is removed from the envelop. Just as a letter is encapsulated in an envelope for delivery, so computer messages are encapsulated.
    - Each computer message is encapsulated in a specific format, called a frame, before it is sent over the network. A frame acts like an envelope; it provides the address of the intended destination and the address of the source host. The forat and the contents of a frame are determined by the type of message being send and the channel over which it is communicated. Messages that are not correctly formatted are not successfully delivered to or processed by the destination host.
    - Analogy
        - A common example of requiring the correct format in human communication is when sending a letter. An envelope has the has the address of the sender and receiver, each located at the proper place on the envelop. If the destination address and formatting are not correct, the letter is not delivered.
    - Network
        - Similar to sending a letter, a message is sent over a computer network follows a specific format rules for it to be delivered and processed. Internet Protocol(IP) is a protocol with a similar function to the envelope example.

        ![Encapsulation](images/encapsulation.png)

        - In the image above, the fields of the Internet Protocol version 6 (IPv6) packet identify the source of the packet and its destination. IP is responsible for sending a message from the message source to destination over one or more networks.
