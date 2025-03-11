# AwardDistributor Contract

This contract is used to distribute awards to different addresses based on a percentage. The contract is only accessible by the owner.

## Functions

### distributeEth

Distribute the native currency (ETH) to the different addresses based on a percentage.

- `onlyOwner`: Only the owner of the contract can call this function.

### distributeERC20

Distribute an ERC20 token to the different addresses based on a percentage.

- `onlyOwner`: Only the owner of the contract can call this function.

### donateAndDistribute

Donate native currency (ETH) to the contract and distribute it to the different addresses based on a percentage.

- Anyone can call this function.

### donateAndDistributeERC20

Donate an ERC20 token to the contract and distribute it to the different addresses based on a percentage.

- Anyone can call this function.

## Addresses and Percentages

The contract has four addresses with their respective percentages:

- `ur369gifthAddress_30`: 30%
- `ur369impactAddress_30`: 30%
- `ur369Address_30`: 30%
- `ur369devsncomAddress_10`: 10%

## Testing

The contract has been tested using Truffle Suite and Ganache. The tests are located in the `test` folder.

## Deployment

The contract has been deployed on the ethereum mainnet. The address of the contract is `0x661ae8ab07242bedcd19c8c189287ebeb96093c4`.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
