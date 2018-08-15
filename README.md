# Direct Debit Debtor
NOTE: This is a proof of concept for demonstration purposes.

## Introduction
Service for tracking Direct Debit payment debtors.

## Application Overview
The application allows for a certificate reference, expiry date, and value amount of debt to be recorded. Every 21 days (SLA), a simple workflow will escalate the record for the user to manually send a reminder letter of the debt.

# Running
## Execution
```
java -jar target/ppc-debtor-app-0.0.1-SNAPSHOT.jar
```

## Homepage
```
http://localhost:8080/
```