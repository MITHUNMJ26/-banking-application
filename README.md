Banking Application (Spring Boot + JPA + MySQL)

A simple **Banking REST API** built with **Spring Boot, Spring Data JPA (Hibernate), and MySQL**.  
This project demonstrates creating REST APIs for a basic banking system with CRUD operations.

 * Features include
- Create a new bank account  
- Fetch account details by ID  
- Deposit money into an account  
- Withdraw money from an account
  
* Technicalities used
- Java 
- **Spring Boot 3**
- **Spring Data JPA (Hibernate)**
- **MySQL**
- **Maven**
- **Lombok**

API Endpoints
1. Create Account
POST /api/accounts
<img width="1714" height="849" alt="Post account" src="https://github.com/user-attachments/assets/504e94c8-9efb-4dd9-bb4a-d9682eb73a3e" />
2. Get Account by ID
GET /api/accounts/{id}
<img width="1729" height="883" alt="get account" src="https://github.com/user-attachments/assets/702d87c6-c293-4be1-a088-08904d6bc1b7" />
3. Deposit Money
PUT /api/accounts/{id}/deposit
<img width="1701" height="844" alt="deposite" src="https://github.com/user-attachments/assets/565741a5-cbb8-448a-8be0-fd8dc2e21c6b" />
4. Withdraw Money
PUT /api/accounts/{id}/withdraw
<img width="1717" height="892" alt="withdraw" src="https://github.com/user-attachments/assets/2ce6e74f-c615-450a-9623-da1c4da35582" />

