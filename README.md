# xdc-smartcontract-xrc-721
xdc-smartcontract-xrc-721

This set of interfaces and contracts are all related to the [ERC721 Non-Fungible Token Standard](https://eips.ethereum.org/EIPS/eip-721).

The EIP consists of 2 interfaces which fulfill different roles, found here as {IXRC721} and {IXRC721Receiver}.

## Usage

#### This XRC721 supports the following methods-
- balanceOf
- ownerOf
- approve
- getApproved
- setApprovalForAll
- isApprovedForAll
- transferFrom
- safeTransferFrom

### Requirements:
- Solidity 0.5.0

### Note:
This core set of contracts is designed to be unopinionated, allowing developers to access the internal functions in XRC721 (such as _mint) and expose them as external functions in the way they prefer.
