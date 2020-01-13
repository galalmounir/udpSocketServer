# UDP Socket Server Example
This is a simple UDP socket game server example in python. 
Currently the server expects a packet with "connect" in order for a client to connect.
Afterwards, the server will periodically send random colors to all connected clients.
If a client does not send a heartbeat at least once every 5 seconds. The server drops the client.

### Usage
`cd ~`

`mkdir labs` or `cd labs`

`git clone https://github.com/galalmounir/udpSocketServer.git`

`cd udpSocketServer`

`python3 udpSocketServer`
