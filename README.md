
# Fastify API for Transaction Management

## Tech Stack

<div style="display: flex;justify-content: space-between;padding-left: 60px;padding-right: 60px;">
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/typescript/typescript-original.svg" height="50" alt="typescript logo"/>          
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/fastify/fastify-plain.svg" height="50" alt="fastify logo" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sqlite/sqlite-plain.svg" height="50" alt="sqlite logo"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/knexjs/knexjs-original.svg" height="50" alt="knex logo"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vitest/vitest-original.svg" height="50" alt="vitest logo"/>
</div>


## Description: 

The Fastify API project aims to provide a POC of a platform for managing transactions. This API allows users to perform various actions related to their account transactions seamlessly. Here's an overview of the project features based on the specified requirements:

### Functional Requirements:

**Transaction Creation:**
   - Users can create new transactions, specifying whether it's a credit or debit transaction.

**Account Summary:**
   - Users have the capability to obtain a summary of their account, which includes details such as total balance and recent transaction history.

**Transaction Listing:**
   - The API enables users to list all transactions that have occurred in their account.

**Single Transaction Viewing:**
   - Users can view detailed information about a single transaction.

### Business Rules:

**Transaction Types:**
   - Transactions can be either credit or debit, affecting the account balance accordingly.

**User Identification:**
   - The API includes mechanisms to identify users between requests, ensuring security and personalized experiences.

**User Transaction Visibility:**
   - Users are restricted to viewing only the transactions they created, maintaining privacy and data integrity.
