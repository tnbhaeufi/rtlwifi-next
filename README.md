sudo apt install build-essential git
git clone https://github.com/tnbhaeufi/rtlwifi-next
cd rtlwifi-next
make
sudo make install
sudo modprobe rtl8822be
