# ESPWoTThing
_Generic WoT Connection for ESP devices_

The goal of this project is to create and provide a template for building secure WoT devices that conform to a WoT standard proposed by Mozilla and W3C, and that is compatible with Mozilla's implementation of that standard.

The general process is as follows:

1. Start Access Point for initial configuration
2. Obtain or open a web server certificate
3. Start secure web server
4. Advertise via SSDP
5. Authenticate connected client (a WoT gateway)
6. Return WoT configuration in JSON format
7. If WoT gateway accepts
    1. Disable SSDP
    2.	Start WoT services
    3.	Periodically check for updates

However, there is nothing here yet, so don't waste your time.
