## Lab 4: DELETE Request (Delete Data) using Postman

### Objective
Learn how to delete data using a **DELETE** request and understand how APIs handle resource removal.

---

### API Details
- **Method**: DELETE  
- **URL**: https://jsonplaceholder.typicode.com/posts/1  
- **Tool**: Postman

> Note: This is a public **mock API** used for learning. Data is not actually removed from the server.

---

### Step-by-Step Instructions

#### Step 1: Create a New Request
- Open **Postman**
- Click **New → HTTP Request**

---

#### Step 2: Select HTTP Method
- Change the method to **DELETE**

---

#### Step 3: Enter Request URL
https://jsonplaceholder.typicode.com/posts/1  


📌 This represents deleting the post with **ID = 1**

---

#### Step 4: Send the Request
- Click **Send**

> No request body is required for DELETE in this lab.

---

### Expected Response

#### Status Code
200 OK

(or sometimes `204 No Content` depending on API)

#### Response Body
```json
{}
```

**Key Concepts**

- DELETE → Used to remove a resource  
- Endpoint → API URL where the delete action happens  
- 200 OK / 204 No Content → Delete request processed successfully  
- No Body Required → DELETE usually does not need request body  

**Student Exercise**  

1. Change the post ID in the URL (example: /posts/5)  
2. Send the DELETE request  
3. Observe the status code  
4. Try sending the same request again and compare responses  