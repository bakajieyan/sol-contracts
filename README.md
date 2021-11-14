Steps on how to deploy a Project with Payment Splitter

1. Setup the PaymentSplitter.sol
2. Pass the constructor arguments of the payee and the shares like:

```
["addess1", "address2", "address3"]
```
Ps. dont forget to include your address to put in the payees

and for the shares:

```
[20, 40, 40]
```
Ps. the sum of all shares must be equal to 100

3. Depoly the PaymentSplitter.sol

4. Copy or save the contract address of the Deployed PaymentSplitter.sol

5. Setup NFT.sol and rename the file to your project name

6. Pass the constructor arguments, as for the _payments parameter paste the contract address of the Deployed PaymentSplitter.sol

7. Deploy NFT.sol
