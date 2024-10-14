# SolToken
A Solidity program that simulates the minting of tokens using the simple functions of solidity.
## How to Run
The program can be run at an online IDE for Solidity called [remix](https://remix.ethereum.org).
### Creating a new file
On the top left inside the File Explorer tab, click the create new file button and name the file anything you want.

![image](https://github.com/user-attachments/assets/40a8cf69-f1d4-481f-91ca-00de641c1af6)

### Compiling
![image](https://github.com/user-attachments/assets/34faeda9-be09-4aaf-9e44-3e25546140a6)

Select a compiler that is greater than or equal to the version `0.8.18`.

### Deploying
![image](https://github.com/user-attachments/assets/30810cdc-92aa-4194-b8df-cc396d05bb47)

Finally, click the `deploy` button to run the program.

## How to use
![image](https://github.com/user-attachments/assets/3276f297-f846-4e3d-9577-74f437102846)

After deploying, you can view your deployed contracts at the bottom and execute the available functions, as well as monitor the values of different variables.

![image](https://github.com/user-attachments/assets/b223dbb9-27b2-49a9-8a98-c9d9adeab3fa)

This is where the addresses can be found which can easily be copied to your clipboard by clicking this button.


![image](https://github.com/user-attachments/assets/5d4358c2-d6fd-4985-a282-3a8126abce35)

Click the dropdown arrow for a better view of the parameters of a function.

## Functions and Variables
The functions are highlighted in orange while the variables are blue.
### Functions
- `mint` - Adds a certain value to the corresponding address.
- `burn` - Subtracts a certain value to the corresponding address only if there is enough balance.
### Variables
- `balances` - A mapping of addresses to values (input address to check balance).
- `totalSupply` - The sum of the balances of all accounts.
- `tokenName` - The name of the nonexistent coin.
- `tokenAbbr` - The abbreviation of the coin.
