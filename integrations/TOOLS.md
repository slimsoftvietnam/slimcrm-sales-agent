# Integration Registry Template

Configure connections in the private runtime, not in this public repository. Do not store access tokens, email addresses, spreadsheet URLs, personal phone numbers, or customer data here.

| Integration | Runtime status | Required behavior |
|---|---|---|
| Email | Configure per operator | Verify sending identity, recipient, and send capability before use; record actual send result. |
| Messaging | Configure per operator | Verify exact profile/chat and channel capability. State clearly if replies cannot be monitored. |
| Google Sheets or CRM | Configure per operator | Use the authorized pipeline as the working record; do not claim synchronization unless tested. |
| Public web research | Use only accessible public sources | Record source URL and check date; do not bypass login or privacy boundaries. |

If a connection is missing or cannot be verified, do not act through it.
