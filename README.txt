Munin-facter-Graphite daemon

MfG collects munin data and sends it to graphite.  Metric names are
configurable through facts. It is written in python.

Installation: 

aptitude install python-yaml munin-node
git clone https://github.com/gauthierc/MfG.git
cd MfG
./setup.py build
./setup.py install

cp mfg.ini.examples /etc/mfg.ini
vim /etc/mfg.init
