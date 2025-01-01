# Acme-s-DLP-Policy-Documentation
This document outlines the implementation of Acme’s Data Loss Prevention (DLP) policy using Microsoft Purview to protect sensitive financial, customer, and corporate information from unauthorized access, sharing, or exfiltration.

### Scope
The DLP policy applies to all sensitive information processed, stored, or transmitted across the following Acme systems and platforms:

- Exchange Email: Emails sent and received by employees, contractors, and partners.
- SharePoint Sites: Shared document libraries, collaboration sites, and sensitive information stored on SharePoint Online.
- OneDrive Accounts: Personal cloud storage accounts associated with individual employees and departments.
- Teams Chat and Channels: Instant messages, attachments, and conversations in Microsoft Teams, including group chats and channel discussions.
- Online Repositories: Cloud-based code repositories, document-sharing platforms, and other third-party integrations used in Acme’s operations.

### Key Features of the Policy
#### Sensitive Information Types:

- PCI DSS-related data (e.g., credit card numbers, CVVs).
- Personally Identifiable Information (e.g., SSNs, email addresses, passport numbers).
- Financial data (e.g., transaction details, account numbers).
- Corporate sensitive data (e.g., contracts, intellectual property).

#### Monitoring and Alerts:

- Automatic detection of sensitive data across all locations.
- Alerts sent to administrators for attempted unauthorized data sharing.
- Notifications to users when sensitive data-sharing attempts are blocked.

#### Actions and Enforcement:

- Automatically block sensitive data from being shared externally.
- Encrypt sensitive data in transit or at rest.
- Quarantine files that violate DLP rules for administrative review.

### Implementation Steps

