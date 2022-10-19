# Ethernaut 10 - Re-entrancy

* If you dont specify a function call a smart contract owned account can run malacious code on your original contract with a fallback function
* A Re-entrancy attack is a recursive calback into original function call for undesired outcome via fallback function
* Ways to avoid is to update state variables before making calls to external contracts
* Checks and effects interactions pattern
* Second tehcnique to avoid re-entrancy mutex(only allows function to execute once with modifier)












## References
https://www.youtube.com/watch?v=0qCNOxVugGk&t
https://ethernaut.openzeppelin.com/level/0x40b8Df5575a55b2f0c55E6e18838AEC7B82aebD7

    #Dao #Hack #reentrancy #DaoHack #mutex