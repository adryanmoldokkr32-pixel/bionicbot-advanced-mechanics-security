---
name: pii-data-masking
description: Protect Personally Identifiable Information (PII) through masking and encryption.
---

# Data Masking & PII Protection

This skill focuses on the 'Privacy' layer, ensuring sensitive user data is never exposed unnecessarily.

## Instructions

1. Identify all PII fields in the database (Emails, Names, Addresses).
2. Implement 'Data Masking' for logs and support dashboards (Ex. user@****.com).
3. Use 'Tokenization' to store sensitive data outside the main database.
4. Encrypt PII fields using unique, per-user keys (Envelope encryption).
5. Audit for 'Data Leakage' in error messages and API responses.

## Examples

- "Mask all email addresses in my application logs automatically."
- "Implement field-level encryption for user birthdates in PostgreSQL."