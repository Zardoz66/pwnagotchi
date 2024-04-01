Hardware Parts List

Main Components

* Raspberry Pi Zero 2 W and Mini HDMI to HDMI Adapter and Micro with Pre Soldered Header (from waveshare)
* waveshare 2.13inch E-Ink Display HAT V4
* Pisugar2 Portable 1200 mAh UPS Lithium Battery Power Module
* Amazon Basics Micro SDXC Memory Card with Full Size Adapter, A2, U3, Read Speed up to 100 MB/s, 64 Gb

Additional Parts

* Three Port USB and Ethernet Hub with Micro USB Connector
* VK172 G-MOUSE USB GPS/GLONASS USB GPS Receiver (U-Blox7)

Software and Resources

https://pwnagotchi.org/
https://github.com/jayofelony/pwnagotchi

Config.toml

main.name = "pwnagotchi"
main.lang = "en"
main.whitelist = [
  "your ssid",
]

ui.display.enabled = true
ui.display.type = "waveshare_4"
ui.display.color = "black"
ui.invert= true
ui.fps = 1
ui.web.enabled = true
ui.web.username = "admin"
ui.web.password = "P@ssw0rd"
main.plugins.memtemp.enabled = true
