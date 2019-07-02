# broadlink-daikin-ir-ac-control
Control Daikin Splits using a Broadlink RM. This project uses https://github.com/mjg59/python-broadlink and adds IR codes for commonly used functions

I use this in my private house, via a raspberry pi, it's the first step of the integration of the old Daikin Air Conditioning system I own into OpenHAB controller to make home automation scenes out of KNX devices and the Daikin AC splits.

## Prerequisites:

Install Debian packages which are a dependency for the Broadlink Python library:

```
sudo apt install python-pip python-dev libffi-dev libssl-dev libxml2-dev libxslt1-dev libjpeg8-dev zlib1g-dev
```

Install Broadlink Python library (I found working the 0.10 version, not the 0.11 one:

```
sudo pip install broadlink==0.10
```
