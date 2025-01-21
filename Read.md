# Smart Contract Voting System

This project is a web application designed for electronic voting, incorporating user interfaces for voter registration, ballot creation, and voting processes. It leverages Solidity smart contracts to manage voting logic and ballots on the blockchain, ensuring transparency and security.

## Features

- **Voter Registration**: Allows users to register as voters within the system.
- **Ballot Creation**: Enables administrators to create and manage ballots for various elections.
- **Voting Process**: Facilitates secure voting by registered users.
- **Blockchain Integration**: Utilizes Solidity smart contracts to handle voting logic and store ballots on the blockchain, ensuring immutability and transparency.

## Project Structure

The project is organized into the following directories:

- **frontend**: Contains the front-end code for the web application, including user interfaces for registration, ballot creation, and voting.
- **smartvotingEthereum**: Includes the Solidity smart contracts responsible for managing the voting logic and interacting with the Ethereum blockchain.

## Getting Started

To set up and run the project locally, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/syedibtisam/smart-contract-voting.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd smart-contract-voting
   ```
3. **Install Dependencies**:
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```
   - For the smart contracts:
     ```bash
     cd ../smartvotingEthereum
     npm install
     ```
4. **Compile and Deploy Smart Contracts**:
   - Ensure you have [Truffle](https://www.trufflesuite.com/truffle) installed.
   - Compile the contracts:
     ```bash
     truffle compile
     ```
   - Deploy the contracts to a local blockchain (e.g., [Ganache](https://www.trufflesuite.com/ganache)):
     ```bash
     truffle migrate
     ```
5. **Run the Frontend Application**:
   - Navigate back to the `frontend` directory:
     ```bash
     cd ../frontend
     ```
   - Start the development server:
     ```bash
     npm start
     ```
   - Open your browser and navigate to `http://localhost:3000` to access the application.

## Prerequisites

- [Node.js](https://nodejs.org/) and npm installed.
- [Truffle Suite](https://www.trufflesuite.com/truffle) for smart contract management.
- [Ganache](https://www.trufflesuite.com/ganache) or another local Ethereum blockchain for testing.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Note: This README provides an overview of the project based on the available information. For more detailed instructions and documentation, please refer to the project's source code and comments.*
