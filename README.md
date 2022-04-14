# SmartContracts-SharedWallet
This is the SmartContract I have created as a part of the Ethereum Solidity Developer Bootcamp.

Anyone can send money to this SmartContract.
There is a possibility to check who is the owner of the SmartContract ('owner').
Owner can add allowance meaning owner can setup how much it is posible to withdraw by certain address ('addAllowance').
It is possible to Transfer Samrt Contract Ownership to another address ('transferOwnership').
It is possible to check allowance for each address ('allowance').
Function 'renounceOwnership' is supposed to renounce ownership from owner but in this case it is used as an example of 'reverting' a function so it always gives an error
"cannot revert owner".

