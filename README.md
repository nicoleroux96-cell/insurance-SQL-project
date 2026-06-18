

# Insurance Underwriting Portfolio Analysis

## Project Overview

This project simulates an insurance underwriting portfolio using PostgreSQL and SQL.

The objective was to analyze broker performance, underwriting decisions, portfolio composition, premium distribution, and account concentration through a series of business-focused analytical queries.

---

### Database Structure

The project consists of four relational tables:

### Brokers
Contains information for 10 unique brokers.

### Applicants
Contains insured company (applicant) information including industry and province for 80 unique applicants (companies).

### Submissions
Contains insurance submissions and underwriting decisions. Each of the 80 unique applicants has at lease one submission, for a total of 150 submissions in this table.

### Policies
Contains all the submissions under the status 'Approved', for a total of 83 policies. Each policy (approved submission) has a written premium, and a start and end date.

---

## Table Relationships

Brokers → Submissions

Applicants → Submissions → Policies

---

## Analytical Queries

1. Portfolio Summary
2. Policy Premium Distribution
3. Portfolio Total Premium by Province
4. Top 10 Accounts (Companies) by Premium
5. Portfolio Composition by Industry
6. Bind (Approval) Rate by Industry
7. Broker Submission Volume
8. Broker Bind (Approval) Rate
9. Broker Decline Rate
10. Submission Status Analysis

---

## Tools Used

- Microsoft Excel (to generate table data)
- PostgreSQL
- VS Code
