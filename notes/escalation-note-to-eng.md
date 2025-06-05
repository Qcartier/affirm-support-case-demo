### Internal Escalation - Webhook Error Case

*Issue Summary:*

Webhook payloads from merchant "Fable&Fig" are triggering 400 Bad Request errors. Root cause appears to be malformed JSON — missing event_type field.

*Merchant Impact:*  
Transactions failing to log in Affirm’s system, causing sync issues in their checkout flow.

*Suggested Fix:*

Coordinate with Merchant Dev Team to ensure event_type is properly structured.

*Reference:* [logs/webhook-error.json](../logs/webhook-error.json)
