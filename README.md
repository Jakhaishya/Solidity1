# Solidity1
# Metacrafters--EVM-Proof-Beginner
Here we have to create ERC -20 token contract implementedd in Solidity. The contract helps us for the creation and destruction of tokens,as well as storing information about the token.

# Requirements
1. The public variables in the contract stores the details about the coin:
   >tokenName: A string that represent the token's name.
   >abbrv: A string that represent the token;s abbreviation.
   >totalSupply: A unsigned integer that represents the token's entire supply.
2. The contract has an address to balance mapping:
   balance: An association between addresses and the accompanying token balances.
3. The contract provides a mint funtion that adds a specified amount to both the balance at the "sender" address and the overall supply:

 
