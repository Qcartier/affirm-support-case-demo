**Internal Note (Tier 2 Escalation)**

- Merchant: FitFuel (Shopify)
- Time of error: May 30th, 11:42 AM EST
- Logs indicate: Expired API key (`401 Unauthorized`) and failed webhook delivery
- Shopify store settings confirmed misconfigured webhook endpoint

✅ Solution:
- Reissued new API key and instructed merchant to update settings
- Reconfigured webhook with correct URL
- Tested and verified endpoint is now receiving Affirm order events

Ticket to be closed after merchant confirmation
