# 🔐 API Security Risk Analysis – Task 03

---

## 👩‍💻 Intern Details

* **Name:** J. Sahithi
* **Role:** Cyber Security Intern
* **Organization:** Future Interns

---

## 📌 Project Overview

This project focuses on analyzing the security risks of a public API. APIs are widely used in modern applications such as mobile apps, SaaS platforms, and web services. However, insecure APIs can expose sensitive data and allow unauthorized access.

The goal of this project is to identify common API vulnerabilities and provide appropriate security recommendations.

---

## 🌐 API Tested

* **API Name:** JSONPlaceholder
* **Base URL:** https://jsonplaceholder.typicode.com

---

## 🎯 Objectives

* Analyze API endpoints using Postman
* Identify security vulnerabilities
* Evaluate authentication and authorization
* Assess data exposure
* Suggest remediation strategies

---

## 🛠️ Tools Used

* **Postman** – API testing
* **Web Browser** – API review
* **Screenshot Tool** – evidence collection

---

## 🔍 Methodology

* Selected a public API for testing
* Sent GET requests using Postman
* Tested endpoints like:

  * `/users`
  * `/users/1`
  * `/posts`
  * `/comments`
* Analyzed responses for:

  * authentication
  * authorization
  * data exposure
  * security headers

---

## ⚠️ Identified Risks

### 🟥 No Authentication

* API accessible without login
* Anyone can access data

### 🟥 Broken Authorization

* Users can access other users' data
* No access control

### 🟧 Excessive Data Exposure

* Sensitive details like email, address exposed

### 🟧 No Rate Limiting

* Unlimited requests allowed

### 🟨 Missing Security Headers

* No protection against common web attacks

---

## 📊 Risk Summary

| Risk                     | Severity  |
| ------------------------ | --------- |
| No Authentication        | High 🔴   |
| Broken Authorization     | High 🔴   |
| Excessive Data Exposure  | Medium 🟠 |
| No Rate Limiting         | Medium 🟠 |
| Missing Security Headers | Low 🟡    |

---

## 🛠️ Recommendations

* Implement authentication (JWT/API keys)
* Enforce authorization controls
* Limit data exposure
* Apply rate limiting
* Add security headers

---

## 📸 Evidence

Screenshots of API testing using Postman are included in the repository.

---

## 📁 Repository Structure

```
📂 API-Security-Analysis
 ┣ 📄 Report.docx
 ┣ 📂 Screenshots
 ┃ ┣ users.png
 ┃ ┣ single-user.png
 ┃ ┣ posts.png
 ┃ ┗ comments.png
 ┗ 📄 README.md
```

---

## ✅ Conclusion

This project highlights common API security risks such as lack of authentication, broken authorization, and excessive data exposure. These vulnerabilities can lead to serious issues in real-world applications if not properly addressed.

---

## ⭐ Final Note

This project demonstrates practical understanding of API security and aligns with real-world SaaS security analysis practices.
