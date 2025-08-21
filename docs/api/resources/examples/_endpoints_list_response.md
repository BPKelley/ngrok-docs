<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
  "endpoints": [
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-21T10:08:33Z",
      "description": "sample cloud endpoint",
      "domain": {
        "id": "rd_31anAZOjbAyBwiZpc42nqNboBzc",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31anAZOjbAyBwiZpc42nqNboBzc"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31anBJnJMZyAsENjDntAKAP6PMa",
      "metadata": "{\"environment\": \"staging\"}",
      "pooling_enabled": false,
      "proto": "https",
      "public_url": "https://endpoint-example2.com",
      "traffic_policy": "{\"on_http_request\":[{\"actions\":[{\"type\":\"deny\",\"config\":{\"status_code\":404}}]}]}",
      "type": "cloud",
      "updated_at": "2025-08-21T10:08:33Z",
      "uri": "https://api.ngrok.com/endpoints/ep_31anBJnJMZyAsENjDntAKAP6PMa",
      "url": "https://endpoint-example2.com"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-21T10:08:30Z",
      "hostport": "77c39079a354.ngrok.paid:443",
      "id": "ep_31anAqbuYZmcPvXY4wIJmeiZbGw",
      "name": "command_line",
      "pooling_enabled": false,
      "principal": {
        "id": "usr_31an4PX7f1M06iuwpGVBFZMojRl",
        "uri": ""
      },
      "proto": "https",
      "public_url": "https://77c39079a354.ngrok.paid",
      "tunnel": {
        "id": "tn_31anAqbuYZmcPvXY4wIJmeiZbGw",
        "uri": "https://api.ngrok.com/tunnels/tn_31anAqbuYZmcPvXY4wIJmeiZbGw"
      },
      "tunnel_session": {
        "id": "ts_31anAwHiYAFG1M1VP14RsFv1v4q",
        "uri": "https://api.ngrok.com/tunnel_sessions/ts_31anAwHiYAFG1M1VP14RsFv1v4q"
      },
      "type": "ephemeral",
      "updated_at": "2025-08-21T10:08:30Z",
      "upstream_url": "http://localhost:80",
      "url": "https://77c39079a354.ngrok.paid"
    },
    {
      "bindings": [
        "public"
      ],
      "created_at": "2025-08-21T10:08:28Z",
      "domain": {
        "id": "rd_31anAZOjbAyBwiZpc42nqNboBzc",
        "uri": "https://api.ngrok.com/reserved_domains/rd_31anAZOjbAyBwiZpc42nqNboBzc"
      },
      "edge": {
        "id": "edgtls_31anAYXHrPDdy5LoOdPGWKEHfhY",
        "uri": "https://api.ngrok.com/edges/tls/edgtls_31anAYXHrPDdy5LoOdPGWKEHfhY"
      },
      "hostport": "endpoint-example2.com:443",
      "id": "ep_31anAW6zxjlsIogP9kQ2xkTkYOW",
      "pooling_enabled": false,
      "proto": "tls",
      "public_url": "tls://endpoint-example2.com",
      "type": "edge",
      "updated_at": "2025-08-21T10:08:28Z"
    }
  ],
  "next_page_uri": null,
  "uri": "https://api.ngrok.com/endpoints"
}
```
