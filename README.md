sudo apt install build-essential git\n
git clone https://github.com/tnbhaeufi/rtlwifi-next\n
cd rtlwifi-next\n
make\n
sudo make install\n
sudo modprobe rtl8822be\n
