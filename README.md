# wifiSpammer
A python script to spam a bunch of silly wifi networks, inspired by [Spacehun's esp8266_beaconSpam](https://github.com/spacehuhn)

## Requirements
This script will require

* A wireless network card capable of monitor mode
* Scapy for Python (see [installing Scapy](#installing-scapy))

## Usage
```
usage: wifiSpammer.py [-h] [-f FILE] [-v VENDOR] [-i INTERFACE] [-l] [-r]

Another silly beacon spammer ;)

optional arguments:
  -h, --help            show this help message and exit
  -f FILE, --file FILE  File to import the SSIDs from (default wifi.lst)
  -v VENDOR, --vendor VENDOR
                        Vendor to spoof (-l to list available vendors)
  -i INTERFACE, --interface INTERFACE
                        Interface used to spam SSIDs
  -l, --list-vendors    List vendors
  -r, --random-mac      Uses a fully random BSSID instead of using a vendor
```

## Installing Scapy
To install scapy open a terminal and type
```
pip3 install scapy
```
## Disclaimer
This project is a proof of concept for testing and educational purposes. I do not take responsibility for the trouble you may get into, and please be mindful with the SSID names

## License
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE) for details

## Additional notes
This script **only runs on linux** and **must be executed with root privileges**

As much as I'd like, not all networks appear at the same time
