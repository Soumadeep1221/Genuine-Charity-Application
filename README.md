
<br />
<p align="center">
       <img src="https://drive.google.com/uc?export=view&id=17oE81x8pLWTI3GjqXKJKAtfxnJMUpdNl" alt="Logo" width="120" height="120">


  <h1 align="center">Genuine-Charity-Application</h1>
    <br><br>
  </p>
</p>


## 🤔 About Project

Create a Transparent Charity System using Smart Contracts on Ethereum.
## 👨‍💻 Team members
* [Shreyas Penkar](https://github.com/Shreyas-Penkar)
* [Jainam Dharod](https://github.com/madmax19)
* [Purva Anjarlekar](https://github.com/Caddonix)
* [Aishwarya Harkare](https://github.com/Aishwarya856)
* [Rohan Sawai](https://github.com/rohansawai)
* [Santanu Kumar](https://github.com/santanukumar666)

## 🙏 Mentors
* [Pratim Ugale](https://github.com/pratimugale)
* [Shivani Pawar](https://github.com/shivanipawar00)

## 📃 Description

* We have created a Solidity Smart Contract for this cause and we have used web3, ganache-cli, mocha, to test out our contract.

* In the contracts folder, you will find a final solidity contract and the individual modules inside contracts_classified directory.

* On the Frontend Part we have html,css,javascript and full UI of Genuine Charity App along with Admin Panel in the website folder.

* Included a test directory with a test file to test all the functions used in the contract by deploying it on ganache and using web3 to utilize the ABI.

* Included a sample React Template so that the frontend can be used to include the website along with the test code to make a production app.

* Included code to compile the contract and to deploy the contract on the Rinkeby Test Network using the Infuria node module.

* The website and the test modules are not yet connected and the code is placed in seperate folders.

* GitHub repo link: [Link to repository](https://github.com/Shreyas-Penkar/Genuine-Charity-Application)
* Drive Link to Screenshots: [Link to Drive](https://github.com/Shreyas-Penkar/Genuine-Charity-Application)
* EthFiddle Link to Test the Contract - [Link to EthFiddle](https://ethfiddle.com/4iviewhMlS)

## 🛠Technology stack

Tools and technologies that we learnt and used in the project.

1. Solidity
2. HTML,CSS,JS,React
3. Node JS
4. web3,ganache-cli,mocha,solc node modules

## 🚀 Instructions to run the application (DEVELOPMENT)

1. Clone the Repository

```bash
git clone https://github.com/Shreyas-Penkar/Genuine-Charity-Application.git
```

2. Create a Node app and install dependencies

```bash
npm init
```
after following the steps run 
```
npm install web3@1.0.0-beta.26
npm install mocha@8.2.1
npm install solc@0.4.17
npm install truffle-hdwallet-provider
npm install ganache-cli@6.12.2
```

3. Refer to the package.json file for full details on the installed packages.

4. To run the Contract online, refer to the EthFiddle Link above.

5. To compile the contract use 
```bash
node compile.js
```

6. To run the test module, in your package.json under the "scripts" object, add 
```
"test": "mocha --timeout 15000"
```
then run 
```bash
npm run test
```
### Ganache Deployment Diagram
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1-0H4cSyhOn3qdP8ZPpl22Z_nDiH5qWoc)
 
7. To deploy the contract on the Rinkeby Test Network using Infura, follow the steps - 
* Register on Infura - https://infura.io/register 
* Follow all the steps there for account activation
* After that you'll see a dashboard similar to this -
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1w8vioZQUxLInTexHPJsrR1xQVx9a0Vb1)

* Install the MetaMask Browser extension - [Link to MetaMask Chrome Extension](https://chrome.google.com/webstore/detail/metamask/nkbihfbeogaeaoehlefnkodbefgpgknn?hl=en)
* Make an account and note down the 12 word mnemonic generated.
* Now, Go to Infura and get the link to the Test Ethereum Network, it would look something like this - 
  ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1DfdDBAx15G_fOvvJk60lf4PdDJcrG6Ja)
* Now enter the 12 word mnemonic and the link in deploy.js over here - 
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1epZItPaEAeWtY_KiW0Xpn0oLYXvWZitL)
* Now run this command on the terminal - 
```bash
node deploy.js
```
### Infura Deployment Diagram
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=13TAQNZtYjfQvamANL9RYIdrZMGJK-BRq)


## 📝Applications
> Many fake charity organizations pose as genuine and loot money from innocent people in the name of charity. Most people want to donate money to a good cause of charity, but they are unsure if the money is going to reach the right hands of the destitute.  The blockchain system can bring transparency to online charity trusts. Contributors can see the journey of the donation in realtime and confirm if it’s reaching the deserving hands or not.

## 👨‍🎓What did we learn from this project

1. Shreyas Penkar - </br> It was awesome working as a leader in this project. I learnt how Blockchains work giving me a clear understanding of the various moving pieces and concepts regarding Blockchain. I was able to contribute to a solidity contract and write tests for the same. I gained many useful skills related to management, leadership, team-work and also got to know a lot about my co-workers and mentors. It was fun working with them on this project. So, overall it was a huge success.
2. Jainam Dharod - </br>It was wonderful experience working on this project and exploring this wonderful new domain of Blockchain Technology.I learbt Smart Contracts, Solidity Programming language through this project. Apart from this, I also learnt a lot from my teammates and mentors who helped me every step throughout this project.Overall, this was a great experience for me. 
3. Purva Anjarlekar - </br> Working on this project was a delightful and educative experience. I have to say, I couldn't have asked for better teammates. We all got to learn blockchain and the meets we had corresponding to this subject, especially the one in the beginning with our super senior was simply awesome. Apart from the topics in blockchain, working with this team helped me improve my people skills. Overall, this was an amazing experience and I have the team and SkillUp project to thank for it!
4. Aishwarya Harkare - </br> Collaborating with the team was indeed wonderful experience for me. Working on this project I could dive into the whole new world of Blockchain Technology.I learnt Smart Contract , Solidity programming language through this project. I got to write a bit of Smart Contract for this Application. Further, I coordinated with my collegue Purva Anjarlekar in making Frontend of the website. Working with Teammates and mentors helped me gain skills such as team-work , communication skills. Thus, this was a great adventure for me.
5. Rohan Sawai - </br> It was an incredible experience for me. I got to learn the concept of Blockchain technology and various concepts related to Blockchain. As a member of this team, I contributed to the Solidity contract, a small part of frontend and also wrote tests. I learned skills like team-work, time-management and how to effectively communicate with my team. Furthermore, would like to thank our leader, Shreyas and mentors for guiding me right from basic learning resources. Overall it was an amazing experience!    
6. Santanu Kumar - </br> I had a great time working on this project.I was introduced to the blockchain technology.I got to learn vaious concepts regarding Blockchain, Solidity language etc. During the project I got to run a local blockchain system which helped me to clear my concepts.It was fun writing the smart contracts and testing them.Further ,close coordination and communication with my team members and mentors helped us complete this project and I would like to thank them all for guiding me and providing me with the resources.



## 🔮Future scope
* As the frontend is not yet connected to the contract, we could first connect it using a sample node server or by using React.
* Make the UI/UX even better.
* Make an Andriod app for this idea.

## 🎨Screenshots
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=12TAfrme-NDTBkhtnWFr3TsyEOdtMP4Jl)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1vK4JK8lPMLAarbBzuHBsdPWO5ypKhU1S)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1YcszBNbehBJ_l639gY1zPWC-IDkClrq5)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1CZUn1mj9NRQlItvdrmk28IiZLIG4QVZ9)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1ZtbV-GH0r1XLZtSrGpfCVZGDVONUhZc6)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=12xJ4IyhTOcyuqcB5VJ__Qx0oRosAS9M4)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1dp_Q8c1b0pzpoiwW18sP1ioYb5jKzRes)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1jsvI2qNV5XfWeUTMfaGMupVOlBxufukY)
 ![Screenshot alt text](https://drive.google.com/uc?export=view&id=1rwQZdVSvsD39PS-p6UKssF1Gn_gIbcWC)
