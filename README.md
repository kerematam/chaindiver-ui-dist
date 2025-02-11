# Chain Diver

[![Website](https://img.shields.io/website?url=https%3A%2F%2Fchaindiver.com)](https://chaindiver.com)

This repository contains the UI distribution code for [Chain Diver](https://chaindiver.com) - a blockchain data analytics platform. Built as a Single Page Application with React, it enables users to explore blockchain data through natural language queries, execute SQL statements, and generate REST APIs.

## 🚀 Features
- **SQL Query Generation** based on natural language input.
- **Execute SQL Queries** directly on blockchain data.
- **Generate APIs** from SQL queries for seamless integration.
- **Runs Blockscout for Indexing** blockchain data.
- **Supports Fuji C-Chain** (alpha version).

## 🛠 Build
```sh
# Clone the repository
git clone https://github.com/yourusername/chain-diver-ui.git
cd chain-diver-ui

docker build -t chaindiver-ui-distribution .
docker run -p 80:80 chaindiver-ui-distribution
```

## 📜 License
MIT License © 2025 Chain Diver

