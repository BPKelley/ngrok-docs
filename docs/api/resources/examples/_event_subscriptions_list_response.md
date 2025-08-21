<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "event_subscriptions": [
    {
      "created_at": "2025-08-21T10:08:34Z",
      "description": "ip policy creations",
      "destinations": [
        {
          "id": "ed_31anBPlm7QbuQutpnlhLVVS9vIH",
          "uri": "https://api.ngrok.com/event_destinations/ed_31anBPlm7QbuQutpnlhLVVS9vIH"
        }
      ],
      "id": "esb_31anBPBNgBwCdcP0lOSNRRKCbU7",
      "metadata": "{\"environment\": \"staging\"}",
      "sources": [
        {
          "type": "ip_policy_created.v0",
          "uri": "https://api.ngrok.com/event_subscriptions/esb_31anBPBNgBwCdcP0lOSNRRKCbU7/sources/ip_policy_created.v0"
        }
      ],
      "uri": "https://api.ngrok.com/event_subscriptions/esb_31anBPBNgBwCdcP0lOSNRRKCbU7"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/event_subscriptions"
}
```
