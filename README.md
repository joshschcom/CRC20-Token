# CRC20-Token
A small and easy description for deploying CRC-20 Tokens to the Cronos Blockchain. We'll use remix aswell as Metamask in this example. 

# Open remix.ethereum.org
Create New File and name it SAMPLENAME.sol

# Paste the code into it(crc20sample.sol)

# Change the Name to your liking on Paragraph 155
"SAMPLENAME"

# Declare the name, symbol, decimals and total supply to your cryptotoken
Starting at paragraph 168 "SAMPLE", Paragraph 169 "SAMP", Paragraph 170 "8", Paragraph 171 "10000000000000" Note: You hav to add the decimals behind the inital supply. In our example in Paragraph 171, we have a supply of 1000000((1Million) + 8 decimals(00000000) = 100000000000000")

# Use the right compiler version and compile
Aswell as choose Enable Optimization(200)

# Deploy with Injected Web 3
Sign the transaction and deploy the contract. Dont forget choosing the right contract and Account.

# After the trasaction went through, view the Transaction on the Cronos Block Explorer
You'll see that a new Token has been created and transferred to your Metamask account. Copy Paste the contract(!) address into the "Import Tokens" Tab on Metamask. It will fill out the rest of the Info in a short time afterwards. You'll now see your Token in your Account. 
Congratulations! You now made your very own CRC20 Token.
