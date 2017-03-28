# node-red-contrib-s7comm

A Node-RED node to communicate with Siemens S7 PLCs.


## About
-----------
The Hilscher Node-RED *node-red-contrib-s7comm* node is designed to communicate with a SIMATIC S7-300/1200/1500 SPS of SIEMENS based on the RFC1006-communication protocol. The S7comm node can build up a connection with the SIMATIC-S7. Furthermore it can Read/Write Addresses of the SPS with specific S7-Datatype.

It is using the Open-Source Library nodeS7 as its Framework which is able to handle the communication with the SPS. Special thanks to plcpeople for creating nodes7.

## Install
-----------
Run the following command in your Node-RED user directory (typically `~/.node-red`):

        npm i node-red-contrib-s7comm

## Getting Started
-----------
See [USAGE.md](USAGE.md) for more details.


## Contributing
-----------
Patches/Pull-requests are always welcome. For simple typos and single line fixes please just raise an issue pointing out our mistakes. Clearly describe the issue including steps to reproduce when it is a bug.

For further help, or general discussion, please use the
Node-RED [mail group](https://groups.google.com/forum/#!forum/node-red) on GoogleGroups.


## Copyright and license
-----------
Copyright 2017, Hilscher Gesellschaft für Systemautomation mbH, under the [MIT license](LICENSE).


## Additional Resources
-----------
* [NodeS7 Library for SIMATIC PLC communication](https://github.com/plcpeople/nodeS7)
* [Wireshark plugin for SIMATIC PLC communication](https://sourceforge.net/projects/s7commwireshark)


