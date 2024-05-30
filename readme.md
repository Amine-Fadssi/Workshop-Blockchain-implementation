# Java Blockchain Implementation

## Overview

This project provides a Java-based implementation of a blockchain, a decentralized and immutable ledger technology. The project aims to offer a practical understanding of blockchain concepts and facilitate learning through hands-on development.

## Features

- **Core Components**: Includes essential blockchain components such as blocks, transactions, and validation mechanisms.
- **Proof of Work**: Implements the proof of work algorithm for mining new blocks and securing the blockchain network.
- **Transaction Pool**: Manages pending transactions before inclusion in blocks during the mining process.
- **Hashing Utility**: Provides utility functions for applying the SHA-256 hashing algorithm.
- **Testing Suite**: Includes a testing suite (`BlockchainTest`) to verify the functionality and integrity of the blockchain implementation.

## Project Structure

The project is organized into the following folders:

- `blockchain`: Contains Java classes for blockchain implementation, including `Block`, `Blockchain`, `Transaction`, and `TransactionPool`. This is where the core logic of the blockchain resides.
- `tests`: Includes test classes for validating blockchain functionality (`BlockchainTest`). Test cases ensure that the blockchain operates as expected and remains robust.
- `utils`: Houses utility classes, such as `HashUtil`, for cryptographic hashing operations. These utilities support essential functions like hash calculation within the blockchain.
- `Main.java`: Entry point for the application. This class initializes the blockchain and provides a starting point for experimentation and testing.

## Getting Started

To get started with the project:

1. Clone the repository to your local machine.
2. Open the project in your preferred Java IDE.
3. Explore the `blockchain` package to understand the core components and their functionality.
