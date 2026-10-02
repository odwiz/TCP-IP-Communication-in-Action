# How Information Travels Across a Network: Opening a Secure Website (Transport Layer)
### Overview
As part of a team of junior network analysts I was tasked to explain how data moves across a network using the TCP/IP model. The scenario followed throughout is opening a secure website (HTTPS).

## Main Responsibility
Explain how a reliable connection is created between a client and a web server before any secure data is exchanged.

## Topics Covered
**Transport Layer and Protocols**
- The role of the TCP/IP Transport Layer
- Introduction to TCP (Transmission Control Protocol)
- Comparison of TCP vs UDP \

**TCP Three-Way Handshake**
- SYN: the client requests a connection
- SYN-ACK: the server acknowledges and responds
- ACK: the client confirms, and the connection is established

**Ports**
- Source and destination ports
- Why HTTPS normally uses TCP port 443
- The ephemeral (dynamic) client port

**Reliability**
- How TCP ensures reliable delivery (sequencing, acknowledgements, retransmission)
- Encapsulation, Decapsulation and OSI Mapping
- How data is wrapped (encapsulated) as it moves down the stack and unwrapped (decapsulated) at the destination
- Mapping TCP/IP layers to the OSI model

## Learning Objectives
By the end of this, I was able to:

- Describe the purpose of the Transport Layer
- Walk through the TCP three-way handshake step by step
- Explain how source/destination ports identify a connection
- Justify why HTTPS uses TCP port 443
- Compare TCP and UDP and explain when each is used
- Relate encapsulation and decapsulation to the OSI layers

## Contents
- `/notes`: speaker notes and references in PDF.
