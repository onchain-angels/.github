# Onchain Angels 😇

An AI-powered financial coach that helps traders make smarter financial decisions by providing behavioral insights based on their on-chain actions. Think of it as your personal "guardian angel" that guides you at crucial moments to keep you aligned with your financial goals.

## Ecosystem Overview 🌟

Each repository plays a vital role in ensuring the Onchain Angels solution works seamlessly together: 🤝

- 🤖 **Agent:** AI agent that processes data and generates personalized behavioral insights.

- 💻 **Backend:** Handles data processing and generation, integrating with external services such as Alchemy, Etherscan, CoinGecko, and OpenAI.

- 🌐 **Frontend:** Intuitive and lightweight user interface enabling profile creation and system interaction.

- 🔒 **Nillion:** Secure data management through Nillion Secret Vault, ensuring privacy and data integrity.

- 🐍 **Nillion-sv-wrappers-py:** Python utility library to communicate with Nillion db.

<img src="https://github.com/onchain-angels/.github/blob/master/profile/images/workflow_v2.jpg" alt="workflow"/>

## Repositories 🚀

### 1. **Agent** 🤖

- **Repository:** [https://github.com/onchain-angels/onchain-angels-agent](https://github.com/onchain-angels/onchain-angels-agent)
- **Description:**  
    Houses the AI agent - a customized fork of [elizaOS/eliza-starter](https://github.com/elizaOS/eliza-starter), featuring custom character configurations, Farcaster and Twitter/X integration clients, and a plugin for retrieving users' latest transaction data from the backend.
- **Tech Stack:**
  - PENDING
- **Deployment:** Autonome

### 2. **Backend** 💻

- **Repository:**
    [https://github.com/onchain-angels/onchain-angels-backend](https://github.com/onchain-angels/onchain-angels-backend)
- **Description:**  
    This repository contains APIs for profile management and user activity webhooks. It handles all server-side logic, including wallet and token management, plus integrations with blockchain data providers (Alchemy, Etherscan, CoinGecko). Implements webhooks that summarize user actions and relay them to the agent.
- **Tech Stack:**
  - Python
  - Django
  - Django REST Framework
  - PostgreSQL
- **Deployment:** Heroku [https://api.onchain-angels.com/](https://api.onchain-angels.com/api/v1/schema/swagger-ui/)

### 3. **Frontend** 🌐

- **Repository:** [https://github.com/onchain-angels/onchain-angels-frontend](https://github.com/onchain-angels/onchain-angels-frontend)
- **Description:**  
    Web application where users can create profiles to receive AI-powered financial insights. User information is securely stored in the backend and utilized to generate personalized agent responses.
- **Tech Stack:**
  - Next.js
  - Tailwind CSS
  - TypeScript
- **Deployment:** Vercel [https://onchain-angels.com/](https://onchain-angels.com/)

### 4. **Nillion** 🔒

- **Repository:** [https://github.com/onchain-angels/nillion](https://github.com/onchain-angels/nillion)
- **Description:**  
  - Forked from [NillionNetwork/nillion-sv-wrappers](https://github.com/NillionNetwork/nillion-sv-wrappers)
  - Used for testing and schema development for Backend-Agent information exchange
  - Not implemented in the current submission but planned for future development
- **Tech Stack:**
  - JavaScript
  - Node.js
  - nillion-sv-wrappers

### 5. **nillion-sv-wrappers-py** 🐍

- **Repository:** [https://github.com/onchain-angels/nillion-sv-wrappers-py](https://github.com/onchain-angels/nillion-sv-wrappers-py)
- **Description:**  
    A Python library that provides wrappers for seamless integration with the Nillion Secret Vault. Inspired by [NillionNetwork/nillion-sv-wrappers](https://github.com/NillionNetwork/nillion-sv-wrappers) JavaScript implementation, it offers an abstraction layer for secure, decentralized data storage and encryption operations.
- **Tech Stack:**
  - Python
  - nilql
