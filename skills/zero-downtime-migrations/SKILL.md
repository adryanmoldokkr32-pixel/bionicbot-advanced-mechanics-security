---
name: zero-downtime-migrations
description: Execute complex database schema changes without taking the application offline.
---

# Zero-Downtime Database Migrations

This skill focuses on the 'Expand-Contract' pattern for database changes, ensuring users never see a 503 Maintenance page.

## Instructions

1. Step 1: Add new columns/tables without removing old ones (Backward Compatible).
2. Step 2: Update code to write to BOTH old and new structures.
3. Step 3: Run a background job to migrate existing data.
4. Step 4: Update code to read/write ONLY from the new structure.
5. Step 5: Remove the old columns/tables (Contract phase).

## Examples

- "Rename a column in a production database with 1TB of data without downtime."
- "Split a 'users' table into 'users' and 'profiles' while keeping the site live."