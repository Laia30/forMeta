# Assignment
This program show how to make tokens in remix.ethereum.org
# Create a Token
Token name is META.
The code can monitor the overall supply of coins, create new tokens (mint), and remove existing tokens (burn).
# Description
The nbtoken.sol contract meets the specified Solidity requirements by incorporating public variables to store coin information such as tokenName, tokenAbbrv, and totalSupply. It also utilizes a public mapping variable called balances to associate addresses with their balances, where the address is of type address and the balance is of type uint (unsigned integer). The contract includes three functions: mintToken, burnToken, and balance. The mintToken function increases the balance of a given address by a specified value and increments the total supply accordingly. Conversely, the burnToken function decreases the balance of a specified address by a given value and reduces the total supply correspondingly. The balance function retrieves the balance associated with a given address.
# Executing Program
> To execute this program, utilize Remix, an online Solidity IDE. Begin by accessing the Remix website at https://remix.ethereum.org/.

> Once on the Remix website, initiate a new file by selecting the "+" icon in the left-hand sidebar. Save the file with a .sol extension. Paste the contents of nbtoken.sol into the newly created file.

> To compile the code, navigate to the "Solidity Compiler" tab in the left-hand sidebar. Ensure that the "Compiler" option is set to "0.8.18" (or another compatible version), then click on the "Compile nbtoken.sol" button.

> After successful compilation, deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Choose the nbtoken contract from the dropdown menu, then click the "Deploy" button.

> Now, in the section labeled "Deployed Contracts" at the bottom-left of the page, you'll find the deployed contract. By clicking on NBTOKEN, you'll access functions such as burnToken and mintToken for burning and minting coins respectively. Additionally, the "balances" button will display the balance associated with the address entered in the text field to the right of the button. Furthermore, three more buttons will provide information regarding the token name, its abbreviation, and the total supply.

