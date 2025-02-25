# Building an Ethereum Blockchain App: 8 Supply Chain Smart Contract dApp

## Supply chain app

- Framework that connects producers and consumers
- Manages products and services along that journey

## Blockchain

- Reduce costs
- Transparence & visibility

### Assests

- Product bought by customers

### Partecipants

- All supply chain partecipants
- Manufactures
- Suppliers
- Shippers
- Customers

### Ownership structure

- Which partecipant currently owns the product
- Tracks the product
  
### Payment tokens

- Partecipants pay each other with tokens as ownership changes.

### Supply chain design

- Initialize tokens
  - Establish initial pool of payment tokens
- Transfer tokens
  - Move tokens between accounts as payment
- Authorize token payments
  - Allow token transfer
- Add & update partecipants
- Move products along supply chain
  - Transfer product ownership
- Add & update products
- Track and asset
  - Where is the product now
  - Find product owrnership

## Decentralized application (dApp)

Application that runs in more different nodes

### Advantages

- Automatic history tracking
- Built-in fault tollerance
- Trusted data
- Allow users to access blockchain data
  
## Payment token smart contract data items

- Total number of tokens in circulation (totSupply)
- Descriptive name (name)
- Decimal precision (decimal)
- Short identifier (symbol)
- Current balance of each user (balances)
- Tokens authorized to transfer (allowed)