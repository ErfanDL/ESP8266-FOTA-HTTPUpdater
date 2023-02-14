# ESP8266 FOTA HTTPUpdater
A simple Arduino example for self-updating ESP8266 boards over the Internet and network.
# Usage
1. on your http host, in the public HTML folder make a firmware.json file with the following content:

- `{"ver" : 1.00, "link" : "link to yout firmware bin file"}`
- for example: `{"ver" : 1.00, "link" : "http://192.168.1.1/updates/test.bin"}`
