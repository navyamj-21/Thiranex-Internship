# Task 1 — Password Strength Analyzer

## What it does
- Checks password length, complexity, and common patterns
- Uses zxcvbn for smart strength estimation
- Shows estimated crack time
- Hashes passwords with bcrypt before storing
- Prevents reuse of old passwords using SQLite

## How to run
1. pip install bcrypt zxcvbn
2. python password_checker.py

## Concepts used
- Cryptographic hashing (bcrypt)
- Salting
- Password entropy
