# otp-generator-gmail
A Python project that generates and sends One-Time Passwords (OTPs) to users via Gmail using the smtplib module for email verification and secure access workflows. Useful for authentication systems in web and desktop applications.
# 🔐 OTP Generator and Email Sender using Gmail (Python)

This Python project generates a One-Time Password (OTP) and sends it securely to a user’s Gmail address using the built-in `smtplib` library. It can be used for basic authentication flows such as login verification, signup verification, or password reset.

---

##  Features

- ✅ Generates a secure 6-digit OTP
- ✅ Sends OTP to any Gmail address using SMTP
- ✅ Simple and interactive CLI (Command Line Interface)
- ✅ Verifies user-entered OTP
- ✅ Includes basic input validation and security practices

---

## 📂 Project Structure

---

## How It Works

1. User provides a Gmail address.
2. A 6-digit OTP is generated using Python’s `random` module.
3. The OTP is sent via email using Gmail’s SMTP service.
4. The user enters the OTP they received.
5. The system verifies if it’s correct or expired.

---

##  Technologies Used

- **Python 3**
- `smtplib` – to send emails
- `email.message` – to construct the email body
- `random` – for OTP generation
- `getpass` *(optional)* – to securely input the sender's email password

  
