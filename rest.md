# REST API Design and Best Practices

## 1. Choosing Correct REST API Design Approach
You want to address the following use cases when implementing REST API calls:
1. Subsequent calls do not need to reference previous data.
2. If a call fails, there is no need to roll back changes made by earlier steps.

**Which of these REST API design approaches can you use to achieve this?**
- [ ] Batch APIs
- [ ] Composite APIs
- [ ] Either Choice 1 or 2
- [ ] Neither Choice 1 nor 2

<details>
<summary>Click to show the answer</summary>
**Answer:** Either Choice 1 or 2
</details>

---

## 2. API Consuming Best Practices
When consuming a REST API in Java, which of the following is **NOT** a common way to improve performance and scalability?  
- [ ] Caching results
- [ ] Using a load balancer
- [ ] Using a message queue
- [ ] Calling the API synchronously for each request

<details>
<summary>Click to show the answer</summary>
**Answer:** Calling the API synchronously for each request
</details>

---

## 3. Imposing Layered System Constraints in REST
The requirement for a layered system is considered as a fundamental principle in REST.  
**Which of these architectural benefits are attained by imposing layered system constraints?**
- [ ] Placing a bound on overall system complexity
- [ ] Promotion of substrate independence
- [ ] Interface uniformity
- [ ] Only Choice 1 and Choice 2
- [ ] Only Choice 2 and Choice 3

<details>
<summary>Click to show the answer</summary>
**Answer:** Only Choice 1 and Choice 2
</details>

---

## 4. Weather Application Security
You are developing a RESTful API for a weather application. The API has an endpoint `/weather/{city}` that retrieves the weather information for a specific city. However, the API response contains sensitive information like the API key and internal server details.  

**How can you address this security concern?**
- [ ] Implement authentication and authorization mechanisms to restrict access to the API.
- [ ] Use HTTPS (HTTP Secure) to encrypt the communication between the client and server.
- [ ] Apply input validation to prevent any malicious input or SQL injection attacks.
- [ ] Implement output filtering and data masking to remove sensitive information from the API response.

<details>
<summary>Click to show the answer</summary>
**Answer:** Implement output filtering and data masking to remove sensitive information from the API response
</details>

---

## 5. Banking Application Error
You are developing a RESTful API for a banking application. The API has an endpoint `/accounts/{accountId}/balance` that retrieves the account balance for a given account ID. However, when you send a GET request to `/accounts/12345/balance`, you receive a response with the status code 404 (Not Found).  

**What could be the possible cause of this issue, and how can you fix it?**
- [ ] The account with ID 12345 does not exist in the system. Verify that the account ID is valid and corresponds to an existing account.
- [ ] The API endpoint is incorrect. You should use `/accounts/{accountId}` instead of `/accounts/{accountId}/balance`.
- [ ] The request is missing the necessary authentication token. Include the authentication token in the request headers to access account-specific information.
- [ ] The server is experiencing an internal error. Check the server logs for any error messages and address the underlying issue.

<details>
<summary>Click to show the answer</summary>
**Answer:** The account with ID 12345 does not exist in the system. Verify that the account ID is valid and corresponds to an existing account.
</details>

---

## 6. Circuit Breaker Pattern
You are using the circuit breaker pattern in your REST API server to handle application failures and failure operations. To achieve better results, you decide to combine the retry pattern and the circuit breaker pattern.  

**Which of these attacks would your application be vulnerable to in the given scenario?**
- [ ] Denial of Service (DoS) attack
- [ ] Pagination attack
- [ ] It leads to incorrect caching header
- [ ] All Choices 1, 2 and 3

<details>
<summary>Click to show the answer</summary>
**Answer:** Denial of Service (DoS) attack
</details>

---

## 7. Imposing Constraints on a RESTful API
In the context of the REST architecture, which of the following statements accurately describe the benefits of imposing constraints on a RESTful API?  
1. Improved scalability and performance.  
2. Enhanced reliability and fault tolerance.  
3. Increased interoperability and ease of integration.  
4. Simplified client-server communication.  
5. Streamlined caching and caching efficiency.  

**Answer Options**
- [ ] 2, 3, 4 and 5
- [ ] 2, 3 and 4
- [ ] 1, 3 and 5
- [ ] 1, 2, 3 and 5

<details>
<summary>Click to show the answer</summary>
**Answer:** 1, 2, 3 and 5
</details>

---


## 8. Analyzing Constraints Applied to the REST Architectural System
You are analyzing the constraints applied to the REST Architectural system.  

**Which of these constraints would you credit with the promotion of independent evolvability?**
- [ ] Uniform Interface
- [ ] Layered System
- [ ] Code-On-Demand
- [ ] Client-server interaction constraint

<details>
<summary>Click to show the answer</summary>
**Answer:** Layered System
</details>

---

## 9. Making a POST Request Cacheable
You have a requirement wherein you have to make a POST request cacheable.  

**What will you do to achieve the objective?**
- [ ] Add an Expires header to the response
- [ ] Add a Cache-Control header to the response
- [ ] POST requests are by default cacheable
- [ ] Either Choice 1 or Choice 2

<details>
<summary>Click to show the answer</summary>
**Answer:** Either Choice 1 or Choice 2
</details>

---

## 10. @Transactional Annotation on an Interface
In which of the given cases would you expect the `@Transactional` annotation applied on an interface to work as expected?  
1. The interface is declared as abstract.  
2. You are using interface-based proxies.  

**Answer Options**
- [ ] Only 1
- [ ] Only 2
- [ ] Both 1, 2
- [ ] None of these

<details>
<summary>Click to show the answer</summary>
**Answer:** Only 2
</details>

---
