# Linux Hardening Basics

Linux hardening refers to the process of reducing the attack surface of a system by applying security configurations and best practices.

The objective is to make the system more resistant to unauthorized access and exploitation.

## Principle of Least Privilege

Users and services should only have the permissions necessary to perform their tasks.

Examples:

* Avoid running services as root
* Restrict file permissions
* Use separate user accounts for services

## System Updates

Keeping software updated is critical to reduce exposure to known vulnerabilities.

Best practices:

* Regularly apply security patches
* Monitor security advisories
* Maintain updated packages

## Secure Authentication

Authentication mechanisms should be configured securely.

Recommendations:

* Enforce strong password policies
* Disable unused accounts
* Prefer key-based SSH authentication

## Service Management

Minimize the number of running services.

Steps:

* Disable unnecessary services
* Monitor open ports
* Restrict network exposure

## Logging and Monitoring

Logs are essential for detecting suspicious activity.

Important areas to monitor:

* Authentication logs
* System logs
* Network activity

Continuous monitoring improves incident detection and response capabilities.
