# ESP8266 FOTA HTTPUpdater
A simple Arduino example for self-updating ESP8266 boards over the Internet and network.
# Usage
1. upload the code to your ESP8266 board with your own WiFi credential.
2. on your http host, in the public HTML folder make a firmware.json file with the following content:
- `{"ver" : 1.01, "link" : "link to yout firmware bin file"}`
- for example: `{"ver" : 1.01, "link" : "http://192.168.1.1/updates/test.bin"}`
- change the version number to 1.01 in your code and compile its bin file.
- upload the compiled bin file to the same folder where firmware.json is saved.
- now esp will download and install the newer firmware version.
