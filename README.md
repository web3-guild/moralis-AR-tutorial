# moralis-AR-tutorial
followup of the moralis AR tutorial with some side additions to build an cross native application template for making AR/mixed reality apps across different paltforms. 
- [ ] refactor the documentation in order to describe the development tutorials across different  platforms (AR, 3D modelling and other projects) for building the  whole tutorial series for web3 building in metaverse.
- [ ] run the tutorial of moralis


## tutorial steps followed: 
1. setting up the AR development enviornment: 
  1.1 using the Unity Hub and unity AR core installation, relevant resources :
    - [web3-unity-sdk](https://github.com/MoralisWeb3/web3-unity-sdk).
    - [unity-web3-simple-ar-metaverse](https://github.com/MoralisWeb3/unity-web3-sample-ar-metaverse).
    - [and the whole suite of tools](https://github.com/MoralisWeb3?q=unity&type=all&language=&sort=) managed by them. understand their development of modules  and then  create  the whole development suite for the other AR softwares.
   1.2 installing the modules for the development enviornment(android, ios, flutter based cross manageable, etc).
   1.3 take an template project for AR for having the build setup.
    - [ ] setting up the ARCore support for the IOS. 
  
  1.4 understanding the main programmable components in the unity game-engine(optional): 
    - in order to understand the different components in order to make more advance smart contract logic driven programs, [here](https://docs.unity3d.com/Manual/class-GameObject.html) are the list of the classes defined in the unity for providing scripting capablities directly in the game engine enviornment.
    
  
  
  
3. Setup Moralis dapp.
  - first get the api endpoint setup in the moralis   
  -  open the plugin and adding the details .
  -  then going to the main screen 
    - before that, understand the functions of the different components of the unity main editor  screen from [here](https://docs.unity3d.com/Manual/UsingTheEditor.html).  
    -  main components that will be shown in the status bar will be the web3 modules developed for the game logic interaction (ie with the GameObject in the screen), eg:
        - Authentication with wallet
        - game manager. 
          - building the state machine smart contract  pattern in building the game.     

       


4. Project structure overview. 
5. Creating the metaverse item.
    - Fetching the gaming objects and their correpsonding states 
       - for each of the operation that creates the state change, we will be defining in 'projects/state/*.cs' file that will define the above class for building the projects. 
       -    then import the  differtent sates with the objects in order to definde the behaviours and their correponsing  events 
          -   like shooting state interacting with the   given objecty, and based on the criteria ., and hte game is created only when the shoot is no the particular component in the shooting box.
       -   then redering the projects from the IPFS in the given states noe the state is being invoked by the offchain game program.
         -  learn how to build the game design patterns [here from illuwaar on java](https://github.com/iluwatar/java-design-patterns). 
 
7. deploying the smart contract
     -  importing an template   smart contract template (fonudry, hardhat). 
     -  adding the contracs and the script that needs to be automatedly deployed (with the address of the user and other parameters for meta-transaction) when there is interaction with the  NFT component.  
     -  deploy the script !!!!
     -  minify the deployed ABI (to be  store by the gameManager obeject) along with the address in the moralis SDK.
     -  then use the moralis SDK functions (Moralis.star(...) or Moralis.ExecutioncontarctFunction(GameManager, contractaddress, <<ERC721 parameters>> )).
     - defining the metadataURI params  for the different NFT objects in the metaverse.
     - 

8. minting item as NFT by build for the platform you want to build(phone, tablet):   
