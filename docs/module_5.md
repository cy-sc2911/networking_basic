### Communication Principles ###

## Communication Protocols
- Just like humans, computers use rules, or protocols, in order to communicate. Protocols are required for computers to properly communicate across the network. In both a wired or wireless environment, a local network is defined as an area where all hosts must "speak the same language", which, in computer terms means they must "share a common protocol".

- Networking protocols define many aspects of communication over the local network.
    - Message format
        - When a message is sent, it must use a specific format or structure. Message formats depend on the type of message and the channel that it used to deliver message.

    - Message size
        - The rules that govern the size of the pieces communicated across the network are very strict. They can also be different, depending on the channel used. When a long message is sent from one host to another over a network. it may be necessary to break the message into smaller pieces in order to ensure that the message can be delivered reliably.

    - Timing
        - Many network communication functions are dependent on timing. Timing determines the speed at which the bits are transmitted across the network. It also affects when an individual host can send data and the total amount of data that can be sent in any transmissiion.

    - Encoding
        - Messages sent across the network are first converted into bits by the sending host. Each bit is encoded into a pattern of sounds, light waves, or electrical impulses depending on the network media over which the bits are transmitted. The destination host receives and decodes the signals in order to interpret the message.

    - Encapsulation
        - Each message transmitted on a network must include a header that contains addressing information that identifies the source and destination hosts, otherwise it cannot be delivered. Encapsulation is the process of adding this information to the pieces of data that make up the message. In addition to addressing, there may be other information in the header that ensures that the message is delivered to the correct application on the destination host.

    - Message pattern
        - Some messages require an acknowledgment before the next message can be sent. This type of request/response pattern is a common aspect of many networking protocols. However, there are other types of messages that may be simple streamed across the network, without concern as to whether they reach their destination.

# Communication Standards
- A standard is a set of rules that determines how something must be done. Networking and internet standards ensure that all devices connecting to the network implement the same set of rules or protocols in the same manner. Using standards, it is possible for different types of devices to send information to each other over the internent.

# Network Standards Organization
- An internet standard is the end result of a comprehensive cycle of discussion, problem solving, and testing. These different standards are developed, published, and maintained by a variety of organizations. When a new standard is proposed, each stage of the development and approval process is recorded in a numbered Requests for Comments(RFC) document so that the evolution of the standard is tracked. RFCs for internet standards are published and managed by the Internet Engineering Task Force (IETF).

## Network Communication Models

