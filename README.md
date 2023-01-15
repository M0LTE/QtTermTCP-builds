# QtTermTCP-builds
Build pipeline for QtTermTCP.

Builds on/for Ubuntu amd64.

```
sudo apt install libqt5serialport5
wget https://github.com/M0LTE/QtTermTCP-builds/releases/download/release/QtTermTCP
chmod +x QtTermTCP
./QtTermTCP
```

Remember to add your user to the `dialout` group to be able to access serial ports.
