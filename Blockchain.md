# Blockchain

## Abstract
This proposal details the flow Specification, intercommunication and exchange of data on the Blockchain network

### Motivation
All communication between client apps and the business network should be handled on a distributed ledger.

### Use Cases / Scenarios
- A request (lending, forex, loan) and client apps posts (CRUD action) to the chaincode service (smart contract).
- All smart contracts emit events over websocket to the blockchain business network.
- All requests (lending, forex, loan) and client apps subscribe to business network events over websocket to receive messages from smart contract.

### API & Integration

### Specification
```
```
