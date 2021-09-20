# Multicall <img width="100" align="right" alt="Multicall" src="https://user-images.githubusercontent.com/304108/55666937-320cb180-5888-11e9-907b-48ba66150523.png" />

Multicall aggregates results from multiple contract constant function calls.

This reduces the number of separate JSON RPC requests that need to be sent
(especially useful if using remote nodes like Infura), while also providing the
guarantee that all values returned are from the same block (like an atomic read)
and returning the block number the values are from (giving them important
context so that results from old blocks can be ignored if they're from an
out-of-date node).

This smart contract is intended to be used with
[Multicall.js](https://github.com/velerofinance/multicall.js) in front-end dapps.

### Multicall Contract Addresses
| Chain   | Address |
| ------- | ------- |

[comment]: <> (| Mainnet | [0xeefba1e63905ef1d7acba5a8513c70307c1ce441]&#40;https://etherscan.io/address/0xeefba1e63905ef1d7acba5a8513c70307c1ce441#contracts&#41; |)

[comment]: <> (| Kovan   | [0x2cc8688c5f75e365aaeeb4ea8d6a480405a48d2a]&#40;https://kovan.etherscan.io/address/0x2cc8688c5f75e365aaeeb4ea8d6a480405a48d2a#contracts&#41; |)

[comment]: <> (| Rinkeby | [0x42ad527de7d4e9d9d011ac45b31d8551f8fe9821]&#40;https://rinkeby.etherscan.io/address/0x42ad527de7d4e9d9d011ac45b31d8551f8fe9821#contracts&#41; |)

[comment]: <> (| Görli   | [0x77dca2c955b15e9de4dbbcf1246b4b85b651e50e]&#40;https://goerli.etherscan.io/address/0x77dca2c955b15e9de4dbbcf1246b4b85b651e50e#contracts&#41; |)

[comment]: <> (| Ropsten | [0x53c43764255c17bd724f74c4ef150724ac50a3ed]&#40;https://ropsten.etherscan.io/address/0x53c43764255c17bd724f74c4ef150724ac50a3ed#code&#41; |)

[comment]: <> (| xDai    | [0xb5b692a88bdfc81ca69dcb1d924f59f0413a602a]&#40;https://blockscout.com/poa/dai/address/0xb5b692a88bdfc81ca69dcb1d924f59f0413a602a&#41; |)

[comment]: <> (| Polygon | [0x11ce4B23bD875D7F5C6a31084f55fDe1e9A87507]&#40;https://explorer-mainnet.maticvigil.com/address/0x11ce4B23bD875D7F5C6a31084f55fDe1e9A87507/contracts&#41;)

[comment]: <> (| Mumbai  | [0x08411ADd0b5AA8ee47563b146743C13b3556c9Cc]&#40;https://explorer-mumbai.maticvigil.com/address/0x08411ADd0b5AA8ee47563b146743C13b3556c9Cc/transactions&#41;)

### Multicall2 Contract Addresses
Multicall2 is the same as Multicall, but provides addition functions that allow calls within the batch to fail. Useful for situations where a call may fail depending on the state of the contract.

| Chain   | Address |
| ------- | ------- |

[comment]: <> (| Mainnet | [0x5ba1e12693dc8f9c48aad8770482f4739beed696]&#40;https://etherscan.io/address/0x5ba1e12693dc8f9c48aad8770482f4739beed696#contracts&#41; |)

[comment]: <> (| Kovan   | [0x5ba1e12693dc8f9c48aad8770482f4739beed696]&#40;https://kovan.etherscan.io/address/0x5ba1e12693dc8f9c48aad8770482f4739beed696#contracts&#41; |)

[comment]: <> (| Rinkeby | [0x5ba1e12693dc8f9c48aad8770482f4739beed696]&#40;https://rinkeby.etherscan.io/address/0x5ba1e12693dc8f9c48aad8770482f4739beed696#contracts&#41; |)

[comment]: <> (| Görli   | [0x5ba1e12693dc8f9c48aad8770482f4739beed696]&#40;https://goerli.etherscan.io/address/0x5ba1e12693dc8f9c48aad8770482f4739beed696#contracts&#41; |)

[comment]: <> (| Ropsten | [0x5ba1e12693dc8f9c48aad8770482f4739beed696]&#40;https://ropsten.etherscan.io/address/0x5ba1e12693dc8f9c48aad8770482f4739beed696#code&#41; |)

### Third-Party Deployments

The following addresses have been submitted by external contributors and have not been vetted by Multicall maintainers.

| Chain   | Address |
| ------- | ------- |

[comment]: <> (| RSK Mainnet   | [0x6c62bf5440de2cb157205b15c424bceb5c3368f5]&#40;https://explorer.rsk.co/address/0x6c62bf5440de2cb157205b15c424bceb5c3368f5&#41; |)

[comment]: <> (| RSK Testnet   | [0x9e469e1fc7fb4c5d17897b68eaf1afc9df39f103]&#40;https://explorer.testnet.rsk.co/address/0x9e469e1fc7fb4c5d17897b68eaf1afc9df39f103&#41; |)

[comment]: <> (| BSC Mainnet   | [0x41263cba59eb80dc200f3e2544eda4ed6a90e76c]&#40;https://bscscan.com/address/0x41263cba59eb80dc200f3e2544eda4ed6a90e76c&#41; |)

[comment]: <> (| BSC Testnet   | [0xae11C5B5f29A6a25e955F0CB8ddCc416f522AF5C]&#40;https://testnet.bscscan.com/address/0xae11c5b5f29a6a25e955f0cb8ddcc416f522af5c&#41; |)
