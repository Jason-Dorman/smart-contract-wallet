# smart-contract-wallet

This is a smart contract wallet built with Solidity. It allows the owner to add funds, designate an allowance to a different user and allows that user to withdraw funds. Thrid party libraries are used like SmartMath to track withdraws to avoid double spending. This wallet also emits indexed events to allow the user to search the logs to see what's happening inside the smart contract.
