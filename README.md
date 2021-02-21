# NFTPlatz
NFT based marketplace for digital artwork

How to install:
1. Clone this git repostiory 
2. In root folder, run command "npm install"

How to run:
1. Create a file in root folder with the name secret.json
2. Enter account mnemonic in this format in the file -
{
    "secret": "mnemonic phrases"
}
3. Create a fie in root folder with name ".env" and enter FROM ACCOUNT as follows:
FROM_ACCOUNT=<0x Binance Smart Chain Address/Account>
4. In root folder, run command "node server.js"
5. Use browser to create NFT token for digital artwork with URL, for example, http://localhost:4000