## Hyperledger Install

* Fabric
* Composer
* Explorer

__Linux Mint 18.3 Cinnamon 64 bit__

Start with the composer install: https://hyperledger.github.io/composer/unstable/installing/development-tools.html
* I had trouble with the npm install of the composer-cli with npm v5.6.0 and node v8.11.2
  * npm install -g composer-cli errored out for not having access to /usr/lib/node_modules
  * running sudo npm install -g composer-cli errored out on a node-gyp rebuild
  * I did a chmod 777 on /usr/lib/node_modules and ran the straight npm install -g composer-cli and it worked
 
Make sure you have all of the pre-reqs: https://hyperledger.github.io/composer/unstable/installing/installing-prereqs.html


_Note_: 
Helpful for putting Docker on mint: http://linuxbsdos.com/2016/12/13/how-to-install-docker-and-run-docker-containers-on-linux-mint-1818-1/


Reference for further reading:
http://hyperledger-fabric.readthedocs.io/en/latest/install.html
