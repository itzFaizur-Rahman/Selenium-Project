# Selenium Cucumber - Guest Checkout Automation

Automated end-to-end test suite for the [AskOmDch demo store](https://askomdch.com/store), built using **Selenium WebDriver**, **Cucumber (BDD)**, and **Java**.

## 📌 Overview

This project automates the **guest checkout flow** on a WooCommerce-based demo store.

The automation covers the following workflow:

1. Open the store as a guest user
2. Select the **Blue Shoes** product
3. Add the product to the cart
4. Navigate to the Checkout page
5. Enter billing details
6. Handle country and state dropdowns
7. Place the order
8. Verify the order confirmation message

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Java** | Programming language |
| **Selenium WebDriver** | Browser automation |
| **Cucumber** | BDD and feature file implementation |
| **JUnit / TestNG** | Test execution |
| **Maven** | Dependency and build management |
| **ChromeDriver** | Chrome browser automation |
| **Gherkin** | Writing BDD scenarios |

---

## 📂 Project Structure

```text
SeleniumProject2/
│
├── src/
│   ├── main/
│   │   └── java/
│   │       └── ...
│   │
│   └── test/
│       ├── java/
│       │   └── SeleniumProject2/
│       │       ├── stepdefs/
│       │       │   └── MyStepdefs.java
│       │       │
│       │       └── runners/
│       │           └── TestRunner.java
│       │
│       └── resources/
│           └── features/
│               └── checkout.feature
│
├── pom.xml
└── README.md
