<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "next_page_uri": null,
  "tls_edges": [
    {
      "backend": null,
      "created_at": "2025-08-21T10:08:39Z",
      "description": "acme tls edge",
      "hostports": [
        "example.com:443"
      ],
      "id": "edgtls_31anBzX69d0Z4sUox8IEsFelQtd",
      "ip_restriction": null,
      "metadata": "{\"environment\": \"staging\"}",
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31anBzX69d0Z4sUox8IEsFelQtd"
    },
    {
      "backend": {
        "backend": {
          "id": "bkdhr_31anATMLkXyFIAFjghhYKbTx7s6",
          "uri": "https://api.ngrok.com/backends/http_response/bkdhr_31anATMLkXyFIAFjghhYKbTx7s6"
        },
        "enabled": true
      },
      "created_at": "2025-08-21T10:08:27Z",
      "description": "acme tls edge",
      "hostports": [
        "endpoint-example2.com:443"
      ],
      "id": "edgtls_31anAYXHrPDdy5LoOdPGWKEHfhY",
      "ip_restriction": null,
      "mutual_tls": null,
      "policy": null,
      "tls_termination": null,
      "traffic_policy": null,
      "uri": "https://api.ngrok.com/edges/tls/edgtls_31anAYXHrPDdy5LoOdPGWKEHfhY"
    }
  ],
  "uri": "https://api.ngrok.com/edges/tls"
}
```
