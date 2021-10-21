### **mint**

1: _(verb)_ to create an OBJKT (NFT) on https://www.hicetnunc.xyz/

***

1. You should have already created a wallet (we recommend Temple or Kukai). Click on “Sync". Your browser will show a pop up asking you to sync with your wallet.

![sync button](https://i.ibb.co/25CWLk3/sync.png)

![Beacon wallet popup (choose your wallet)](https://i.ibb.co/T8PZVbN/beacon.png)

2. Approve the sync in your wallet
3. Click the [OBJKTS (mint NFTs)] button in the hamburger drop down menu
6. Fill out the information for your OBJKT. Edition size is final, you can burn some of them but can't add. Title, descriptions, tags, and royalties are also final. You can input the price of the OBJKT after the minting is complete. You can upload display images/gifs depending on the media type. **The file size limit is currently 100mb**.
7. Click on preview to see the preview
8. Click on [mint]. Approve from your wallet, and the Tezos transaction will go through.
9. Check in your wallet if the minting was confirmed. Times vary for how long the confirmation should take, but it usually takes a couple of minutes.

**Imporant:** _At this point your OBJKT doesn’t have a price on it._ 

Continue to the [How to swap 🔃](https://github.com/hicetnunc2000/hicetnunc/wiki/How-to-swap-🔃) to learn how to set prices for your OBJKTs.

***

**Hint:** _Based on the edition number that you minted, you will see a number of “OBJKTS” in your tezos wallet. These newly minted OBJKTs now belong to you._


***

### HELP! I keep getting the `BACKTRACKED` error and I'm using temple wallet! (`transaction likely to fail`)
You will have to manually set max storage fees (it only charges the storage fee that was really used in the operation). 

```suggested parameters:
mint - set storage to 310
swap - set storage to 180
```
![Storage fee adjustment in template wallet](https://i.ibb.co/7W3FNRR/Screen-Shot-2021-05-24-at-10-33-33-AM.png)

### HELP! I tried to raise the storage fees but I'm still getting the `BACKTRACKED` error!
If raising storage fees doesn't work, you'll have to switch to using kukai wallet. You don't need to make a new wallet to do this. [Here](https://youtu.be/_9TwCzBBJGU) is a video tutorial on how to import your wallet to Kukai.

