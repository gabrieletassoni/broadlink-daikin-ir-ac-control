# broadlink-daikin-ir-ac-control
Control Daikin Splits using a Broadlink RM. This project uses https://github.com/mjg59/python-broadlink and adds IR codes for commonly used functions

I use this in my private house, via a raspberry pi, it's the first step of the integration of the old Daikin Air Conditioning system I own into OpenHAB controller to make home automation scenes out of KNX devices and the Daikin AC splits.

## Install script:

Copy and paste the following command to start the setup script (must be root):

```
source <(curl -s https://raw.githubusercontent.com/gabrieletassoni/broadlink-daikin-ir-ac-control/master/bin/setup)
```
