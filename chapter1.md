# chapter 1: Fundamentals

## Definitions:

### Computer network:

- A `computer network` is a set of `nodes` connected by `communication links`, or A computer network is a collection of interconnected devices that communicate with each other to share resources and information. These devices can include computers, servers, smartphones, and other digital equipment.

- A `node` can be a computer printer or any other device capable of sending or receiving data.

- A `communication link` refers to a physical (wired) or virtual (wireless) connection that enables communication between two or more devices or entities in a network.

- `End devices` are devices that originate or consume data within a network. They are the final destination or source of data transmission.

- `Intermediary devices` are network devices that facilitate communication between end devices and ensure data is transferred efficiently across the network.

<img src="./IMG/network_example.png">

## Basic characteristics any computer network:

### Fault tolerance

- `Fault tolerance` is the capability of a network to continue operating correctly even when one or more of its components fail.
Fault tolerance is Ability to continue operating despite failures or malfunctions.

### Scalability

- `Scalability` is the ability of a network to grow and handle an increasing amount of work or accommodate expansion without compromising performance.

### Quality of Service

- `Quality of Service` refers to the set of technologies and policies used to manage and prioritize network traffic to ensure the performance of critical applications.

### Security

- `Security` involves protecting the network and its data from unauthorized access, attacks, and other threats to ensure confidentiality, integrity, and availability.

## Network Protocols & Communications:

### Data communication:

- `Data communications` are the exchange of data between two nodes via some form of `link` or `transmission medium` sush as cable.

### Data transmission:

- `Data transmission` also known as `data flow`, refers to the process of sending data from one point to another through a communication channel. It involves the movement of data between devices

#### -> Data Transmission Modes:

- Simplex: Data flows in one direction only (e.g., TV broadcast).
- Half-Duplex: Data flows in both directions, but not simultaneously (e.g., walkie-talkies).
- Full-Duplex: Data flows in both directions simultaneously (e.g., telephone conversations).

### Network Protocols:

- `Protocols` are sets of rules that govern how devices communicate and exchange data in a network. They define the standards and conventions for various aspects of communication, ensuring that devices can understand each other and cooperate effectively.

- protocols used in network communication play a critical role in defining various aspects beyond just data transmission. They encompass a wide range of functions and specifications to ensure efficient and reliable communication between devices. Here's how protocols define these aspects:

1. Message Encoding, Formatting, and Encapsulation
Encoding: Protocols specify how data should be encoded into binary format for transmission over the network. Different encoding schemes, such as ASCII, UTF-8, or binary formats, may be used depending on the type of data and the protocol being employed.

- Formatting: Protocols define the structure and format of data packets or frames. This includes specifying fields such as headers, trailers, and data payload sizes. For example, in Ethernet frames, there are fields for source and destination MAC addresses, frame type, data payload, and CRC for error detection.

- Encapsulation: Protocols encapsulate data by adding protocol-specific headers and trailers to the original data. Each layer of the OSI (Open Systems Interconnection) or TCP/IP model adds its own headers or trailers to the data as it passes through the network stack.

2. Message Timing
Timing: Protocols govern when data packets should be transmitted and how timing is synchronized between sender and receiver. Timing aspects include data transmission rates (bandwidth), latency (delay in transmission), and synchronization methods to ensure that data is transmitted and received in a coordinated manner.
3. Message Size
- Message Size: Protocols define the maximum size of data packets or frames that can be transmitted over the network. This maximum transmission unit (MTU) varies depending on the protocol and the type of network medium (e.g., Ethernet, Wi-Fi). Large messages may be fragmented into smaller packets to fit within the MTU size.
4. Message Delivery Options
Delivery Options: Protocols specify options for delivering data packets, including:

- Reliable vs. Unreliable Delivery: Protocols like TCP provide reliable delivery, ensuring that all data packets are received and in the correct order. UDP, on the other hand, offers unreliable delivery, where some packets may be lost or arrive out of order.

- Flow Control: Protocols manage the flow of data between sender and receiver to prevent congestion and optimize performance. Flow control mechanisms regulate the rate at which data is transmitted based on network conditions and the receiver's ability to process data.

- Error Handling: Protocols include mechanisms for error detection (e.g., checksums, CRC) and error recovery (e.g., retransmission of lost packets) to ensure data integrity and reliability during transmission.