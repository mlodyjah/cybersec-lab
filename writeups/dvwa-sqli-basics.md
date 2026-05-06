# DVWA SQL Injection Basics

## Goal
Understand basic SQL Injection vulnerabilities in a controlled environment.

## Environment
- DVWA
- Docker
- Burp Suite

## Tested payloads
- 1' OR '1'='1
- 1' --
- 1'#

## Observations
- application returned multiple users
- input was not sanitized
- SQL query logic could be modified

## Skills learned
- HTTP request manipulation
- SQL Injection basics
- Burp Repeater usage