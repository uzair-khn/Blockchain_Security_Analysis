# Blockchain Security Analysis
## Description:

The analysis involve the examination of the Blockchain Smart Contract to find any vulnerabilities/weakness or any risk that could compromise the security related to the smart contracts. <br/>
The analysis will be static analysis like it will be done before deployment of any smart contract. <br/>
I use the online platform for this project named Remix IDE.

## What is needed for the project: 

- Choose any blockchain platform like Remix ID, Hyperledger Fabric, or EOS. I choose:
  <br/> ***Remix IDE i.e. Ethereum blockchain*** : Link <a>https://remix.ethereum.org/</a> 
- Plugins : Solidity Static Analysis & MythX Security Verification

## Working Steps
- Open Remix IDE which will look this,<br/><br/>
<img src = "https://github.com/uzair-khn/Blockchain_Security_Analysis/blob/main/imgs/p1.PNG" width="1000px" height="500px"> <br/>

   Create a folder in the IDE with whatever name you like. Mine by, **my_contracts**<br/>
   ➡️🖱️ Folder and add file named ***Smart_contract1.sol*** <br/><br/>
  <img src="https://github.com/uzair-khn/Blockchain_Security_Analysis/blob/main/imgs/p2.PNG"> <br/>
  
 - Furthermore, we need smart contracts with vulnerabilities and risk. <br/>
    There are many resources where you get it or make your own one. But for this project, i take from the resources like:<br/>
    - Openzeppelin.com <a> https://docs.openzeppelin.com/contracts/4.x/ </a>
    - ConsenSys <a> https://github.com/ConsenSys/smart-contract-best-practices </a>
    - Chatgpt 
   
           Note: We are implementing only few smart contracts like 
   
 - Write them in the files you made under <my_contracts> folders.<br/><br/>
    <img src="https://github.com/uzair-khn/Blockchain_Security_Analysis/blob/main/imgs/p3.PNG" height="500px"> <br/>
    
 - ***First Manually analyze the smart contract and find out the vulnerability that will be detected, then Automate.***
 
 - Open File Explorer in Remix IDE , Check for these security analysis tools in ***Plugin Manager***: <br/>
     - Solidity Static Analysis
     - MythX
     <br/>Activate both of them.<br/><br/>
     <img src="https://github.com/uzair-khn/Blockchain_Security_Analysis/blob/main/imgs/p4.PNG" height="400px"> <br/>
     - We are only analyzing the Security Section, <br/> <br/>
     <img src="https://github.com/uzair-khn/Blockchain_Security_Analysis/blob/main/imgs/p5.PNG" height="400px"> 
     
 - Compile the code with Ctrl+S or ▶️
 
 ### UseCase One of Smart Contract : Reentrancy Attack
 - After compling it, it does give error which seems like this, <br/> <br/>
   <img src="https://github.com/uzair-khn/Blockchain_Security_Analysis/blob/main/imgs/p6.PNG" height="400px">
   
 
 

