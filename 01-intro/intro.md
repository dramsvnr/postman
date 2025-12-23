## 🔹 Introduction to APIs & Postman (10–15 mins)

### 📌 Topics Covered

### 1️⃣ What is an API?
An **API (Application Programming Interface)** acts as a **bridge** that allows two applications to communicate with each other.

**Real-world analogy:**
- A **restaurant menu** → lists available options  
- You (**client**) → place an order  
- Kitchen (**server**) → prepares the food  
- API → waiter that takes request & returns response  

---

### 2️⃣ REST API Basics
**REST (Representational State Transfer)** is a popular API design style that:
- Uses standard HTTP protocols  
- Works over URLs (endpoints)  
- Exchanges data mainly in **JSON** format  

Example:
```text
https://api.example.com/users  
```

### 3️⃣ HTTP Methods
| Method | Purpose     | Example Use Case     |
| ------ | ----------- | -------------------- |
| GET    | Read data   | Get user details     |
| POST   | Create data | Create a new user    |
| PUT    | Update data | Update existing user |
| DELETE | Remove data | Delete a user        |

---
### 4️⃣ Request vs Response  

- Request  
    - Sent from client to server  
    - Contains:  
        - Method (GET, POST, etc.)  
        - URL  
        - Headers  
        - Body (optional)   

- Response  
    - Sent from server to client  
    - Contains:  
        - Status code (200, 201, 400, 500)  
        - Headers  
        - Body (JSON data)  

---
### 5️⃣ What is Postman?  

Postman is an API client tool used to:  
- Test REST APIs
- Send HTTP requests
- Validate responses
- Automate API testing
- Share API collections with teams