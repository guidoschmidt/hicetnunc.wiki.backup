Metadata & OBJKT files are uploaded & pinned in Infura (https://github.com/hicetnunc2000/hicetnunc/blob/main/src/data/ipfs.js#L12), and then they're downloaded from ipfs.io, cloudflare or pinata public gateways. (https://github.com/hicetnunc2000/hicetnunc/blob/main/src/pages/objkt-display/tabs/info.js#L11). The delays could be due to propagation from Infura to the public gateways.

To run your own node, you can use the following Tools:

IPFS Pinning
Hicetnunc IPFS Pinning by Matt DesLauriers
Running IPFS node to pin content by Adam Eivy

