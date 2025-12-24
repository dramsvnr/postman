## Lab 1: First API Request using Postman

### Objective
Send a GET request and understand request-response flow.

### Steps
1. Open Postman and create a new HTTP request
2. Select method as GET
3. Use URL: https://postman-echo.com/get
4. Add query parameters:
   - name=student
   - course=postman
5. Click Send

### Expected Result
- Status Code: 200 OK
- JSON response showing query parameters in `args`  

![firstlab](../assets/images/03-firstlab/01.png)  

This confirms Postman is working correctly.
