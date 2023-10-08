# Source
https://hub.docker.com/r/linuxserver/unifi-controller

## Important to connect the ubiquiti devices to the controller (adopt)
For Unifi to adopt other devices, e.g. an Access Point, it is required to change the inform IP address. Because Unifi runs inside Docker by default it uses an IP address not accessible by other devices. To change this go to Settings > System > Advanced and set the Inform Host to a hostname or IP address accessible by your devices. Additionally the checkbox "Override" has to be checked, so that devices can connect to the controller during adoption (devices use the inform-endpoint during adoption).

## Troubleshooting
### Adopting devices
the next link brings you to the troubleshooting page of the unifi controller. https://help.ui.com/hc/en-us/articles/360012622613-UniFi-Device-Adoption 
