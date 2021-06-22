Metadata & OBJKT files are uploaded & pinned in Infura (https://github.com/hicetnunc2000/hicetnunc/blob/main/src/data/ipfs.js#L12), and then they're downloaded from ipfs.io, cloudflare or pinata public gateways. (https://github.com/hicetnunc2000/hicetnunc/blob/main/src/pages/objkt-display/tabs/info.js#L11). The delays could be due to propagation from Infura to the public gateways.

