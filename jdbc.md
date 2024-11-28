## 1. Creating a JDBC Session
You are creating a session using the create session method. The argument related to acknowledgment mode is ignored.  

**What can be inferred from the given information regarding the value of the first argument?**
- [ ] true
- [ ] false
- [ ] 0
- [ ] 1

<details>
<summary>Click to show the answer</summary>
**Answer:** true
</details>

---

## 2. Setting the Query Timeout Period
In your Java application, you need to set the query timeout period in seconds on prepared statements while querying using JDBC.  

**If the name of the connection is `con`, which of the following lines of code can be used to implement this?**
- [ ] `preparedstatement = con.prepareStatement(query); preparedstatement.setTimeout(seconds);`
- [ ] `preparedstatement = con.prepareStatement(query); preparedstatement.QueryTimeout = seconds;`
- [ ] `preparedstatement = con.prepareStatement(query); preparedstatement.QueryTimeout(seconds);`
- [ ] `preparedstatement = con.prepareStatement(query); preparedstatement.setQueryTimeout(seconds);`

<details>
<summary>Click to show the answer</summary>
**Answer:** `preparedstatement = con.prepareStatement(query); preparedstatement.setQueryTimeout(seconds);`
</details>

---

## 3. Close JDBC Connection
**Which method is used to close a JDBC connection?**
- [ ] closeConnection()
- [ ] close()
- [ ] disconnect()
- [ ] releaseConnection()

<details>
<summary>Click to show the answer</summary>
**Answer:** close()
</details>

---

## 4. Using DriverManagerDataSource for Development
You have received the instructions to use `DriverManagerDataSource` for development purposes in your Spring application. However, you feel that this could lead to serious issues and disagree with the decision.  

**Which of the following statements support the decision taken by you?**
- [ ] You will not be able to perform pooling
- [ ] Multiple requests for a connection will perform poorly
- [ ] DBCP will not be accessible while making connection requests in this manner
- [ ] Only Choice 1 and Choice 2
- [ ] All of these

<details>
<summary>Click to show the answer</summary>
**Answer:** All of these
</details>

---

## 5. Executing a PreparedStatement Object
You are executing a `PreparedStatement` object by calling the `executeQuery` method when working with JDBC. When doing so, you notice that the statement executed was a DDL statement.  

**What will `executeUpdate` return in the given situation?**
- [ ] 0
- [ ] 1
- [ ] null
- [ ] The last updated row

<details>
<summary>Click to show the answer</summary>
**Answer:** 0
</details>

---

## 6. Creating SQL Basic Statements
You want to create SQL basic statements in Java.  

**Which of the given statement types in JDBC will not allow you to execute queries with the database?**
- [ ] PreparedStatement
- [ ] CallableStatement
- [ ] QueryStatement
- [ ] Statement

<details>
<summary>Click to show the answer</summary>
**Answer:** QueryStatement
</details>

---

## 7. Retrieving the map object
What could most likely be the issue if an SQLException is thrown when retrieving the map object associated with the connection object?

**Answer Options:**
- [ ] The JDBC driver does not support this method
- [ ] The given parameter is not a java.util.Map object
- [ ] The method is called on a closed connection
- [ ] Both Choice 1 and 3
- [ ] Both Choice 2 and 3

<details>
<summary>Click to show the answer</summary>
**Answer:** Both Choice 1 and 3
</details>

---

## 8. Creating a ResultSetMetaData interface
Which method in the `ResultSetMetaData` interface is used to return the total number of columns in the ResultSet object?

**Answer Options:**
- [ ] `public int getColumnCount() throws SQLException`
- [ ] `public String getColumnName(int index) throws SQLException`
- [ ] `public String getColumnTypeName(int index) throws SQLException`
- [ ] `public String getTableName(int index) throws SQLException`

<details>
<summary>Click to show the answer</summary>
**Answer:** `public int getColumnCount() throws SQLException`
</details>

---

## 9. Type of ResultSet object
Which of the following is not a type of `ResultSet` object?

**Answer Options:**
- [ ] TYPE_FORWARD_ONLY
- [ ] CONCUR_WRITE_ONLY
- [ ] TYPE_SCROLL_INSENSITIVE
- [ ] TYPE_SCROLL_SENSITIVE

<details>
<summary>Click to show the answer</summary>
**Answer:** CONCUR_WRITE_ONLY
</details>

---

## 10. Exception error in JDBC
Which exception is thrown when there is an error in JDBC?

**Answer Options:**
- [ ] SQL Exception
- [ ] IO Exception
- [ ] FileNotFoundException
- [ ] ClassNotFoundException

<details>
<summary>Click to show the answer</summary>
**Answer:** SQL Exception
</details>

