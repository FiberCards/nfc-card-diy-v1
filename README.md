# FiberCards NFC Business Card DIY Kit

A DIY kit for building your own battery-free NFC business card. Assemble the board, then tap it with an NFC-enabled phone to share a link and light up the LEDs.
The copper spiral on the board acts as an inductor and NFC antenna. The phone's changing magnetic field induces a voltage in the coil, and the NFC chip harvests this energy to power the microcontroller and LEDs. To reprogram the NFC chip, you can do so using your phone, through an app such as [NFC Tools](https://nfc.software/en).

The hardware design is in [`cad/`](cad/), and the firmware is in [`firmware/`](firmware/).
