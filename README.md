# ATM & Banking Relational Database Management System (RDBMS)

## Objective
Designed and implemented a comprehensive relational database schema for a miniature Automated Teller Machine (ATM) and banking network. This project ensures strict data integrity, financial transaction security, and properly normalized relationships between core banking entities.

## Technical Toolkit
- **Language:** SQL (Oracle / Management Studio)
- **Database Architecture:** Relational Database Design, Schema Normalization (1NF, 2NF, 3NF)
- **Modeling Tools:** Entity-Relationship Diagrams (ERD)

## Project Phases & Core Capabilities

### 1. Conceptual & Logical Design
- Formulated a detailed business scenario mapping the operations of bank branches, customers, multiple account types, secure cards, and ATM physical terminals.
- Developed a robust **Entity-Relationship Diagram (ERD)** to model entities, attributes, and cardinality constraints accurately.

### 2. Schema Implementation & Normalization
- Translated the ERD into a production-ready relational schema, applying normalization techniques to eliminate data redundancy.
- Created physical tables with optimal data types, enforcing strict **Primary Keys (PK)** and **Foreign Keys (FK)** to secure data references.

### 3. Transactional Integrity & Features
Designed the database structures to robustly handle and log complex banking operations, including:
- **User Authentication:** Secure tracking of Card Numbers linked with encrypted/hashed PIN codes.
- **Account Management:** Support for customers holding multiple account types simultaneously (e.g., Savings and Current accounts) with real-time balance tracking.
- **Financial Transaction Logging:** Structured schema to securely log and audit core operations:
  - **Deposits:** Updating balances and recording transaction metadata (Date, Amount, Account ID).
  - **Withdrawals:** Deducting requested amounts after verifying card and account validity.
  - **Fund Transfers:** Securing transactions between a sender and a receiver account, updating both balances seamlessly.

---

## Database Blueprint (ER Diagram)
Below is the visual blueprint of the database architecture showing the entities and relational constraints:

![ATM System ER Diagram](Untitled Diagram-Schema.drawio 22-ER Diagram.drawio.svg)
