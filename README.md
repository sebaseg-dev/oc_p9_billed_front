# OpenClassrooms – Project 9 Billed

## 📌 Description

Source code of **Project 9 – Billed**, completed as part of the **OpenClassrooms JavaScript React Developer path**.

This project focuses on **debugging and testing a SaaS HR application**.
The main objectives were to:

* **Debug** parts of the front-end using the **Chrome Debugger**
* Write **unit tests** in JavaScript to validate components
* Implement **integration tests** to ensure proper interaction between features
* Draft a **manual end-to-end test plan** to verify the full employee workflow

Both the **backend** and **frontend** were provided as starter repositories, and the work consisted of **fixing existing bugs** and **completing missing test coverage**.

⚠️ **Educational project**: This repository was created for learning purposes during my training. It is **not intended for production use**.

---

## 🎯 Learning Objectives

* Write **integration tests** in JavaScript
* Debug a web application with the **Chrome Debugger**
* Write **unit tests** in JavaScript
* Draft a **manual end-to-end test plan**

---

## 🏗 Project Structure & Setup

### Project architecture

This project is the **frontend** connected to a **backend API** which must also be run locally.

Backend repository: [Billed-app-FR-Back](https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-back)

Clone the backend first:

```bash
git clone https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-Back.git
```

Then clone the frontend (this repository):

```bash
git clone https://github.com/sedomu/oc_p9_Billed-app-FR-Front.git
```

---

### Running the application locally

#### Step 1 – Start the backend

Follow the instructions in the [**backend README**](https://github.com/OpenClassrooms-Student-Center/Billed-app-FR-Back/blob/main/README.md).

#### Step 2 – Start the frontend

```bash
npm install
npm install -g live-server
live-server
```

Open the application in your browser at: `http://127.0.0.1:8080/`

---

### User accounts

* **Administrator:**

  ```
  username: admin@test.tld
  password: admin
  ```

* **Employee:**

  ```
  username: employee@test.tld
  password: employee
  ```

---

## ✅ Test Results & Coverage

* **CI** automatically runs on every PR to main via [GitHub Actions](https://github.com/sedomu/oc_p9_Billed-app-FR-Front/actions/workflows/node.js.yml) (all tests ✅)
* **Jest reports** published automatically to [GitHub Pages](https://sedomu.github.io/oc_p9_Billed-app-FR-Front/) (coverage > 80% ✅)
* Manual **end-to-end test plan** ensures functionality for the alpha version

---

### Running tests locally

Run all tests with Jest:

```bash
npm run test
```

Run a single test file:

```bash
npm i -g jest-cli
jest src/__tests__/your_test_file.js
```

View test coverage report:

```
http://127.0.0.1:8080/coverage/lcov-report/
```

---

## 🛠 Tech stack

* JavaScript (Vanilla)
* Jest for unit & integration testing
* Live Server for local development
* Chrome Debugger for debugging
* GitHub Actions for CI/CD

---

## ⚠️ Disclaimer

This is a **training project** created as part of the OpenClassrooms curriculum.
It is not optimised for production use. Some implementations may have been simplified to focus on learning objectives.