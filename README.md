# Vault having Cross Function Reentrancy

The function from which the malicious external call is made is different from the function to which the re-entry is made by the malicious contract, but both the functions use require statements that check the same state variable.


## License

This Contract is released under the [MIT License](LICENSE) and thanks to [OpenZeppelin](https://openzeppelin.com).

