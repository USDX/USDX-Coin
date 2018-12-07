# USDXCOIN


## License
-------

Onix coin released under the terms of the MIT license. See (COPYING) for more
information or see https://opensource.org/licenses/MIT.

## Requirements to compile (Ubuntu)
```
sudo apt-get install git build-essential libssl-dev libboost-all-dev libqrencode-dev libdb++-dev libminiupnpc-dev qt-sdk -y
```

## Compiling USDXd (Console)
```
git clone https://github.com/onix-project/usdxcoin.git
cd usdxcoin/src
make -f makefile.unix
```

## Compiling USDX-qt (Graphical Interface)
```
git clone https://github.com/onix-project/usdxcoin.git
cd usdxcoin
qmake USE_UPNP=- USE_QRCODE=0 USE_IPV6=0 
make
```
