# hotwallet/lightningd

Run a lightning node on the Bitcoin network.

```sh
docker run hotwallet/lightning lightningd \
--network=bitcoin \
--bitcoin-rpcconnect=bitcoind.hotwallet.com \
--bitcoin-rpcuser=rpcuser \
--bitcoin-rpcpassword=rpcpassword
```

More config options can be found here:
https://lightning.readthedocs.io/lightningd-config.5.html

This image enables:
- PostgreSQL
- Prometheus (monitoring)

This docker image is based on [Blockstream's lightningd image](https://github.com/Blockstream/bitcoin-images/tree/master/lightningd).