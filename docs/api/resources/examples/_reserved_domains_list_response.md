<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "reserved_domains": [
    {
      "acme_challenge_cname_target": null,
      "certificate": {
        "id": "cert_31an8TZzy9RLHEhvlV7ng53aerV",
        "uri": "https://api.ngrok.com/tls_certificates/cert_31an8TZzy9RLHEhvlV7ng53aerV"
      },
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": "2udamkamcl8pjmrff.2y3qcjkdmr9cidmox.local-ngrok-cname.com",
      "created_at": "2025-08-21T10:08:11Z",
      "domain": "myapp.mydomain.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31an8ZopZsacXXSn0mU9Qeh3DN7",
      "is_dev": false,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31an8ZopZsacXXSn0mU9Qeh3DN7"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": {
        "authority": "letsencrypt",
        "private_key_type": "ecdsa"
      },
      "certificate_management_status": {
        "provisioning_job": {
          "error_code": null,
          "msg": "Managed certificate provisioning in progress.",
          "retries_at": null,
          "started_at": "2025-08-21T10:08:12Z"
        },
        "renews_at": null
      },
      "cname_target": "4knqktdwka2umyjjc.2y3qcjkdmr9cidmox.local-ngrok-cname.com",
      "created_at": "2025-08-21T10:08:12Z",
      "description": "Device 0001 Dashboard",
      "domain": "manage-0002.app.example.com",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31an8gOTyJA8IRBSbtGkQczm3id",
      "is_dev": false,
      "metadata": "{\"service\": \"dashboard\"}",
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31an8gOTyJA8IRBSbtGkQczm3id"
    },
    {
      "acme_challenge_cname_target": null,
      "certificate": null,
      "certificate_management_policy": null,
      "certificate_management_status": null,
      "cname_target": null,
      "created_at": "2025-08-21T10:07:41Z",
      "description": "Your dev domain",
      "domain": "friendly-related-lynx.ngrok-free.dev",
      "error_redirect_url": null,
      "http_endpoint_configuration": null,
      "https_endpoint_configuration": null,
      "id": "rd_31an4mXJB8FYfcokrA2edyps3SY",
      "is_dev": true,
      "region": "",
      "uri": "https://api.ngrok.com/reserved_domains/rd_31an4mXJB8FYfcokrA2edyps3SY"
    }
  ],
  "uri": "https://api.ngrok.com/reserved_domains"
}
```
