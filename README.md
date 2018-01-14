Fork of great work done by derekhe.

Add an issue using python-uinput because it does not recognize absolute position on my octopi and I passed a few hour struggling with relative position. So I replaced with python-libxdo.

# Install (Thanks Kaz Fukuoka to fix this guide)
ssh into your raspiberry

```
git clone https://github.com/kubkpower/waveshare-7inch-touchscreen-driver
cd waveshare-7inch-touchscreen-driver
chmod +x install.sh
sudo apt-get update
sudo ./install.sh
sudo restart
```
