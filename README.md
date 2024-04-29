commands:
1.npm install -g truffle
2.mkdir helloworld
    cd helloworld
    truffle init
3.truffle create contract HelloWorld

//It will create HelloWorld.sol in contracts folder.

4.Use following command to build:
    truffle compile

4. Create migration file using following command
    truffle create migration HelloWorld    

5.truffle develop

6.truffle migrate

7.To test deployment, let's start truffle console and run our smart contract methods to verify.
    truffle console
    let instance = await HelloWorld.deployed()
    instance.getGreeting()

if you get “hello world”, it means successfully deployed 

Congratulations!

Congrats on finishing the tutorial and having deployed smart contract using truffle framework. 