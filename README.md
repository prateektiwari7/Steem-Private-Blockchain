To setup Private chain in Steem Blockchain.

1.create config.ini file and add the seed-node to IP(host):port-of-server

2.Build the main node, create the config.ini file. And build it with steemd -d library-path-of-config.ini (main-node.ini = config.ini)

3.In Order to set your private Chain id. Edit the code in steemd/libraies/protocol/include/steemd/protocol (edit the config.hpp file )

4.The peer node config.ini file is as (see peer-node.ini)

5.In order to change total supply of STEEM change the steemd/libraies/protocol/include/steemd/protocol (edit the config.hpp) else codee 
