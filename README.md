## BTCPayServer LND Docker

For origin repository you want to go to:

https://github.com/lightningnetwork/lnd

The purpose of this repository is to help auto-build Docker LND image that's by default used by BtcPayServer. Mostly it's there so we can streamline development... and more quickly get to the point where BtcPayServer supports LND. Image produced by this repository is available on:

https://hub.docker.com/r/btcpayserver/lnd/

Long term we want to eliminate this repository and depend on official LND Docker image published by lightningnetwork.