# QtTermTCP-builds
Build pipeline for QtTermTCP.

Builds on/for Ubuntu amd64.

```
sudo apt install libqt5serialport5
wget https://github.com/M0LTE/QtTermTCP-builds/releases/download/release/QtTermTCP
chmod +x QtTermTCP
./QtTermTCP
```

## Usage

To use QtTermTCP as a front-end for a KISS modem, such as NinoTNC, follow these steps:

- Start QtTermTCP
- Setup menu -> KISS setup
- Enable KISS interface: tick
- MYCALL: your callsign
- Select Device: something like ttyACM0
- Speed: as appropriate for your modem, 57600 for NinoTNC

Leave the rest alone. Then:

- Connection menu -> KISS connect
- Connection mode: Session
- Call to: the callsign of the station you want to connect to, e.g. GB7RDG
- Digis: as appropriate, or none.

Remember to add your user to the `dialout` group to be able to access serial ports.
