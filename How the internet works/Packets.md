are a formatted unit of data that carries information. It consists of control information and payload. The original data is segmented into these packets, which are then converted into binary. *They work at **Layer 3** of the [[OSI model]]*

The composition is the header, payload, and sometimes a trailer. 
* The header will include source and destination addresses, sequencing details, and error checking data
* Payload is the data being sent
* The trailer might contain additional control and error checking info

They will get routed to their destination by networking devices like routers and switches.

Packet switching allows intermediary [[routers]] and [[switches]] to process packets independently from each other. This means the network is not dependent from an individual connection, in other words, this design prevents any single connection from monopolizing the network. 

Routers and switches use algorithms and protocols such as the [[Internet Protocol]] (IP), and [[Transmission Control Protocol]] (TCP), to determine the most efficient path for each packet. This path is based on factors like network congestion, number of hops, and the physical distance between devices

The receiving device will reassemble the packets in the correct sequence and deserialize the binary into the correct format