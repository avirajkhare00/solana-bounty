# solana-bounty

URL: https://github.com/solana-labs/solana/blob/master/SECURITY.md#security-bug-bounties

Rough idea:

 - Solana uses Quic + Gossip which means their entire traffic flows over UDP not TCP.
 - While initializing the client, we will get IPv4 addresses.
 - Idea is to use very own GitHub/GitLab/BitBucket CI in such a fashion that halts their any of the layer.

TO Read:
 - https://en.wikipedia.org/wiki/QUIC
