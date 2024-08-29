# Personal Data

# Overview of PII, Non-PII, Personal Data, Logging, and Bcrypt

## 1. What Is PII, Non-PII, and Personal Data?
- **PII (Personally Identifiable Information)**: Information that can identify an individual, such as names, addresses, and social security numbers. It requires protection due to privacy concerns.
- **Non-PII**: Data that cannot identify an individual, such as aggregate statistics or demographic information. It is generally less sensitive.
- **Personal Data**: A broader term that includes any data related to an identified or identifiable individual, encompassing both PII and other related information.

## 2. Logging Documentation
Logging documentation provides guidelines on how to implement logging in software applications. It typically includes:
- Best practices for logging events and errors.
- Recommendations on what information to log.
- Instructions on managing log files and ensuring they are secure.

## 3. Bcrypt Package
The bcrypt package is a library used for securely hashing passwords. Key features include:
- Implementation of the bcrypt hashing algorithm, which is designed to be slow to resist brute-force attacks.
- It helps in storing passwords in a hashed format, enhancing security by preventing exposure of plain text passwords.

## 4. Logging to Files, Setting Levels, and Formatting
- **Logging to Files**: Writing log messages to files for later review, which aids in tracking application behavior and troubleshooting.
- **Setting Levels**: Different severity levels (DEBUG, INFO, WARNING, ERROR, CRITICAL) help categorize log messages, allowing developers to filter and focus on relevant logs.
- **Formatting**: Structuring log messages for clarity and readability, which can include timestamps, log levels, and message content to facilitate easier analysis.
