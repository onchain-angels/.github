# Onchain Angels 😇

AI-powered financial coach that helps traders make better financial decisions by responding to on-chain actions with behavioural insights. Think of it as an "angel on your shoulder" that nudges you at key moments to keep you aligned with your goals.
Below is a brief description of each repository. 

## Ecosystem Overview 🌟

Each repository plays an essential role in ensuring that the Onchain Angels solution operates in an integrated manner: 🤝

- 🤖 **Agent:** PENDING

- 💻 **Backend:** Data generation and processing, including integration with external services like Alchemy, Etherscan, CoinGecko and OpenAI.

- 🌐 **Frontend:** A simple & lightweight user interface that allows users to create a profile on the app, integrates with the backend.

- 🔒 **Nillion:** Secure data management through the Nillion Secret Vault, ensuring privacy and integrity.

- 🐍 **Nillion-sv-wrappers-py:** A Python utility library that simplifies cryptographic operations and communication with Nillion, enabling the creation of customized solutions.


## Repositories 🚀

### 1. **Agent** 🤖
- **Repository:** [https://github.com/onchain-angels/onchain-angels-agent](https://github.com/onchain-angels/onchain-angels-agent) 🔗
- **Description:**  
    This repository hosts the interactive agent. It is a fork of [elizaOS/eliza-starter](https://github.com/elizaOS/eliza-starter) and allows customization of characters and clients, enabling integration with platforms like Twitter and Discord.
- **Tech Stack:**
    - PENDING
- **Deployment:** PENDING


### 2. **Backend** 💻
- **Repository:**
    [https://github.com/onchain-angels/onchain-angels-backend](https://github.com/onchain-angels/onchain-angels-backend) 🔗
- **Description:**  
    This repository contains the backend of the application, built with Django and Django REST Framework. It manages all server-side logic, including wallet and token handling, as well as integrations with external platforms such as Alchemy, Etherscan, CoinGecko, and OpenAI.
- **Tech Stack:**
    - Python
    - Django
    - Django REST Framework
    - PostgreSQL
- **Deployment:** Heroku

---

### 3. **Frontend** 🌐
- ** Repository:** [https://github.com/onchain-angels/onchain-angels-frontend](https://github.com/onchain-angels/onchain-angels-frontend) 🔗
- **Description:**  
    This repository hosts the front-end of the application, developed with modern frameworks (such as Next.js) and technologies, delivering a rich and responsive user interface.
- **Tech Stack:**
    - Next.js
    - Tailwind CSS
    - TypeScript
- **Deployment:** Vercel

---

### 4. **Nillion** 🔒
- **Repository:** [https://github.com/onchain-angels/nillion](https://github.com/onchain-angels/nillion) 🔗
- **Description:**  
    - A clone of [nillion-sv-wrappers](https://github.com/NillionNetwork/nillion-sv-wrappers).
    - Used for testing and creating schemas for the exchange of information between the Backend and the Agent.
- **Tech Stack:**
    - JavaScript
    - Node.js
    - nillion-sv-wrappers

---

### 5. **nillion-sv-wrappers-py** 🐍
- **Repository:** [https://github.com/onchain-angels/nillion-sv-wrappers-py](https://github.com/onchain-angels/nillion-sv-wrappers-py) 🔗
- **Description:**  
    This Python library implements wrappers to facilitate integration with the Nillion Secret Vault. Inspired by the [JS wrappers](https://github.com/NillionNetwork/nillion-sv-wrappers) version, it provides an abstraction layer for encryption operations, share distribution, and data unification.
- **Tech Stack:**
    - Python
    - nilql