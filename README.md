# 🔐 Air-Gapped Password Generator Pro

A professional, privacy-first password generation toolkit that runs entirely in your browser.

No servers. No tracking. No accounts. No analytics.

Everything happens locally on your device using the browser's cryptographically secure random number generator.

---

## Why?

Most online password generators require you to trust a remote website.

This project removes that trust requirement.

The application is designed to work completely offline, making it suitable for:

* Personal password generation
* Enterprise environments
* Air-gapped systems
* Security professionals
* Privacy-conscious users
* Penetration testing labs
* Incident response environments

Simply download the HTML file and open it in any modern browser.

No installation required.

---

# Features

## 🔑 Password Generator

Generate highly secure passwords with configurable options:

* Adjustable length (8–128 characters)
* Uppercase letters
* Lowercase letters
* Numbers
* Symbols
* Avoid ambiguous characters (0 O l I 1 etc.)
* Force first character to be a letter
* Prevent repeated consecutive characters
* Include custom characters
* Exclude unwanted characters

---

## 🧠 Passphrase Generator

Generate memorable but secure passphrases.

Options include:

* 3–8 word phrases
* Multiple separator styles
* Optional capitalization
* Optional random number
* Optional random symbol

Ideal for password managers and master passwords.

---

## 🔢 Secure PIN Generator

Generate secure numeric PIN codes.

Supports:

* 4-digit
* 6-digit
* 8-digit

Optional protection against:

* Sequential numbers
* Repeated patterns
* Weak PIN combinations

---

## 🔍 Password Analyzer

Evaluate existing passwords without sending them anywhere.

Displays:

* Entropy calculation
* Password strength
* Estimated cracking time
* Character composition
* Unique character count
* Security warnings
* Improvement suggestions

Everything is analyzed locally.

---

## 📑 Bulk Password Generator

Generate multiple passwords instantly.

Perfect for:

* IT administrators
* Lab environments
* Temporary credentials
* User onboarding
* Password rotations

---

## 📜 Session History

Keeps generated passwords only during the current browser session.

The history:

* Never touches disk
* Is never stored permanently
* Disappears when the page is refreshed or closed

---

# Security

Security is the primary design goal.

## Cryptographically Secure Random Numbers

Passwords are generated using the browser's **Web Crypto API (`crypto.getRandomValues()`)**, which provides a cryptographically secure pseudorandom number generator (CSPRNG).

No use of:

* `Math.random()`
* Predictable seeds
* Weak random generators

---

## Completely Offline

The application works without an internet connection.

Once downloaded:

* Disconnect your network
* Open the HTML file
* Generate passwords safely

No server is ever involved.

---

## No Data Collection

This application:

* Does not collect data
* Does not transmit passwords
* Does not log activity
* Does not use analytics
* Does not fingerprint users
* Does not require accounts

---

## No Storage

Generated passwords are **not** stored in:

* Local Storage
* Session Storage
* Cookies
* IndexedDB

Only temporary in-memory session history exists, which is automatically cleared when the page closes or refreshes.

---

## Content Security Policy

The application includes a restrictive Content Security Policy (CSP) to reduce attack surface.

The policy blocks:

* External websites
* Remote JavaScript
* External CSS
* Remote images
* Third-party resources

Only the code contained within the HTML file is permitted to execute.

---

## Air-Gapped Ready

Designed to be used on isolated systems.

Suitable for:

* Secure environments
* Classified networks
* Industrial systems
* Offline password generation
* Security operations

---

# Privacy

Your passwords never leave your computer.

The application performs **100% of its work locally** inside your browser.

Nothing is uploaded.

Nothing is shared.

Nothing is tracked.

---

# Requirements

Any modern browser supporting:

* Web Crypto API
* JavaScript
* HTML5

Examples:

* Chrome
* Edge
* Firefox
* Safari

---

# Installation

No installation required.

1. Download `index.html`
2. Disconnect from the internet (optional but recommended)
3. Open the file in your browser
4. Start generating secure passwords

---

# Project Highlights

* 🔒 Cryptographically secure random generation
* 🌐 Fully offline capable
* 💾 Zero persistent storage
* 🛡️ Privacy first
* 🔑 Password generator
* 🧠 Passphrase generator
* 🔢 PIN generator
* 🔍 Password analyzer
* 📑 Bulk generation
* 📜 Temporary in-memory history
* ⚡ Single HTML file
* 🚀 No dependencies
* 📱 Responsive interface

---

# Security Notice

This application is designed to maximize privacy by performing all operations locally. While every effort has been made to follow secure development practices, users should independently review the source code before using it in high-security or production environments. As with any security software, trust should be based on transparency and code review.

---

# License

Feel free to fork, improve, and contribute.

If this project helps you, consider giving it a ⭐ on GitHub.
