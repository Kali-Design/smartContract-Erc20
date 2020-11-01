# smartContract-Erc20

Steps :
TransactionCounter.sol
Deploy contract and copy contract address

FirstERC20.sol
Deploy contract with address of TransactionCounter contract and copy contract address

FirstIco.sol
Deploy with address of FirstERC20 contract

TransactionCounter.sol
Approve FirstERC20 address by calling addTicker function with the address of FirstERC20 contract

FirstERC20.sol
Approve FirstIco address by calling approve function with the address of FirstIco contract and a maximum amount allowed to FirstIco contract responsible for selling tokens