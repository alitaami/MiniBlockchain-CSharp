# Blockchain Simulation in C#

🚀 A simple blockchain simulation built with C# to understand the fundamental structure of blockchains, including blocks, transactions, mining, nodes and etc.. .

## 📌 Features
- Create new transactions 📜
- Mine new blocks ⛏️
- View the full blockchain 📂
- Register and resolve nodes for a decentralized network 🌐
- Get the miner's wallet balance 💰

## 🏗️ Technologies Used
- **.NET Core Web API** for exposing blockchain endpoints
- **C#** for implementing blockchain logic
- **Swagger** for easy API testing

## 🔧 Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/alitaami/MiniBlockchain-CSharp.git
   cd MiniBlockchain-CSharp
   ```

2. Install dependencies:
   ```bash
   dotnet restore
   ```

3. Run the application:
   ```bash
   dotnet run
   ```

4. Access the API`s in Swagger after building the project in your localhost

## 🚀 API Endpoints
### Transactions
- `POST /transactions/new` → Create a new transaction
- `GET /transactions/get` → Get all pending transactions

### Blockchain
- `GET /chain` → Get the full blockchain
- `GET /mine` → Mine a new block

### Nodes (for decentralization)
- `POST /nodes/register` → Register new nodes
- `GET /nodes/resolve` → Resolve conflicts using consensus
- `GET /nodes/get` → Get the list of nodes

### Miner
- `GET /wallet/miner` → Get the miner's wallet balance

## 🛠 Future Improvements
- Proof-of-Stake (PoS) implementation
- Smart contract simulation
- Improved consensus mechanisms

## 📜 License
This project is open-source under the **MIT License**.

---

🔗 **Contributions Welcome!** If you want to improve this project, feel free to fork it and submit a pull request. Happy coding! 😃

