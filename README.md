# VizterCoin-Blockchain-Explorer
Block explorer for VizterCoin.

#### Installation

1) It takes data from daemon VizterCoind. It should be accessible from the Internet. Run VizterCoind with open port as follows:
```bash
./VizterCoind --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=3997
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.


### Development
Donate: [Wrkz] WrkzRNDQDwFCBynKPc459v3LDa1gEGzG3j962tMUBko1fw9xgdaS9mNiGMgA9s1q7hS1Z8SGRVWzcGc8Sh8xsvfZ6u2wJEtoZB

### Note

A lot of this code is derived from the Karbovanets/Karbowanec-Blockchain-Explorer & turtlecoin/block-explorer

### Hosting Your Own VizterCoin Explorer

```bash
git clone https://github.com/vizx-enterprises/block-explorer-js.git
```

After That You Can Serve the Sites With Your Hosts
##### Some Examples

###### Surge.sh

```bash
cd block-explorer-js
surge
#With Domain
surge yourdomain.xyz
```

###### Serve
```bash
cd block-explorer-js
serve
```
Now go to http://localhost:5000/ or http://yourmachinesipaddess:5000/

You Can Host Our Explorer With Other Hosts Too
If you need help you can open a issue at this page.
