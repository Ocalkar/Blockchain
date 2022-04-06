**Steps To Develop Your First Truffle Project**

**Open Powershell Window**

**Create a Directory Under Your Development/Workspace Directory**

md firstProject

cd firstProject

**Generate Your First Project Using Truffle**

Truffle init

**Open The Generated Code in VS Code**

code .

**Make The Necessary Configurations of recently generated  Truffle-config.js file**

Open Ganache start new network and then get the port number of RPC Server 

Edit the Below Lines and update  port number in Truffle-config.js file

     development: {
      host: "127.0.0.1",     // Localhost (default: none)
      port: 7545,            // Standard Ethereum port (default: none)
      network_id: "*",       // Any network (default: none)
     },

**Create HelloWorld.sol file under Contract folder of your firstProject**

```
pragma solidity ^0.8.12;

contract HelloWorld {
    string private helloMessage = "Hello World!";

    function getHelloMessage() public view returns(string memory)
    {
    return helloMessage;
    }

}
```

For the first line 

```
pragma solidity ^0.8.12;
```
You can to edit solidity version by your local solidity versionby typing below command in powershell

Truffle version
