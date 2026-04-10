# Default Credentials Exposure - Pentest Lab

## Objective
This lab demonstrates how weak authentication practices can lead to unauthorized access.

## Scope
- Single web application target
- Black-box testing approach

## Key Finding
- Default credentials were found exposed in the application source code
- These credentials allowed unauthorized login access

## Impact
- Full unauthorized access to the application
- Security misconfiguration due to unchanged default credentials

## Methodology Summary
- Directory enumeration was performed
- Sensitive endpoint discovered via robots.txt
- Login page analyzed and source code inspected
- Default credentials identified and used for access

## Tools Used
- Gobuster
- Web browser developer tools

## Note
This assessment was performed in a controlled lab environment for educational purposes.
