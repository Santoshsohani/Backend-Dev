# Backend 

## Internet
Internet is Just millions of computers, servers conncected together with the help of routers and switches. These device communicate with eachother with the set of rules called as internet protocol. 

**Core Building Blocks**: 
- Internet Protocol : IPV4 and IPV6 (Routing and Addressing and transfers from source to destination)
- TCP : Transmission Control Protocol - provides reliable data transfer and retries on failure
- UPD : User Datagram Protoco - Faster but doesn't gurantee


**Data Flow - User Requests for `google.com`**
1. DNS - Extract IP Address for the given Domain name.
2. TCP Handshake : SYN, SYN-ACK, ACK
3. TLS/SSL Handshake : Exchange Public keys and generate session ID
4. HTTP Method : Wrapped under TLS
5. Routing and Packaging : Divided into packets
6. Server Response : HTML,CSS and JS
7. Rendering onto browser.

