
# Fastify API for Transaction Management

## Tech Stack

![TypeScript Badge](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=fff&style=flat-square)
![Fastify Badge](https://img.shields.io/badge/Fastify-000?logo=fastify&logoColor=fff&style=flat-square)
![SQLite Badge](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=fff&style=flat-square)
![Knex.js Badge](https://img.shields.io/badge/Knex.js-D26B38?logo=knexdotjs&logoColor=fff&style=flat-square)
![Vitest Badge](https://img.shields.io/badge/Vitest-6E9F18?logo=vitest&logoColor=fff&style=flat-square)

## Description

The Fastify API project aims to provide a POC of a platform for managing transactions. This API allows users to perform various actions related to their account transactions seamlessly. Here's an overview of the project features based on the specified requirements:

### Functional Requirements

**Transaction Creation:**

- Users can create new transactions, specifying whether it's a credit or debit transaction.

**Account Summary:**

- Users have the capability to obtain a summary of their account, which includes details such as total balance and recent transaction history.

**Transaction Listing:**

- The API enables users to list all transactions that have occurred in their account.

**Single Transaction Viewing:**

- Users can view detailed information about a single transaction.

### Business Rules

**Transaction Types:**

- Transactions can be either credit or debit, affecting the account balance accordingly.

**User Identification:**

- The API includes mechanisms to identify users between requests, ensuring security and personalized experiences.

**User Transaction Visibility:**

- Users are restricted to viewing only the transactions they created, maintaining privacy and data integrity.
