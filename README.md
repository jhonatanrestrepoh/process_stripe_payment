# 🛠️ Payment Processor

A simple yet robust payment processing system built in Python. This project demonstrates how to handle online payments, send customer notifications, and maintain transaction logs. It integrates with Stripe for secure payment processing and offers multi-channel customer notifications via email and SMS.

---

## 🔍 Key Features

- **Payment Processing**: Securely processes payments using the Stripe API.
- **Customer Notifications**: Notifies customers via email or SMS after a successful transaction.
- **Transaction Logging**: Keeps a record of all payment transactions for audit purposes.
- **Environment Variable Support**: Uses `dotenv` to manage sensitive keys securely.

---

## 📂 Project Structure

- **PaymentProcessor Class**: Handles customer data validation, payment processing, and notifications.
- **Environment Variables**: Manages the Stripe API key via a `.env` file.
- **Logging**: Writes transaction details to a `transactions.log` file for easy tracking.

---

## 🚀 Technologies Used

- **Python**
- **Stripe API** (for payment processing)
- **dotenv** (for environment variable management)
- **smtplib & email.mime** (for email notifications)

---

## 📘 How to Use

1. **Clone the repository**.
2. **Create a `.env` file** and add your `STRIPE_API_KEY`.
3. **Run the script** to process sample transactions and send customer notifications.

---

This repository is a great starting point for those looking to understand payment systems, API integration, and customer communication workflows.
