# beba_goose
1. Install Mininet
   ```
   sudo git clone https://github.com/mininet/mininet
   cd mininet
   sudo git tag
   sudo git checkout -b mininet-2.2.1 2.2.1
   sudo mininet/util/install.sh -n
   ```
2. Install beba-goose switch
   ```
   cd ofsoftswitch13_goose/
   ./boot.sh
   ./configure
   make
   make install
   ```
