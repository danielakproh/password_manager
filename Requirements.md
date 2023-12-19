# Password Manager Project Requirements

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Technologies](#technologies)
- [User Interface](#user-interface)
- [Security Considerations](#security-considerations)
- [Password Generation](#password-generation)
- [Testing](#testing)
- [Documentation](#documentation)
- [Version Control](#version-control)
- [Future Improvements](#future-improvements)

## Introduction

Provide a brief overview of the password manager project
This project is a desktop app that lets you generate and store passwords securely similar to what NordPass does but a lot less sophisticated :). It aims to eliminate the bad habit of using the same password over and over across many different websites which is not a safe practice.

## Features

- Generate passwords with different levels of complexity
- Securely store user information in a database (CRUD operations)
- Allow multiple account creation
- Have Sign up, Sign in, Forgot Password, Remember Password features
- Web version (nice-to-have)

## Technologies

- Language: Python
- Frontend Framework: PyQT
- Data Storage: SQLite

## User Interface

Describe the user interface requirements. This can include:

- GUI design
- Have a login welcome page
- Once logged in, we'll have a left-side panel with "All passwords", "Generate New Password", "About"
- Have a "copy" icon to automatically copy password
- Display all saved passwords as a list (later versions will be able to sort them)
- Dark theme button

## Security Considerations

Outline the security measures that will be implemented to ensure the safety of user data. This can include:

- Password encryption algorithm: XOR-based
- Secure data storage: Encryption, Authentification, Authorization, Data Backup/recovery

## Password Generation

Define the requirements for the password generation feature, including:
Users will be able to customize their passwords as far as:

- Length
- Number of special characters and digits
- Capitalization

## Testing

Test Driven Development

## Documentation

Coming soon.

## Version Control

This project will follows the Gitflow standard.

## Future Improvements

Coming soon.
