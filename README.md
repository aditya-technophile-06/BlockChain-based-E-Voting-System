# 🗳️ Blockchain-based E-Voting System (Demonstration)

![evote](https://github.com/user-attachments/assets/21019fa8-8453-4234-a9a1-a8c36370a4a3)

> **🏆 This project won 1st place in the National Level Hackathon Infothon 3.0 for the Social Innovation category.**

---

## 🎯 Project Overview

The **Blockchain-based E-Voting System** is a demonstration that showcases a secure, decentralized voting process built using Django, PostgreSQL, SHA-256 encryption, and Merkle Trees. It simulates key blockchain concepts like **immutability**, **tamper-proofing**, and **decentralization**, making it ideal for secure and transparent elections.

This project is designed to tackle issues in traditional voting systems, such as fraud, tampering, and centralization. It ensures:
- **🔒 Security**: Using SHA-256 encryption for secure data transmission and storage.
- **📊 Transparency**: Real-time vote counting and tamper-proof storage using Merkle Trees.
- **🛡️ Immutability**: Once votes are cast, they cannot be altered, ensuring integrity.
  
---

## 💡 Why This Project?

Traditional voting systems are vulnerable to fraud, manipulation, and centralization issues. By simulating decentralized voting using blockchain concepts like **SHA-256 encryption** and **Merkle Trees**, this project ensures a **tamper-proof** and **transparent** voting process. This demonstration shows how blockchain can revolutionize elections, providing transparency and enhancing security.

---

## ✨ Key Features

| Feature | Description |
| --- | --- |
| 🔑 **OTP Authentication** | Voter authentication via OTP-based email verification to ensure secure access. |
| 🔐 **SHA-256 Encryption** | Every vote is encrypted with SHA-256 for security and tamper-proof storage. |
| 🌳 **Merkle Trees** | Provides data integrity and ensures votes cannot be tampered with after submission. |
| 📊 **Real-time Vote Counting** | Votes are instantly counted and displayed for full transparency. |
| 💻 **Decentralized Concept** | Simulates decentralization by using Merkle Trees for vote integrity and transparency. |

---


## 📜 Technology Stack

- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript
- **Database**: PostgreSQL (for deployment), SQLite (for local testing)
- **Encryption**: SHA-256 for secure vote transmission
- **Data Integrity**: Merkle Trees for tamper-proof and immutable vote storage
- **Deployment**: Heroku for easy deployment

---

## 🗂️ Project Structure

    ├── static/                     # Static files (CSS, JavaScript, Images)
    │   ├── css/
    │   ├── js/
    ├── templates/                  # HTML templates for frontend
    │   ├── index.html
    │   ├── vote.html
    ├── voting_app/
    │   ├── models.py               # Database models for storing vote and user data
    │   ├── views.py                # Backend logic for vote authentication and processing
    │   ├── urls.py                 # URL routing for the application
    ├── db.sqlite3                  # Local database for testing (use PostgreSQL in production)
    ├── manage.py                   # Django management script
    ├── requirements.txt            # Project dependencies
    └── README.md                   # Project README file

---

## ⚙️ How to Run the Project

- To run the Blockchain-based E-Voting System locally:

  Step 1: Clone the repository
  
  ```bash
        git clone https://github.com/your-username/blockchain-e-voting-system.git
        cd blockchain-e-voting-system

  ```

  Step 2: Install the necessary dependencies

  ```bash
        pip install -r requirements.txt
  ```

  Step 3: Migrate the database

  ```bash
        python manage.py migrate

  ```
  
  Step 4: Run the Django development server

  ```bash
        python manage.py runserver

  ```
  Step 5: Access the application

  Open your browser and navigate to http://127.0.0.1:8000/ to start the voting process.

## 🔑 Security Features

- OTP Authentication: Ensures secure access for voters via email verification.
- SHA-256 Encryption: Encrypts every vote for tamper-proof submission and storage.
- Merkle Tree Structure: Ensures vote integrity and prevents any modifications once votes are cast.

## 🔍 How It Works

- Voter Registration: Voters register using their email and receive an OTP for secure authentication.
- Casting a Vote: Once authenticated, the voter casts their vote, which is encrypted using SHA-256.
- Merkle Tree Validation: Each vote is added to a Merkle Tree, ensuring that it cannot be altered or tampered with.
- Real-Time Vote Counting: Votes are counted in real-time and results are instantly displayed.

## 📈 Future Enhancements

- Blockchain Integration: Fully integrate with a blockchain network to make the system entirely decentralized.
- Voter Anonymity: Implement zero-knowledge proofs to enhance voter privacy while ensuring transparency.
- Multiple Elections: Add support for managing multiple elections simultaneously.
- Mobile Optimization: Develop a mobile-friendly version for easier access.

## 📽️ Project Demo Video

🎥 Watch the Demo: Click here to watch a full demonstration of how the Blockchain-based E-Voting System works.
