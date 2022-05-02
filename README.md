
# Create NFT Collection in Rarible or OpenSea
* To Get Faucet in [rinbeky](https://rinkebyfaucet.com/)

* To Follow [open sea doc](https://docs.opensea.io/docs/part-3-adding-metadata-and-payments-to-your-contract)

* To create Account in  [IPFS NFT Storage](https://nft.storage/)

* To upload images with  
  ```bash
  npx ipfs-car --pack images --output images.car
  ```
* To upload metadata but to remember change path image of metadata
  ```bash
  npx ipfs-car --pack metadata --output metadata.car
  ``` 

* In your smart contract set base url see example
 ```js
    function _baseURI() internal pure override returns (string memory) {
        return "https://bafybeigmknes2urvsmmmwwuav3yazogrnfgprnqkz7f2iqtmegmirucp6i.ipfs.nftstorage.link/metadata/";
    }
 ```

* create account in [Rarible](https://rinkeby.rarible.com/items/owned)

* Smart Contract NFT ``0x53a24e1d32b096370f1201cf5dc1cf899ca12154``


* validate api in opensea 
  ```
    curl https://testnets-api.opensea.io/asset/0x53a24e1d32b096370f1201cf5dc1cf899ca12154/0/validate/
  ```
* see dir
  ```
    tree -L 3 -I 'node_modules*|cache*'
  ```