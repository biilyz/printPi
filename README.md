# printPi
# UPDATE YOU PI
<br>

```sh
sudo apt update
sudo apt upgrade
```
<br>

# install CUPS

```sh
sudo apt install cups
```
<br>

# add your User Name on lpadmin

<br>

```sh
sudo usermod -a -G lpadmin root
```
<br>

# restart Cups sever

<br>

```sh
sudo cupsctl --remote-any
sudo /etc/init.d/cups restart
```
<br>

# Check you printer driver

<br>

```sh
sudo lsusb
```
<br>

# Install driver printer

<br>
if you have Samsung printer run it

<br>

```sh
sudo apt install driver-printer-splix
```
<br>
if your have onather printer , download and install it (xp-365b)

<br>

```sh
sudo apt install git -y
git clone https://github.com/biilyz/printPi
```
<br>
then 

<br>

```sh
sudo apt-get install libcupsimage2
cd printPi
sudo dpkg -i xprinter.deb
```
<br>

# Finish open your browser to use Cups

<br>

```sh
https://hostnameraspberrypi:631
```
