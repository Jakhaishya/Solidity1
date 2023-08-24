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

# Parameters:
_address: The address to which the tokens will be minted.
_value: The amount of tokens to be minted.

# Actions:
Increase the totalSupply by _value.
Increase the balance of the _address by _value.

4. The contract has a burn function that decreases the total supply and the balance of the "sender" address y a given value:
   _address: The address from which the tokens will be burned.
   _value: The amount of tokens to be burned.

Actions:
Check if the balance of the _address is greater than or equal to  _value.

If true, decrease the totalSupply by _value.
Decrease  the balance of the _address by _value.

# Usage
Install the myToken contract on a Ethereum network that is supported.

When the contract is launched, you may communicate with it by calling the following functions:

mint: allocates newly created tokens to a certain address.

# Parameter:
_address: The address to which the token will be minted.
_value: The amount of tokens to be minted.

burn: reduces the total supply and the balance of a given address by burning existing tokens.

# Parameters:
_address: The address from which the tokens will be burned.
_value: The amount of tokens to be burned.

# License
The MIT License governs this agreement. MIT is the SPDX-License_Identifier. 
