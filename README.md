# Rosecoin2 [ROSE2, R]
http://rosecoin.info

## What is RoseCoin2?
Rosecoin2 is like Bitcoin, but based on Litecoin, and also much more rose.
http://rosecoin.info

## License - Much license
RoseCoin2 is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Frequently Asked Questions

### How much rose can exist?
Total of 0.9B coins

### make rosecoind
Step1:
sudo apt-get install libssl-dev libdb-dev libdb++-dev libminiupnpc-dev libminiupnpc8 libboost1.48-all-dev build-essential git

Step2:
git clone https://github.com/rosecoin/rose2.git
cd rose2/src
mkdir obj
make -f makefile.unix USE_UPNP=1 USE_IPV6=0
strip rosecoind (Unless you're debugging, strip debug symbols: strip rosecoind)

Step3:edit .conf
nano ~/.rosecoin/rosecoin.conf

### Ports
RPC 32777
P2P 32778

