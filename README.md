# `Information`
This should be a fun exercise.

## Router Protocol

<!-- <p align="center" >

<img src="https://user-images.githubusercontent.com/124175970/224509096-12e4864a-6819-4c8c-8998-41c7a96ba026.jpg" />
  </p> -->

<!-- ![router-protocol-crypto-ninjas](https://user-images.githubusercontent.com/124175970/224509096-12e4864a-6819-4c8c-8998-41c7a96ba026.jpg) -->

<img src="https://user-images.githubusercontent.com/124175970/224509096-12e4864a-6819-4c8c-8998-41c7a96ba026.jpg" width="8000000em" height="400em" />


# `Company Information`

Router Protocol is a solution introduced to address the issues hindering the usability of cross-chain liquidity migration in the DeFi ecosystem. It acts as a bridge connecting various layer 1 and layer 2 blockchains, allowing for the flow of contract-level data across them. The Router Protocol can either transfer tokens between chains or initiate operations on one chain and execute them on another.

Please check the [official documentation of Router Protocol](https://www.routerprotocol.com/)

# `Why participate in Router Student Expert Program ?`

We reward 🏅 badges to individuals who complete our assignments!

The journey is divided into multiple stages, each with its own set of points. As you complete Assignment 1, you'll earn a certain number of points, and the same goes for Assignment 2, all the way up to the Final Assignment. Once you've earned a certain benchmark points, you'll receive an NFT badge as a token of your achievement.

Each assignment has its own unique set of points. For every 100 points earned, you'll receive a 🥉 Bronze Router Expert badge, for 500 points, you'll get a 🥈 Silver badge, and for 1000 points, you'll receive a coveted 🥇 Gold badge. These badges will add an extra shine to your resume and can be a golden ticket to working with us.

This initiative is perfect for those interested in pursuing a career in the web 3 space, and the badges can serve as a glowing recommendation for future opportunities. So what are you waiting for? Let's get started on the path to becoming a Router Expert! 🚀

# `Assignment description`

**To build a CrossChain NFT using Router CrossTalk with the following instructions:-**

![nftRouter](https://user-images.githubusercontent.com/124175970/224004658-177790e4-c7f5-4cb4-9c44-810bd6c780d0.gif)

1. Give the NFT a name - "Your name" and symbol - "Your Name's first and 2nd name first letter used as abbreviation".

2. Use Mumbai Testnet as the source chain and Fuji Testnet as the destination chain.

3. Mint the NFT with id = 450 on the source chain.

4. Transfer the NFT from the source chain to the destination chain.

5. Commit your solidity file to the repository.

6. Copy the transaction hash from the Router Explorer and submit in this [form](https://docs.google.com/forms/d/e/1FAIpQLSd8Xuiuw32kOqGsWmT5s7GLjLVZ_rHXw9bAJbdbr0XzrVG6RA/viewform?embedded=true) 

**Number of Points:**

You will earn 100 points after you have been evaluated based on the assignmnet.

# `Evaluation Process:`

We'll evaluate you on the basis of the following :

1. Whether you made use of the CrossTalk Library to build the CrossChain NFT.

2. Whether you followed all the instructions given in **Assignment description** or not

3. Whether you transferred the NFT from the source chain (Mumbai Testnet) to the destination chain (Fuji Testnet) using Router CrossTalk. We check this by the transaction hash that you provide in the form]

# `Recommended qualifications`

**Desired Skills:**

- Familiarity with the Git and GitHub
- Familiarity with Basics of Blockchain.
- Familiarity with Basics of Solidity Language.
- Understands the need of going Cross-Chain.


### Eligibility

To participate, you must be:

* 16 years or older

* Passionate about Web3 


# `Resources`

**1. CrossChain NFT Cookbook:-**

> Effortlessly transfer NFT's from one chain to another. Made using Router Cross-Talk.

This project is built with [Router CrossTalk](https://dev.routerprotocol.com/crosstalk-library/overview/introduction)

Router Protocol is a solution introduced to address the issues hindering the usability of cross-chain liquidity migration in the DeFi ecosystem. It acts as a bridge connecting various layer 1 and layer 2 blockchains, allowing for the flow of contract-level data across them. The Router Protocol can either transfer tokens between chains or initiate operations on one chain and execute them on another.

Please check the [official documentation of Router Protocol](https://www.routerprotocol.com/) 


# 🎯 `Steps`


✍️ **Setting up your editor:**

Browse to [Remix IDE](https://remix.ethereum.org/) and create a new file with ".sol" extension.

💿 **Install all dependencies:**

You don't need to install any dependencies. Remix automatically downloads all the dependencies for you during the time of compile.

🧑‍💻 **Create your CrossChain ERC-721 Contract:**

To create the contract for your CrossChain ERC-721 , copy-paste the [`Code`](#Full-Code) in the Remix Work Area and compile it.
The Code has been comprehensively explained in this repository. Click [`here`](#Initiating-the-Contract) for the explanation.

🚀 **Deploying the Contract:**

You need to deploy the same contract on the source chain as well as the destination chain and pass in the required parameters to the [`constructer`](#Creating-state-variables-and-the-constructor) while deploying.

🔨 **Mint created ERC-721 token on Source Chain:**

In order to mint the created ERC-721 token on the source , mint function defined in openzeppelin can be used.

🤝 **Set destination contract to source contract and source contract to destination contract:**

To set destination contract to source contract and source contract to destination contract, we make use of setContractOnChain function. For more info, go to [`Setting up the Destination Contract on the Source Contract`](#Setting-up-the-Destination-Contract-on-the-Source-Contract)

💵 **Send Route tokens to the source contract:**

To send Route tokens to the source contract, copy the source contract address, visit https://devnet-faucet.routerprotocol.com/ , paste the address there and click on Get Route

🚂 **Transfer minted ERC-721 tokens from source chain to destination chain:**

To transfer minted ERC-721 tokens from source chain to destination chain, we make use of transferCrosschain function, which burns token with given id on source chain and mint the same token having same id on the destination chain. For more info, go to [`Transferring tokens from a source chain to a destination chain`](#Transferring-tokens-from-a-source-chain-to-a-destination-chain)

🔍 **Browse to [Router Devnet Explorer](https://devnet-explorer.routerprotocol.com/crosstalks)** to see the transactions made. Wait for sometime till you see 4 green checks in your transaction column.This indicates, the tokens have been successfully transferred to the destination chain

📖 For more detailed steps , refer [Step by Step guide for CrossChain ERC-20](https://github.com/router-resources/Workshop-ERC20)

# 🧭 `Table of contents`
- [🚀 Steps](#-quick-start)
- [🧭 Table of contents](#-table-of-contents)
- [`Initiating the Contract`](#Initiating-the-Contract)
- [`Creating state variables and the constructor`](#Creating-state-variables-and-the-constructor)
- [`Setting up the Destination Contract on the Source Contract`](#Setting-up-the-Destination-Contract-on-the-Source-Contract)
- [`Transferring tokens from a source chain to a destination chain`](#Transferring-tokens-from-a-source-chain-to-a-destination-chain)
- [`Handling a cross-chain request`](#Handling-a-cross-chain-request)
- [`Handling the acknowledgement received from destination chain`](#Handling-the-acknowledgement-received-from-destination-chain)
- [`Full Code`](#Full-Code)


  
## `Initiating the Contract`

For initiating the smart contract named "nft", the contract imports four external contracts :-

1. **ICrossTalkApplication.sol**

2. **IGateway.sol**

3. **ERC721.sol**

The "ICrossTalkApplication.sol" and "IGateway.sol" contracts are imported from the "evm-gateway-contract/contracts" and "ERC721.sol" from "openzeppelin/contracts/token".The "nft" contract implements the "ICrossTalkApplication" and "ERC721.sol" contract by inheriting from them. This means that the "nft" contract must have all the functions and variables defined in the "ICrossTalkApplication" contract. By importing and implementing these contracts, the "nft" contract will have access to their functionality and will be compatible with other contracts that follow the same standards.

```sh
//SPDX-License-Identifier: UNLICENSED
pragma solidity >=0.8.0 <0.9.0;

import "evm-gateway-contract/contracts/ICrossTalkApplication.sol";
import "evm-gateway-contract/contracts/IGateway.sol";
import "@openzeppelin/contracts/token/ERC721/ERC721.sol";

contract nft is ERC721, ICrossTalkApplication {
}
```
## `Creating State Variables and the Constructor`

The smart contract has the following state variables:

1. **onwer** - an address variable which stores the address from which the contract has been deployed.

2. **gatewayContract** - an address variable which holds the address of the gateway contract. Gateway contracts are contracts which are pre-deployed on supported blockchains for cross-chain communication.The source chain's gateway contract communicates with the destination chain's gateway contract, enabling communication between application contracts deployed on different chains. Find GatewayContract Addresses [here](https://devnet.lcd.routerprotocol.com/router-protocol/router-chain/multichain/chain_config)

3. **destGasLimit** - a uint64 variable which indicates the amount of gas required to execute the function that will handle cross-chain requests on the destination chain.

4. **ourContractOnChains** - a mapping which maps a chain type and chain ID to the address of nft contract deployed on different chains. This mapping will be used to set the address of the destination contract to the source contract and visa versa

The constructor of the smart contract takes three parameters:

1. **gatewayAddress** - an address variable which holds the address of the gateway contract.

2. **_destGasLimit** - a uint64 variable which indicates the amount of gas required to execute the function that will handle cross-chain requests on the destination chain.

Inside nft contract contructor, pass the name of your token followed by its symbol.

The smart contract extends the ERC721 standard and includes all the required functions and variables such as balanceOf, mint, burn and others.

```sh
    address owner;
    address public gatewayContract;
    uint64 public destGasLimit;
    mapping(uint64 => mapping(string => bytes)) public ourContractOnChains;
constructor( address payable gatewayAddress,
        uint64 _destGasLimit ) ERC721("Token","RTK")
        {
            gatewayContract=gatewayAddress;
            destGasLimit=_destGasLimit;
            owner=msg.sender;
        }
```

## `Setting up the Destination Contract on the Source Contract`

**setContractOnChain**:-

The given code defines a setter function setContractOnChain which allows the owner to set the address of a destination contract on the source chain and visa versa. The function takes three parameters:

chainType - a uint64 variable which represents the type of the chain (e.g. Ethereum, Binance Smart Chain, etc.)
chainId - a string which represents the ID of the chain where the contract is deployed.
contractAddress - an address variable which holds the address of the nft contract deployed on the other chain we want to send the tokens to.
The function first checks whether the caller is the owner by comparing the msg.sender with the admin address variable. If the caller is not the owner, the function will revert with an error message "only owner".

If the caller is the owner, the function will convert the contractAddress to bytes using the toBytes function and store it in the ourContractOnChains mapping using the chainType and chainId as the keys.

```sh
function setContractOnChain(
    uint64 chainType, 
    string memory chainId, 
    address contractAddress
) external {
    require(msg.sender == onwer, "only owner");
    ourContractOnChains[chainType][chainId] = toBytes(contractAddress);
}
```
## `Transferring tokens from a source chain to a destination chain`

**transferCrossChain:-**

This function allows a user to transfer their NFTs from their account on one chain to their account on a destination chain. The function burns the NFTs specified by their id's from the user's account, creates a cross-chain communication request to the destination chain, and passes the transfer parameters as payload in the request.

The function accepts the following parameters:

1. **_dstchainType**: A uint64 representing the type of the destination chain. See the link provided in the description for the list of available chain types.

2. **_dstchainId**: A string representing the ID of the destination chain.

3. **destGasPrice**: A uint64 representing the gas price of the destination chain.

4. **recipient**: Wallet address on the destination chain we want to transfer our NFT to.

5. **id**: A uint256 variable specifying the id of the NFT we want to transfer to the recipient on the destination chain

The function burns the NFT with specified id from the user's account and creates a cross-chain communication request to the destination chain. The payload for the request is generated by ABI encoding "amount" and "recipient".The function uses the ourContractOnChains mapping to retrieve the address of the nft contract on the destination chain.

The function calls the requestToDest function of the Gateway Contract to generate the cross-chain communication request to the destination chain.The requestToDest function in Router's Gateway contracts is used to send a request to the Destination Chain .To execute a cross-chain request, users can call this function and pass the payload and required parameters from the source to the destination chain.

**requestToDest** function takes in these parameters:-

1. **requestArgs** is a struct having these parameters:-
a) expiryTimestamp: The timestamp by which your cross-chain call will expire
b) isAtomicCalls: To make a batch of transactions atomic, set it to true else false
c) feePayer: This specifies the address on the Router chain from which the cross-chain fee will be deducted. For example:- Utils.RequestArgs(1000000000000000, false, Utils.FeePayer.APP)

2. **actType** and **actGasParams** should also be passed as parameters to requestToDest function to set the acknowledgement type , gas limit and gas price for acknowledgment
Utils.AckType(Utils.AckType.NO_ACK),
Utils.AckGasParams (destGasLimit, destGasPrice)

3. **destinationChainParams**: is a struct having these parameter:-
a)gasLimit: Required gas limit for executing cross-chain requests b)gasPrice: Gas price in wei to be used on the destination chain. c)destChainType: Represents the type of chain
d)destChainId: Chain ID of destination chain, in string format.
Utils.DestinationChainParams(destGasLimit,destGasPrice,_dstChainType,
_dstChainId)

4. **contractCalls**: struct , including an array of payloads and contract addresses to be sent to the destination chain. You can send any information you want, and each piece of data will be sent to the respective contract address that you specify in the arrays.
struct ContractCalls {
    bytes[] payloads;
    bytes[] destContractAddresses;}


```sh
 function transferCrossChain(
        uint64 _dstChainType,
        string memory _dstChainId, 
        uint64 destGasPrice,
        address recipient,
        uint256 id
    ) public {
        bytes memory payload = abi.encode(id, recipient);

        
        _burn(id);

      

        bytes[] memory addresses = new bytes[](1);
        addresses[0] = ourContractOnChains[_dstChainType][_dstChainId];
        bytes[] memory payloads = new bytes[](1);
        payloads[0] = payload;

        IGateway(gatewayContract).requestToDest(
            Utils.RequestArgs(1000000000000000, false, Utils.FeePayer.APP),
            Utils.AckType(Utils.AckType.NO_ACK),
            Utils.AckGasParams(destGasLimit, destGasPrice),
            Utils.DestinationChainParams(
                destGasLimit,
                destGasPrice,
                _dstChainType,
                _dstChainId
            ),
            Utils.ContractCalls(payloads, addresses)
        );

       
    }
  ```
 
## `Handling a cross-chain request`

**handleRequestFromSource function:-**

This function is called by the Gateway contract on the destination chain, which is triggered when a cross-chain transfer request is sent by our contract on the source chain. This function receives several parameters, including the source contract address, the payload, the source chain ID, and the source chain type.

1. **srcContractAddress**: A bytes array that represents the address of the contract on the source chain that initiated the cross-chain transfer request.

2. **payload**: A bytes array that containing the payload we sent from the source chain.

3. **srcChainId**: A string that represents the ID of the source chain from which the cross-chain transfer request originated.

4. **srcChainType**: An unsigned 64-bit integer that represents the type of the source chain from which the cross-chain transfer request originated.

he function first checks that the call is made only by the Gateway contract and that the request is received from our contract on the source chain. If the conditions are not met, the function will revert the transaction.

The payload that was sent with the cross-chain transfer request contains recipient's address, the id of NFT to be minted on the destination chain. The function decodes the payload using abi.decode() function.

After decoding the payload, the function uses the _mint function of the ERC-721 contract from the OpenZeppelin library to mint the ERC-721 token to the recipient's address on the destination chain. 

Finally, the function returns an empty string. Note : We have to return atleast an empty string as per the function definition.

```sh
function handleRequestFromSource(
        bytes memory srcContractAddress,
        bytes memory payload,
        string memory srcChainId,
        uint64 srcChainType
    ) external returns (bytes memory) {

        
        require(
            keccak256(srcContractAddress) ==
                keccak256(ourContractOnChains[srcChainType][srcChainId]),
            "Invalid src chain"
        );
        (uint256 amount, address recipient) = abi.decode(
            payload,
            (uint256, address)
        );

        _mint(recipient, amount);

        
        return "";
    }
```
## `Handling the acknowledgement received from destination chain`

**handleCrossTalkAck:-**

The handleCrossTalkAck function is a public function that needs to be implemented in the contract to satisfy the ICrossTalkApplication interface.
The function takes three parameters: **eventIdentifier**, **execFlags**, and **execData** . However, since we are only implementing an empty function, we do not need to use these parameters.

The handleCrossTalkAck function does not perform any operation on the contract or on the blockchain. It is implemented as an empty function and only serves as a placeholder to satisfy the interface requirements.

Therefore, the handleCrossTalkAck function should be implemented with an empty body as shown in the code provided.

```sh
function handleCrossTalkAck(
  uint64, //eventIdentifier,
  bool[] memory, //execFlags,
  bytes[] memory //execData
) external view override {}
```

## `Full Code`

```sh
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.17;
import "evm-gateway-contract/contracts/ICrossTalkApplication.sol";
import "evm-gateway-contract/contracts/IGateway.sol";
import "@openzeppelin/contracts/token/ERC721/ERC721.sol";
contract nft is ERC721, ICrossTalkApplication{
  
    address owner;
    address public gatewayContract;
    uint64 public destGasLimit;
    mapping(uint64 => mapping(string => bytes)) public ourContractOnChains;
constructor( address payable gatewayAddress,
        uint64 _destGasLimit ) ERC721("Token","RTK")
        {
            gatewayContract=gatewayAddress;
            destGasLimit=_destGasLimit;
            owner=msg.sender;
        }
    modifier onlyOwner() {
        require(owner == msg.sender, "Caller is not owner");
        _;
    }
        function mint(address to, uint256 id) public onlyOwner {
        _mint(to, id);
    }
        function setContractOnChain(
        uint64 chainType,
        string memory chainId,
        address contractAddress
    ) external onlyOwner {
        ourContractOnChains[chainType][chainId] = toBytes(contractAddress);
    }
        function transferCrossChain(
        uint64 _dstChainType,
        string memory _dstChainId, 
        uint64 destGasPrice,
        address recipient,
        uint256 id
    ) public {
        bytes memory payload = abi.encode(id, recipient);

        
        _burn(id);

      

        bytes[] memory addresses = new bytes[](1);
        addresses[0] = ourContractOnChains[_dstChainType][_dstChainId];
        bytes[] memory payloads = new bytes[](1);
        payloads[0] = payload;

        IGateway(gatewayContract).requestToDest(
            Utils.RequestArgs(1000000000000000, false, Utils.FeePayer.APP),
            Utils.AckType(Utils.AckType.NO_ACK),
            Utils.AckGasParams(destGasLimit, destGasPrice),
            Utils.DestinationChainParams(
                destGasLimit,
                destGasPrice,
                _dstChainType,
                _dstChainId
            ),
            Utils.ContractCalls(payloads, addresses)
        );

       
    }
        function toBytes(address a) public pure returns (bytes memory b) {
        assembly {
            let m := mload(0x40)
            a := and(a, 0xFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF)
            mstore(
                add(m, 20),
                xor(0x140000000000000000000000000000000000000000, a)
            )
            mstore(0x40, add(m, 52))
            b := m
        }
    }
    function setDestinationGasPrice(uint64 _destGasLimit) public{
        destGasLimit=_destGasLimit;
    }
    function handleRequestFromSource(
        bytes memory srcContractAddress,
        bytes memory payload,
        string memory srcChainId,
        uint64 srcChainType
    ) external returns (bytes memory) {

        
        require(
            keccak256(srcContractAddress) ==
                keccak256(ourContractOnChains[srcChainType][srcChainId]),
            "Invalid src chain"
        );
        (uint256 id, address recipient) = abi.decode(
            payload,
            (uint256, address)
        );

        _mint(recipient, id);

        
        return "";
    }

  function handleCrossTalkAck(
        uint64, // eventIdentifier
        bool[] memory, // execFlags
        bytes[] memory // execData
    ) external {}



}
```

**2. CrossTalk Cheatsheet**

![CrossTalk Cheatsheet](https://user-images.githubusercontent.com/124175970/224511349-e12f08a1-84d2-4d83-94f1-17b18ca5683f.jpeg)

**3. [Router Devnet Docs](http://devnet-docs.routerprotocol.com/crosstalk/understanding-crosstalk)**






