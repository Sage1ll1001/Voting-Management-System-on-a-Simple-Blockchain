# Voting-Management-System-on-a-Simple-Blockchain

🗳️ Voting Management System using a Simple Blockchain

A Python console-based blockchain application for secure voting.
This project is part of the **Blockchain Module Assignment** and demonstrates how blockchain concepts can be applied to record votes immutably.

## 📌 Project Overview

This is a **menu-driven Voting Management System** built using Python.
It uses a simple blockchain structure to securely store votes.
Each vote is stored inside a block that contains:

* Voter ID
* Candidate Name
* Timestamp
* Previous Block Hash
* Current Block Hash

This ensures **immutability**, **security**, and **tamper detection**.

### ✔️ Entities

* Voter

  * voter_id
  * name
  * has_voted (boolean to prevent double voting)

* Candidate

  * candidate_id
  * name

### ✔️ System Functionalities

| Feature          | Description                                   |
| ---------------- | --------------------------------------------- |
| Add Candidate    | Admin can add a new candidate (no duplicates) |
| Add Voter        | Admin can register voters                     |
| Cast Vote        | A registered voter can vote only once         |
| Print Blockchain | Shows all blocks with hashes                  |
| Validate Chain   | Confirms if the blockchain is untampered      |
| Exit             | Quit the program                              |

### ✔️ Blockchain Components

* Genesis Block
* Hash-based linking
* SHA-256 hashing
* Validation and tamper detection

## 🧠 How It Works

1. Admin registers voters and candidates.
2. Voter casts a vote.
3. A new block is created containing:

   * voter_id
   * candidate name
   * timestamp
   * previous block hash
4. The block is added to the chain.
5. Validation checks ensure data integrity.

## 🧪 Sample Output

* Adding candidates
* Adding voters
* Casting votes
* Blockchain printing
* Chain validation


## 🔒 Security Features

* Prevents duplicate voters
* Prevents duplicate candidates
* Prevents double voting
* SHA-256 hashing
* Immutable blockchain structure

## 📘 Learning Outcomes

By completing this project, you will understand:
✔ How blockchains store data
✔ Hashing and linking blocks
✔ Data immutability
✔ Basic menu-driven applications in Python
✔ Applying blockchain concepts to real-world scenarios


## 🧑‍💻 Author:- Sagar Singh
Blockchain Fundamentals – Voting System Project

