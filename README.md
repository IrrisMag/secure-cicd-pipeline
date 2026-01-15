# Secure CI/CD Pipeline

This project demonstrates a beginner-friendly secure CI/CD pipeline using GitHub Actions.

## Features
- Python Flask demo application
- CI pipeline with GitHub Actions
- Static Application Security Testing (Bandit)
- Secret scanning with TruffleHog

## Why this project?
Security should be integrated early in the development lifecycle. This project shows how to implement basic DevSecOps practices.

## How it works
Every push triggers:
1. Dependency installation
2. Application test
3. SAST scan
4. Secret scanning


## Security Gates
The pipeline automatically fails if Bandit detects security issues in the code, enforcing secure coding practices.


Secret scanning is performed using TruffleHog to detect hardcoded credentials before they reach production.
