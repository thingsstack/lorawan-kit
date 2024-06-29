# Lorawan

Java implementation of the LoRaWAN® protocol stack together with the reference implementation of the main LoRaWAN network elements and some utilities.
In particular it includes the implementation of:
* complete LoRaWAN protocol stack (LoRaWAN MAC layer and above), as defined by the standard LoRaWAN® specifications;
* Semtech protocol, that can be used between a LoRaWAN gateway and the network server;
* LoRaWAN server, integratiting a Network Server, a Join Server, and an Application Server;
* LoRaWAN virtual gateway, that is a LoRaWAN gateway where the LoRa PHY layer is replaced by a virtual PHY layer on top of UDP/IP;
* some virtual devices, that are software devices that can communicate with one or more virtual gateways by means of a virtual PHY layer (on top of UDP/IP).
* other LoRaWAN utilities for capturing and/or analyzing LoRaWAN traffic.



## Dependencies

The following two small libraries are required for compiling and/ or using the lorawan library:
* [zutil](https://github.com/zoolu-org/zutil) - some utilities used for managing command line options, byte arrays, JSON strings, etc. 
* [ipstack](https://github.com/ipstack-dev/ipstack) - network libraries used for packet handling.

You can download these libraries from the corresponding repositories or you can find them, as jar files, directly in the `lib` folder.




* [mjcoap](https://github.com/thingsstack/mjcoap) - CoAP implementation used in some examples of virtual devices.

In the [lib](https://github.com/ipstack-dev/lorawan/tree/main/lib) folder the corresponding jar files are provided.

For simplicity, the all-in-one jar file [lorawan-all.jar](https://github.com/ipstack-dev/lorawan/blob/main/lorawan-all.jar) containing binary code from all libraries is also provided.

## Reference applications

More information regarding LoRaWAN server, gateway, and device reference implementation can be found here:

- [server](https://github.com/ipstack-dev/lorawan-server/blob/main/doc/server.md)
- [gateway](https://github.com/ipstack-dev/lorawan/blob/main/gateway.md)
- [device](https://github.com/ipstack-dev/lorawan/blob/main/device.md)


