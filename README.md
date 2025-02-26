```
# MoodNFT Project

## Overview
MoodNFT is an ERC-721 based NFT that reflects the owner's mood. The NFT can be in either a HAPPY or SAD state.

## Contracts
- `BasicNft.sol`: A simple ERC-721 NFT contract.
- `MoodNft.sol`: A dynamic NFT that changes based on the owner's mood.

## Compilation
Run the following command to compile the contracts:
```sh
make compile
```

## Deployment
To deploy the contract, run:
```sh
make deploy
```

## Cleaning
To remove compiled files, run:
```sh
make clean
```

## Mood States
The MoodNFT supports two states:

### HAPPY 😊
![Happy Mood](https://upload.wikimedia.org/wikipedia/commons/3/3a/Happy_face.svg)

### SAD 😞
![Sad Mood](https://upload.wikimedia.org/wikipedia/commons/7/7b/Sad_face.svg)

🚀