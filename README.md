# Starter Next/Hardhat Project

##  This project features 4 functions namely getBalance, deposit, withdraw, and transferOwnership.
# getBalance - returns the balance of the wallet
# deposit - allows the user to deposit from the wallet by 1, 10, 100, or 1000 ETH
# withdraw - allows the user to withdraw from the wallet by 1, 10, 100, or 1000 ETH
# transferOwnership - transfers ownership of the account

After cloning the github, you will want to do the following to get the code running on your computer.

1. Inside the project directory, in the terminal type: npm i
2. Open two additional terminals in your VS code
3. In the second terminal type: npx hardhat node
4. In the third terminal, type: npx hardhat run --network localhost scripts/deploy.js
5. Back in the first terminal, type npm run dev to launch the front-end.

After this, the project will be running on your localhost. 
Typically at http://localhost:3000/
