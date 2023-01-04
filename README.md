# ICO
![ICO1](https://user-images.githubusercontent.com/121422342/210549561-4d995bd3-8a51-4660-96bb-01cea6c2b33b.PNG)

![ICO3](https://user-images.githubusercontent.com/121422342/210553162-7c5217cd-ae0d-4fd6-bdf1-d692d3ec1dd5.PNG)

To setup a Hardhat project, open up a terminal and execute these commands:
```
mkdir ICO
cd ICO
mkdir hardhat-tutorial
cd hardhat-tutorial
npm init --yes
npm install --save-dev hardhat
```
In the same directory where you installed Hardhat run:
```
npx hardhat
```
In the same terminal, install @openzeppelin/contracts as we will be importing Openzeppelin's ERC20 Contract and Openzeppelin's Ownable Contract in our CryptoDevToken contract.
```
npm install @openzeppelin/contracts
```
Create a new file inside the contracts directory and call it ICryptoDevs.sol.
Create another file inside the contracts directory and call it CryptoDevToken.sol.

Now we will install the dotenv package to be able to import the env file and use it in our config. Open up a terminal pointing to the hardhat-tutorial directory and execute this command:
```
npm install dotenv
```
Compile the contract, open up a terminal pointing to the hardhat-tutorial
```
npx hardhat compile
```
Execute this command in the same directory to deploy the contract:
```
npx hardhat run scripts/deploy.js --network goerli
```
To develop the website we will be using React and Next Js. React is a javascript framework which is used to make websites and Next Js is built on top of React. You first need to create a new next app. Your folder structure should look something like this:
```
- ICO
       - hardhat-tutorial
       - my-app
```
To create this my-app, in the terminal point to the ICO folder and type:
```
npx create-next-app@latest
```
Now to run the app, execute these commands in the terminal:
```
cd my-app
npm run dev
```
Open up a terminal pointing to my-app directory and execute this command:
```
npm install web3modal
```
In the same terminal also install ethers.js:
```
npm install ethers
```
Now in your terminal which is pointing to my-app folder, execute the following:
```
npm run dev
```
